# unXSS
=========

>Library to provide utility methods to escape and unescape HTML entitiesand save you from XSS attacks.

### Installation

  npm install unxss --save

### Usage
```
  var unxss = require('unxss')
      escape = unxss.escape,
      unescape = unxss.unescape;

  var html = `<h1>Hello World</h1>`,
      escaped = escape(html),
      unescaped = unescape(escaped);

  console.log('html', html, 'escaped', escaped, 'unescaped', unescaped);
```
### Tests

  npm `test`

###License

>MIT
