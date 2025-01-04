## Working with 3D Transforms

Whenever you need to work with the 3D space or property, you need to add a perspective to the containing element of the target element e.g

```css
body {
	perspective: 1000px;
}
```

This indicates the distance from the screen to your eyes.

Common properties include

- `rotateX`
- `rotateY`
- `rotateZ` - this will give the same effect as `rotate` in the 2D space
- `translateZ`
