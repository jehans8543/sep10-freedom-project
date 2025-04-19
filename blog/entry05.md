# Entry 5
##### 04.19.2025

## Learning About Animate.CSS
Trying how to learn and use my tool, [animate.css](https://animate.style/), has proven to be a bit difficult for me to do. The reason why it was difficult was becasue I had to start off and learn the basics of CSS aniamtions. In order for me to use animate.css to its full extent I had to have a versatile knowledge in css animating in general. 

### How I learned
#### [Free Code Camp](https://www.freecodecamp.org/)
In order to learn more about animating in CSS, I used the Free Code Camp _Legacy Responsive Web Design Challenges_ as my main tool in learning the basics.

In my [previous blog](entry04.md) I already used Free Code Camp to learn about the `@keyframes` function. In order to summarize key frames is: 
* `@keyframes` controls what happens during the animation
  * inside of `@keyframes` we have `animation-name`
    * as the name suggests, it sets a name for the animation
  * we also have `animation-duriation` inside of the `@keyframes` property
    * `animation-duriation` makes the animation play for a certain amount of time

While I was tinkering I learned that `@keyframes` is typically used for creating transitions, effects, or motion graphics: 

```CSS
@keyframes gradientAnimation {
    0% {
        background-position: 0% 50%;
    }
    50% {
        background-position: 100% 50%;
    }
    100% {
        background-position: 0% 50%;
    }
}
```
* `animation-fill-mode`
  *  specifies the style applied to an element when the animation has finished
  *  You are able to set it to different directions such as _forwards_
* Positioning (fixed or relative)
  * right, left, top, and bottom are used to create movement in animation rules
  * Relative
    * places an element relative to its normal position in the flow
  * Fixed
    * Positions an element relative to the viewport
* `animation-iteration-count`
  * controls how many times you would like to loop through the animation
    * setting the animation to _infinite_ will make the animation play infinitly, hence the name
* `animation-timing-function`
  *  controls how quickly an animated element changes over the duration of the animation
    * default vlaue is _ease_
      * starts slow, speeds up in the middle, slows again towards the end
    * _ease-out_
      * quick at the begining, slows down in the end
    * _ease-in_
      * slow at the begining, fast in the end
    * _linear_
      * constant animation speed 
       



[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
