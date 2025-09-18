# Boot Video Launcher (Android 4.4)

一个小体积的伪装桌面 App，开机时播放视频，播放完毕后跳转回真正的桌面。

## 使用
1. 替换 `app/src/main/res/raw/boot_video.mp4` 为你自己的视频（建议 ≤5MB）。
2. 在 Android Studio 打开项目，执行 `Build -> Make Project`。
3. APK 会出现在 `app/build/outputs/apk/release/app-release.apk`。
4. 安装到车机，设置为临时默认桌面，即可在开机时播放视频。

## GitHub Actions
本仓库内置 `.github/workflows/android.yml`，推送到 GitHub 后会自动打包 APK，构建结果在 **Actions → Artifacts** 下载。
