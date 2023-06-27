# prettier-config

> Personal Prettier config

## Installation
### Only Prettier
Install `@wardes/config-prettier`:
``` bash
npm i -D prettier @wardes/prettier-config
```

``` bash
yarn add -D prettier @wardes/prettier-config
```

``` bash
pnpm add -D prettier @wardes/prettier-config
```

Add the following to your `package.json`:

```json
{
  "prettier": "@wardes/prettier-config"
}
```

<br/>

### Prettier & Eslint
If you want to use this config with eslint, you must install `eslint-config-prettier`
```bash
npm i -D prettier @wardes/prettier-config eslint-config-prettier 
```

```bash
yarn add -D prettier @wardes/prettier-config eslint-config-prettier 
```

```bash
pnpm add -D prettier @wardes/prettier-config eslint-config-prettier 
```

And add it to your eslint config:
```json
{
  "extends": [
    "some-other-config-you-use",
    "prettier"
  ]
}
```
