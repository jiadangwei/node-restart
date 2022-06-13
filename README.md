
### node-restart


node-restart is a tool that helps develop Node.js based applications by automatically restarting the node application when file changes in the directory are detected.

node-restart does not require any additional changes to your code or method of development. node-restart is a replacement wrapper for node. To use node-restart, replace the word node on the command line when executing your script.


node-restart can replace nodemon. Solve the problem of frequent nodemon modification and frequent port occupation



### Installation

```
npm install -g node-restart
```

### Usage
node-restart  wraps your application, so you can pass all the arguments you would normally pass to your app:
```
"scripts": {
    "dev": "node-restart ./app.js --watch ./src"
  },
```
### node-restart

node-restart是一种帮助开发节点的工具。通过在检测到目录中的文件更改时自动重新启动节点应用程序，实现基于js的应用程序。

node-restart不需要对代码或开发方法进行任何其他更改。node-restart是节点的替换包装。要使用node-restart，请在执行脚本时替换命令行上的单词node

node-restart 可替代nodemon。解决nodemon修改频繁端口经常被占用的问题



### 安装

```
npm install -g  node-restart
```

### 使用
node-restart  通过传递参数启动应用，./app.js 为node应用 --watch ./src 监听指定目标文件是否有变化（--watch为空监听项目所有目录）， 如果有变化自动重启:
```
"scripts": {
    "dev": "node-restart ./app.js --watch ./src"
  },
```