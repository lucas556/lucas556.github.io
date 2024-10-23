---
title: Golang安装
date: 2023-09-09 09:19:09 +0800
categories: [environment]
tags: [golang]
---

依赖环境 Golang 安装(1.16.4)：

'''
wget -c https://studygolang.com/dl/golang/go1.16.4.linux-amd64.tar.gz -O - | sudo tar -xz -C /usr/local

# vim ~/.bashrc
export PATH=$PATH:/usr/local/go/bin
export GOPROXY=https://goproxy.cn
source ~/.bashrc
'''