# typescript4.x + react17 开发jira项目

首先基于官方脚手架 [Create React App](https://github.com/facebook/create-react-app)初始化一个typescript项目.

## 然后，我们安装依赖prettier用来格式化代码
## 安装lint-staged在commit的时候，自动使用eslint，注意在package.json添加其他文件判断
```
  "lint-staged": {
    "*.{js,css,md,ts,tsx,jsx}": "prettier --write"
  }
```
