# single-spa-webpack-config-react-ts

## Getting started

- Supported Node Engine

```
node - v16.12.0
yarn - 1.22.19
```

**How to Use it**

- Install as a node module package like

```
yarn add -D single-spa-webpack-config-react-ts
```

- Added Below line in your project `webpack.config.js` like,

```js
const {
  singleSpaWebpackConfig,
} = require("single-spa-webpack-config-react-ts");

module.exports = singleSpaWebpackConfig(<your_organization_name>, <your_project_name>, <customize_webpack_config>);
```

- Added Below line in your project `babel.config.js` like,

```js
const { singleSpaBabelConfig } = require("single-spa-webpack-config-react-ts");

module.exports = singleSpaBabelConfig(<customize_babel_config>);
```

- Added Below line in your project `tailwind.config.js` like,

```js
const { singleSpaTailwindConfig } = require("single-spa-webpack-config-react-ts");

module.exports = singleSpaTailwindConfig(<customize_tailwind_config>);
```

- Added Below line in your project `postcss.config.js` like,

```js
const { singleSpaPostcssConfig } = require("single-spa-webpack-config-react-ts");

module.exports = singleSpaPostcssConfig(<customize_postcss_config>);
```
