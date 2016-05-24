# Orgztion Services shared eslint-config
Use on `ES2015`, `ES.next` and `React` projects.

# Based on shared `standard` eslint-config
* [eslint-config-standard](https://github.com/feross/eslint-config-standard)
* [eslint-config-standard-react](https://github.com/feross/eslint-config-standard-react)

## Install

```sh
npm install --save-dev https://github.com/orgztion/eslint-config-orgztion-services.git#master
```

# dependencies
```
npm install --save-dev babel-eslint eslint-config-standard
 eslint-config-standard-react eslint-plugin-react eslint-plugin-promise eslint-plugin-standard
```

## Use

In your project's `.eslintrc`, use the `extends` feature:

```json
{
  "extends": ["eslint-config-orgztion-services"]
}
```
