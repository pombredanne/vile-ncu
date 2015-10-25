# vile-ncu

A [vile](http://vile.io) plugin for [npm-check-updates](https://github.com/tjunnone/npm-check-updates).

## Requirements

- [nodejs](http://nodejs.org)
- [npm](http://npmjs.org)

## Installation

    npm i vile-ncu

## Restrictions

Currently, you need to have your `package.json` in your `pwd`.

## Architecture

- `src` is es6+ syntax compiled with [babel](https://babeljs.io)
- `lib` generated js library

## Hacking

    cd vile-ncu
    npm install
    npm run dev
    npm test
