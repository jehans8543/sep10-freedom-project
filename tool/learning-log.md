# Tool Learning Log

## Tool: **Animate.CSS**

---

### 03/09/2025:
* Created a subdirectory folder in my tool folder, in order to practice what I learned
  * Created a HTML file for my code
  * installed animate.css
* I visited the [Animate.CSS](https://animate.style/) website
  * Read the section about **Delay classes**
    * type of class
    * different types of delay speeds, applicable with any animation
      * `animate__delay-2s	2s`
* Practice.html
  * used `animate__bounceOut` to test out the delay feature
    * When trying out the delay count I could not notice any differences
    * tried difference animations and speeds to see if there was a difference
* Next Steps:
  * Watch youtube videos surrounding animation delays
    * [Learn CSS Animations in 9 Minutes](https://www.youtube.com/watch?v=z2LQYsZhsFw&ab_channel=Coding2GO)
    * [CSS Animation 28 - animation delay](https://www.youtube.com/watch?v=8RrTJY_z36c&ab_channel=VirtualAddiction)

### 03/16/2025:
* [Learn CSS Animations in 9 Minutes](https://www.youtube.com/watch?v=z2LQYsZhsFw&ab_channel=Coding2GO)
  * when your changes contains more than one step then you need to use animation
  * `@keyframes`
   * Assigns animation rule to an element
   * then give animation an name 
  * Sequence of animation used with percentages
    * 0% - begining, 100% - end
  * You need to be specific when to animate what CSS property
  * `animation-timing-function`
    * Makes the timing of an animation more specific
  * Linear - consistent speed
  * Ease - smoother speed
* [CSS Animation 28 - animation delay](https://www.youtube.com/watch?v=8RrTJY_z36c&ab_channel=VirtualAddiction)
  *  Defines when an animation will start
  * Begins execution sometime after it is applied
  * The numeric value represents an offset, defines how long of an delay there is going to be
* Next Steps:
  * Taking what I learned and incoorprating it into my code
  * Conencting the animations I learned from the videos with _Animate.CSS_

 ### 03/23/2025:
* I wanted to find a new way to learn how to use animate.css
  * I choose to try out how AI will explain it to me, specifically _ChatGPT_
    * **I only planned to use ChatGPT to see how they _explained_ it, I do not plan on plaragrizing the code from their examples**
* ChatGPT:
  * I learned that by default all animations last by 1 second
    * change this by using `animation-duriation`
      * Do this in style.css or as a inline code
  * Trigger animations when an element enters the viewport using JavaScript
    * **I decided to come back to learning about this later when I understand the basics of my tool more**
  * You can loop animations using `animate_infinite`
  * Javascript
    * apply animations via javacript
    * remove animations after completeion using javascript
* In JSBIN I tested out some of the animations on the offical animate.css documentation
* Next Steps:
  * Trying to further develop my tinkering
  * learn more about how Javascript works if I have time
 
### 03/31/2025
* Made a basic website on my IDE to tinker animations with
  *  Made with HTML, Bootstrap, CSS, and Animate.CSS
* Tinkering:
  * I tested to see if animating code that is within a `container-fluid` would work
    * Doesn't work
    * changes the bootstrap; causing it to not even be there anymore
  * I tried adding the animations within the `<h2>` but in the end it made my pargraph to become the headings and just caused a lot of errors in general
  * Decorating and exploring differet animations to my website
  * Tried incoorporating the animations with bootstrap componets
    * Searched up on ChatGPT if it was possible to mix bootstrap components with animate.css
    * ![boot-animate](https://github.com/user-attachments/assets/4839a3f0-7dd9-4011-a06e-89bf4bc6957d)
    * After finding out that it was possible to animate boostrap components I got to adding them immediately
  * I added a card component and animated it to fade in and it worked!
* Videos:
  * I wanted to watch a video on how to aniamte using javascript
    * [How to animate CSS dynamically in JavaScript](https://youtu.be/GMTb1q4T1MY?si=x0BxjlblqVSkCb82)
      * To make an object move you would have to create a new element
       * Use `querey.selector`
      * add a class, not keyframes
      * specify duration with `animation-duriation`
      * you use the class you made earlier as your keyframe and make the same class name as your `animation-name`
      * every time you refresh the browser the keyframes should play
      * Using the from and to keyframe commands you can further complex your animations
        * you can use any css property during this part of the aniamtion
* Troubleshooting:
  * animate.css + bootstrap
    * I found out that the aniamtion is only not working with one of my `<h2>`
      * After further eximanation I found out that I made a small spelling error in my animation code
   


<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
