---
title: CUDA NVCC安装
date: 2023-09-09 09:09:09 +0800
categories: [environment]
tags: [cuda]
---

CUDA运算需要安装NVCC

安装cuda-toolkit-11-2（ubuntu18.04）
'''
wget https://developer.download.nvidia.com/compute/cuda/11.2.2/local_installers/cuda_11.2.2_460.32.03_linux.run
sudo sh cuda_11.2.2_460.32.03_linux.run
'''
'''
# set PATH
# vim ~/.bashrc
export PATH=$PATH:/usr/local/cuda-11.2/bin
export LD_LIBRARY_PATH=/usr/local/cuda-11.2/lib64
export CUDA_HOME=/usr/local/cuda

source ~/.bashrc
nvcc --version
'''
