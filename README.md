# Simple Flex Grid

Easy-to-use grid based on Flexbox in pure CSS.

## Why will it be useful to me?

If you are implementing a website with a simple responsive layout, using [Bootstrap] or other frameworks can be time loss with unuseful CSS, or make you import more that you need.

Simple Flex Grid provides you a CSS grid layout.

1. It is in pure CSS
2. It is small
3. It doesn't change your fonts
4. It doesn't change your colors
5. It is simple
6. It is flex
7. And it is nothing else than a grid

## What is a responsive grid?

A grid is useful

## Notes

Breakpoints are based on [Material Design Viewport Breakpoints], while `container` class width is based on [Bootstrap]

## Installation

**Via NPM**

```
npm i -D @paulbarre/simple-flex-grid
```

Then into your main javascript file (ES6 module):

```js
import '@paulbarre/simple-flex-grid'
```

## Breakpoints

Device|Code|Types|Range|Container max-width
:-|:-|:-|:-|:-|:-
Extra small|xs|small to large handset|< 600px|none
Small|sm|small to medium tablet|600px > < 960px|540px
Medium|md|large tablet to laptop|960px > < 1264|720px
Large|lg|desktop|1264 > < 1904px|960px
Extra large|xl|4k and ultra-wides|> 1904px|1140px

## Grid

