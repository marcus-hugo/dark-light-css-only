# CSS Only Dark/Light Theme

A simple webpage tutorial for a CSS only dark/light theme solution.

Without adding a reset or styles, this is the css that makes it work `color-scheme` and `prefers-color-scheme`, and together:

```css
@media (prefers-color-scheme: light) {
  html {
    color-scheme: light;
  }
}

@media (prefers-color-scheme: dark) {
  html {
    color-scheme: dark;
  }
}
```

The colors were inspired by Tailwind CSS and Tania Rascia's New Moon theme for VS Code.
here's a link [https://github.com/taniarascia/new-moon]

Will build on this project for the next tutorial with a toggle switch and JavaScript to come soon...
