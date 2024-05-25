## 帧同步网页小游戏

一个乐观帧同步的最简单示例。

* node.js+socket.io开发
* 支持断线重连，可用以演示帧同步中的“追帧"阶段的表现

## 如何运行

## 服务端
```shell
$ cd server
$ npm install -d
$ npm run start
```


## 客户端

> 使用任意方法启动一个http服务即可，反正只是一个静态页面

- npx
```shell
cd client
npx http-server -p 8080 -o
```

- python
```shell
$ cd client
$ python3 -m http.server 8080
```

* 启动完成后访问：[http://127.0.0.1:8080/](http://127.0.0.1:8080/)

## 示例截图
![](README/preview.png)