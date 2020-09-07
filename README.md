# node.js-text
# node.js-text
## 启动应用
```
node server.js 8888
```
或者
```
node serve 8888
```
## 添加路由
*编辑server.js文件，添加if else
*重新运行node server.js 8888

## 后台启动应用
touch log node server.js 8888 >log log 2 >&1 &
