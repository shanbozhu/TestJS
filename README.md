# TestJS

### 安装node

`brew install node`

安装`node.js`时会自动安装`npm`

### 全局安装typescript

`npm i -g typescript`

typescript：用来编译TS代码，提供`tsc`命令，实现TS转化为JS。

### 全局安装ts-node

`npm i -g ts-node`

ts-node：提供了`ts-node`命令。直接在Node.js中执行TS代码。

解释：`ts-node`命令在内部偷偷的将TS转化为JS，然后再运行JS代码。

原因：Node.js/浏览器，只认识JS代码，不认识TS代码。需要先将TS代码转化为JS代码，然后才能运行。

参考文档：https://www.jianshu.com/p/5f5cdcbc8b00
