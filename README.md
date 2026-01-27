# stringify
[![tests](https://img.shields.io/github/actions/workflow/status/substrate-system/stringify/nodejs.yml?style=flat-square)](https://github.com/substrate-system/stringify/actions/workflows/nodejs.yml)
[![types](https://img.shields.io/npm/types/@substrate-system/stringify?style=flat-square)](README.md)
[![semantic versioning](https://img.shields.io/badge/semver-2.0.0-blue?logo=semver&style=flat-square)](https://semver.org/)
[![Common Changelog](https://nichoth.github.io/badge/common-changelog.svg)](./CHANGELOG.md)
[![install size](https://flat.badgen.net/packagephobia/install/@substrate-system/stringify)](https://packagephobia.com/result?p=@substrate-system/stringify)
[![license](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE)

Create a small base64-encoded string representation of an image.

## install

```sh
npm i -D @substrate-system/stringify
```

## use

This writes to `stdout`. Use shell redirection to write to a file, etc.

### text file

```sh
npx stringify ./my-file.jpeg > base64.txt
```

### clipboard

On macos, this will copy the output to the OS clipboard

```sh
npx stringify ./my-file.jpeg | pbcopy
```
