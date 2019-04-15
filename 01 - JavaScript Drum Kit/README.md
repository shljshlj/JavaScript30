# 01 - Drum Kit

key event listener, audio play and toggle class

view demo [here](https://shljshlj.github.io/JavaScript30/01-JavaScript Drum Kit/index.html)

`transform`, `transition` [CSS Transitions and Transforms ](https://thoughtbot.com/blog/transitions-and-transforms)
- Transforms move or change the appearance of an element, while transitions make the element smoothly and gradually change from one state to another.

- `keyCode` property of key event


```
const audio = document.querySelector('audio');
audio.currentTime = 0;
audio.play();
```