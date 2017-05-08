# eslint-config-fbjs-extended

[![Build Status][travis-image]][travis-url]

[fbjs/opensource][fbjs] eslint config, extended with the following plugins:

- [import][import]
- [filenames][filenames]
- [unicorn][unicorn]

See [rules.json](./rules.json) for the actual config used

## Usage

- `npm install --save-dev eslint-config-fbjs-extended`
- Extend from `fbjs-extended` in your eslint config

## License

MIT - see [LICENSE][license-url]

[travis-image]: https://travis-ci.org/claudiorodriguez/eslint-config-fbjs-extended.svg?branch=master
[travis-url]: https://travis-ci.org/claudiorodriguez/eslint-config-fbjs-extended
[import]: https://github.com/benmosher/eslint-plugin-import
[filenames]: https://github.com/selaux/eslint-plugin-filenames
[unicorn]: https://github.com/sindresorhus/eslint-plugin-unicorn
[fbjs]: https://github.com/facebook/fbjs/tree/master/packages/eslint-config-fbjs
[license-url]: ./LICENSE
