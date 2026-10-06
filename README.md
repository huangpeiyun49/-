# 实验一：计算机视觉库的安装
## 一、实验目的

掌握 Anaconda 的安装与基本操作，熟悉 GPU 使用环境的配置及对应版本 PyTorch 的安
装，并完成 OpenCV 的安装与配置

## 二、实验内容

1、Anaconda的安装及配置

<img width="309" height="382" alt="屏幕截图 2026-09-24 135517" src="https://github.com/user-attachments/assets/b6d06ecf-e101-4a64-a56a-1aa7660e2e19" />

2、conda的基本操作与OpenCV的安装

1. conda create -n [env_name] python==[version] 创建虚拟环境并制定python版本。

2. activate cv 进入创建的虚拟环境， pip install opencv-python 安装OpenCV。

<img width="536" height="356" alt="屏幕截图 2026-09-24 141551" src="https://github.com/user-attachments/assets/2c978a85-353f-495b-bdf7-566931ab8151" />

<img width="845" height="514" alt="屏幕截图 2026-09-24 141924" src="https://github.com/user-attachments/assets/2f6255a4-6230-428d-9aea-b36231331010" />

3、GPU加速环境配置

1. nvidia-smi 显示显卡状态信息，如下：

<img width="835" height="590" alt="屏幕截图 2026-09-24 142001" src="https://github.com/user-attachments/assets/b8f81085-0b3b-45d5-94ab-f575b35a22b0" />

4、PyTorch安装

1. 结合CUDA版本至PyTorch官网选择对应版本进行下载，页面如下：

<img width="761" height="295" alt="屏幕截图 2026-09-24 142053" src="https://github.com/user-attachments/assets/93629b9a-82a0-4060-883a-4031757d6a0c" />

3. conda list pytorch 可以看到已经成功安装，信息如下：

<img width="1270" height="700" alt="屏幕截图 2026-09-24 144203" src="https://github.com/user-attachments/assets/5be1f195-a93b-4abc-9a9a-2f5c92fac407" />

## 三、实验总结

1. 此次实验较为基础，主要是后续CV实验搭建实验环境。
   
2. 熟悉了Anaconda虚拟环境管理的基本操作。

3. 结合CUDA与cuDNN配置了GPU加速环境，为深层网络的高效训练奠定了基础。
