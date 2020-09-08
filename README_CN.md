# Scoop-Darkatse [![Build status](https://img.shields.io/appveyor/ci/Darkatse/Scoop-Darkatse/master.svg?style=popout&logo=appveyor&label=AppVeyor)](https://ci.appveyor.com/project/Darkatse/Scoop-Darkatse/branch/master)[![Excavator](https://github.com/Darkatse/Scoop-Darkatse/workflows/Excavator/badge.svg)](https://github.com/Darkatse/Scoop-Darkatse/actions)

本 scoop 源收集了一些我个人平时使用的程序。  
[*Scoop简介 —— Windows 上体验最好的「包管理器」*](https://sspai.com/post/52496)

[English](https://github.com/Darkatse/Scoop-Darkatse/blob/master/README.md)|[简体中文](https://github.com/Darkatse/Scoop-Darkatse/blob/master/README_CN.md)  

包含哪些软件？
------------

| 名称 | 描述 |
|----------|-------------|
| Auto Dark Mode | 让win10自动切换夜间主题 |
| Netch | 通用游戏加速器 |
| memtest | win下的内存测试工具 |
| RevokeMsgPatcher | QQ/TIM/WeChat 防撤回补丁 |
| Termius | 跨平台同步的SSH客户端 |
| YogaDNS | 强大的Windows DNS客户端 |



如何使用scoop
=====

前置要求:

* 确保至少安装了 [PowerShell 5](https://aka.ms/wmf5download) (或者 [PowerShell Core](https://docs.microsoft.com/en-us/powershell/scripting/install/installing-powershell-core-on-windows?view=powershell-6)) 以及 [.NET Framework 4.5](https://www.microsoft.com/net/download) 。


在 Windows 8 和 10 当中 Power Shell 已经被安装了  
想要安装Scoop，只需要在 Power Shell 中输入  

    Invoke-Expression (New-Object System.Net.WebClient).DownloadString('https://get.scoop.sh')  

*或者用短命令*  

    iwr -useb get.scoop.sh | iex

安装后请输入 `scoop help` 来查看指南。


如何添加该源
=====

简单的在 Power Shell 输入  
    `scoop bucket add Darkatse https://github.com/Darkatse/Scoop-Darkatse.git`  
即可
    
查看是否成功：

    scoop bucket list

更新scoop列表：

    scoop update
    
测试下能否搜到memtest:
    
    scoop search memtest

恭喜你，你已经完成了所有必要的操作！
