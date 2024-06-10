# @erboladaiorg/totam-mollitia-tenetur <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Give a regex, get a robust predicate function that tests it against a string. This will work even if `RegExp.prototype` is altered later.

## Getting started

```sh
npm install --save @erboladaiorg/totam-mollitia-tenetur
```

## Usage/Examples

```js
var regexTester = require('@erboladaiorg/totam-mollitia-tenetur');
var assert = require('assert');

var tester = regexTester('a');
assert.ok(tester('a'));
assert.notOk(tester('b'));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@erboladaiorg/totam-mollitia-tenetur
[npm-version-svg]: https://versionbadg.es/ljharb/@erboladaiorg/totam-mollitia-tenetur.svg
[deps-svg]: https://david-dm.org/ljharb/@erboladaiorg/totam-mollitia-tenetur.svg
[deps-url]: https://david-dm.org/ljharb/@erboladaiorg/totam-mollitia-tenetur
[dev-deps-svg]: https://david-dm.org/ljharb/@erboladaiorg/totam-mollitia-tenetur/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@erboladaiorg/totam-mollitia-tenetur#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@erboladaiorg/totam-mollitia-tenetur.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@erboladaiorg/totam-mollitia-tenetur.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@erboladaiorg/totam-mollitia-tenetur.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@erboladaiorg/totam-mollitia-tenetur
[codecov-image]: https://codecov.io/gh/ljharb/@erboladaiorg/totam-mollitia-tenetur/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@erboladaiorg/totam-mollitia-tenetur/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@erboladaiorg/totam-mollitia-tenetur
[actions-url]: https://github.com/erboladaiorg/totam-mollitia-tenetur/actions
