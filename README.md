# reqsrc
The stupidest npm package ever seen for the laziest people ever 

```
$ npm install reqsrc --save
```

Then you are free to be really lazy in importing files from ./src directory
```javascript
const req = require('reqsrc')

const lib = req('library') // require ./src/library.js
```