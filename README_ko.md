# Wukong Virtual Location - Android Mock GPS 도구 | 悟空虚拟定位

Wukong Virtual Location(Mock Location)은 Android의 모의 위치 기능으로 테스트 위치를 제공합니다. 지도에서 지점을 선택하거나 장소 검색, 좌표 입력, 경로 시뮬레이션을 사용할 수 있으며 루팅이 필요하지 않습니다.

**[⬇ APK 다운로드](https://github.com/ChenGuoqing1001/MockLocation/releases/latest/download/MockLocation-google.apk)** · [Google Play](https://play.google.com/store/apps/details?id=com.yangtools.gps.simulator)

[![GitHub release](https://img.shields.io/github/v/release/ChenGuoqing1001/MockLocation)](https://github.com/ChenGuoqing1001/MockLocation/releases/latest) [![GitHub stars](https://img.shields.io/github/stars/ChenGuoqing1001/MockLocation)](https://github.com/ChenGuoqing1001/MockLocation/stargazers)

## 앱 미리보기

<p>
  <img src="assets/screenshots/map.png" width="260" alt="앱 미리보기 — Map / Mock Location" />
  <img src="assets/screenshots/route.png" width="260" alt="앱 미리보기 — Route / Speed" />
</p>

<details>
<summary>다른 언어</summary>

[中文](README.md) · [English](README_en.md) · [Español](README_es.md) · [Français](README_fr.md) · [Deutsch](README_de.md) · [日本語](README_ja.md) · [한국어](README_ko.md) · [Русский](README_ru.md) · [Português](README_pt.md) · [Português (BR)](README_pt_BR.md) · [Italiano](README_it.md) · [العربية](README_ar.md) · [हिन्दी](README_hi.md) · [Türkçe](README_tr.md) · [Nederlands](README_nl.md) · [Tiếng Việt](README_vi.md) · [ไทย](README_th.md) · [தமிழ்](README_ta.md) · [Bahasa Indonesia](README_id.md)

</details>

## 주요 기능

- 지도 지점 선택 및 장소·주소 검색.
- WGS84, GCJ-02, BD-09 좌표 입력 및 변환.
- 경유 지점과 이동 속도를 설정하는 경로 시뮬레이션.
- Google, AMap, Baidu 등 사용 가능한 지도 전환.
- 즐겨찾기와 기록을 통한 테스트 위치 재사용.

## Android 모의 위치 설정 방법

1. APK를 다운로드하고 설치합니다. 필요한 경우 사용한 브라우저나 파일 관리자에 APK 설치를 허용합니다.
2. 설정의 휴대전화 정보에서 빌드 번호를 7번 눌러 개발자 옵션을 활성화합니다. 메뉴 이름은 기기마다 다릅니다.
3. 개발자 옵션의 모의 위치 앱 선택에서 이 앱을 선택합니다.
4. 위치 권한을 허용하고 지점이나 좌표를 지정한 뒤 시뮬레이션을 시작합니다.
5. 테스트 앱의 위치를 새로 고치고 테스트가 끝나면 시뮬레이션을 중지합니다.

## 모의 위치가 적용되지 않을 때

선택한 모의 위치 앱, 위치 권한 및 실행 상태를 확인하세요. 재설치 후에는 앱을 다시 선택하세요. Android는 모의 위치를 표시하므로 일부 앱은 이를 감지하거나 거부할 수 있습니다.

## Xiaomi / HyperOS에서 백그라운드 실행이 중지될 때

화면을 잠그거나 다른 앱으로 전환할 때 중지된다면 배터리 제한, 백그라운드 활동, 자동 시작 설정이 있는지 확인하세요. 테스트에 필요한 백그라운드 실행을 허용한 후 다시 확인하세요. 설정 이름은 시스템 버전에 따라 다릅니다.

## 검색이 실패하거나 좌표가 어긋날 때

지도 로딩이나 검색 실패 시 네트워크를 확인하고 지도 소스를 바꿔 보세요. 좌표가 어긋나면 입력과 일치하는 WGS84, GCJ-02 또는 BD-09 좌표계를 선택하세요.

## 개인정보 및 사용 안내

즐겨찾기와 기록은 기기에 저장됩니다. 지도와 검색은 네트워크 서비스를 사용하므로 완전한 오프라인 앱이 아닙니다. 개인정보와 인앱 구매는 Google Play 안내를 확인하세요. 개발, 테스트 및 시연에 사용하고 테스트 대상 서비스의 규칙을 준수하세요.

[Android](https://developer.android.com/studio/debug/dev-options) · [Google Play](https://play.google.com/store/apps/details?id=com.yangtools.gps.simulator)

## 다운로드 및 버전

- [APK 다운로드](https://github.com/ChenGuoqing1001/MockLocation/releases/latest/download/MockLocation-google.apk)
- [Google Play](https://play.google.com/store/apps/details?id=com.yangtools.gps.simulator)
- [GitHub Releases](https://github.com/ChenGuoqing1001/MockLocation/releases)

<details>
<summary>대체 다운로드</summary>

- [LanzouCloud](https://wwnr.lanzouv.com/b0knhjugb)
- [123Pan](https://www.123pan.com/s/k6bMjv-adiI.html)

</details>

## 문제 신고

앱 버전, 기기 모델, Android 버전 및 재현 절차를 포함해 신고하세요: [GitHub Issues](https://github.com/ChenGuoqing1001/MockLocation/issues).
