# 悟空虚拟定位 — Android 模拟定位与 GPS 路线测试工具

悟空虚拟定位（Mock Location）通过 Android 的模拟位置功能，为地图、导航和 LBS 应用提供测试位置。支持地图选点、地点搜索、坐标输入和路线模拟，无需 Root。

**[⬇ 下载 APK](https://github.com/ChenGuoqing1001/MockLocation/releases/latest/download/MockLocation-google.apk)**

<p>
  <br />
  <a href="https://play.google.com/store/apps/details?id=com.yangtools.gps.simulator">
    <img src="assets/google-play-badge.svg" width="180" alt="Google Play" />
  </a>
</p>

[![GitHub release](https://img.shields.io/github/v/release/ChenGuoqing1001/MockLocation)](https://github.com/ChenGuoqing1001/MockLocation/releases/latest) [![GitHub stars](https://img.shields.io/github/stars/ChenGuoqing1001/MockLocation)](https://github.com/ChenGuoqing1001/MockLocation/stargazers)

## 应用预览

<p>
  <img src="assets/screenshots/map.png" width="260" alt="悟空虚拟定位：地图选点与开始模拟位置" />
  <img src="assets/screenshots/route.png" width="260" alt="悟空虚拟定位：路线规划与速度设置" />
</p>

<details>
<summary>其他语言 / Other languages</summary>

[中文](README.md) · [English](README_en.md) · [Español](README_es.md) · [Français](README_fr.md) · [Deutsch](README_de.md) · [日本語](README_ja.md) · [한국어](README_ko.md) · [Русский](README_ru.md) · [Português](README_pt.md) · [Português (BR)](README_pt_BR.md) · [Italiano](README_it.md) · [العربية](README_ar.md) · [हिन्दी](README_hi.md) · [Türkçe](README_tr.md) · [Nederlands](README_nl.md) · [Tiếng Việt](README_vi.md) · [ไทย](README_th.md) · [தமிழ்](README_ta.md) · [Bahasa Indonesia](README_id.md)

</details>

## 核心功能

- **地图选点与搜索**：拖动或选择目标位置，也可以搜索地点和地址。
- **坐标输入**：支持 WGS84、GCJ-02、BD-09 坐标及转换。
- **路线模拟**：添加路径点、设置移动速度，用于测试移动中的定位行为。
- **地图切换**：提供 Google、高德、百度等地图来源。
- **收藏与历史**：保存常用测试地点，方便重复验证。

## Android 如何设置模拟定位

1. 下载 APK 并安装；如果系统询问，允许当前浏览器或文件管理器安装该 APK。
2. 打开手机「设置」，在「关于手机」中找到版本号并连续点击 7 次，按提示启用「开发者选项」。不同品牌的入口名称可能不同。
3. 在「开发者选项」中找到「选择模拟位置信息应用」，选择本应用。
4. 返回应用，按提示授予位置权限，选择地图位置或输入坐标，然后启动模拟。
5. 在需要测试的应用中刷新定位，检查是否使用了目标位置；测试结束后停止模拟。

开发者选项的入口可参考 [Android 官方说明](https://developer.android.com/studio/debug/dev-options)。系统版本兼容性以实际安装提示及商店说明为准。

<details>
<summary>通过 ADB 安装</summary>

安装 Android Platform Tools，在设备上开启 USB 调试并授权电脑后，在 APK 所在目录执行：

```bash
adb install -r MockLocation-google.apk
```

</details>

## 模拟定位不生效怎么办？

先确认「模拟位置信息应用」仍选中本应用，并检查应用内是否已启动模拟、位置权限是否已授予。更新或重新安装后，可以重新选择模拟位置应用，再刷新测试应用的定位。

Android 会标记模拟位置，部分应用可能识别或拒绝这些位置。本工具不保证所有第三方应用都接受模拟定位，详情可参考 [Android 模拟位置标记说明](https://developer.android.com/reference/android/location/Location#isMock())。

## 小米 / HyperOS 切到后台后停止模拟怎么办？

先检查应用是否仍在运行。若切到后台或锁屏后停止，在系统的应用设置中检查电池限制、后台运行及自启动选项，按测试需要允许后台运行，再重新测试。不同 MIUI / HyperOS 版本的选项名称和路径可能不同。

## 地点搜索失败或地图加载不出来怎么办？

检查网络连接和当前地图服务是否可用，尝试切换地图来源。地点搜索使用百度地图 API；地图加载和搜索需要联网，不能把应用所有功能视为完全离线。

## 输入坐标后位置偏移怎么办？

确认输入坐标的类型，并选择对应的 WGS84、GCJ-02 或 BD-09 坐标系。不同坐标系混用可能导致位置偏移；建议使用一个已知地点核对转换结果。

## 隐私与使用说明

收藏和历史记录保存在设备本地；地图和搜索功能会访问对应的地图服务。详细隐私说明与付费项目以 [Google Play 页面](https://play.google.com/store/apps/details?id=com.yangtools.gps.simulator)及其隐私政策为准。

本工具用于定位功能开发、测试和演示。请遵守使用场景的规则，不用于伪造打卡、欺骗奖励或绕过业务系统。

## 下载与版本

- [下载 APK](https://github.com/ChenGuoqing1001/MockLocation/releases/latest/download/MockLocation-google.apk)
- <a href="https://play.google.com/store/apps/details?id=com.yangtools.gps.simulator"><img src="assets/google-play.svg" width="20" alt="" /> Google Play</a>
- [GitHub Releases](https://github.com/ChenGuoqing1001/MockLocation/releases)

<details>
<summary>备用下载</summary>

- [蓝奏云](https://wwnr.lanzouv.com/b0knhjugb)
- [123 云盘](https://www.123pan.com/s/k6bMjv-adiI.html)

</details>

## 问题反馈

请提供应用版本、手机型号、Android / 系统版本和复现步骤，提交到 [GitHub Issues](https://github.com/ChenGuoqing1001/MockLocation/issues)。
