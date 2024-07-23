# TestJS

### 1. 安装node

`brew install node`

安装`node.js`时会自动安装`npm`

### 2. 全局安装typescript

`npm i -g typescript`

typescript：用来编译ts代码，提供`tsc`命令，将ts编译为js。

```
// 将ts编译为js
tsc test.ts

// node执行js
node test.js
```

### 3. 全局安装ts-node

`npm i -g ts-node`

ts-node：提供`ts-node`命令。直接执行ts代码。

```
// ts-node执行ts
ts-node test.ts
```

解释：`ts-node`命令在内部偷偷的将ts编译为js，然后再运行js代码。

原因：Node.js/浏览器，只识别js代码，不识别ts代码。需要先将ts代码编译为js代码，然后才能运行。

参考文档：https://www.jianshu.com/p/5f5cdcbc8b00
