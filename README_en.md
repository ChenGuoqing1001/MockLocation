# Wukong Virtual Location — Android Mock GPS & Route Testing

Wukong Virtual Location (Mock Location) supplies test locations through Android’s mock location feature. Pick a map point, search places, enter coordinates or simulate a route to test maps, navigation and location-based apps. No root required.

**[⬇ Download APK](https://github.com/ChenGuoqing1001/MockLocation/releases/latest/download/MockLocation-google.apk)**

<p>
  <br />
  <a href="https://play.google.com/store/apps/details?id=com.yangtools.gps.simulator">
    <img src="assets/google-play-badge.svg" width="180" alt="Google Play" />
  </a>
</p>

[![GitHub release](https://img.shields.io/github/v/release/ChenGuoqing1001/MockLocation)](https://github.com/ChenGuoqing1001/MockLocation/releases/latest) [![GitHub stars](https://img.shields.io/github/stars/ChenGuoqing1001/MockLocation)](https://github.com/ChenGuoqing1001/MockLocation/stargazers)

## App preview

<p>
  <img src="assets/screenshots/map.png" width="260" alt="Mock Location map picker and Start Mock control" />
  <img src="assets/screenshots/route.png" width="260" alt="Mock Location route planning and speed settings" />
</p>

<details>
<summary>Other languages</summary>

[中文](README.md) · [English](README_en.md) · [Español](README_es.md) · [Français](README_fr.md) · [Deutsch](README_de.md) · [日本語](README_ja.md) · [한국어](README_ko.md) · [Русский](README_ru.md) · [Português](README_pt.md) · [Português (BR)](README_pt_BR.md) · [Italiano](README_it.md) · [العربية](README_ar.md) · [हिन्दी](README_hi.md) · [Türkçe](README_tr.md) · [Nederlands](README_nl.md) · [Tiếng Việt](README_vi.md) · [ไทย](README_th.md) · [தமிழ்](README_ta.md) · [Bahasa Indonesia](README_id.md)

</details>

## Features

- **Map picker and place search**: Choose a point or search for a place or address.
- **Coordinate input**: Work with WGS84, GCJ-02 and BD-09 coordinates and conversion.
- **Route simulation**: Add waypoints and set movement speed for location testing.
- **Map sources**: Switch between Google, AMap, Baidu and other available maps.
- **Favorites and history**: Save test locations for repeatable checks.

## How to set up mock location on Android

1. Download and install the APK. If prompted, allow the browser or file manager used for this installation to install the APK.
2. In Settings, find the Build number under About phone and tap it seven times. Follow the prompts to enable Developer options. Menu names vary by device.
3. Open Developer options, find Select mock location app, and select this app.
4. Open the app, grant the requested location permission, choose a point or enter coordinates, and start mocking.
5. Refresh location in the app you are testing. Stop mocking when the test is finished.

See [Android’s Developer options guide](https://developer.android.com/studio/debug/dev-options) for device settings. Check the installer and store listing for device compatibility.

<details>
<summary>Install with ADB</summary>

Install Android Platform Tools, enable USB debugging and authorize the computer on your device. Run this command from the APK directory:

```bash
adb install -r MockLocation-google.apk
```

</details>

## Why is mock location not working?

Confirm this app is still selected as the mock location app, mocking is running, and location permission is granted. After an update or reinstall, select the app again and refresh location in your test app.

Android marks mock locations. Some apps can detect or reject them; compatibility with every third-party app is not guaranteed. See [Android’s mock location API](https://developer.android.com/reference/android/location/Location#isMock()).

## Why does mocking stop in the background on Xiaomi / HyperOS?

Check whether the app is still running. If mocking stops after switching apps or locking the screen, review battery restrictions, background activity and autostart settings, where available. Allow background operation for your test and check again. Setting names vary across MIUI / HyperOS versions.

## Why does place search or map loading fail?

Check your network and map service availability, then try another map source. Place search uses the Baidu Maps API. Map loading and search need network access; the app is not entirely offline.

## Why are my entered coordinates offset?

Select the coordinate system that matches your input: WGS84, GCJ-02 or BD-09. Mixing coordinate systems can shift the location. Use a known place to check the conversion.

## Privacy and use

Favorites and history are stored on the device. Map and search features contact their map services. See the [Google Play listing](https://play.google.com/store/apps/details?id=com.yangtools.gps.simulator) and its privacy policy for privacy details and in-app purchases.

Use this tool for location development, testing and demonstrations. Follow the rules of the services you test; do not use it to falsify attendance, deceive reward systems or bypass business controls.

## Downloads and releases

- [Download APK](https://github.com/ChenGuoqing1001/MockLocation/releases/latest/download/MockLocation-google.apk)
- <a href="https://play.google.com/store/apps/details?id=com.yangtools.gps.simulator"><img src="assets/google-play.svg" width="20" alt="" /> Google Play</a>
- [GitHub Releases](https://github.com/ChenGuoqing1001/MockLocation/releases)

<details>
<summary>Alternative downloads</summary>

- [LanzouCloud](https://wwnr.lanzouv.com/b0knhjugb)
- [123Pan](https://www.123pan.com/s/k6bMjv-adiI.html)

</details>

## Report a problem

Include the app version, device model, Android / system version and steps to reproduce in [GitHub Issues](https://github.com/ChenGuoqing1001/MockLocation/issues).
