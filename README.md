# v2rayN

A GUI client for Windows, Linux and macOS, support [Xray](https://github.com/XTLS/Xray-core)
and [sing-box](https://github.com/SagerNet/sing-box)
and [others](https://github.com/2dust/v2rayN/wiki/List-of-supported-cores)

[![GitHub commit activity](https://img.shields.io/github/commit-activity/m/2dust/v2rayN)](https://github.com/2dust/v2rayN/commits/master)
[![CodeFactor](https://www.codefactor.io/repository/github/2dust/v2rayn/badge)](https://www.codefactor.io/repository/github/2dust/v2rayn)
[![GitHub Releases](https://img.shields.io/github/downloads/2dust/v2rayN/latest/total?logo=github)](https://github.com/2dust/v2rayN/releases)
[![Chat on Telegram](https://img.shields.io/badge/Chat%20on-Telegram-brightgreen.svg)](https://t.me/v2rayn)

## How to use

Read the [Wiki](https://github.com/2dust/v2rayN/wiki) for details.

## Telegram Channel

[github_2dust](https://t.me/github_2dust)

修复“已损坏”报错如果软件已经拖入“应用程序”文件夹，但依然提示损坏，请在终端中运行以下命令清除隔离属性：￼￼
1. 在终端中输入以下命令（注意最后有一个空格）：bashsudo xattr -r -d com.apple.quarantine ￼￼
2. 打开你的 应用程序 文件夹，把 v2rayN 的图标直接拖拽到终端窗口中（这会自动填充它的路径，例如 /Applications/v2rayN.app）。
3. 完整的命令看起来像这样：bashsudo xattr -r -d com.apple.quarantine /Applications/v2rayN.app￼
4. 按下回车，再次输入开机密码确认。完成后重新双击打开 v2rayN。
