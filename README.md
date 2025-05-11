[![Release](https://github.com/asd-xiv/prettier-config/actions/workflows/release.yml/badge.svg?branch=main)](https://github.com/asd-xiv/prettier-config/actions/workflows/release.yml)
[![npm version](https://img.shields.io/npm/v/@asd14/prettier-config.svg)](https://www.npmjs.com/package/@asd14/prettier-config)

# @asd14/prettier-config

> ASD14's reusable Prettier configuration.

<!-- vim-markdown-toc GFM -->

* [Installation](#installation)
* [Usage](#usage)
* [Configuration Details](#configuration-details)
* [Peer dependencies](#peer-dependencies)
* [License](#license)

<!-- vim-markdown-toc -->

## Installation

```sh
npm install --save-dev @asd14/prettier-config prettier@^3
```

## Usage

In your your `.prettierrc`:

```json
"@asd14/prettier-config"
```

## Configuration Details

```json
{
  "printWidth": 80,
  "tabWidth": 2,
  "useTabs": false,
  "semi": false,
  "singleQuote": false,
  "quoteProps": "consistent",
  "jsxSingleQuote": false,
  "trailingComma": "es5",
  "bracketSpacing": true,
  "bracketSameLine": true,
  "arrowParens": "avoid",
  "proseWrap": "always",
  "endOfLine": "lf"
}
```

## Peer dependencies

This package requires and assumes you already installed:

```json
  "peerDependencies": {
    "prettier": "^3"
  },
```

## License

MIT
