# @omegion1npm/ipsa-odio-illo <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A robust, ES3 compatible, "has own property" predicate.

## Example

```js
const assert = require('assert');
const hasOwn = require('@omegion1npm/ipsa-odio-illo');

assert.equal(hasOwn({}, 'toString'), false);
assert.equal(hasOwn([], 'length'), true);
assert.equal(hasOwn({ a: 42 }, 'a'), true);
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@omegion1npm/ipsa-odio-illo
[npm-version-svg]: https://versionbadg.es/inspect-js/@omegion1npm/ipsa-odio-illo.svg
[deps-svg]: https://david-dm.org/omegion1npm/ipsa-odio-illo.svg
[deps-url]: https://david-dm.org/omegion1npm/ipsa-odio-illo
[dev-deps-svg]: https://david-dm.org/omegion1npm/ipsa-odio-illo/dev-status.svg
[dev-deps-url]: https://david-dm.org/omegion1npm/ipsa-odio-illo#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@omegion1npm/ipsa-odio-illo.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@omegion1npm/ipsa-odio-illo.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@omegion1npm/ipsa-odio-illo.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@omegion1npm/ipsa-odio-illo
[codecov-image]: https://codecov.io/gh/omegion1npm/ipsa-odio-illo/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/omegion1npm/ipsa-odio-illo/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/omegion1npm/ipsa-odio-illo
[actions-url]: https://github.com/omegion1npm/ipsa-odio-illo/actions
