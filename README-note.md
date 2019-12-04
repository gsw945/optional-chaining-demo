##### 包安装
```bash
# 全局安装，yarn国内源版本
npm install tyarn -g --registry=https://registry.npm.taobao.org
# 使用 CRA 创建项目并运行
tyarn create react-app optional-chaining-demo
cd optional-chaining-demo
tyarn start
# CRA 默认 webpack 配置重写支持
tyarn add customize-cra react-app-rewired -D
# optional chaining 语法支持
tyarn add @babel/plugin-proposal-optional-chaining -D
# nullish coalescing operator 语法支持
tyarn add @babel/plugin-proposal-nullish-coalescing-operator -D
```

##### 参考
* [创建新的 React 应用 - Create React App](https://zh-hans.reactjs.org/docs/create-a-new-react-app.html#create-react-app)
* [Enabling optional chaining in a create-react-app](https://medium.com/@adostes/enabling-optional-chaining-in-a-create-react-app-a9f626a515d9)
* [ESNext: JavaScript “Nullish Coalescing Operator”](https://medium.com/@bramus/esnext-javascript-nullish-coalescing-operator-3e56afb64b54)
* [How to configure CRA with TS to support nullish-coalescing-operator](https://stackoverflow.com/questions/58436422/how-to-configure-cra-with-ts-to-support-nullish-coalescing-operator/58585626#58585626)
* [在 create-react-app 中使用](https://ant.design/docs/react/use-with-create-react-app-cn#Import-on-demand)