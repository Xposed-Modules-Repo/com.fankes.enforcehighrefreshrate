# 强制高刷新率

![Eclipse Marketplace](https://img.shields.io/badge/license-AGPL3.0-blue)
![Eclipse Marketplace](https://img.shields.io/badge/version-v1.0-green)
[![Telegram](https://img.shields.io/badge/Follow-Telegram-blue.svg?logo=telegram)](https://t.me/XiaofangInternet)

适用于 OPPO、一加、三星系列设备系统的强制高刷新率，其余系统未做测试。

## Developer

[酷安 @星夜不荟](http://www.coolapk.com/u/876977)

## 作用域说明

只需勾选系统界面 (com.android.systemui)。

# 效果说明

此模块会修改当前系统设置的屏幕刷新率为最高，如果你的屏幕最高刷新率为 90 Hz/120 Hz/144 Hz 或更高，则每次都会修改为此刷新率。

理论对以前最高只有 60 Hz 的设备无效，也不需要此模块。

## 使用说明

启用模块后重启一次系统界面，每次锁屏再解锁即会自动设置为最高刷新率。

未对 ColorOS 12.1 以外的系统做过测试，请自行测试。

## 贡献

本模块使用 [YukiHookAPI](https://github.com/fankes/YukiHookAPI) 构建。

YukiHookAPI 是一个使用 Kotlin 重构的高效 Hook API 构建工具，让你的 Xposed 模块开发变得更加简单。

版权所有 © 2019-2022 Fankes Studio(qzmmcn@163.com)