# &lt;apollo-pdf-viewer&gt;

[&lt;apollo-pdf-viewer&gt;](https://vaadin.com/components/apollo-pdf-viewer) is a Web Component providing &lt;element-functionality&gt;, part of the [Vaadin components](https://vaadin.com/components).

[Live Demo ↗](https://vaadin.com/components/apollo-pdf-viewer/html-examples)
|
[API documentation ↗](https://vaadin.com/components/apollo-pdf-viewer/html-api)

[![npm version](https://badgen.net/npm/v/@vaadin/apollo-pdf-viewer)](https://www.npmjs.com/package/@vaadin/apollo-pdf-viewer)
[![Bower version](https://badgen.net/github/release/vaadin/apollo-pdf-viewer)](https://github.com/vaadin/apollo-pdf-viewer/releases)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/vaadin/apollo-pdf-viewer)
[![Build Status](https://travis-ci.org/vaadin/apollo-pdf-viewer.svg?branch=master)](https://travis-ci.org/vaadin/apollo-pdf-viewer)
[![Coverage Status](https://coveralls.io/repos/github/vaadin/apollo-pdf-viewer/badge.svg?branch=master)](https://coveralls.io/github/vaadin/apollo-pdf-viewer?branch=master)
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/vaadin/web-components?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
[![Published on Vaadin Directory](https://img.shields.io/badge/Vaadin%20Directory-published-00b4f0.svg)](https://vaadin.com/directory/component/vaadinapollo-pdf-viewer)
[![Stars on vaadin.com/directory](https://img.shields.io/vaadin-directory/star/apollo-pdf-viewer-directory-urlidentifier.svg)](https://vaadin.com/directory/component/vaadinapollo-pdf-viewer)
<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="apollo-pdf-viewer.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<apollo-pdf-viewer>
  ...
</apollo-pdf-viewer>
```

[<img src="https://raw.githubusercontent.com/vaadin/apollo-pdf-viewer/master/screenshot.png" width="200" alt="Screenshot of apollo-pdf-viewer">](https://vaadin.com/components/apollo-pdf-viewer)


## Installation

The Vaadin components are distributed as Bower and npm packages.
Please note that the version range is the same, as the API has not changed.
You should not mix Bower and npm versions in the same application, though.

Unlike the official Polymer Elements, the converted Polymer 3 compatible Vaadin components
are only published on npm, not pushed to GitHub repositories.

### Polymer 2 and HTML Imports compatible version

Install `apollo-pdf-viewer`:

```sh
bower i vaadin/apollo-pdf-viewer --save
```

Once installed, import it in your application:

```html
<link rel="import" href="bower_components/apollo-pdf-viewer/apollo-pdf-viewer.html">
```
### Polymer 3 and ES Modules compatible version


Install `apollo-pdf-viewer`:

```sh
npm i @vaadin/apollo-pdf-viewer --save
```

Once installed, import it in your application:

```js
import '@vaadin/apollo-pdf-viewer/apollo-pdf-viewer.js';
```

## Getting started

Vaadin components use the Lumo theme by default.

To use the Material theme, import the correspondent file from the `theme/material` folder.

## Entry points

- The component with the Lumo theme:

  `theme/lumo/apollo-pdf-viewer.html`

- The component with the Material theme:

  `theme/material/apollo-pdf-viewer.html`

- Alias for `theme/lumo/apollo-pdf-viewer.html`:

  `apollo-pdf-viewer.html`


## Running demos and tests in browser

1. Fork the `apollo-pdf-viewer` repository and clone it locally.

1. Make sure you have [npm](https://www.npmjs.com/) installed.

1. When in the `apollo-pdf-viewer` directory, run `npm install` and then `bower install` to install dependencies.

1. Make sure you have [polymer-cli](https://www.npmjs.com/package/polymer-cli) installed globally: `npm i -g polymer-cli`.

1. Run `npm start`, browser will automatically open the component API documentation.

1. You can also open demo or in-browser tests by adding **demo** or **test** to the URL, for example:

  - http://127.0.0.1:8080/components/apollo-pdf-viewer/demo
  - http://127.0.0.1:8080/components/apollo-pdf-viewer/test


## Running tests from the command line

1. When in the `apollo-pdf-viewer` directory, run `polymer test`


## Following the coding style

We are using [ESLint](http://eslint.org/) for linting JavaScript code. You can check if your code is following our standards by running `gulp lint`, which will automatically lint all `.js` files as well as JavaScript snippets inside `.html` files.


## Big Thanks

Cross-browser Testing Platform and Open Source <3 Provided by [Sauce Labs](https://saucelabs.com).


## Contributing

  To contribute to the component, please read [the guideline](https://github.com/vaadin/vaadin-core/blob/master/CONTRIBUTING.md) first.


## License

Apache License 2.0

Vaadin collects development time usage statistics to improve this product. For details and to opt-out, see https://github.com/vaadin/vaadin-usage-statistics.
