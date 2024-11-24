# Scoop-Darkatse [![Build status](https://img.shields.io/appveyor/ci/Darkatse/Scoop-Darkatse/master.svg?style=popout&logo=appveyor&label=AppVeyor)](https://ci.appveyor.com/project/Darkatse/Scoop-Darkatse/branch/master)[![Excavator](https://github.com/Darkatse/Scoop-Darkatse/workflows/Excavator/badge.svg)](https://github.com/Darkatse/Scoop-Darkatse/actions)


This scoop bucket is a collection of apps that I personally use.  
[Scoop](https://github.com/lukesampson/scoop) is a command-line installer for Windows, like homebrew.  
With scoop, you can install, update and uninstall these software from the command line with ease.

[English](https://github.com/Darkatse/Scoop-Darkatse/blob/master/README.md)|[简体中文](https://github.com/Darkatse/Scoop-Darkatse/blob/master/README_CN.md)  

Feature Apps
------------

| Manifest | Description |
|----------|-------------|
| Shanaencoder | An Useful audio/video encoding program |
| Netch | Game accelerator |
| memtest | A RAM tester that runs under Windows |
| RevokeMsgPatcher | Revoke Message Patcher for QQ/TIM/WeChat |
| Termius | A cross-platform SSH client |
| YogaDNS | Advanced DNS Client for Windows |



How to start use scoop
=====

Requirements:

* Make sure [PowerShell 5](https://aka.ms/wmf5download) (or later, include [PowerShell Core](https://docs.microsoft.com/en-us/powershell/scripting/install/installing-powershell-core-on-windows?view=powershell-6)) and [.NET Framework 4.5](https://www.microsoft.com/net/download) (or later) are installed. 


On Windows 8 and 10 Power Shell already installed.
For run just type in cmd:

    powershell

To install scoop (run in powershell console):

    Invoke-Expression (New-Object System.Net.WebClient).DownloadString('https://get.scoop.sh')  

*or shorter*  

    irm get.scoop.sh | iex
    
You can use proxies if you have network trouble in accessing GitHub, e.g.

    irm get.scoop.sh -Proxy 'http://<ip:port>' | iex

Once installed, run `scoop help` for instructions.


How to add this bucket
=====

To make it easy to install apps from this bucket, run  

    scoop bucket add Darkatse https://github.com/Darkatse/Scoop-Darkatse.git
    
Check that it works:

    scoop bucket list

For update run:

    scoop update
    
For example, search all avialable memtest packages:
    
    scoop search memtest

You've completed all the necessary steps, just enjoy it!
