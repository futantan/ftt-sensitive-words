## npm-package demo

```js
const senstiveWords = require('ftt-sensitive-words').default
const filtered = senstiveWords(
  'The new apple macbook pro will have a touchbar',
  ['pro', 'touchbar']
)
console.log(filtered)
// The new apple macbook *** will have a ***
```