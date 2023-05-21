date: 2023-05-22

```css
@keyframes fly {
  to {
    transform: rotate(40deg) translate(0px, -500px);
  }
}

.rocket {
  animation: fly;
  animation-delay: 1s;
  animation-duration: 1s;
  animation-timing-function: ease-in;
  animation-fill-mode: forwards;
}
```
