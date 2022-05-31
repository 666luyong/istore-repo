# istore-repo
iStore的ipk仓库，存放已编译的ipk文件

# PR指南
## 原则
为节省仓库体积以及防止恶意软件：
1. 请勿提交OpenWRT官方仓库已经存在的包
2. 如果是开源软件请在PR信息中提供仓库地址
3. 如果是非开源软件请在PR信息中提供官方网站链接

## 流程
1. Fork本仓库
2. 从`main`分支创建自己的分支
3. 修改完成以后发起PR，PR的目标分支选择`pending`，不要选择`main`

注意：`main`分支是保护分支，任何人包括管理员都不能直接提交，必须通过其它分支发起PR来变更