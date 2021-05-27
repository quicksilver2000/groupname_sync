# 目录

- [开始](#开始)
  - [下载](#下载)
  - [安装](#安装)
  - [使用](#使用)

# 开始
在https://github.com/wosiwq/groupname_synchttps://github.com/wosiwq/groupname_sync的基础上修了点小bug
## 下载

直接下载或clone本项目

## 安装

1. 将``groupname_sync``文件夹放入``hoshino``的``modules``文件夹
2. 复制``groupname_sync.example``到``config``文件夹，重命名为``groupname_sync.py``，打开后按照注释进行配置
3. 修改``_bot_.py``，在``MODULES_ON``中添加 ``groupname_sync``
4. 重启HoshinoBot


## 使用
1. 启用群昵称同步
2. 禁用群昵称同步
3. 修改群名

在**启用**了 `群昵称同步` 服务后，使用 **启用群昵称同步** 命令，即可开始自动同步yobot中的进度，效果大致如下

> K.A.会战群
> K.A.会战群28-4

启用群昵称同步指令后面可以额外添加参数(str) 如 `启用群昵称同步 K.A.` 则会把默认群名修改为K.A. 自动修改时也以K.A.为准

