masuP.net_style
===============

CSS of [masuP.net](https://masup.net) 

## CSS Style Guide

```
.Block {
  property: value;
}

.Block__element.-modifier,
.Block__otherElement.-state {
  property: value;
}
```

## Source Directory

- style.css
  - /setting
    - custom properties, custom media queries ...
  - /library
    - import from ../node_modules or other library
  - /foundation
    - element.css
    - variable.css
  - /component
    - some components ...
