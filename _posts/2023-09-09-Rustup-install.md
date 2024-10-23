---
title: Rustup安装
date: 2023-09-09 09:29:09 +0800
categories: [environment]
tags: [golang]
---

依赖环境 Rustup 安装：

'''
mkdir -p $HOME/.cargo
# vim $HOME/.cargo/config

[source.crates-io]
replace-with = 'ustc'

[source.ustc]
registry = "git://mirrors.ustc.edu.cn/crates.io-index"
'''

'''
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

# vim ~/.bashrc
export PATH=$PATH:$HOME/.cargo/bin
'''