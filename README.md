#Prettier config

Prettier config to have persistent format across projects

## Install

```
npm install --save-dev @nguyennk92/prettier-config
```

## Usage

```
// package.json
{
  ...
  prettier: "@nguyennk92/prettier-config"
}

// or for override
// .prettierrc.js
module.exports = {
  ...require("@nguyennk92/prettier-config"),
  semi: false,
};
```
