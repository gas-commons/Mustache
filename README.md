# Mustache.gs
Mustache.js for Googe Apps Script

## Usage
### Add library
project key: `13re0EpD6XiVa5zHXndGiYtcH-QMnbeE5MJH190pJ8xCYhmuW5sX2ZO5R`

### Use in your script
```js
var template = '{{title}} spends {{calc}}'
var data = {
  title: 'Joe',
  calc: function () {
    return 2 + 4;
  }
}

var output = Mustache.render(template, data)  //Joe spends 6
```

## Reference
* [janl/mustache.js](https://github.com/janl/mustache.js)
