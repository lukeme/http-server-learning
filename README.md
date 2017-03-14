# Http Server Learning

- [x] [step1] 单进程阻塞 http server, 实现 file index
- [x] [step2] 整理 step1 的代码
- [x] [step3] 多进程阻塞 http server, 实现 file index
- [x] [step4] HttpParse 解析 http request/response
- [ ] [step5] 单进程 stream_select 版本 版本的 http server, 实现 file index
- [ ] [stepN] 单进程非阻塞 select/epoll 等
- [ ] [stepN] 多进程非阻塞


# TODO

- rpc
- websocket ?
- tcp 拆包？
- 平滑重启如果做？


# 重要参考文档

- [Fast portable non-blocking network programming with Libevent](http://www.wangafu.net/~nickm/libevent-book/TOC.html)
- [RPC 的概念模型与实现解析](http://mp.weixin.qq.com/s?__biz=MzAxMTEyOTQ5OQ==&mid=2650610547&idx=1&sn=2cae08dbf62d9a6c2f964ffd440c0077)
- [pico http parser](https://github.com/h2o/picohttpparser) 
