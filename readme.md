# go-http

临时用服务器,默认端口 `8080`,可以自己在命令工具后定义端口。

在执行目录为根目录建立一个虚拟目录。
提供上传入口 `/upload` .

```sh
# 文件生成
go build -ldflags "-s -w"
upx go-http
```
