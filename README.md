# prism-themes-scss

Copied from [prism-themes](https://www.npmjs.com/package/prism-themes) except with scss.

## Install

```
yarn add -D github:harrybrwn/prism-themes-css#main
```

## Usage

```scss
@use "prism-themes-scss";

html[data-theme="dark"] {
  @include prism-themes-scss.prism-one-dark();
}
html[data-theme="light"] {
  @include prism-themes-scss.prism-one-light();
}
```
