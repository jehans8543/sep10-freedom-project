# Entry 4
##### 02.28.2025 

## Choosing a Tool 
The tool that I ended up choosing was called _Animate.CSS_ which was one of the mild options from the tool list. Originally I thought that I was going to use the tool _A-frame_, but after reseraching about it a bit I realized that it would be hard to connect it with my topic, Government. A-frame is used to create 3D models, and though it would have been interesting to make a model of my topic, it would have been hard for me to do so since my topic is more of a system rather than a physical. Therefore I decided it's best to do Animate CSS, my second choice, since it would enhance the visual appearance of my website. 

### What is Animate.CSS?
[Animate.CSS](https://animate.style/) is considered to be a library of premade cross-browser animations for your webpage, with it the simplicty being able to greatly enhance your webpage. In order to use Animate.CSS you can either install it with an _npm_, _install with yarn_, _impoprt it into your file_, or _add it directly to your webpage using a CDN_. When it came to installing Animate.CSS I used the adding it to your webpage option using a CDN:

```HTML
<head>
  <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"
  />
</head>
```
### Tinkering 
When it came to tinkering with Animate.CSS the main resources that I used to learn more about it is [Free Code Camp](https://www.freecodecamp.org/) to learn more about the concepts of the code, and [JSBIN](https://jsbin.com/?html,output) to actually tinker with the code. 

#### @Keyframes 
Animate.CSS comes with different animations to animate your text or elements with, but you would have to use **_@keyframes_** in order to directly use the provided animations. Though my problem was that I did not know how to use nor what was @keyframes to begin with. In order to learn more about it I went to _Free Code Camp_ :
![keyframes](https://github.com/user-attachments/assets/5c69750b-3334-4e11-89b2-2724be3f6c81)
Through this Free Code Camp lesson I was able to learn that @keyframes is use for control what happens during the animation. 
* `animation-name`- sets the name of the animation
* `animation-duriation` - sets the length of time for the animation
* Percentages such as 0% - 100% is used to sepcify excatly what happens to the animation during the duriation
  * 0% - element during opening scene
  * 100% - element during ending scene

After learning more about `@keyframes` I was able to tinker with it on JSBIN using it with Animation.CSS. While tinkering I learned that I did not have to directly use @keyframes, though I was able to use the properties of keyframes in order to make the animation appear. The animation that I decided to test it out is the `bounce` animation. 

```CSS
.animate__animated animate__bounce {
   display: inline-block;
  margin: 0 0.5rem;
  
  animation: bounce;
   animation-duration: 2s;
}

 div {
    height: 40px;
    width: 70%;
    background: lightblue;
    margin: 50px auto;
    border-radius: 5px;
  }
```
This code would then make my text bounce up for a duriation of 2 seconds, as I have stated in the @keyframes. The animation that I have used in my code is exclusive to the tool that I used, Animate.CSS. 

## Skills 

### Problem Solving 
A skill that I was able to learn is problem solving, one of the challenges that I encournted on my tinkering process is getting the animation to work, and trying to figure out how it is connected to @keyframes. I kept on struggling and struggling, and was even tempting to give up, untill I went back to the Free Code Camp lesson. After reviewing the lesson that I did I was able to make the connection between @keyframes and Animate.CSS, and I figured out that `animation-duriation` is what connects @keyframes and Animate.CSS together. I was able to learn that problem solving comes with a process with testing it out, finding the mistake, reviewing it, and finally look for a solution. 

### Attention to Detail 
I was able to learn this skill through minor mistakes that I would make throughout my code. Often times my code would not work, despite me seemingly doing everything right. Though the more I look over it I would realize that I would make the smallest mistakes, such as spelling class names wrong. Making such small errors like this can change the whole course of your code, making you have to restart. That's why I learned to always look over every tiny little detail of my code before I confirm it. Without double checking, it can cost you the whole thing. That's why paying attention to detail is a crucial skill I learned in throughout this process. 

## Summary 




[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)
