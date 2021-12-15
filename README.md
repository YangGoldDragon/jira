# typescript4.x + react17 开发jira项目

首先基于官方脚手架 [Create React App](https://github.com/facebook/create-react-app)初始化一个typescript项目.

### 然后，我们安装代码格式化工具
1. 安装prettier（安装的是开发依赖不是vscode插件）用来统一代码风格
2. 安装lint-staged在commit的时候，自动使用eslint，注意在package.json添加其他文件判断,比如tsx
```javascript
  "lint-staged": {
    "*.{js,css,md,ts,tsx,jsx}": "prettier --write"
  }
```
