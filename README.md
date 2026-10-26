# 小涡助手 · Android 更新

小涡助手安卓版的公开下载与更新入口。

## 下载安装

[下载最新版 APK](https://github.com/PN-BUG/xiaowo-updates/releases/download/android-latest/DandelionLanding.apk)

支持 Android 8.0 及以上。首次安装或从旧更新源迁移时，请手动下载安装新版；之后可在应用的“接收设置 → 应用更新”中检查新版，启动自动检查默认每天最多一次。安装时由 Android 系统提示确认。

## 发布与校验

- `android-latest` 提供最新的 `android-update.json` 和便捷 APK 下载入口。
- `android-<版本号>` 提供对应版本的 APK，更新清单使用这一固定版本地址，避免替换附件时下载内容不一致。
- 每份更新清单包含版本号、最低 Android API、安装包大小、SHA-256 和版本说明。客户端还会核对应用包名与原安装签名。

本仓库用于公开分发 APK、更新清单与发布说明。发布附件不包含签名密钥或应用私有配置。
