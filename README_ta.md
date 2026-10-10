# Wukong Virtual Location - Android Mock GPS கருவி | 悟空虚拟定位

[简体中文](README.md) · [English](README_en.md)

Wukong Virtual Location (Mock Location), Android-இன் மாதிரி இருப்பிட வசதியைக் கொண்டு சோதனை இருப்பிடங்களை வழங்குகிறது. வரைபடத்தில் புள்ளியைத் தேர்ந்தெடுக்கவும், இடத்தைத் தேடவும், ஆயங்களை உள்ளிடவும் அல்லது வழித்தடத்தை உருவகப்படுத்தவும். Root தேவையில்லை.

**[⬇ APK பதிவிறக்கவும்](https://github.com/ChenGuoqing1001/MockLocation/releases/latest/download/MockLocation-google.apk)**

<p>
  <br />
  <a href="https://play.google.com/store/apps/details?id=com.yangtools.gps.simulator">
    <img src="assets/google-play-badge.svg" width="180" alt="Google Play" />
  </a>
</p>

[![GitHub release](https://img.shields.io/github/v/release/ChenGuoqing1001/MockLocation)](https://github.com/ChenGuoqing1001/MockLocation/releases/latest) [![GitHub stars](https://img.shields.io/github/stars/ChenGuoqing1001/MockLocation)](https://github.com/ChenGuoqing1001/MockLocation/stargazers)

## செயலியின் முன்னோட்டம்

<p>
  <img src="assets/screenshots/map.png" width="260" alt="செயலியின் முன்னோட்டம் — Map / Mock Location" />
  <img src="assets/screenshots/route.png" width="260" alt="செயலியின் முன்னோட்டம் — Route / Speed" />
</p>

<details>
<summary>பிற மொழிகள்</summary>

[中文](README.md) · [English](README_en.md) · [Español](README_es.md) · [Français](README_fr.md) · [Deutsch](README_de.md) · [日本語](README_ja.md) · [한국어](README_ko.md) · [Русский](README_ru.md) · [Português](README_pt.md) · [Português (BR)](README_pt_BR.md) · [Italiano](README_it.md) · [العربية](README_ar.md) · [हिन्दी](README_hi.md) · [Türkçe](README_tr.md) · [Nederlands](README_nl.md) · [Tiếng Việt](README_vi.md) · [ไทย](README_th.md) · [தமிழ்](README_ta.md) · [Bahasa Indonesia](README_id.md)

</details>

## அம்சங்கள்

- வரைபடத்தில் புள்ளிகளைத் தேர்ந்தெடுத்தல் மற்றும் இடம் அல்லது முகவரியைத் தேடுதல்.
- WGS84, GCJ-02 மற்றும் BD-09 ஆயங்களை உள்ளிடுதல் மற்றும் மாற்றுதல்.
- இடைநிலைப் புள்ளிகள் மற்றும் வேகத்துடன் வழித்தட உருவகப்படுத்தல்.
- Google, AMap மற்றும் Baidu போன்ற கிடைக்கும் வரைபடங்களுக்கு இடையில் மாறுதல்.
- விருப்பங்கள் மற்றும் வரலாற்றிலிருந்து சோதனை இடங்களை மீண்டும் பயன்படுத்துதல்.

## Android-இல் மாதிரி இருப்பிடத்தை அமைப்பது எப்படி

1. APK-ஐப் பதிவிறக்கி நிறுவவும். தேவைப்பட்டால், பயன்படுத்தும் உலாவி அல்லது கோப்பு மேலாளருக்கு நிறுவும் அனுமதி வழங்கவும்.
2. தொலைபேசி பற்றிய பகுதியில் உள்ள Build number-ஐ ஏழு முறை தட்டி உருவாக்குநர் விருப்பங்களை இயக்கவும். பட்டி பெயர்கள் சாதனத்திற்கு ஏற்ப மாறலாம்.
3. உருவாக்குநர் விருப்பங்களில் இந்தச் செயலியை மாதிரி இருப்பிடச் செயலியாகத் தேர்ந்தெடுக்கவும்.
4. இருப்பிட அனுமதி வழங்கி, புள்ளியைத் தேர்ந்தெடுக்கவும் அல்லது ஆயங்களை உள்ளிட்டு உருவகப்படுத்தலைத் தொடங்கவும்.
5. சோதனைச் செயலியில் இருப்பிடத்தைப் புதுப்பித்து, சோதனை முடிந்ததும் உருவகப்படுத்தலை நிறுத்தவும்.

## மாதிரி இருப்பிடம் ஏன் செயல்படவில்லை?

தேர்ந்தெடுத்த செயலி, இருப்பிட அனுமதி மற்றும் உருவகப்படுத்தலின் நிலையைச் சரிபார்க்கவும். மீண்டும் நிறுவிய பிறகு செயலியை மறுபடியும் தேர்ந்தெடுக்கவும். Android மாதிரி இருப்பிடங்களைக் குறிக்கிறது; சில செயலிகள் அவற்றைக் கண்டறியவோ மறுக்கவோ முடியும்.

## Xiaomi / HyperOS-இல் பின்னணியில் உருவகப்படுத்தல் நின்றால்

திரையைப் பூட்டியதும் அல்லது வேறு செயலிக்கு மாறியதும் நின்றால், பேட்டரி கட்டுப்பாடுகள், பின்னணிச் செயல்பாடு மற்றும் கிடைத்தால் தானியங்கித் தொடக்க அமைப்புகளைச் சரிபார்க்கவும். சோதனைக்குத் தேவையான பின்னணி இயக்கத்தை அனுமதிக்கவும். அமைப்புகள் கணினிப் பதிப்பிற்கு ஏற்ப மாறலாம்.

## தேடல் தோல்வி அல்லது ஆயங்களின் இடமாற்றம்

தேடல் அல்லது வரைபடம் ஏற்றுதல் தோல்வியடைந்தால், இணைய இணைப்பைச் சரிபார்த்து மற்றொரு வரைபட மூலத்தை முயற்சிக்கவும். இருப்பிடம் விலகினால், உள்ளீட்டிற்கு ஏற்ற WGS84, GCJ-02 அல்லது BD-09 ஆய முறையைத் தேர்ந்தெடுக்கவும்.

## தனியுரிமை மற்றும் பயன்பாடு

விருப்பங்களும் வரலாறும் சாதனத்தில் சேமிக்கப்படுகின்றன. வரைபடங்களும் தேடலும் இணையச் சேவைகளைப் பயன்படுத்துகின்றன; செயலி முழுமையாக இணையமின்றி இயங்காது. தனியுரிமை மற்றும் செயலிக்குள் வாங்குதல் பற்றிய விவரங்களுக்கு Google Play-ஐப் பார்க்கவும். உருவாக்கம், சோதனை மற்றும் விளக்கக் காட்சிகளுக்குப் பயன்படுத்தி, சோதிக்கும் சேவைகளின் விதிகளைப் பின்பற்றவும்.

[Android](https://developer.android.com/studio/debug/dev-options) · [Google Play](https://play.google.com/store/apps/details?id=com.yangtools.gps.simulator)

## பதிவிறக்கங்கள் மற்றும் பதிப்புகள்

- [APK பதிவிறக்கவும்](https://github.com/ChenGuoqing1001/MockLocation/releases/latest/download/MockLocation-google.apk)
- <a href="https://play.google.com/store/apps/details?id=com.yangtools.gps.simulator"><img src="assets/google-play.svg" width="20" alt="" /> Google Play</a>
- [GitHub Releases](https://github.com/ChenGuoqing1001/MockLocation/releases)

<details>
<summary>மாற்றுப் பதிவிறக்கங்கள்</summary>

- [LanzouCloud](https://wwnr.lanzouv.com/b0knhjugb)
- [123Pan](https://www.123pan.com/s/k6bMjv-adiI.html)

</details>

## சிக்கலைத் தெரிவிக்கவும்

செயலியின் பதிப்பு, சாதன மாதிரி, Android பதிப்பு மற்றும் சிக்கலை மீண்டும் உருவாக்கும் படிகளைச் சேர்க்கவும்: [GitHub Issues](https://github.com/ChenGuoqing1001/MockLocation/issues).
