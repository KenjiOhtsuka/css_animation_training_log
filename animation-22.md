date: 2023-05-22

```css
.robot {
  animation-duration: 5s;
  animation-iteration-count: 2;
  animation-direction: alternate;
  
  animation: move;
}

@keyframes move {
  to {
    left: 400px;
  }
}

.robot-paused {
  animation-play-state: paused;
}
```
