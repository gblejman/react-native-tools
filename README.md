# react-native-tools
React Native bill of materials

## Install

```sh
npm i  --save-dev gblejman/react-native-tools#stage-0
```

## Displaying lint output in the editor

Include this line in `package.json`:

```js
{
  // ...
  "eslintConfig": {
    "extends": "./node_modules/react-native-tools/eslint.js"
  }
}
```

### Stage 0 decorator-support

Create a `.babelrc` with:

```json
{
  "presets": ["react-native-stage-0"]
}
```

For experimental legacy decorator support:

```json
{
  "presets": ["react-native-stage-0/decorator-support"]
}
```
