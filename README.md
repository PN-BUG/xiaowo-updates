# 小涡助手 · 下载与更新

小涡助手 Windows 与 Android 版的公开下载入口。本仓库用于分发安装包、更新清单、校验文件与发布说明。

## Windows 1.5.0 · 轻量版

[下载 Windows x64 ZIP](https://github.com/PN-BUG/xiaowo-updates/releases/download/windows-1.5.0/SoftwareToolkit-win-x64-lightweight.zip) · [发布说明](https://github.com/PN-BUG/xiaowo-updates/releases/tag/windows-1.5.0) · [SHA-256 校验文件](https://github.com/PN-BUG/xiaowo-updates/releases/download/windows-1.5.0/SoftwareToolkit-win-x64-lightweight.zip.sha256)

需要 Windows 10/11 x64 和 [.NET 8 Desktop Runtime x64](https://dotnet.microsoft.com/zh-cn/download/dotnet/8.0)。解压整个 ZIP 后运行 `SoftwareToolkit.exe`，保留旁边的 `tools.json` 和 `tools/`。升级前请备份自己的工具配置。

新增离线二维码识别：选图、拖图、粘贴、屏幕识别及多二维码结果，可复制、打开网页或加入画板。

## Android 1.5.0

[下载最新版 APK](https://github.com/PN-BUG/xiaowo-updates/releases/download/android-latest/DandelionLanding.apk) · [1.5.0 固定版本](https://github.com/PN-BUG/xiaowo-updates/releases/tag/android-1.5.0)

支持 Android 8.0 及以上。首次安装、1.3.x 或旧更新源的 1.4.0，请手动覆盖安装新版；之后可在“接收设置 → 应用更新”中检查升级，默认每天启动时最多自动检查一次，安装由 Android 系统确认。

新增离线相机扫码、图片识别，以及桌面图标长按菜单中的“扫码 / 图片识别 / 连接电脑”。提供窄屏、大字号与圆屏布局。桌面菜单依赖启动器支持；实际摄像头、手机及手表显示仍待真机验证。手表目前按兼容侧载适配。

## 更新与校验

- `android-latest` 提供固定地址的 `android-update.json` 和便捷 APK 下载入口。
- `android-<版本号>` 提供对应版本的固定 APK，更新清单指向该地址，旧版本附件保留。
- `windows-<版本号>` 提供 Windows 发布包及 SHA-256 校验文件。
- Android 清单包含版本号、最低 Android API、文件大小、SHA-256 和版本说明；客户端还会核对应用包名与原安装签名。
- 公开桌面包仅保留运行文件、工具脚本与许可证，发布附件不含 Android 构建源码、签名密钥或个人配置。
