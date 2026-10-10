# Wukong Virtual Location - เครื่องมือ Mock GPS สำหรับ Android | 悟空虚拟定位

[简体中文](README.md) · [English](README_en.md)

Wukong Virtual Location (Mock Location) ให้ตำแหน่งทดสอบผ่านฟีเจอร์ตำแหน่งจำลองของ Android เลือกจุดบนแผนที่ ค้นหาสถานที่ ป้อนพิกัด หรือจำลองเส้นทางได้ โดยไม่ต้อง Root

**[⬇ ดาวน์โหลด APK](https://github.com/ChenGuoqing1001/MockLocation/releases/latest/download/MockLocation-google.apk)**

<p>
  <br />
  <a href="https://play.google.com/store/apps/details?id=com.yangtools.gps.simulator">
    <img src="assets/google-play-badge.svg" width="180" alt="Google Play" />
  </a>
</p>

[![GitHub release](https://img.shields.io/github/v/release/ChenGuoqing1001/MockLocation)](https://github.com/ChenGuoqing1001/MockLocation/releases/latest) [![GitHub stars](https://img.shields.io/github/stars/ChenGuoqing1001/MockLocation)](https://github.com/ChenGuoqing1001/MockLocation/stargazers)

## ตัวอย่างแอป

<p>
  <img src="assets/screenshots/map.png" width="260" alt="ตัวอย่างแอป — Map / Mock Location" />
  <img src="assets/screenshots/route.png" width="260" alt="ตัวอย่างแอป — Route / Speed" />
</p>

<details>
<summary>ภาษาอื่น</summary>

[中文](README.md) · [English](README_en.md) · [Español](README_es.md) · [Français](README_fr.md) · [Deutsch](README_de.md) · [日本語](README_ja.md) · [한국어](README_ko.md) · [Русский](README_ru.md) · [Português](README_pt.md) · [Português (BR)](README_pt_BR.md) · [Italiano](README_it.md) · [العربية](README_ar.md) · [हिन्दी](README_hi.md) · [Türkçe](README_tr.md) · [Nederlands](README_nl.md) · [Tiếng Việt](README_vi.md) · [ไทย](README_th.md) · [தமிழ்](README_ta.md) · [Bahasa Indonesia](README_id.md)

</details>

## ฟีเจอร์

- เลือกจุดบนแผนที่และค้นหาสถานที่หรือที่อยู่
- ป้อนและแปลงพิกัด WGS84, GCJ-02 และ BD-09
- จำลองเส้นทางด้วยจุดแวะและความเร็วที่ปรับได้
- สลับแผนที่ที่มีให้ใช้ เช่น Google, AMap และ Baidu
- ใช้รายการโปรดและประวัติเพื่อทดสอบซ้ำ

## วิธีตั้งค่าตำแหน่งจำลองบน Android

1. ดาวน์โหลดและติดตั้ง APK หากระบบร้องขอ ให้สิทธิ์ติดตั้งแก่เบราว์เซอร์หรือตัวจัดการไฟล์ที่ใช้
2. ในหัวข้อเกี่ยวกับโทรศัพท์ แตะหมายเลขบิลด์เจ็ดครั้งเพื่อเปิดตัวเลือกสำหรับนักพัฒนา ชื่อเมนูอาจต่างกันตามอุปกรณ์
3. ในตัวเลือกสำหรับนักพัฒนา เลือกแอปนี้เป็นแอปตำแหน่งจำลอง
4. ให้สิทธิ์ตำแหน่ง เลือกจุดหรือป้อนพิกัด แล้วเริ่มจำลอง
5. รีเฟรชตำแหน่งในแอปที่ทดสอบ และหยุดจำลองเมื่อทดสอบเสร็จ

## ทำไมตำแหน่งจำลองจึงไม่ทำงาน

ตรวจสอบแอปที่เลือก สิทธิ์ตำแหน่ง และสถานะการจำลอง หลังติดตั้งใหม่ให้เลือกแอปอีกครั้ง Android ทำเครื่องหมายตำแหน่งจำลอง บางแอปจึงอาจตรวจพบหรือปฏิเสธได้

## Xiaomi / HyperOS: การจำลองหยุดเมื่อทำงานเบื้องหลัง

หากหยุดหลังล็อกหน้าจอหรือสลับแอป ให้ตรวจสอบข้อจำกัดแบตเตอรี่ การทำงานเบื้องหลัง และการเริ่มอัตโนมัติถ้ามี อนุญาตการทำงานเบื้องหลังสำหรับการทดสอบ การตั้งค่าอาจต่างกันตามเวอร์ชันระบบ

## ค้นหาไม่สำเร็จหรือพิกัดคลาดเคลื่อน

ตรวจสอบเครือข่ายและลองแหล่งแผนที่อื่นหากค้นหาหรือโหลดแผนที่ไม่สำเร็จ หากตำแหน่งคลาดเคลื่อน ให้เลือกระบบพิกัดที่ตรงกับข้อมูลที่ป้อน ได้แก่ WGS84, GCJ-02 หรือ BD-09

## ความเป็นส่วนตัวและการใช้งาน

รายการโปรดและประวัติเก็บอยู่บนอุปกรณ์ แผนที่และการค้นหาใช้บริการเครือข่าย แอปจึงไม่ได้ทำงานแบบออฟไลน์ทั้งหมด ดูข้อมูลความเป็นส่วนตัวและการซื้อในแอปที่ Google Play ใช้เครื่องมือนี้สำหรับการพัฒนา ทดสอบ และสาธิตตามกฎของบริการที่ทดสอบ

[Android](https://developer.android.com/studio/debug/dev-options) · [Google Play](https://play.google.com/store/apps/details?id=com.yangtools.gps.simulator)

## ดาวน์โหลดและเวอร์ชัน

- [ดาวน์โหลด APK](https://github.com/ChenGuoqing1001/MockLocation/releases/latest/download/MockLocation-google.apk)
- <a href="https://play.google.com/store/apps/details?id=com.yangtools.gps.simulator"><img src="assets/google-play.svg" width="20" alt="" /> Google Play</a>
- [GitHub Releases](https://github.com/ChenGuoqing1001/MockLocation/releases)

<details>
<summary>ลิงก์ดาวน์โหลดสำรอง</summary>

- [LanzouCloud](https://wwnr.lanzouv.com/b0knhjugb)
- [123Pan](https://www.123pan.com/s/k6bMjv-adiI.html)

</details>

## รายงานปัญหา

ระบุเวอร์ชันแอป รุ่นอุปกรณ์ เวอร์ชัน Android และขั้นตอนที่ทำให้เกิดปัญหา: [GitHub Issues](https://github.com/ChenGuoqing1001/MockLocation/issues).
