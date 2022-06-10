克隆仓库到本地后, 在项目目录下执行下面的指令, 安装依赖
```shell
npm i
```
> tips: 如果上面的指令比较慢, 先执行下面指令设置一下代理（配合clashX）, 再回到第一步
> `npm config set proxy http://127.0.0.1:7890 && npm config set https-proxy http://127.0.0.1:7890`

运行起来：

```shell
node index.js 
```

--------------------------------
[https://docs.mango.markets/developer-resources/code-examples](https://docs.mango.markets/developer-resources/code-examples)Mango官方文档的示例代码是typescript,要转换成javascript才能运行，用这个在线工具转换：https://www.typescriptlang.org/play

