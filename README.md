[![Published on NPM](https://img.shields.io/npm/v/@advanced-rest-client/websocket-request.svg)](https://www.npmjs.com/package/@advanced-rest-client/websocket-request)

[![Build Status](https://travis-ci.org/advanced-rest-client/websocket-request.svg?branch=stage)](https://travis-ci.org/advanced-rest-client/websocket-request)

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/advanced-rest-client/websocket-request)


# websocket-request

Web socket request panel.

## Example:

```html
<websocket-request></websocket-request>
```

## API components

This components is a part of [API components ecosystem](https://elements.advancedrestclient.com/)

## Usage

### Installation
```
npm install --save @advanced-rest-client/websocket-request
```

### In an html file

```html
<html>
  <head>
    <script type="module">
      import './node_modules/@advanced-rest-client/websocket-request/websocket-request.js';
    </script>
  </head>
  <body>
    <websocket-request></websocket-request>
  </body>
</html>
```

### In a Polymer 3 element

```js
import {PolymerElement, html} from './node_modules/@polymer/polymer/polymer-element.js';
import './node_modules/@advanced-rest-client/websocket-request/websocket-request.js';

class SampleElement extends PolymerElement {
  static get template() {
    return html`
    <websocket-request></websocket-request>
    `;
  }
}
customElements.define('sample-element', SampleElement);
```

### Installation

```sh
git clone https://github.com/advanced-rest-client/websocket-request
cd api-url-editor
npm install
npm install -g polymer-cli
```

### Running the demo locally

```sh
polymer serve --npm
open http://127.0.0.1:<port>/demo/
```

### Running the tests
```sh
polymer test --npm
```
