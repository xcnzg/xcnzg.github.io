---
title: XCN桌面钱包更新及Solo挖矿教程
date: 2022-07-10 17:55:05
tags: 钱包, 客户端, 挖矿, 快速上手
categories: 动态
---
1.桌面钱包下载地址：[XCN氪石币钱包下载 | 氪石币中国官网 (xcnzg.com)](http://localhost:4000/2022/07/08/wallet/)，打开网页后下载桌面钱包Windows版本，下载之后是一个名为cryptonite-gui-0-1-6-win64.rar的压缩文件，直接解压，解压之后双击cryptonite-qt.exe这个可执行程序即可运行钱包文件，第一次运行钱包程序会提示你区块文件保存路径，新手请使用默认路径（即存放在系统盘）；

2.运行钱包之后会进入区块文件更新的过程，此过程需要时间漫长，这里提供一个更新更为快捷的方法，先将钱包程序关闭，将cryptonite.conf文件复制到该路径C:\Users\Administrator\AppData\Roaming\Cryptonite（桌面钱包程序默认保存区块文件的路径，默认为隐藏文件，需要打开隐藏文件查看功能，否则找不到这个路径），重新打开桌面钱包程序，此时会发现更新速度会快很多，从0开始更新到最新区块预计耗时两小时左右；
![氪石币安装路径截图](http://localhost:4000/medias/quick-start/001.png)

conf文件下载：[cryptonite.conf](http://localhost:4000/medias/quick-start/cryptonite.conf)

3.当桌面钱包程序更新到最新区块之后，电脑里如果有Nvidia（英伟达）的独立显卡，那可以尝试本机solo挖矿，目前算力较低，一块3060的独立显卡（算力有锁版本，算力预计28MH）按目前算力大概能挖出来两万个以上的XCN代币，solo挖矿需下载配套的挖矿程序，下载好挖矿程序之后点击solo.bat即可进入挖矿流程，这里需要注意的是杀毒软件会把挖矿程序判定为病毒，所以运行挖矿程序之前先关闭杀毒软件或者运行挖矿程序之后杀毒软件提示病毒要处理的时候把挖矿程序设置为可信任程序即可，正常挖矿界面如下图所示：
![氪石币钱包运行截图](http://localhost:4000/medias/quick-start/002.png)

挖矿软件下载：[XCN挖矿软件](http://localhost:4000/medias/quick-start/XCN.rar)