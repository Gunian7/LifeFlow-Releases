# LifeFlow 桌面版发布目录

本仓库用于发布 LifeFlow（时流）桌面版的安装程序与自动更新清单。

## 下载

最新版本发布于 Releases 中的 `desktop-latest`。

| 文件 | 说明 |
| --- | --- |
| `LifeFlow-Setup.exe` | Windows 安装程序 |
| `latest.yml` | 自动更新清单，客户端据此判断是否存在新版本 |
| `LifeFlow-Setup.exe.blockmap` | 增量下载所需的块索引文件 |

## 系统要求

Windows 10 或 Windows 11（64 位）。

## 安装

安装程序尚未申请代码签名证书，首次运行时 Windows SmartScreen 可能显示安全提示。请依次选择「更多信息」与「仍要运行」以完成安装。

## 自动更新

应用启动后会在后台检查并下载新版本，下载完成后提示用户重启以完成安装。更新来源为本仓库的 `desktop-latest`。

## 数据存储

用户数据保存在 `%APPDATA%\LifeFlow` 目录。卸载程序不会删除该目录，如需彻底清除请手动删除。

## 反馈

使用中如遇问题，请发送邮件至 1328037882@qq.com。

## 关于本仓库

本仓库仅托管编译产物，不包含应用源代码。
