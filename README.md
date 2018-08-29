# eslint-config-web-app
![npm version](https://img.shields.io/npm/v/eslint-config-web-app.svg)

Eslint configration for web apps.

## usage

```sh
npm install -D eslint-config-web-app
```

```js
// .eslintrc.js
module.exports = {
  extends: ['web-app']
};
```

如果需要关闭规则，则在上面添加 `rules` 规则，修改后的如下所示

```js
module.exports = {
    extends: ['web-app'],
    rules: {
        'no-console': 'off',
        'no-case-declarations': 'off'
    }
};
```



