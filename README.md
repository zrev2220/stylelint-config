# `@zrev2220/stylelint-config`

![npm (scoped)](https://img.shields.io/npm/v/@zrev2220/stylelint-config)

My personal Stylelint config.

## Usage

Install:

```bash
npm install --save-dev stylelint @zrev2220/stylelint-config
```

Create/edit `.stylelintrc`:

```jsonc
{
  "extends": "@zrev2220/stylelint-config"
}
```

Lint your styles:

```bash
npx stylelint -i .gitignore --aei --mw 0 "**/*.{css,scss}"
```

See also the [`extends` config property](https://stylelint.io/user-guide/configure#extends).
