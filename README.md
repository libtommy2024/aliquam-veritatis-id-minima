# @libtommy2024/aliquam-veritatis-id-minima <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Get the byte length of an ArrayBuffer, even in engines without a `.byteLength` method.

## Example

```js
const assert = require('assert');
const byteLength = require('@libtommy2024/aliquam-veritatis-id-minima');

assert.equal(byteLength([]), NaN, 'an array is not an ArrayBuffer, yields NaN');

assert.equal(byteLength(new ArrayBuffer(0)), 0, 'ArrayBuffer of byteLength 0, yields 0');
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@libtommy2024/aliquam-veritatis-id-minima
[npm-version-svg]: https://versionbadg.es/inspect-js/@libtommy2024/aliquam-veritatis-id-minima.svg
[deps-svg]: https://david-dm.org/inspect-js/@libtommy2024/aliquam-veritatis-id-minima.svg
[deps-url]: https://david-dm.org/inspect-js/@libtommy2024/aliquam-veritatis-id-minima
[dev-deps-svg]: https://david-dm.org/inspect-js/@libtommy2024/aliquam-veritatis-id-minima/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@libtommy2024/aliquam-veritatis-id-minima#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@libtommy2024/aliquam-veritatis-id-minima.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@libtommy2024/aliquam-veritatis-id-minima.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@libtommy2024/aliquam-veritatis-id-minima.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@libtommy2024/aliquam-veritatis-id-minima
[codecov-image]: https://codecov.io/gh/inspect-js/@libtommy2024/aliquam-veritatis-id-minima/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@libtommy2024/aliquam-veritatis-id-minima/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@libtommy2024/aliquam-veritatis-id-minima
[actions-url]: https://github.com/libtommy2024/aliquam-veritatis-id-minima/actions
