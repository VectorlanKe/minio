在minio单文件对象鉴权的基础上兼容文件夹鉴权

```
//打包
//cmd 设置环境变量
set GOARCH=amd64
//linux windows
set GOOS=linux
go build
//go build main.go
```

## 官方项目地址：https://github.com/minio/minio
## 官方文档地址：https://min.io/docs/minio/kubernetes/upstream/
## 重要的
### 独立/文件系统模式继续适用于任何版本，包括RELEASE.2022-10-24T18-35-07Z。要继续使用独立部署，请安装该 MinIO 版本或任何更早版本。
### 使用独立或文件系统MinIO 模式升级到RELEASE.2022-10-29T06-21-33Z或更高版本的部署在尝试启动 MinIO 时收到错误。（Unable to use the drive /MinIO/data: Drive /MinIO/data: found backend type fs, expected xl or xl-single: Invalid arguments specified）
## 对应文档：https://min.io/docs/minio/linux/operations/install-deploy-manage/migrate-fs-gateway.html
