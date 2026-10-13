# APK Releases

MRongM 应用的公开 APK 下载仓库，按应用和版本发布安装包。

## 下载

- [Timekeeper 1.0.2 APK](https://github.com/MRongM/apk-releases/releases/download/timekeeper-v1.0.2/timekeeper-1.0.2-code3.apk)
- [全部版本](https://github.com/MRongM/apk-releases/releases)

## Timekeeper 安装说明

- 支持 Android 8.0（API 26）及以上。
- 应用不依赖 Google Play 服务（GMS）；语音播报需要系统中可用的 TTS 引擎和对应语言的已安装离线语音。
- 下载 APK 后，按系统提示允许安装来自该来源的应用。
- 首次使用请检查精确闹钟、通知权限，以及手机的后台运行限制。
- 本仓库 APK 使用独立的分发签名。与 Google Play 或其他渠道的安装包签名不同可能无法覆盖安装；卸载旧版会清除应用数据，请先记录设置。
- 后续本仓库的 Timekeeper APK 将沿用同一分发签名。

## 仓库内容

本仓库仅提供下载说明、版本说明和校验值。APK 放在 GitHub Release 附件中；源码、签名密钥和凭据不在此公开。

发布前检查 APK 签名、包名、版本、SHA-256，并执行项目单元测试和 Android Lint。构建通过不代表所有设备兼容性已验证。
