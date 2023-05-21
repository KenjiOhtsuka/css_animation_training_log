date: 2023-05-22

```css
@keyframes fly {
  to {
    transform: translate(240px, 260px) rotate(-45deg);
  }
}

.rocket {
  animation: fly;
  animation-duration: 1.5s;
  animation-timing-function: ease-out;
  animation-fill-mode: forwards;
}
```
