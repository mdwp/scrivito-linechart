# Scrivito Linechart
[![CMS: Scrivito](https://img.shields.io/badge/CMS-Scrivito-brightgreen.svg)](https://scrivito.com) [![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

A linechart React component/Scrivito widget for the Scrivito CMS.

## Screenshot

![Screenshot](https://raw.githubusercontent.com/mdwp/scrivito-linechart/master/linechart-screenshot.png)

## Installation

Open your terminal.

`$ cd` to your Scrivito project

```shell
$ npm install scrivito-linechart
```

Import the widget in your javascript (e.g. in `index.js` or `Widgets/index.js`).

Add this line to your index.js:

```js
import "scrivito-linechart";
```

## Features

Linechart for normal, dashed or vertical lines..

## Widget properties

In the widget properties you can set:

- Chart type
- Labels for two comparable values e.g. Foo, Bar
- Chart values
  - Name e.g. 'January', 'February' ...
  - Value (number) for 'January'
  - Value (number) for 'February'
  - ...