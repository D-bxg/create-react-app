<!--
 * @Author: D_bxg
 * @Date: 2021-02-23 00:04:31
 * @LastEditors: D_bxg
 * @LastEditTime: 2021-02-24 13:40:26
 * @Description: file content
 * @FilePath: \create-react-app\README.md
-->
# 开始

把项目克隆到本地后，只需要执行^yarn^就可以初始化。当然，这是在安装了 yarn 的基础上。

# 项目依赖

```js
/**
 * create-react-app脚手架
 */
"@testing-library/jest-dom": "^5.11.4",//create-react-app脚手架自带
"@testing-library/react": "^11.1.0",//create-react-app脚手架自带
"@testing-library/user-event": "^12.1.10",//create-react-app脚手架自带
"react": "^17.0.1",//react核心文件，create-react-app脚手架自带
"react-dom": "^17.0.1",//react-dom核心文件，create-react-app脚手架自带
"react-scripts": "4.0.2",//react脚本文件，create-react-app脚手架自带
"web-vitals": "^1.0.1",//create-react-app脚手架自带
/**
 * react-router
 */
"react-router-dom": "^5.2.0",//路由

"@craco/craco": "^6.1.1",//覆盖PostCSS配置

"prop-types": "^15.7.2",//预设props时的依赖

"pubsub-js": "^1.9.2",//两个组件之间传递状态值
/**
 * redux系列
 */
"redux": "^4.0.5",//redux核心文件，含有store、action、reducer
"redux-thunk": "^2.3.0",//redux异步方法解决方案
"react-redux": "^7.2.2",//外层容器概念，引入connect
/**
 * AJAX
 */
"axios": "^0.21.1",
/**
 * Tailwind 
 * CSS框架
 */
"@tailwindcss/postcss7-compat": "^2.0.3",
"postcss": "7",// 支持PostCSS 8
"autoprefixer": "9",
"tailwindcss": "npm:@tailwindcss/postcss7-compat",
```
