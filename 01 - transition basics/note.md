## CSS Transition Property

There are essentially two ways to use the CSS transition property

### Way One

You use the CSS transition property `transition-property`, with this you can define all the properties of an element that you will like to apply a transition to to e.g

```css
transition-property: width background-color color;
```

Any transition you apply will be applied to all this properties at once.

### Way Two

Using the `transition` keyword which is a shortcut for combining all CSS transition properties. This gives more flexibility to apply different transition properties to an element e.g

```css
transition: background-color 3s ease-in 1s, width 2s ease-in-out 4s;
```

In the above, there will be a delay for **1 second** before the background color changes over a ** 3 second** period while the width will have a delay of **4 seconds** before it changes over a period of **2 seconds**

## What properties can be transitioned?

- Properties that can be expressed as numbers - this makes sense because the browser is able to compute the value start value and end value
- Properties that can be expressed in colors
