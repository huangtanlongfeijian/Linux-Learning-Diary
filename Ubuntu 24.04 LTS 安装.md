---
aliases:
记录时间: 2025-12-04
更新时间: 2025-12-09
tags:
---
# 大版本是这个即可，后面的子版本不重要
## 第一步，下载Ubuntu 24.04 LTS

官方网站：
https://ubuntu.com/blog/tag/ubuntu-24-04-lts
> 下载desktop版的，不要下载server版的

## 第二步，制作启动U盘
官方网站：
http://rufus.ie/zh

## 第三步，安装步骤
https://www.sysgeek.cn/install-ubuntu-24-04-lts/
https://www.bilibili.com/opus/861067292754051097

## 学习资料
官方社区
https://ubuntu.com/tutorials

## 安装好之后 
### **Step 1：先确认系统能正常更新**
打开 **Terminal（快捷键：Ctrl + Alt + T）** 输入：
```shell
sudo apt update
sudo apt upgrade -y
```
这一步确保你的 Ubuntu 是最新状态。
 ### **Step 2：安装常用软件（基础工具）**
建议一条命令全部安装：
```shell
sudo apt install -y build-essential git curl wget vim net-tools gnome-tweaks fcitx5 fcitx5-chinese-addons python3-pip python3-venv
```
