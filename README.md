# @nvitaterna/eslint-config-prettier

Airbnb's ESLint config with a couple small tweaks and prettier integration.

# How to use
Install `typescript`, `eslint` `prettier`, and `@nvitaterna/eslint-config-prettier` and put it into your `.eslintrc.js` and `.prettierrc.js`.

```bash
$ npm install typescript eslint prettier @nvitaterna/eslint-config-prettier --save-dev
```

`.eslintrc.js`

```js
module.exports = {
  extends: "@nvitaterna/eslint-config-prettier"
};
```

`.prettierrc.js`

```js
module.exports = {
  ...require('@nvitaterna/eslint-config-prettier/.prettierrc.js'),
};

```
