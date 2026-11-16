# Entry 1
##### 10/10/26


### Context
This years freedom project, we will be constructing a game/app of our choice. In order to process how my project will be created I had to pick a tool. I had a few ideas in mind. One idea i had was a rhythm game. To make this i could use the tool <a href="https://threejs.org/"> threejs </a>. I really love rhythm games, i could create one that allows the player to have fun and work on their response time. 
Another idea was to make a tennis game. Using <a href="https://threejs.org/"> threejs </a> or <a href="https://q5play.org/learn/ "> q5play </a> to make the POV camera of the player be able to move to the tennis ball when the opponent hits. Another idea was A story game that Based my 9th grade comic book story, a stroy game that gives you option of how the story goes. 


### What Tool did i pick? 

For my freedom project, i have chosen to create a a stroy board game. The tool that im chosing is called <a href="https://animejs.com/"> Animejs </a>. It caught my attention because of the properties it has. Its a library and it allows you to create animation using javascript. I wanted to use this tool because i want to make my characters move across the screen in my storyboard game. Im really intrigued with animiation 
While i was tinkering with this tool, I recognized some properties i learned last year when learning animation. I used Codepen to code and tinker with the animations.

### Animating a character

To make this happen, in codepen i give my character an ID and on css I adjust the size. Then on Javascript i call the function and give it its animation. 

<p> code example: </p>

#### In CSS

```
#character {
  font-size: 40px;
  position: absolute;
  left: 10px;
  top: 70px;
```


#### In Javascript: 

```
function moveCharacter() {
  animte({
    targets: `#character`,
    translateX: 250,
    duration: 2000,
    easing: `easeInOutQuad`
  });
}
```

* The targets is what choses the item, in this case my character
* TranslateX is what moves it horizontally. if i were to move it up and down i would use Y
* the duration is how long the aniamtion lasts
* easing controls how the movement goes. For example, instead of the animation moving at the same speed the entire time, easing makes it start and/or end at a different speed. In this case, easeInOutQuad makes the animation start off slowly, speed up and then end off slowly again.

### Sources

What really helped me better understand how <a href="https://animejs.com/"> Animejs </a> works is this video I saw that was posted on my slack channel.  https://youtu.be/uRDLFXxihgc?is=d4S9hB4icZ8EeOZC  
<p> Its a short 10 minute video of a tutorial on my tool. It help me better understand how to code anmation and it guided me and gave me step by step processes.</p>

### Engineering Design Process
I plan to continue tinkering with <a href="https://animejs.com/"> Animejs </a> and to learn out to animate a scene and input my own drawings to animate. 

### Skills 
* From last year, i used the skill of memorization to remember how animating code was
* Taking notes of coding and labeling what each part does to have a better understanding of how the code functions



[Next](entry02.md)

[Home](../README.md)
