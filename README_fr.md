# Wukong Virtual Location - Outil Mock GPS pour Android | 悟空虚拟定位

Wukong Virtual Location (Mock Location) fournit des positions de test via la fonction de localisation simulée d’Android. Choisissez un point sur la carte, recherchez un lieu, saisissez des coordonnées ou simulez un itinéraire. Aucun root requis.

**[⬇ Télécharger APK](https://github.com/ChenGuoqing1001/MockLocation/releases/latest/download/MockLocation-google.apk)**

<p>
  <br />
  <a href="https://play.google.com/store/apps/details?id=com.yangtools.gps.simulator">
    <img src="assets/google-play-badge.svg" width="180" alt="Google Play" />
  </a>
</p>

[![GitHub release](https://img.shields.io/github/v/release/ChenGuoqing1001/MockLocation)](https://github.com/ChenGuoqing1001/MockLocation/releases/latest) [![GitHub stars](https://img.shields.io/github/stars/ChenGuoqing1001/MockLocation)](https://github.com/ChenGuoqing1001/MockLocation/stargazers)

## Aperçu de l’application

<p>
  <img src="assets/screenshots/map.png" width="260" alt="Aperçu de l’application — Map / Mock Location" />
  <img src="assets/screenshots/route.png" width="260" alt="Aperçu de l’application — Route / Speed" />
</p>

<details>
<summary>Autres langues</summary>

[中文](README.md) · [English](README_en.md) · [Español](README_es.md) · [Français](README_fr.md) · [Deutsch](README_de.md) · [日本語](README_ja.md) · [한국어](README_ko.md) · [Русский](README_ru.md) · [Português](README_pt.md) · [Português (BR)](README_pt_BR.md) · [Italiano](README_it.md) · [العربية](README_ar.md) · [हिन्दी](README_hi.md) · [Türkçe](README_tr.md) · [Nederlands](README_nl.md) · [Tiếng Việt](README_vi.md) · [ไทย](README_th.md) · [தமிழ்](README_ta.md) · [Bahasa Indonesia](README_id.md)

</details>

## Fonctionnalités

- Sélection de points sur la carte et recherche de lieux ou d’adresses.
- Saisie et conversion de coordonnées WGS84, GCJ-02 et BD-09.
- Simulation d’itinéraires avec points de passage et vitesse réglable.
- Choix entre les cartes disponibles, dont Google, AMap et Baidu.
- Favoris et historique pour reproduire les tests.

## Configurer une localisation simulée sur Android

1. Téléchargez et installez l’APK. Si nécessaire, autorisez le navigateur ou gestionnaire de fichiers utilisé à installer l’APK.
2. Dans les paramètres, trouvez le numéro de build sous À propos du téléphone et touchez-le sept fois pour activer les options pour les développeurs. Les menus varient selon l’appareil.
3. Dans les options pour les développeurs, choisissez cette application comme application de localisation simulée.
4. Accordez l’autorisation de localisation, choisissez un point ou saisissez des coordonnées, puis lancez la simulation.
5. Actualisez la position dans l’application testée et arrêtez la simulation après le test.

## Pourquoi la localisation simulée ne fonctionne-t-elle pas ?

Vérifiez l’application sélectionnée, l’autorisation de localisation et l’état de la simulation. Après une réinstallation, sélectionnez à nouveau l’application. Android marque les positions simulées ; certaines applications peuvent les détecter ou les refuser.

## Xiaomi / HyperOS : arrêt en arrière-plan

Si la simulation s’arrête après le verrouillage de l’écran ou un changement d’application, vérifiez les restrictions de batterie, l’activité en arrière-plan et le démarrage automatique, si disponibles. Autorisez le fonctionnement en arrière-plan pour votre test. Les réglages varient selon la version du système.

## Échec de recherche ou coordonnées décalées

Vérifiez le réseau et essayez une autre source de carte en cas d’échec de recherche ou de chargement. Si la position est décalée, choisissez le système correspondant aux coordonnées saisies : WGS84, GCJ-02 ou BD-09.

## Confidentialité et utilisation

Les favoris et l’historique restent sur l’appareil. Les cartes et recherches utilisent des services réseau ; l’application n’est pas entièrement hors ligne. Consultez la fiche Google Play pour la confidentialité et les achats intégrés. Utilisez cet outil pour le développement, les tests et les démonstrations dans le respect des règles des services testés.

[Android](https://developer.android.com/studio/debug/dev-options) · [Google Play](https://play.google.com/store/apps/details?id=com.yangtools.gps.simulator)

## Téléchargements et versions

- [Télécharger APK](https://github.com/ChenGuoqing1001/MockLocation/releases/latest/download/MockLocation-google.apk)
- <a href="https://play.google.com/store/apps/details?id=com.yangtools.gps.simulator"><img src="assets/google-play.svg" width="20" alt="" /> Google Play</a>
- [GitHub Releases](https://github.com/ChenGuoqing1001/MockLocation/releases)

<details>
<summary>Téléchargements alternatifs</summary>

- [LanzouCloud](https://wwnr.lanzouv.com/b0knhjugb)
- [123Pan](https://www.123pan.com/s/k6bMjv-adiI.html)

</details>

## Signaler un problème

Indiquez la version de l’application, le modèle de l’appareil, la version d’Android et les étapes de reproduction : [GitHub Issues](https://github.com/ChenGuoqing1001/MockLocation/issues).
