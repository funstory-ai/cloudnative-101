# cloudnative-101
Cloud Native 101 训练指北

**中文** ｜ [**English**](./README.md)


## 安装Vagrant和VirtualBox

Vagrant和VirtualBox提供了一个标准的课程实验环境。

1. 访问[Virtualbox](https://www.virtualbox.org/wiki/Downloads)下载VirtualBox的安装程序，选择和系统对应的版本。
2. 访问[Vagrant](https://www.vagrantup.com/downloads):
   - 对于Linux用户，下载之后推荐将文件移动到`/usr/local/bin`目录下。
   - 对于OS X用户，Vagrant提供了一个DMG安装器，直接安装即可。
   - 对于Windows用户，再见。

## 开始之前

首先，将仓库克隆到本地
```bash
git clone https://github.com/funstory-ai/cloudnative-101.git
```
之后请在终端中按照图中提示进行操作。

![](./static/screenshot-1.png)

## 开始

```bash
cd cloudnative-101/box 
vagrant up # It may take a while because it need to download the virtual machine image from AliyunOSS
vagrant ssh
```

![](./static/screenshot-2.png)

在这之后会进入虚拟的命令行环境中。

实验结束后请这样结束:
```bash
exit
vagrant destroy
```