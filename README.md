# 青刻 Android

青刻 Android 由独立开发者维护。本仓库发布 APK、更新清单和版本说明。

## 下载

- [GitHub Releases](https://github.com/amin180231-creator/qingke-android-updates/releases/latest)
- [GitCode 更新仓库](https://gitcode.com/Maple_One/qingke-android-updates)
- [GitCode 最新 APK（1.1.1 / 1000036）](https://api.gitcode.com/api/v5/repos/Maple_One/qingke-android-updates/raw/Qingke-Android-v1.1.1-build1000036-release.apk)

当前安装包：`Qingke-Android-v1.1.1-build1000036-release.apk`。

## 更新检查

应用启动时自动检查，也可在“版本更新”页手动检查。1000036 起优先读取 GitCode 的 `latest.json`，发现更新后打开对应 APK 下载地址；失败后尝试 GitHub 来源。清单包含版本名称、内部版本号、安装包文件名及更新说明。下载完成后由 Android 系统确认安装。

旧版 1.1.1 若只比较版本名称，需要手动覆盖安装一次；1000035 及之后的检查器可识别同名版本的内部版本号。

## 发布同步

每次发布同时提交最新 APK 与 `latest.json`，再从本 GitHub 仓库镜像同步至 GitCode。Git 镜像不会复制 Releases 附件，因此仓库文件中也提供最新 APK。每次替换时删除旧 APK 文件，只保留最新安装包。

覆盖安装使用相同正式签名。版本记录见 CHANGELOG.md。

