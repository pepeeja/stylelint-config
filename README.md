# @pepeeja/stylelint-config

[![license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/pepeeja/stylelint-config/blob/main/LICENSE) [![npm latest package](https://img.shields.io/npm/v/@pepeeja/stylelint-config/latest.svg)](https://www.npmjs.com/package/@pepeeja/stylelint-config)

Stylelint setup for projects

## Install

```shell
// with npm
npm install @pepeeja/stylelint-config

// with yarn
yarn add @pepeeja/stylelint-config
```

## Usage

Stylelint configuration has several options based on used environment. You can find list of available configurations below.

### Standard

Create `.stylelintrc` file in the root directory of your project with the following content:

```json
{
  "extends": "@pepeeja/stylelint-config"
}
```

### SCSS

To apply React specific rules there is additional configuration which is inherited from standard one.
Create `.stylelintrc` file in the root directory of your project with the following content:

```json
{
  "extends": "@pepeeja/stylelint-config/scss"
}
```

## License

This project is licensed under the terms of the [MIT License](LICENSE)
