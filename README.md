# unXSS
=========

>Library to provide utility methods to escape and unescape HTML entitiesand save you from XSS attacks.

### Installation

  npm install scapegoat --save

### Usage
```
  var scapegoat = require('scapegoat')
      escape = scapegoat.escape,
      unescape = scapegoat.unescape;

  var html = `<h1>Hello World</h1>`,
      escaped = escape(html),
      unescaped = unescape(escaped);

  console.log('html', html, 'escaped', escaped, 'unescaped', unescaped);
```
### Tests

  npm `test`

###License

>MIT
