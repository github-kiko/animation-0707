
### 注意：由于涉及到iframe、所以需要一个轻量级的服务器来跑此项目，不能直接打开html使用，不然会有跨域问题。

### Http-server是一个轻量级的基于nodejs的http服务器，它最大好处就是：
可以使任意一个目录成为服务器的目录，完全抛开后台的沉重工程，直接运行想要的js代码。
### 全局安装http-server
npm i -g http-server
### 在要成为服务器的目录下运行如下命令运行
http-server
### 若要禁用缓存，请使用如下命令运行 
http-server -c-1


