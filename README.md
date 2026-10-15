# 青刻 Android

青刻 Android 由独立开发者维护。本仓库只发布 Android APK 和版本说明，不包含应用源码。

## 下载

在 [Releases](https://github.com/amin180231-creator/qingke-android-updates/releases/latest) 获取最新正式版 APK。

## 应用内检查更新

应用启动时会自动检查公开 Release；发现较新版本时会提示用户，也可以在应用内的「版本更新」页面手动检查。检查时优先通过 GH-Proxy 获取公开版本信息；代理不可用时回退 GitHub 官方 API。检查只读取公开 Release 信息，不上传设备或账号数据。下载始终跳转到 GitHub 官方发布页，安装由 Android 系统确认。

## 安装与升级

下载 APK 后按 Android 系统提示安装。覆盖升级需要与已安装版本的签名一致；如果系统提示签名不匹配，请不要继续安装。
