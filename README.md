# g-pages

[![NPM Downloads][downloads-image]][downloads-url]
[![NPM Version][version-image]][version-url]
[![License][license-image]][license-url]
[![Dependency Status][dependency-image]][dependency-url]
[![devDependency Status][devdependency-image]][devdependency-url]
[![Code Style][style-image]][style-url]

> static web app workflow

## Installation

```shell
$ npm install g-pages

# or yarn
$ yarn add g-pages
```

## Usage

<!-- TODO: Introduction of API use -->

```javascript
const gPages = require('g-pages')
const result = gPages('zce')
// result => 'zce@zce.me'
```

## API

<!-- TODO: Introduction of API -->

### gPages(name[, options])

#### name

- Type: `string`
- Details: name string

#### options

##### host

- Type: `string`
- Details: host string
- Default: `'zce.me'`

## Contributing

1. **Fork** it on GitHub!
2. **Clone** the fork to your own machine.
3. **Checkout** your feature branch: `git checkout -b my-awesome-feature`
4. **Commit** your changes to your own branch: `git commit -am 'Add some feature'`
5. **Push** your work back up to your fork: `git push -u origin my-awesome-feature`
6. Submit a **Pull Request** so that we can review your changes.

> **NOTE**: Be sure to merge the latest from "upstream" before making a pull request!

## License

[MIT](LICENSE) &copy; George <xiaoju.zh@qq.com>



[downloads-image]: https://img.shields.io/npm/dm/g-pages.svg
[downloads-url]: https://npmjs.org/package/g-pages
[version-image]: https://img.shields.io/npm/v/g-pages.svg
[version-url]: https://npmjs.org/package/g-pages
[license-image]: https://img.shields.io/github/license/George/g-pages.svg
[license-url]: https://github.com/George/g-pages/blob/master/LICENSE
[dependency-image]: https://img.shields.io/david/George/g-pages.svg
[dependency-url]: https://david-dm.org/George/g-pages
[devdependency-image]: https://img.shields.io/david/dev/George/g-pages.svg
[devdependency-url]: https://david-dm.org/George/g-pages?type=dev
[style-image]: https://img.shields.io/badge/code_style-standard-brightgreen.svg
[style-url]: https://standardjs.com
