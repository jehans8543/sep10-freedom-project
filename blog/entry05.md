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
    
#### Youtube Videos
While searching for information on how to use animate.css, I came across some youtube videos that talked about the tool specifically, or talking to css properties that are related to it:

* [CSS Animation 28 - animation delay](https://www.youtube.com/watch?v=8RrTJY_z36c&ab_channel=VirtualAddiction)
  *  Defines when an animation will start
  * Begins execution sometime after it is applied
  * The numeric value represents an offset, defines how long of an delay there is going to be
* [How to animate CSS dynamically in JavaScript](https://youtu.be/GMTb1q4T1MY?si=x0BxjlblqVSkCb82)
  * To make an object move you would have to create a new element
    * Use `querey.selector`
  * Add a class, not keyframes
  * Specify duration with `animation-duriation`
  * You use the class you made earlier as your keyframe and make the same class name as your `animation-name`
  * Every time you refresh the browser the keyframes should play
  * Using the from and to keyframe commands you can further complex your animations
    * You can use any css property during this part of the aniamtion

For the most part I found watching youtube videos to be helpful, especially seeing how they would tinker their code and how I can incooporate that into my own. 

#### ChatGPT 
Though using ChatGPT is not reccomended to use often times when it comes to coding, it can be helpful. ChatGPT is especially helpful when you need to ask questions, it is also a good source to find explanations to help develop your understanding on how to use your code. 

While tinkering, I wanted to see if it was possible to mixed bootstrap elements and animate.css elements together, and it didn't work at first. In order to confirm this I then asked ChatGPT if this was true and it told me: 

![boot-animate](https://github.com/user-attachments/assets/4839a3f0-7dd9-4011-a06e-89bf4bc6957d)

From the response that I got, I realized that I messed up on adding the cdn for aniamte.css, and after quickly fixing that issue I was able to get started with animating bootstrap componets with animate.css components: 

```HTML
<div>
  <nav class="navbar bg-body-tertiary">
    <div class="container-fluid">
      <a class="navbar-brand animate__animated animate__jello" href="#" >
        Bootstrap
      </a>
    /div>
  </nav>
</div>
```
```HTML
 <div class="container-fluid">
   <div style="text-align: center;">
     <h1 class="animate__animated animate__rubberBand">Tinkering</h1>
   </div>
</div>
```
_The two snippets of code are from the tinkering webpage I made using my IDE, both are from two different bootstrap componets_

ChatGPT not only expanded my knowledge on how to use my tool, but it also gave me other resources that will work well and be compatiable with my tool

![animate css-chat](https://github.com/user-attachments/assets/f3cf471a-ad2d-4863-9ae8-7b6cee6e359f)
  * From asking chatGPT I was able to learn that in order to properly use media queries in aimate.css they are dependant on removing or adding classes, unlike without it
  * In order to make your animations more responsive you can use libraries such as AOS or IntersectionObserver API with Animate.css for more nuanced control over the responsiveness

Somwhere throughout my tinkering and me asking ChatGPT questions, I ended up learning that animate.css alters the basic animation code a bit. For example, `animation-duriation` in normal CSS would be `animate-duriation` if you have animate.css installed. This is a important piece of information that I learned, since if you use the prior, your animate.css code can not be modified. 

## Skills 
### Asking Questions 
One of the key aspects of learning is being able to ask question. Though this is a skill that I utilized before, I now realized the full necesity of it while trying to learn my tool. While reseraching I went through the struggle of finding limited resources that explains or goes over my tool. And the limited resources that I did have left me with unanswered questions. Thankfully, I was able to get many of my questions answers by asking ChatGPT. An AI chat bot that is programed to answer questions like such. Being able to find answers to my question not only improved my knowledge on my tool, it also allowed me to become a stronger coder, further allowing me to have a well developed project. 

### Critical Thinking 
While learning more about my tool, I was able to further develop my critical thinking skills. I was able to do this by piecing together the pieces of information that I gathered. For example, such as learning more about `@keyframes`. After learning more about `@keyframes` I was then able to learn more about `animation-iteration-count`, `animation-name`, `animation-duriation`, `animation-timing`, and etc. I was slowly able to piece together different types of code and their functions and put them together to the overall topics, which is animating using `@keyframes`. I was now able to have more control over my animations because I was able to take what I learned and piece them together to learn a whole concept of animation in CSS. 

## Summary 
While learning more about animate.css I ended up **trying** to tinker and create something with the limited knowledge that I had on my tool. And through tinkering and asking questions I was able to **change** my knowledge on the topic. Leading to me to **make** and code that demonstrated what I learned and my solution through multiple attempts of trial and error. 

[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
