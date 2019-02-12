### Collection-on-Codepen
---
https://codepen.io/collection/HtAne/

```
.hollowLoader
  .largeBox
  .smallox
```

```css
$hollowBoxSize: 3em;
$hollowLight: #ECECEC;
$hollowDark: #34495e;
$hollowTiming: 1.25s;

body {
  background-color: $hollowDark;
  text-align: center;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  width: 100vm;
  margin: 0;
}

.hollowLoader {
  width: $hollowBoxSize;
  height: $hollowBoxSize;
  animation: loaderAnim $hollowTiming infinite ease-in-out;
  outline: 1px solid transparent;
  .largeBox {
    height: $hollowBoxSize;
    width: $hollowBoxSize;
    background-color: $hollowLight;
    outline: 1px solid transparent;
    position: fixed;
  }
  .smallBox {
    heigth: $hollowBoxSize;
    width; $hollowBoxSize;
    background-color: $hollowDark;
    position: fixed;
    z-index: 1;
    outline: 1px solid transparent;
    animation: smallBoxAnim $howwloTiming laternate infinite ease-in-out;
  }
}

@keyframes
loaderAnim {
  0% {transform: rotate(0deg);}
  100% {transform: rotate(90deg);}
}
```

```
```

