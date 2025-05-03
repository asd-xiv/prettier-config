# @asd14/prettier-config

> ASD14's reusable Prettier configuration for consistent code formatting.

<!-- vim-markdown-toc GFM -->

* [Installation](#installation)
* [Usage](#usage)
* [Configuration Details](#configuration-details)
* [Peer Dependency](#peer-dependency)
* [License](#license)

<!-- vim-markdown-toc -->

## Installation

Install via npm:

```sh
npm install --save-dev @asd14/prettier-config
```

## Usage

In your project, extend this config in your `.prettierrc`:

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

## Peer Dependency

- **Prettier**: This config requires Prettier version ^3.

## License

MIT
