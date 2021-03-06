# @lukaszbieniek/prettier-config

Shareable [prettier](https://prettier.io/) config

[![npm-version](https://img.shields.io/npm/v/@lukaszbieniek/prettier-config)](https://www.npmjs.com/package/@lukaszbieniek/prettier-config)
[![npm-license](https://img.shields.io/npm/l/@lukaszbieniek/prettier-config)](https://www.npmjs.com/package/@lukaszbieniek/prettier-config)
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)

### Usage

Install package:

```sh
$ npm install --save-dev prettier @lukaszbieniek/prettier-config
```

Extend your config file:

```js
// .prettierrc.js
module.exports = {
  ...require('@lukaszbieniek/prettier-config'),
}
```

### License

See [LICENSE](./LICENSE) file for details.
