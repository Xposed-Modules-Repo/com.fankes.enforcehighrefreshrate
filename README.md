# 强制高刷新率

![Eclipse Marketplace](https://img.shields.io/badge/license-AGPL3.0-blue)
![Eclipse Marketplace](https://img.shields.io/badge/version-v1.0-green)
[![Telegram](https://img.shields.io/badge/Follow-Telegram-blue.svg?logo=telegram)](https://t.me/XiaofangInternet)

适用于 OPPO、一加、三星系列设备系统的强制高刷新率，其余系统未做测试。

## 作用域说明

只需勾选系统界面 (com.android.systemui)。

## 使用说明

启用模块后重启一次系统界面，每次锁屏再解锁即会自动设置为最高刷新率。

## 效果说明

此模块会修改当前系统设置的屏幕刷新率为最高，如果你的屏幕最高刷新率为 90 Hz/120 Hz/144 Hz 或更高，则每次都会修改为此刷新率。

## 问题说明

目前未对 ColorOS 12.1 以外的系统做过测试，请自行测试。

⚠️ 如果你的设备屏幕最高刷新率只有 60 Hz (或更低)，请勿使用此模块，可能不会有效且会锁定为更低刷新率。 **(发生问题后果自负)**

目前接到的已知问题反馈的系统，请勿使用：

- H2OS 11.0.9.1.GM21 (氢OS) 机型：一加 7 Pro [问题现象存放](https://www.aliyundrive.com/s/42rc85DwFT7)

## 请勿用于非法用途

<h3>1.&nbsp本软件免费、由兴趣使然、仅供学习交流而开发，如果你是从其他不明来源的渠道付费得到本软件，则你已上当受骗，若发现欢迎向我们举报。</h3>

<h3>2.&nbsp未经本人许可，禁止转载、搬运本软件的安装包及源代码到 GitHub 以外的平台并提供下载链接。</h3>

## 项目推广

<!--suppress HtmlDeprecatedAttribute -->
<div align="center">
    <h2>嘿，还请君留步！👋</h2>
    <h3>这里有 Android 开发工具、UI 设计、Gradle 插件、Xposed 模块和实用软件等相关项目。</h3>
    <h3>如果下方的项目能为你提供帮助，不妨为我点个 star 吧！</h3>
    <h3>所有项目免费、开源，遵循对应开源许可协议。</h3>
    <h1><a href="https://github.com/fankes/fankes/blob/main/project-promote/README-zh-CN.md">→ 查看更多关于我的项目，请点击这里 ←</a></h1>
</div>

## 贡献

本模块使用 [YukiHookAPI](https://github.com/fankes/YukiHookAPI) 构建。

YukiHookAPI 是一个使用 Kotlin 重构的高效 Hook API 构建工具，让你的 Xposed 模块开发变得更加简单。

版权所有 © 2019-2024 Fankes Studio(qzmmcn@163.com)
