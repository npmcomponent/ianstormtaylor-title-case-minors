*This repository is a mirror of the [component](http://component.io) module [ianstormtaylor/title-case-minors](http://github.com/ianstormtaylor/title-case-minors). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/ianstormtaylor-title-case-minors`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# title-case-minors

  A list of the minor words that shouldn't be capitalized in a title case string.

## Installation

    $ component install ianstormtaylor/title-case-minors
    $ npm install title-case-minors

## Example

```js
var minors = require('title-case-minors');

for (var i = 0; i < minors.length; i++) console.log(minors[i]);
// "a"
// "an"
// "and"
// "as"
// "at"
// ...
```

## License

  MIT
