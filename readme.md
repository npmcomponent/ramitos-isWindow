*This repository is a mirror of the [component](http://component.io) module [ramitos/iswindow](http://github.com/ramitos/iswindow). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/ramitos-iswindow`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# isWindow

based on [jquery/jquery](https://github.com/jquery/jquery/blob/a5037cb9e3851b171b49f6d717fb40e59aa344c2/src/core.js#L226-L228)

## install

```bash
component install isWindow
```

## api

```js
var isWindow = require('isWindow')

isWindow(document.body) // => false
isWindow(window) // => true
```