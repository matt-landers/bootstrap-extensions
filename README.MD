# Bootstrap Extensions

This repository contains a set of extensions for Bootstrap 4's utility classes.

I consistently find myself adding these to projects, so I'm making the available to anyone that wants to use them.

## Usage

`<link src="/node_modules/bootstrap-extensions/dist/bootstrap-extensions.css">`

Build with your project by copying the build.scss (`/node_modules/bootstrap-extensions/build.scss`) file to your project and changing the `@import` paths to work with your project configuration.

** You can also only important the files you want as they all work indepedently of each other.

## Table of Contents

- [Typograpy](#typography)
  - [Font Size](#font-size)
  - [Font Weight](#font-weight)
- [Positioning](#positioning)
  - [Position](#position)
  - [Location](#location)
- [Overflow](#overflow)

## Typography

### Font Weight

All font weights (100-900) are available.

* `.fw-100`
* `...`
* `.fw-900`

Example:
```css
.fw-100 {
    font-weight: 100 !important;
}
```

### Font Size

Font sizes from .25em through 5em via .25em increments starting at fs-1.

* `.fs-1` 
* `...`
* `.fs-20`

Example:
```css
.fs-1 {
    font-size: .25em !important;
}
```

## Positioning

### Position

* `.position-absolute`
* `.position-fixed`
* `.position-relative`
* `.position-static`
* `.position-sticky`

Example:
```css
.position-absolute {
    position: absolute !important
}
```

### Location

Position for left, right, top bottom with the values of 0, 50%, and 100%;

* `.left-0`, `.left-50`, `.left-100`
* `.right-0`, `.right-50`, `.right-100`
* `.top-0`, `.top-50`, `.top-100`
* `.bottom-0`, `.bottom-50`, `.bottom-100`

Exmaples:
```css
.left-0 {
    left: 0 !important;
}
.left-50 {
    left: 50% !important;
}
.left-100 {
    left: 100% !important;
}
```

## Overflow

Overflow for each property (overflow (o), overflow-y (oy), overflow-x (ox)) and value hidden and scroll.

* `.o-hidden`, `.o-scroll`
* `.ox-hidden`, `.ox-scroll`
* `.oy-hidden`, `.oy-scroll`

Example:

```css
.o-hidden {
    overflow: hidden !important;
}
```

# Additions
If you'd like to see additions, feel free to submit a pull request.

# License

[MIT](LICENSE) © Matt Landers