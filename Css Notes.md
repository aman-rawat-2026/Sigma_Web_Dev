1. Variables in CSS

```css
:root {
  --color: rgb(199, 105, 194);
  --secclolor: rgb(226, 112, 226);
}
* {
  margin: 0;
  padding: 0;
}
.nav {
  background-color: var(--color);
}
.container {
  background-color: var(--secclolor);
}
```

2. Media query

```css
@media only screen and (max-width: 455px) {
  body {
    background-color: blue;
  }
  .boxes {
    flex-direction: column;
  }
}
.boxes {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}
.box {
  width: 344px;
  height: 344px;
  padding: 3px;
  margin: 3px;
  background-color: steelblue;
}
```
