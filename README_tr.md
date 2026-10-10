# Wukong Virtual Location - Android Mock GPS Aracı | 悟空虚拟定位

Wukong Virtual Location (Mock Location), Android’in sahte konum özelliği üzerinden test konumları sağlar. Haritada nokta seçin, yer arayın, koordinat girin veya rota simülasyonu yapın. Root gerekmez.

**[⬇ APK indir](https://github.com/ChenGuoqing1001/MockLocation/releases/latest/download/MockLocation-google.apk)**

<p>
  <br />
  <a href="https://play.google.com/store/apps/details?id=com.yangtools.gps.simulator">
    <img src="assets/google-play-badge.svg" width="180" alt="Google Play" />
  </a>
</p>

[![GitHub release](https://img.shields.io/github/v/release/ChenGuoqing1001/MockLocation)](https://github.com/ChenGuoqing1001/MockLocation/releases/latest) [![GitHub stars](https://img.shields.io/github/stars/ChenGuoqing1001/MockLocation)](https://github.com/ChenGuoqing1001/MockLocation/stargazers)

## Uygulama önizlemesi

<p>
  <img src="assets/screenshots/map.png" width="260" alt="Uygulama önizlemesi — Map / Mock Location" />
  <img src="assets/screenshots/route.png" width="260" alt="Uygulama önizlemesi — Route / Speed" />
</p>

<details>
<summary>Diğer diller</summary>

[中文](README.md) · [English](README_en.md) · [Español](README_es.md) · [Français](README_fr.md) · [Deutsch](README_de.md) · [日本語](README_ja.md) · [한국어](README_ko.md) · [Русский](README_ru.md) · [Português](README_pt.md) · [Português (BR)](README_pt_BR.md) · [Italiano](README_it.md) · [العربية](README_ar.md) · [हिन्दी](README_hi.md) · [Türkçe](README_tr.md) · [Nederlands](README_nl.md) · [Tiếng Việt](README_vi.md) · [ไทย](README_th.md) · [தமிழ்](README_ta.md) · [Bahasa Indonesia](README_id.md)

</details>

## Özellikler

- Haritada nokta seçimi ve yer veya adres arama.
- WGS84, GCJ-02 ve BD-09 koordinatlarını girme ve dönüştürme.
- Ara noktalar ve ayarlanabilir hız ile rota simülasyonu.
- Google, AMap ve Baidu gibi kullanılabilir haritalar arasında geçiş.
- Tekrarlanabilir testler için favoriler ve geçmiş.

## Android’de sahte konum nasıl ayarlanır?

1. APK’yı indirip yükleyin. Gerekirse kullanılan tarayıcıya veya dosya yöneticisine yükleme izni verin.
2. Telefon hakkında bölümünde derleme numarasına yedi kez dokunarak geliştirici seçeneklerini açın. Menü adları cihaza göre değişebilir.
3. Geliştirici seçeneklerinde bu uygulamayı sahte konum uygulaması olarak seçin.
4. Konum izni verin, bir nokta seçin veya koordinat girin ve simülasyonu başlatın.
5. Test uygulamasının konumunu yenileyin ve test sonunda simülasyonu durdurun.

## Sahte konum neden çalışmıyor?

Seçilen uygulamayı, konum iznini ve simülasyon durumunu kontrol edin. Yeniden yükledikten sonra uygulamayı tekrar seçin. Android sahte konumları işaretler; bazı uygulamalar bunları algılayabilir veya reddedebilir.

## Xiaomi / HyperOS: arka planda simülasyon duruyor

Ekranı kilitledikten veya uygulama değiştirdikten sonra duruyorsa pil kısıtlamalarını, arka plan etkinliğini ve varsa otomatik başlatmayı kontrol edin. Test için arka planda çalışmaya izin verin. Ayarlar sistem sürümüne göre değişir.

## Arama başarısız veya koordinatlar kaymış

Arama ya da harita yükleme başarısızsa ağı kontrol edip başka harita kaynağı deneyin. Konum kaymışsa girilen koordinatlarla eşleşen WGS84, GCJ-02 veya BD-09 sistemini seçin.

## Gizlilik ve kullanım

Favoriler ve geçmiş cihazda saklanır. Haritalar ve arama ağ hizmetlerini kullanır; uygulama tamamen çevrimdışı değildir. Gizlilik ve uygulama içi satın almalar için Google Play’e bakın. Aracı geliştirme, test ve gösterimler için, test edilen hizmetlerin kurallarına uyarak kullanın.

[Android](https://developer.android.com/studio/debug/dev-options) · [Google Play](https://play.google.com/store/apps/details?id=com.yangtools.gps.simulator)

## İndirmeler ve sürümler

- [APK indir](https://github.com/ChenGuoqing1001/MockLocation/releases/latest/download/MockLocation-google.apk)
- <a href="https://play.google.com/store/apps/details?id=com.yangtools.gps.simulator"><img src="assets/google-play.svg" width="20" alt="" /> Google Play</a>
- [GitHub Releases](https://github.com/ChenGuoqing1001/MockLocation/releases)

<details>
<summary>Alternatif indirmeler</summary>

- [LanzouCloud](https://wwnr.lanzouv.com/b0knhjugb)
- [123Pan](https://www.123pan.com/s/k6bMjv-adiI.html)

</details>

## Sorun bildir

Uygulama sürümünü, cihaz modelini, Android sürümünü ve sorunu yeniden oluşturma adımlarını belirtin: [GitHub Issues](https://github.com/ChenGuoqing1001/MockLocation/issues).
