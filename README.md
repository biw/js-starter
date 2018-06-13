# js-starter

[![Build Status][build-badge]][build]
[![twitter][twitter-badge]][twitter]
<!-- [![version][version-badge]][package] -->
<!-- [![MIT License][license-badge]][license]  -->

A bare-bone repo that has all the files you need to start a new JS library or project with [Babel](https://babeljs.io/), [ESLint](https://eslint.org/), [Prettier](https://github.com/prettier/prettier), [Jest](https://facebook.github.io/jest/), [Travis CI](https://travis-ci.org/), & [Rollup](https://github.com/rollup/rollup). Not trying to do anything magical or novel here, just have found this configuration works well for me.

## Install

```sh
git clone https://github.com/biw/js-starter [project-name]
cd [project-name]
rm -rf .git && git init . # restart git since you don't want js-starter's history
yarn
```

where `[project-name]` is the name of your new project.

Then,

 - Change the LICENSE
 - Update info in `package.json`
 - Review `.babelrc` targets
 - Update this README

## Commands

 - test: `yarn test`
 - run development build: `yarn start`
 - lint & prettier: `yarn lint`
 - build package: `yarn build`
 - reinstall: `yarn reinstall`

## LICENSE

MIT © [Ben Williams](https://719ben.com)


[build-badge]: https://img.shields.io/travis/biw/js-starter.svg?style=flat-square
[build]: https://travis-ci.org/biw/js-starter
[version-badge]: https://img.shields.io/npm/v/js-starte.svg?style=flat-square
[package]: https://www.npmjs.com/package/seal-store
[license-badge]: https://img.shields.io/npm/l/js-starter.svg?style=flat-square
[license]: https://github.com/biw/js-starter/blob/master/LICENSE
[twitter-badge]: https://img.shields.io/twitter/follow/719ben.svg?style=flat-square&logo=twitter&label=Follow
[twitter]: https://twitter.com/719ben
