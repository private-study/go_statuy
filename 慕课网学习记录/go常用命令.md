# go 常用命令

```shell
# 安装依赖 . 会在 `go.mod` 文件下新增一行依赖描述
go get -u go.uber.org/zap@v1.11


# 初始化仓库
go mod init gomotest

# 执行以下命令会自动分析项目里的依赖关系同步到go.mod文件中，同时创建go.sum文件
go mod init


## 该目录下所有的依赖全部都build一遍, 如果没有则安装一遍
go build ./...

```
