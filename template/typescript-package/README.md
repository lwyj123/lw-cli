# {{_ "startCase" name}}

![Issues](https://img.shields.io/github/issues/{{owner}}/{{name}}.svg)
[![NPM version](https://img.shields.io/npm/v/{{#scoped}}@{{owner}}/{{/scoped}}{{name}}.svg)](https://www.npmjs.com/package/{{#scoped}}@{{owner}}/{{/scoped}}{{name}})

{{description}}

## Install

```shell
$ npm install --save {{#scoped}}@{{owner}}/{{/scoped}}{{name}}
```

## Usage

```js
import {{_ "camelCase" name}} from '{{#scoped}}@{{owner}}/{{/scoped}}{{name}}';

{{_ "camelCase" name}} (); // result
```

## License

MIT © {{author}}
