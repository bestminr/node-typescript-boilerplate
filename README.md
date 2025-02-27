# @bestminr/node-typescript

Minimalistic boilerplate to jump-start a [Node.js][nodejs] project in [TypeScript][typescript] [3.7][typescript-37].

What's included:

+ [TypeScript][typescript] [3.7][typescript-37],
+ [TSLint][tslint] with [Microsoft rules][tslint-microsoft-contrib],
+ [Jest][jest] unit testing and code coverage,
+ Type definitions for Node.js and Jest,
+ [Prettier][prettier] to enforce a consistent code style,
+ [NPM scripts for common operations](#available-scripts),
+ a simple example of TypeScript code and unit test,
+ .editorconfig for consistent file format.

## Quick start

This project is intended to be used with the latest Active LTS release of [Node.js][nodejs].

To start, just click the **[Use template][repo-template-action]** link (or the green button),

or clone the repository with following commands:

```sh
git clone https://github.com/bestminr/node-typescript-boilerplate
cd node-typescript-boilerplate
npm install
```

or download and unzip current `master` branch:

```sh
wget https://github.com/bestminr/node-typescript-boilerplate/archive/master.zip -O node-typescript-boilerplate.zip
unzip node-typescript-boilerplate.zip && rm node-typescript-boilerplate.zip
```

Now start adding your code in the `src` and unit tests in the `__tests__` directories. Have fun and build amazing things 🚀

## Available scripts

+ `clean` - remove coverage data, Jest cache and transpiled files,
+ `dev` - transpile TypeScript to ES6 and watch
+ `build` - transpile TypeScript to ES6,
+ `build:watch` - interactive watch mode to automatically transpile source files,
+ `lint` - lint source files and tests,
+ `test` - run tests,
+ `test:watch` - interactive watch mode to automatically re-run tests

## License
Licensed under the APLv2. See the [LICENSE](https://github.com/bestminr/node-typescript-boilerplate/blob/master/LICENSE) file for details.

[ts-badge]: https://img.shields.io/badge/TypeScript-3.7-blue.svg
[nodejs-badge]: https://img.shields.io/badge/Node.js->=%2012.13-blue.svg
[nodejs]: https://nodejs.org/dist/latest-v12.x/docs/api/
[travis-badge]: https://travis-ci.org/bestminr/node-typescript-boilerplate.svg?branch=master
[travis-ci]: https://travis-ci.org/bestminr/node-typescript-boilerplate
[typescript]: https://www.typescriptlang.org/
[typescript-37]: https://www.typescriptlang.org/docs/handbook/release-notes/typescript-3-7.html
[license-badge]: https://img.shields.io/badge/license-APLv2-blue.svg
[license]: https://github.com/bestminr/node-typescript-boilerplate/blob/master/LICENSE

[donate-badge]: https://img.shields.io/badge/☕-buy%20me%20a%20coffee-46b798.svg
[donate]: https://paypal.me/jaqb/5eur

[jest]: https://facebook.github.io/jest/
[tslint]: https://palantir.github.io/tslint/
[tslint-microsoft-contrib]: https://github.com/Microsoft/tslint-microsoft-contrib
[wiki-js-tests]: https://github.com/bestminr/node-typescript-boilerplate/wiki/Unit-tests-in-plain-JavaScript
[prettier]: https://prettier.io

[repo-template-action]: https://github.com/bestminr/node-typescript-boilerplate/generate
