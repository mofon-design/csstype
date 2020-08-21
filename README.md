# CSSType

[![npm](https://img.shields.io/npm/v/@mofon-design/csstype.svg)](https://www.npmjs.com/package/@mofon-design/csstype)

TypeScript definitions for CSS, fork from https://github.com/frenic/csstype.

```ts
import { CSSType } from '@mofon-design/csstype';

const style: CSSType.Properties = {
  colour: 'white', // Type error on property
  textAlign: 'middle', // Type error on value
};
```

## Getting started

```sh
$ npm install @mofon-design/csstype
$ # or
$ yarn add @mofon-design/csstype
```
