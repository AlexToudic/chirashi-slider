[![chirashi](./logo.png)](https://chirashi.js.org)

[![npm version](https://badge.fury.io/js/chirashi.svg)](https://badge.fury.io/js/chirashi)
[![Standard - JavaScript Style Guide](https://img.shields.io/badge/code%20style-standard-brightgreen.svg)](http://standardjs.com/)
[![Code Climate](https://codeclimate.com/github/chirashijs/chirashi/badges/gpa.svg)](https://codeclimate.com/github/chirashijs/chirashi)
[![Issue Count](https://codeclimate.com/github/chirashijs/chirashi/badges/issue_count.svg)](https://codeclimate.com/github/chirashijs/chirashi)
[![Test Coverage](https://codeclimate.com/github/chirashijs/chirashi/badges/coverage.svg)](https://codeclimate.com/github/chirashijs/chirashi/coverage)
[![Build Status](https://travis-ci.org/chirashijs/chirashi.svg?branch=master)](https://travis-ci.org/chirashijs/chirashi)

## Intro

Chirashi.js is a utils library meant to make DOM manipulation and events management easier and faster to read and write without adding overcomplecated internal logic.

The library designed as modules of single functions allowing to reduce size of your production build to only the needed code (thanks to [esnext modules](https://github.com/dherman/defense-of-dot-js/blob/master/proposal.md)).

## Get started

Find API documentation, guide and more on [chirashi.js.org](http://chirashi.js.org).

## Quick view

### Installation

#### Using npm / yarn (recommended)

```
yarn add chirashi
```
or
```
npm i --save chirashi
```

Now you can import methods in your project:

```js
import { ready, append } from 'chirashi'

ready(() => {
  append(document.body, '<h1>Hello World!</h1>')
})
```

#### Standalone

You can download [chirashi.js](https://github.com/chirashijs/chirashi/releases/download/6.5.0/chirashi.js) or [chirashi.min.js](https://github.com/chirashijs/chirashi/releases/download/6.5.0/chirashi.min.js) and load it using a script tag. You can also use CDN version of those files from unpkg using the link [https://unpkg.com/chirashi@6.5.0/dist/chirashi.min.js](https://unpkg.com/chirashi@6.5.0/dist/chirashi.min.js). It'll create an instance of Chirashi on your window. Then use as following example

```js
Chirashi.ready(function () {
  Chirashi.append(document.body, '<h1>Hello World!</h1>')
})
```
