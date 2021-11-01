# Go Mod 包管理

###### 1、go mod init 創建當前目錄的工程，自定義包使用的是Module名稱

go.mod中 module test 相對引用的目錄

如果沒有使用mod 管理，包查找目錄的依賴GOROOT和GOPATH的環境變量的目錄**需要收添加工程目錄到GOPATH**

###### 2、Go Mod 常用命令

1. ###### go mod init

初始化一个go.mod文件到当前目录， 实际上是创建了一个以当前目录为模块的mod。

###### 2、go mod tidy

类似maven update, 通过这个命令下载项目依赖的第三方库，同时会去掉不相关的库。

######  3.go mod vendor 

把第三方的库拷贝到当前目录的vendor目录

###### 4.go mod verify

检查下载的第三方库有没有本地修改，如果有修改，则会返回非0，否则验证成功。





