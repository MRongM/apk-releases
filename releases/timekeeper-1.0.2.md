# Timekeeper 1.0.2（code 3）

当前 Timekeeper 源码的独立签名 Release APK，供直接下载安装。

- 构建日期：2026-10-13
- 包名：`com.mrongm.timekeeper`
- Android 8.0（API 26）及以上
- 源码修订：`bd6db36becfef417c5d08fd36c89d66948e15df8`
- 不依赖 GMS；播报需要可用的系统 TTS 引擎及所选语言的已安装离线语音。
- 此次仅构建并共享当前版本；未新增关闭日期播报的设置，也未包含针对 TTS 延迟的新调整。

## 安装和升级

下载 `timekeeper-1.0.2-code3.apk`，按手机提示允许安装。

本渠道使用独立分发签名，后续版本沿用相同密钥。Google Play 或其他渠道的版本可能无法直接覆盖安装；若需卸载旧版，请先记录设置，卸载会清除数据。

首次使用请检查精确闹钟、通知权限、后台运行限制以及 TTS 离线语音。

## 验证

- `:app:testDebugUnitTest`：281 项，失败 0，错误 0，跳过 0。
- `:app:lintRelease`：无 Error/Fatal，53 条 Warning。
- `:app:assembleRelease`：成功。
- APK v2/v3 签名验证通过；使用 Release 构建，未启用 debuggable。
- 本次未新增真机或模拟器安装测试。

签名证书 SHA-256：`87849958d288078e4265b473450b7c134b9f1f8be7af7160e0a9254c8de1b51b`

APK SHA-256：`7c5798b552b314642c736e6d11a275b05f5dc9e0cfa52e689885a8625d6cd677`

附件 `SHA256SUMS.txt` 可用于核验 APK 完整性。
