# Wukong Virtual Location - Android Mock GPSツール | 悟空虚拟定位

Wukong Virtual Location（Mock Location）は、Androidの模擬位置情報機能を使ってテスト用の位置情報を提供します。地図での地点選択、場所の検索、座標入力、ルートのシミュレーションに対応し、Rootは不要です。

**[⬇ APKをダウンロード](https://github.com/ChenGuoqing1001/MockLocation/releases/latest/download/MockLocation-google.apk)**

<p>
  <br />
  <a href="https://play.google.com/store/apps/details?id=com.yangtools.gps.simulator">
    <img src="assets/google-play-badge.svg" width="180" alt="Google Play" />
  </a>
</p>

[![GitHub release](https://img.shields.io/github/v/release/ChenGuoqing1001/MockLocation)](https://github.com/ChenGuoqing1001/MockLocation/releases/latest) [![GitHub stars](https://img.shields.io/github/stars/ChenGuoqing1001/MockLocation)](https://github.com/ChenGuoqing1001/MockLocation/stargazers)

## アプリのプレビュー

<p>
  <img src="assets/screenshots/map.png" width="260" alt="アプリのプレビュー — Map / Mock Location" />
  <img src="assets/screenshots/route.png" width="260" alt="アプリのプレビュー — Route / Speed" />
</p>

<details>
<summary>その他の言語</summary>

[中文](README.md) · [English](README_en.md) · [Español](README_es.md) · [Français](README_fr.md) · [Deutsch](README_de.md) · [日本語](README_ja.md) · [한국어](README_ko.md) · [Русский](README_ru.md) · [Português](README_pt.md) · [Português (BR)](README_pt_BR.md) · [Italiano](README_it.md) · [العربية](README_ar.md) · [हिन्दी](README_hi.md) · [Türkçe](README_tr.md) · [Nederlands](README_nl.md) · [Tiếng Việt](README_vi.md) · [ไทย](README_th.md) · [தமிழ்](README_ta.md) · [Bahasa Indonesia](README_id.md)

</details>

## 主な機能

- 地図上の地点選択と、場所・住所の検索。
- WGS84、GCJ-02、BD-09の座標入力と変換。
- 経由地点と移動速度を設定するルートシミュレーション。
- Google、AMap、Baiduなど、利用可能な地図の切り替え。
- お気に入りと履歴によるテスト地点の再利用。

## Androidで模擬位置情報を設定する方法

1. APKをダウンロードしてインストールします。必要に応じて、使用するブラウザやファイル管理アプリにインストールを許可します。
2. 設定の「端末情報」などでビルド番号を7回タップし、開発者向けオプションを有効にします。項目名は端末によって異なります。
3. 開発者向けオプションの「仮の現在地情報アプリを選択」などの項目で、このアプリを選びます。
4. 位置情報の権限を許可し、地点または座標を指定してシミュレーションを開始します。
5. テスト対象アプリの位置情報を更新し、テスト終了後にシミュレーションを停止します。

## 模擬位置情報が反映されない場合

アプリの選択、位置情報の権限、シミュレーションの実行状態を確認します。再インストール後はアプリを選び直してください。Androidは模擬位置情報を識別できるようにするため、アプリによっては検出または拒否されます。

## Xiaomi / HyperOSでバックグラウンド動作が止まる場合

画面ロックやアプリ切り替えで停止する場合は、バッテリー制限、バックグラウンド動作、自動起動の設定を確認し、テストに必要な動作を許可します。設定名や場所はシステムのバージョンによって異なります。

## 検索に失敗する、または座標がずれる場合

地図の読み込みや検索に失敗する場合は、ネットワークを確認し、地図を切り替えてください。位置がずれる場合は、入力に合う座標系（WGS84、GCJ-02、BD-09）を選択します。

## プライバシーと利用について

お気に入りと履歴は端末に保存されます。地図と検索はネットワークサービスを使用し、完全なオフライン動作ではありません。プライバシーとアプリ内購入についてはGoogle Playをご確認ください。開発、テスト、デモの目的で、対象サービスのルールに従ってご利用ください。

[Android](https://developer.android.com/studio/debug/dev-options) · [Google Play](https://play.google.com/store/apps/details?id=com.yangtools.gps.simulator)

## ダウンロードとリリース

- [APKをダウンロード](https://github.com/ChenGuoqing1001/MockLocation/releases/latest/download/MockLocation-google.apk)
- <a href="https://play.google.com/store/apps/details?id=com.yangtools.gps.simulator"><img src="assets/google-play.svg" width="20" alt="" /> Google Play</a>
- [GitHub Releases](https://github.com/ChenGuoqing1001/MockLocation/releases)

<details>
<summary>代替ダウンロード</summary>

- [LanzouCloud](https://wwnr.lanzouv.com/b0knhjugb)
- [123Pan](https://www.123pan.com/s/k6bMjv-adiI.html)

</details>

## 問題を報告

アプリのバージョン、端末名、Androidのバージョン、再現手順を添えて報告してください： [GitHub Issues](https://github.com/ChenGuoqing1001/MockLocation/issues).
