# Wukong Virtual Location - Herramienta Mock GPS para Android | 悟空虚拟定位

[简体中文](README.md) · [English](README_en.md)

Wukong Virtual Location (Mock Location) proporciona ubicaciones de prueba mediante la función de ubicación simulada de Android. Selecciona un punto del mapa, busca lugares, introduce coordenadas o simula una ruta. No requiere root.

**[⬇ Descargar APK](https://github.com/ChenGuoqing1001/MockLocation/releases/latest/download/MockLocation-google.apk)**

<p>
  <br />
  <a href="https://play.google.com/store/apps/details?id=com.yangtools.gps.simulator">
    <img src="assets/google-play-badge.svg" width="180" alt="Google Play" />
  </a>
</p>

[![GitHub release](https://img.shields.io/github/v/release/ChenGuoqing1001/MockLocation)](https://github.com/ChenGuoqing1001/MockLocation/releases/latest) [![GitHub stars](https://img.shields.io/github/stars/ChenGuoqing1001/MockLocation)](https://github.com/ChenGuoqing1001/MockLocation/stargazers)

## Vista previa de la aplicación

<p>
  <img src="assets/screenshots/map.png" width="260" alt="Vista previa de la aplicación — Map / Mock Location" />
  <img src="assets/screenshots/route.png" width="260" alt="Vista previa de la aplicación — Route / Speed" />
</p>

<details>
<summary>Otros idiomas</summary>

[中文](README.md) · [English](README_en.md) · [Español](README_es.md) · [Français](README_fr.md) · [Deutsch](README_de.md) · [日本語](README_ja.md) · [한국어](README_ko.md) · [Русский](README_ru.md) · [Português](README_pt.md) · [Português (BR)](README_pt_BR.md) · [Italiano](README_it.md) · [العربية](README_ar.md) · [हिन्दी](README_hi.md) · [Türkçe](README_tr.md) · [Nederlands](README_nl.md) · [Tiếng Việt](README_vi.md) · [ไทย](README_th.md) · [தமிழ்](README_ta.md) · [Bahasa Indonesia](README_id.md)

</details>

## Funciones

- Selección de puntos del mapa y búsqueda de lugares o direcciones.
- Entrada y conversión de coordenadas WGS84, GCJ-02 y BD-09.
- Simulación de rutas con puntos de paso y velocidad configurable.
- Cambio entre mapas disponibles, como Google, AMap y Baidu.
- Favoritos e historial para repetir pruebas.

## Cómo configurar la ubicación simulada en Android

1. Descarga e instala el APK. Si se solicita, permite que el navegador o gestor de archivos utilizado instale el APK.
2. En Ajustes, busca el número de compilación en Acerca del teléfono y púlsalo siete veces para activar las opciones de desarrollador. Los menús varían según el dispositivo.
3. En las opciones de desarrollador, selecciona esta aplicación como aplicación de ubicación simulada.
4. Concede el permiso de ubicación, elige un punto o introduce coordenadas e inicia la simulación.
5. Actualiza la ubicación en la aplicación de prueba y detén la simulación al terminar.

## ¿Por qué no funciona la ubicación simulada?

Comprueba la aplicación de ubicación simulada seleccionada, el permiso de ubicación y que la simulación esté activa. Después de reinstalar, vuelve a seleccionar la aplicación. Android marca las ubicaciones simuladas; algunas aplicaciones pueden detectarlas o rechazarlas.

## Xiaomi / HyperOS: la simulación se detiene en segundo plano

Si se detiene al bloquear la pantalla o cambiar de aplicación, revisa las restricciones de batería, la actividad en segundo plano y el inicio automático, si están disponibles. Permite la ejecución en segundo plano para la prueba. Los ajustes varían según la versión del sistema.

## La búsqueda falla o las coordenadas están desplazadas

Comprueba la conexión y prueba otra fuente de mapas si la búsqueda o la carga del mapa falla. Para coordenadas desplazadas, selecciona el sistema correspondiente a la entrada: WGS84, GCJ-02 o BD-09.

## Privacidad y uso

Los favoritos y el historial se guardan en el dispositivo. Los mapas y la búsqueda usan servicios de red; la aplicación no funciona completamente sin conexión. Consulta la ficha de Google Play para conocer la privacidad y las compras integradas. Usa la herramienta para desarrollo, pruebas y demostraciones siguiendo las reglas de los servicios probados.

[Android](https://developer.android.com/studio/debug/dev-options) · [Google Play](https://play.google.com/store/apps/details?id=com.yangtools.gps.simulator)

## Descargas y versiones

- [Descargar APK](https://github.com/ChenGuoqing1001/MockLocation/releases/latest/download/MockLocation-google.apk)
- <a href="https://play.google.com/store/apps/details?id=com.yangtools.gps.simulator"><img src="assets/google-play.svg" width="20" alt="" /> Google Play</a>
- [GitHub Releases](https://github.com/ChenGuoqing1001/MockLocation/releases)

<details>
<summary>Descargas alternativas</summary>

- [LanzouCloud](https://wwnr.lanzouv.com/b0knhjugb)
- [123Pan](https://www.123pan.com/s/k6bMjv-adiI.html)

</details>

## Informar de un problema

Incluye la versión de la aplicación, el modelo del dispositivo, la versión de Android y los pasos para reproducir el problema: [GitHub Issues](https://github.com/ChenGuoqing1001/MockLocation/issues).
