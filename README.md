# Simple Flex Grid

Easy-to-use grid based on Flexbox in pure CSS.

## Why will it be useful?

Using [Bootstrap](https://getbootstrap.com/docs/4.3/layout/grid/) or other frameworks can be time loss with unuseful CSS, or make import more that what your app needs.

Simple Flex Grid goals:

1. It is in pure CSS
2. It is small
3. It doesn't change your fonts
4. It doesn't change your colors
5. It is simple
6. It is flex
7. It is responsive

## Notes

Grid breakpoints and `container` class max-width are based on [Bootstrap](https://getbootstrap.com/docs/4.3/layout/grid/).

## Installation

**Via NPM**

```
npm i -D @paulbarre/simple-flex-grid
```

Then into your main javascript file (ES6 module):

```js
import '@paulbarre/simple-flex-grid/dist/simple-flex-grid.min.css'
```

## Breakpoints

Device|Code|Types|Range|Container max-width
:-|:-|:-|:-|:-|:-
Extra small|xs|small to large handset|< 600px|none
Small|sm|small to medium tablet|600px > < 960px|540px
Medium|md|large tablet to laptop|960px > < 1264|720px
Large|lg|desktop|1264 > < 1904px|960px
Extra large|xl|4k and ultra-wides|> 1904px|1140px

## Classes

* `row`: define responsive layout.
* `column`: the tag that has to be responsive.
* `<breakpoint>[1-12]`: the tag will covere 1 to 12 columns for the designated breakpoint.
* `<breakpoint>`: the tag will be hidden until the breakpoint is triggered.
* `<breakpoint>0`: the tag will be hidden when the breakpoint is triggered.
* `container`: this class will set margins around the grid layout. Not required if the rows have to covered the full width of the page.

## Examples

Check out the `examples` for a short example. More examples to come.