# es-logical-or-operator
Implementation of the `||` operator as a function (`|| in fp`).

## Installation
```bash
npm install es-logical-or-operator
```
or
```bash
yarn add es-logical-or-operator
```

## Usage
```js
const or = require("es-logical-or-operator")
console.log(or(true, false)) // true
console.log(or(false, true)) // true
console.log(or(false, false)) // false
console.log(or(true, true)) // true
console.log(or(1, 2)) // 1
console.log(or(0, 1)) // 1
```

## License
[EGPSL10X-1.0](https://github.com/10xEngineersQualityProgramming/EGPSL10X-1.0) Licensed