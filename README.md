#Introduce

这是我的 ECMAScript 6 代码测试环境，部署很简单：

```
npm install --save-dev babel-cli babel-preset-es2015 babel-preset-react
```

并且修改 package.json，添加 scripts.

```
//package.json
{
  "name": "es6-babel",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "build": "babel-node es6.js"
  },
  "author": "",
  "license": "ISC",
  "devDependencies": {
    "babel-cli": "^6.22.2",
    "babel-preset-es2015": "^6.22.0",
    "babel-preset-react": "^6.22.0"
  }
}
```

如果要使用本项目。

```
git clone https://github.com/ShiningDan/es6-babel.git
cd es6-babel
npm install
```

然后在 es6.js 中写入 ECMAScript 6 代码

运行`npm run build`即可
