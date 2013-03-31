# sjis.js
Convert Shift-JIS codes from/to String in JavaScript.

## Usage
Use sjis.js or sjis.min.js.

* https://raw.github.com/r7kamura/sjis.js/master/js/sjis.js
* https://raw.github.com/r7kamura/sjis.js/master/js/sjis.min.js

```js
Sjis.fromArrayToString([
  130,
  177,
  130,
  241,
  130,
  201,
  130,
  191,
  130,
  205,
]);
//=> "こんにちは"

Sjis.fromStringToArray("こんにちは")
//=> [130, 177, 130, 241, 130, 201, 130, 191, 130, 205]
```

## Document
http://r7kamura.github.com/sjis.js/docs/sjis.html
