# 编译时注入版本信息

## 背景
- 调试程序通常需要明确当前使用的程序具体版本，这些版本信息如果手动添加的话，会比较繁琐
- `go build` 编译支持注入外部参数到程序

## 实现

借助 `go build -ldflags` 向程序注入当前代码仓库的 git 和 go 等版本信息

## 样例代码

```go

```

## 参考文献
- [Golang写的程序注入一些版本信息，Debug速度自然快不少](https://www.toutiao.com/i6781044784648684036/?tt_from=weixin&utm_campaign=client_share&wxshare_count=1&timestamp=1592575652&app=news_article&utm_source=weixin&utm_medium=toutiao_android&req_id=202006192207320101300371420218D14D&group_id=6781044784648684036)
