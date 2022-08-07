# @santigp258/simplify
Extracts [Path#simplify()](http://paperjs.org/reference/path/#simplify) from Paper.js
## Installation

```bash
npm install @santigp258/simplify
```

or
```bash
yarn add @santigp258/simplify
```
## API
```ts
simplifySvgPath(
  points: [x: number, y: number][], // `{ x: number, y: number }[]` is also acceptable
  {
    tolerance: number = 2.5,
    precision: number = 5,
  } = {}
): string
// SVG path command string such as
// "M10,10c0,3.33333 -2.35702,7.64298 0,10c2.35702,2.35702 6.66667,0 10,0"
```
## Note
This repo is a fork of [@luncheon/simplify-svg-path](https://github.com/luncheon/simplify-svg-path#readme)

Also The logic is a copy of [Paper.js](https://github.com/paper.js) `v0.12.11.`
