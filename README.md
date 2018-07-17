# material-design-css-variables
🎨 CSS variables for Google's Material Design

## How to use

1. Download or copy [material-design-colors.css](./material-design-colors.css) and add it to your project's styles directory

2. Import the document at the top of your main stylesheet:
    
```css
/* main.css */

@import './material-design-colors.css';
```

3. Reference the material variables using [CSS's `var()` function](https://developer.mozilla.org/en-US/docs/Web/CSS/var):

```css
body {
  background: var(--blue500);
  color: var(--gray50);
}
```

## Use with other CSS variables

If you want to use Material Design CSS Variables in addition to your own CSS variables, make sure to import `material-design-colors.css` **first**:

```css
/* main.css */

@import './material-design-colors.css';
@import './other-variables.css';
```
