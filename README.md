# cloudnative-101
The repo is for Cloud Native 101 series training
scripts gits: https://gist.github.com/aseaday/a0972045222ccf0c3976f827f56001a1

[**中文**](./README_ZH.md) ｜ **English**

## Install Vagrant and VirtualBox

The vagrant and virtualbox provide a standard environment for experiments in our lecture of Cloud Native 101.

1. Visit [Virtualbox](https://www.virtualbox.org/wiki/Downloads) to download the virtualbox installer based on your operating system.
2. Download [Vagrant](https://www.vagrantup.com/downloads):
	- For Linux users, you are recommanded to move the binary to `/usr/local/bin`
	- For OS X users, the vagrant prepare a DMG installer, so just install it and you can use it.
	- For Windows users, because most of our developer who don't have it, please solve the problem by yourself.

## Validation

First, clone this repo to your computer.
```bash
git clone https://github.com/funstory-ai/cloudnative-101.git
```

Open a terminal and input the following commands to validate if it has been installed properly.

![gif1](https://raw.githubusercontent.com/funstory-ai/cloudnative-101/master/static/render1.gif)

## Here We Go

```bash
cd cloudnative-101/box 
vagrant up # It may take a while because it need to download the virtual machine image from AliyunOSS
vagrant ssh
```

![gif2](https://raw.githubusercontent.com/funstory-ai/cloudnative-101/master/static/render2.gif)

You will enter into an new shell and just like this

Then

```bash
exit
vagrant destroy
```
