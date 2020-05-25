# Ripple-without-JS
Create [Material Design](https://material.io/) ripple effect in your HTML without using a single line of JavaScript code.

[![forthebadge](https://forthebadge.com/images/badges/validated-html5.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/uses-css.svg)](https://forthebadge.com)

## LIVE DEMO: https://kvaibhav01.github.io/Ripple-without-JS/

## What's the output?
Here it is!

![Ripple demo](https://github.com/Kvaibhav01/Ripple-without-JS/blob/master/rippleWithoutJSGIF.gif)

_Fun isn't it?_

## How to achieve?
If there's no JS, then there's CSS. To achive the task we need to make a new [CSS file](https://github.com/Kvaibhav01/Ripple-without-JS/blob/master/style.css) having:

- **[Container](https://www.w3schools.com/w3css/w3css_containers.asp)**: [`display`](https://www.w3schools.com/cssref/pr_class_display.asp) property set to `flex` to make it of same length regardless of the content.
  
- **Ripple**: [`transform`](https://www.w3schools.com/cssref/css3_pr_transform.asp) property set to `translate3d` to define a 3D translation.

- **Ripple-after**: this is where the ripple effect ends. We can show something like a text but it doesn't make sense here. Therefore the `content` has been set to `""`.
  - `background-image`'s value has been set to the [`radial-gradient`](https://www.w3schools.com/cssref/func_radial-gradient.asp) function which takes in a `circle` as its `shape`, `#fff` or white as the `start-color` and `last-color` as `transparent 10.01%`.
  - `transition` is used along with `transform` with its corresponding timing and `opacity`.
  
#### That's it! Simple, clean and Materialistic!  
  
Read [this article](https://codeburst.io/create-a-material-design-ripple-effect-without-js-9d3cbee25b3e) I wrote to incorporate this in your project file.
