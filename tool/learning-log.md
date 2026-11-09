# Tool Learning Log

## Tool: **animejs**

## Project: **Story Game**

---

### 10/16/26:
Idea: A story game - Based on my 9th grade comic book story, maybe i can make a stroy game that gives you option of how the story goes. 
 	Story: N/A goes to sleep and has lucid dreams. The player gets to control what happens in the dream but has to avoid going through sleep paralysis. 
How will i use the tool for my idea? 
I can add animation to my story background and use the responsive animation tool to the character. To animate my character i can convert my pdf drawings into SVG. Ill have to look more into that.  

### 10/25/26:
Installing my tool: 
 ```
  import { animate } from 'https://esm.sh/animejs';
  ```
Animejs uses rotates, duration, ease, delay, loopDelay, loop. To make an animation, you must use Property Keyframes. Its bascially what moves each motion to where and when to stop. 

It all comes together in a text animation. for example: 
```
import { animate, stagger, splitText } from 'animejs';

const { chars } = splitText('h2', { words: false, chars: true });

animate(chars, {
  // Property keyframes
  y: [
    { to: '-2.75rem', ease: 'outExpo', duration: 600 },
    { to: 0, ease: 'outBounce', duration: 800, delay: 100 }
  ],
  // Property specific parameters
  rotate: {
    from: '-1turn',
    delay: 0
  },
  delay: stagger(50),
  ease: 'inOutCirc',
  loopDelay: 1000,
  loop: true
});
```

### 11/08/26

I tried an example of Anime.js coding for a shape:

```
const { animate } = anime;

animte('.shape', {
translateX: 250,
duration: 1500,
esae: 'inOutQuad',
loop: true,
alternate: true
}); 

```
<p> This created the shapte to move horzontally by 1.5 seconds. </p>
<p> the duration is in milliseconds. </p>
<p> ease: 'inOutQuad' makes the shape start off slowly then speed up and then slows down at the end</p>
<p> loop: true, repeats the animation on a loop </p>
<p> alternate: true, this makes the animation shape switch directions everytime it repeats</p>

<!-- 
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
