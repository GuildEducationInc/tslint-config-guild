![npm](https://img.shields.io/npm/v/tslint-config-guild.svg)

# DEPRECATED

As [tslint is being deprecated in favor of eslint](https://medium.com/palantir/tslint-in-2019-1a144c2317a9), we have transitioned [our eslint config](https://github.com/GuildEducationInc/eslint-config-guild) to now support TypeScript

# Guild Education TypeScript Style

At Guild, our TypeScript style is based on [JavaScript Standard Style](https://standardjs.com/rules.html) with a few exceptions:

- Function declarations should not have a space before the parentheses:
  ```javascript
  function name (arg) { ... } // ✗ avoid
  function name(arg) { ... } // ✓ ok
  ```
## Install

```bash
yarn add --dev tslint-config-guild
```

## Usage

To use the Guild TypeScript Style config, first add `tslint` to your project:

```bash
yarn add --dev tslint
```

Then, add this to your `tslint.json` file:
```json
{
  "extends": "tslint-config-guild"
}
```
