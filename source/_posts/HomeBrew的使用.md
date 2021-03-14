---
title: HomeBrew的使用
date: 2020-01-07 22:08:11
cover: https://i.loli.net/2020/01/07/9inDGxW2wRBdIYF.jpg
tags: 
- Mac
- HomeBrew
categories:
- 工具使用
---
# HomeBrew使用记录
## 简介
HomeBrew是Mac系统的包管理工具，类似于Centos的yum
## 安装
`/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
## 卸载
`usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/uninstall)"`
## 更新
`brew update`

## 用法
1. 安装软件： `brew install 软件名`
2. 卸载软件： `brew uninstall 软件名`
3. 搜索软件： `brew search 软件名`
4. 已安装软件的列表： `brew list`
5. 查看软件信息：  `brew info 软件名`
6. 查看软件安装的地址： `brew link 软件名`




## brew services(管理后台服务)
启动后台服务(同时会注册为跟随系统启动自动运行的服务)：`brew serivces start 服务名`
启动后台服务(不会注册跟随系统启动自动运行的服务)： `brew services run 服务名`
关闭后台服务：`brew serivces stop 服务名`
查看正在运行的服务： `brew services list`




