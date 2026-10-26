# TUM Hermes 安装包

TUM Hermes 是面向 iPad 的学习与笔记 App。这里提供 Mac 和 Windows 安装辅助包，方便把 Hermes 安装到 iPad。

**当前版本：0.19.1（38） · iPadOS 26 或更新版本**

## 下载

| 使用的电脑 | 安装包 | 解压后运行 |
|---|---|---|
| Mac | [下载 Mac 安装包](https://github.com/TurboRadiator/tum-hermes-downloads/releases/download/v0.19.1/TUM-Hermes-0.19.1-Mac-Install-r2.zip) | `Start.command` |
| Windows | [下载 Windows 安装包](https://github.com/TurboRadiator/tum-hermes-downloads/releases/download/v0.19.1/TUM-Hermes-0.19.1-Windows-Install.zip) | `Start.cmd` |

两个安装包均附中文安装指南 `READ-ME.html`，可离线打开阅读。[查看此版本发布页](https://github.com/TurboRadiator/tum-hermes-downloads/releases/tag/v0.19.1)。

## 安装方法

1. 下载对应电脑系统的 ZIP，完整解压，先阅读 `READ-ME.html`。
2. 使用 USB 数据线连接并解锁 iPad，按提示信任电脑。
3. 运行上表的启动文件。Mac 可准备官方 AltServer；Windows 首次按包内指南安装官方 AltServer 及所需 Apple 依赖。
4. Mac 按住 **Option ⌥** 点菜单栏 AltServer，Windows 按住 **Shift** 点通知区域 AltServer，选择 **Sideload .ipa…** 和目标 iPad。
5. 选择包内的 `TUM-Hermes.ipa`，在官方 AltServer 中用自己的 Apple 账号完成签名安装；按 iPad 提示信任开发者并启用开发者模式。

这两个包用于给 iPad 安装 App，无需 Xcode。Apple 登录和签名由使用者在自己的电脑完成。

## 更新与续签

更新前导出重要笔记备份，使用原 Apple 账号覆盖安装，保留已有 Hermes。免费签名通常 7 天到期，可连接设备并用同一账号重新安装续签；不要先卸载 App。详细步骤与常见错误见包内指南。

## 文件校验

```text
e6a40fbb0df36e6385f4bfaef25f74f2a23c9e8a52d161bc4c8c0003441f70d4  TUM-Hermes-0.19.1-Mac-Install-r2.zip
bebcc68f8ce2bff58227abd5b2a2d2e832d893fec16c70cb1605593ef6491e68  TUM-Hermes-0.19.1-Windows-Install.zip
```

安装包包含启动器、IPA、中文指南和 SHA-256 校验清单。第三方许可信息保留在 App 内。本仓库仅用于分发安装包和安装说明。

TUM Hermes 是独立项目，并非 TUM 官方发布的 App。
