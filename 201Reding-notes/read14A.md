# CSS Transforms, Transitions, and Animations

Julia Rozovsky, like most 25-year-olds, had no idea what she wanted to do with her life. She had previously worked for a consulting firm, but it was not a good fit for her. Then she went to Harvard to work as a researcher for two professors, which was exciting but lonely. Perhaps working for a large firm would be a better fit. Perhaps a rapidly expanding start-up.



## Transforms

![Image](https://tipsmake.com/data/images/3d-transform-in-css-picture-1-jtznOkrOW.jpg)

### What Google Learned From Its Quest to Build the Perfect Team?
CSS3 introduced additional methods for positioning and modifying components. Alternative approaches to size, position, and adjust items can now be used to explore general layout techniques. The transform property allows for all of these new techniques.

There are two types of transform properties: two-dimensional and three-dimensional. Each of these has its own set of characteristics and values.


```
div {
 -webkit-transform: scale(1.5);
 -moz-transform: scale(1.5);
 -o-transform: scale(1.5);
  transform: scale(1.5);
}
```

**2D Rotate**

There are a few alternative values that can be used with the transform property. The rotate value allows an element to be rotated from 0 to 360 degrees. If you use a positive value, the element will revolve clockwise, and if you use a negative number, the element will rotate counterclockwise.

```
.box-1 {
  transform: rotate(20deg);
}
.box-2 {
  transform: rotate(-55deg);
}
```

**2D Scale**

Using the scale value within the transform property allows you to change the appeared size of an element.

```
.box-1 {
  transform: scale(.75);
}
.box-2 {
  transform: scale(1.25);
}
```

## Transitions

As previously stated, a transition must occur when an element changes state, and various styles must be designated for each stage. The simplest technique to determine distinct state styles is to use the `:hover`, `:focus`, `:active`, and `:target` pseudo-classes.


## Shorthand Animations

```
.stage:hover .ball {
  animation: slide 2s ease-in-out .5s infinite alternate;
}
.stage:active .ball {
  animation-play-state: paused;
}
```

## CSS3 Transitions That Will Wow Your Users 


```
<style type="text/css">
body > div
{
width:483px;
height:298px;
background:#676470;
transition:all 0.3s ease;
}
</style>
```

**Change color**

Animating a color change used to be extremely difficult, requiring a lot of computation to calculate individual RGB values and then recombining them. Now all we have to do is change the div's class to *“color”* and define the color in our CSS:

`.color:hover{ background:#53a7ea;}`

## Transitional Properties

It's vital to remember that not all properties can be converted; only those with a clear halfway point can. Colors, font sizes, and other similar elements may be transitioned from one value to the next because they have recognizable values in between. Because it lacks a midpoint, the display property, for example, cannot be transitioned. A handful of the more popular transitional properties include the following.

- background-color
- background-position
- border-color
- border-width
- border-spacing
- bottom
- clip 

click here to read more about Transforms:
   [link](https://www.w3schools.com/cssref/css3_pr_transform.asp)

