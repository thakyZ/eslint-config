# @thakyz/eslint-config

<h3>Pluggable [ESLint](https://eslint.org/docs/about/) [configs](https://eslint.org/docs/developer-guide/shareable-configs) for [ECMAScript Next](https://kangax.github.io/compat-table/esnext), [Node.js](https://nodejs.org) and [React Native](https://facebook.github.io/react-native) that you can import, extend and override</h3>

<h3>Updated outdated and deprecated packages.</h3>

[![Join the chat at https://gitter.im/thakyz/eslint-config][gitter-img]][gitter-url]
[![npm version][version-img]][npm-url]
[![npm downloads][downloads-img]][npm-url]
[![GitHub issues][issues-img]][issues-url]
[![Deps][deps-img]][deps-url]
[![Dev Deps][devdeps-img]][deps-url]

## Usage

See individual packages

- [Recommended](https://github.com/thakyz/eslint-config/tree/master/packages/recommended)
- [ESNext](https://github.com/thakyz/eslint-config/tree/master/packages/esnext)
- [Node.js](https://github.com/thakyz/eslint-config/tree/master/packages/node)
- [React Native](https://github.com/thakyz/eslint-config/tree/master/packages/react-native)

To add a git-hook to your commits, consider using [husky](https://github.com/typicode/husky)

```shell
npm install --save-dev husky
```

And in your `package.json`:

```json
  "scripts": {
    "precommit": "eslint ."
  }
```

---

### Config

These configs are biased and opinionated, and err on the side of too many rules instead of too few. Think of them as a superset of your repo's lint config, and discard what you don't like in them. It's easy to override and disable the rules you find inconvenient.

- [Recommended](https://github.com/thakyz/eslint-config/tree/master/packages/recommended)
- [ESNext](https://github.com/thakyz/eslint-config/tree/master/packages/esnext)
- [ESNext Style Guide](https://github.com/thakyz/eslint-config/tree/master/packages/esnext/style-guide)
- [Node.js](https://github.com/thakyz/eslint-config/tree/master/packages/node)
- [Node.js Style Guide](https://github.com/thakyz/eslint-config/tree/master/packages/node/style-guide)
- [React Native](https://github.com/thakyz/eslint-config/tree/master/packages/react-native)
- [React Native Style Guide](https://github.com/thakyz/eslint-config/tree/master/packages/react-native/style-guide)

[gitter-img]: https://badges.gitter.im/thakyz/eslint-config.svg
[gitter-url]: https://gitter.im/thakyz/eslint-config?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge
[version-img]: https://img.shields.io/npm/v/eslint-config-recommended.svg
[npm-url]: https://www.npmjs.com/package/eslint-config-recommended
[downloads-img]: https://img.shields.io/npm/dt/eslint-config-recommended.svg
[issues-img]: https://img.shields.io/github/issues-raw/thakyz/eslint-config.svg?maxAge=2592000
[issues-url]: https://github.com/thakyz/eslint-config/issues
[deps-img]: https://img.shields.io/david/thakyz/eslint-config.svg
[devdeps-img]: https://img.shields.io/david/dev/thakyz/eslint-config.svg
[deps-url]: https://github.com/thakyz/eslint-config/blob/master/package.json
