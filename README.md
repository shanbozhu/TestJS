# TestJS

### 安装node

`brew install node`

安装`node.js`时会自动安装`npm`

### 全局安装typescript

`npm i -g typescript`

typescript：用来编译 TS 代码，提供了 tsc 命令，实现了 TS -> JS 的转化。

### 全局安装ts-node

`npm i -g ts-node`

ts-node：提供了 ts-node 命令。直接在 Node.js 中执行 TS 代码。

解释：ts-node 命令在内部偷偷的将 TS -> JS，然后，再运行 JS 代码。

原因：Node.js/浏览器，只认识 JS 代码，不认识 TS 代码。需要先将 TS 代码转化为 JS 代码，然后才能运行。

参考文档：https://www.jianshu.com/p/5f5cdcbc8b00
