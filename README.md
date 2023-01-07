# Ms-cursor 🖱️🪄

[![GitHub Version](https://img.shields.io/github/v/release/guillaume-rygn/MS-Cursor.svg?style=for-the-badge)](https://github.com/guillaume-rygn/MS-Cursor/releases)

![Demo](./assets/home.gif)

## ***It has never been so easy to have a modern mouse design !***
&nbsp;

## Demo : https://ms-cursor-demo.vercel.app/
&nbsp;

## Installation

Install with npm:
```shell
npm i ms-cursor
```

or install with yarn: 

```shell
yarn add ms-cursor
```
&nbsp;
## Initialize: 

Add JS script: 

with yarn or npm : 
```HTML
<script src='./node_modules/ms-cursor/index.js'></script>
```

with CDN :
```HTML
<script src='https://cdn.jsdelivr.net/npm/ms-cursor@1.2.0/index.min.js'></script>
```

In HEAD of index.html file: 

```HTML
<link rel="stylesheet" href="./node_modules/ms-cursor/style.css" />
```

Or initialize with CDN in HEAD of index.html file: 

```HTML
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/ms-cursor@1.2.0/style.min.css"/>
```

&nbsp;
## How to use it 

After initialize **MS-Cursor** you can set the cursor. You just need to pass an attribute to the script tag.

**If you do not specify anything, the mouse will take the default values!**

&nbsp;
### Size

you can adjust the size of the mouse drag.

```HTML
<!--Default 30-->

<script
    src="./node_modules/ms-cursor/index.js"

    size="60" 
></script>
```
&nbsp;
### Pause Animation

When the mouse movement stops an animation is triggered. Have this attribute you can disable it.

```HTML
<!--Default enable-->

<script
    src="./node_modules/ms-cursor/index.js"

    pause-animation="disable" 
></script>
```
&nbsp;
### Difference

This inverse effect corresponds to the CSS property:
```CSS
mix-blend-mode: difference
```

The colors of the mouse animation when hovering over an element.

```HTML
<!--Default enable-->

<script
    src="./node_modules/ms-cursor/index.js"

    difference="disable" 
></script>
```
&nbsp;
### Cursor

By default the cursor remains visible except when the mouse stops. You can completely disable the cursor with this attribute.

```HTML
<!--Default enable-->

<script
    src="./node_modules/ms-cursor/index.js"

    cursor="disable" 
></script>
```
&nbsp;
### Color

You can change the color of mouse effect.

```HTML
<!--Default white with difference enable and black without difference -->

<script
    src="./node_modules/ms-cursor/index.js"

    color="#ffffff" 
></script>
```
&nbsp;
### Circle-Outline

When the mouse stops, an animation starts and a border appears. You can disable it with this attribute.

```HTML
<!--Default enable-->

<script
    src="./node_modules/ms-cursor/index.js"

    circle-outline="disable" 
></script>
```
&nbsp;
### Color-Outline

When the mouse stops, an animation starts and a border appears. You can change the color of the border with this attribute.
**This attribute not working if you disable pause-animation attribute**

```HTML
<!--Default same color than color attribute-->

<script
    src="./node_modules/ms-cursor/index.js"

    color-outline="#ffffff" 
></script>
```
&nbsp;
### Gradient

You can activate a gradient for your mouse. This attribute replaces the color attribute. You just need to pass every color separate by a comma into a string.

```HTML
<!--Default none-->

<script
    src="./node_modules/ms-cursor/index.js"

    gradient="#1f005c, #48005f, #680060, #830060, #9c155f, #b22c5e, #c5415d, #d5585c, #e36e5c, #ef865e, #f89d63, #ffb56b" 
></script>
```
&nbsp;
## Founder
| [Guillaume Reygner](https://twitter.com/guillaume_rygn) |
| ----------- |
| MS-Cursor Creator | 
&nbsp;
## License

MS Cursor is licensed under the [Hippocratic License](LICENSE.md).

&nbsp;
## Code of conduct

This project and everyone participating in it is governed by the MS Cursor [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. 



