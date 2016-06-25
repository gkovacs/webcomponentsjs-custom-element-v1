# webcomponentsjs-custom-element-v1

This is the v1 branch of CustomElements from the webcomponentsjs project.

It is necessary to have skatejs run within a content script

## Usage

Install via npm:

```
npm install webcomponentsjs-custom-element-v1
```

Within a content script (assuming you want to use skatejs)

```
document.registerElement = null
require('webcomponentsjs-custom-element-v1')
skate = require('skatejs')
```

## Source

This is taken from https://github.com/webcomponents/webcomponentsjs/blob/v1/src/CustomElements/CustomElements.js

Direct link: https://raw.githubusercontent.com/webcomponents/webcomponentsjs/v1/src/CustomElements/v1/CustomElements.js

The particular commit this file is from is https://github.com/webcomponents/webcomponentsjs/commit/b6dafca58d7a302a37269295a69f27f4330c674c
