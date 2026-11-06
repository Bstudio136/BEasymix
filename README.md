<div align="center">
  <h3>🌍 Choose your language / Choisissez votre langue</h3>
  <a href="#english">🇬🇧 English</a> | <a href="#francais">🇫🇷 Français</a>
</div>

---

<div id="english"></div>
🇬🇧<br>
# 🌟 BEasymix Studio | Bstudio136

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Web Audio API](https://img.shields.io/badge/Web_Audio_API-FF5CF0?style=for-the-badge&logo=audio-technica&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-121013?style=for-the-badge&logo=github&logoColor=white)
![License-Restricted](https://img.shields.io/badge/License-Restricted-yellow?style=for-the-badge)

A powerful, 100% client-side web-based audio mixing and mastering studio. Upload your vocal tracks, add your instrumental, and let the app process your song with professional-grade effects, all directly in your browser without any server.

## 🔗 Live Demo
👉 **[Visit the Studio](https://bstudio136.github.io/BEasymix/)**

## ✨ Features

- **Multi-track Loading**: Import your Main Vocal, Instrumental, and Adlibs (WAV, MP3, M4A, OGG, FLAC).

- **Microphone Recording**: Built-in mic support with real-time waveform visualization (Requires HTTPS/Localhost).

- **AI Autotune (Client-side)**: Pitch detection and correction with scale snapping (Chromatic, Major, Minor, etc.).

- **Pro Audio Processing**: 4-band EQ, Compressor, Gate, De-esser, Saturation, Chorus, Delay, and Convolution Reverb.

- **Mastering Chain**: LUFS normalization (BS.1770), Glue compression, Stereo widening (M/S), and Brick-wall Limiter.

- **Live Metering**: Real-time Peak, RMS, and LUFS visual meters.

- **Export**: Render and download your mix in high-quality WAV (16-bit, 24-bit, or 32-bit float).

- **100% Responsive & Local**: Adapts perfectly to mobile (iOS/Android) and desktop. Your data never leaves your device.


## 🛠️ Tech Stack

- **HTML5**: Semantic structure and Canvas for real-time visualizations.

- **CSS3**: CSS Variables, Flexbox, CSS Grid, Animations, responsive design (safe-areas for iOS).

- **JavaScript (Vanilla)**: Complex audio routing, DSP algorithms (SOLA pitch shifting, K-weighting), and UI management.

- **Web Audio API**: Utilizes AudioContext and OfflineAudioContext for high-performance, non-blocking audio rendering.

- **GitHub Pages**: Hosted securely over HTTPS (crucial for microphone access).


## 🚀 Installation & Usage

This project is a single static file. To run it locally:

1. Clone the repository: `git clone https://github.com/Bstudio136/BEasymix.git`

2. **Important for Microphone**: Due to browser security policies, the microphone only works on https:// or localhost. Do not open the file directly (file://). Run a local server: `python3 -m http.server 8000`
3. Open `http://localhost:8000` in your browser.

## 🎨 Customization

To adapt this studio to your own needs:

1. **Colors**: Modify the CSS variables in `:root` to change the theme colors (e.g., `--acc: #7c5cff` for the primary purple).

2. **Presets**: You can add or modify the built-in presets (Pop, Rap, R&B, etc.) by editing the `PRESETS` object in the JavaScript section.
3. **Export Name**: Change the default filename by modifying the value attribute of the `<input id="ex-name">`.

## 👨‍💻 Author

**Bstudio136**

- 🐙 GitHub : [@Bstudio136](https://github.com/Bstudio136)

- 🎵 TikTok : [@bstudio136](https://tiktok.com/@bstudio136)

- 🐦 Twitter / X : [@Bstudio136](https://x.com/Bstudio136)

- 📺 YouTube : [@Bstudio136](https://www.youtube.com/@Bstudio136)


## 📄 License

This project is licensed under the **MIT Non-Commercial & No-Derivatives License (Restricted MIT)**. You are free to use the Software as-is for free, but modifying, reselling, or sublicensing the code is strictly forbidden. See the [LICENSE](LICENSE) file for details.

<a href="https://hiddenswap.com/pay/AgRPwfFe" target="_blank" rel="noopener"><img src="https://hiddenswap.com/pay/AgRPwfFe/button.svg" alt="Donate with any coin" width="247" height="44"></a>

---

<div id="francais"></div>
🇫🇷<br>
# 🌟 BEasymix Studio | Bstudio136

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Web Audio API](https://img.shields.io/badge/Web_Audio_API-FF5CF0?style=for-the-badge&logo=audio-technica&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-121013?style=for-the-badge&logo=github&logoColor=white)
![License-Restricted](https://img.shields.io/badge/License-Restricted-yellow?style=for-the-badge)

Un studio de mixage et mastering audio puissant, 100% côté client (client-side) et s'exécutant dans le navigateur. Importez vos pistes vocales, ajoutez votre instrumental, et laissez l'application traiter votre morceau avec des effets de qualité professionnelle, sans aucun serveur.

## 🔗 Démo en direct
👉 **[Visiter le Studio](https://bstudio136.github.io/BEasymix/)**

## ✨ Fonctionnalités

- **Chargement Multipiste** : Importez votre Voix principale, l'Instrumental et les Adlibs (WAV, MP3, M4A, OGG, FLAC).

- **Enregistrement Micro** : Prise en charge du microphone avec visualisation de la forme d'onde en temps réel (nécessite HTTPS/Localhost).

- **Autotune IA (Côté Client)** : Détection et correction de la hauteur avec accrochage à la gamme (Chromatique, Majeur, Mineur, etc.).

- **Traitement Audio Pro** : EQ 4 bandes, Compresseur, Gate, De-esser, Saturation, Chorus, Delay et Réverbération par convolution.

- **Chaîne de Mastering** : Normalisation LUFS (BS.1770), compression Glue, élargissement stéréo (M/S) et Limiteur brick-wall.

- **Mesure en Direct** : Compteurs visuels en temps réel pour les Peak, RMS et LUFS.

- **Export** : Rendu et téléchargement de votre mix en WAV haute qualité (16-bit, 24-bit ou 32-bit float).

- **100% Responsive & Local** : S'adapte parfaitement aux mobiles (iOS/Android) et ordinateurs. Vos données ne quittent jamais votre appareil.


## 🛠️ Technologies Utilisées

- **HTML5** : Structure sémantique et Canvas pour les visualisations en temps réel.

- **CSS3** : Variables CSS, Flexbox, CSS Grid, Animations, design responsive (safe-areas pour iOS).

- **JavaScript (Vanilla)** : Routage audio complexe, algorithmes DSP (pitch shifting SOLA, K-weighting) et gestion de l'interface.

- **Web Audio API** : Utilisation d'AudioContext et OfflineAudioContext pour un rendu audio haute performance et non-bloquant.

- **GitHub Pages** : Hébergé de manière sécurisée via HTTPS (crucial pour l'accès au microphone).


## 🚀 Installation & Utilisation

Ce projet est un simple fichier statique. Pour le faire fonctionner localement :

1. Clonez le dépôt : `git clone https://github.com/Bstudio136/BEasymix.git`

2. **Important pour le Microphone** : En raison des politiques de sécurité des navigateurs, le microphone ne fonctionne que sur https:// ou localhost. N'ouvrez pas le fichier directement (file://). Lancez un serveur local : `python3 -m http.server 8000`
3. Ouvrez `http://localhost:8000` dans votre navigateur.

## 🎨 Personnalisation

Pour adapter ce studio à vos propres besoins :

1. **Couleurs** : Modifiez les variables CSS dans `:root` pour changer les couleurs du thème (par exemple, `--acc: #7c5cff` pour le violet principal).

2. **Presets** : Vous pouvez ajouter ou modifier les presets intégrés (Pop, Rap, R&B, etc.) en éditant l'objet `PRESETS` dans la partie JavaScript.
3. **Nom d'export** : Changez le nom de fichier par défaut en modifiant l'attribut value de l'`<input id="ex-name">`.

## 👨‍💻 Auteur

**Bstudio136**

- 🐙 GitHub : [@Bstudio136](https://github.com/Bstudio136)

- 🎵 TikTok : [@bstudio136](https://tiktok.com/@bstudio136)

- 🐦 Twitter / X : [@Bstudio136](https://x.com/Bstudio136)

- 📺 YouTube : [@Bstudio136](https://www.youtube.com/@Bstudio136)


## 📄 Licence

Ce projet est sous **Licence MIT Restreinte (MIT Non-Commercial & No-Derivatives License)**. Vous êtes libre de l'utiliser gratuitement tel quel, mais toute modification, sous-licence ou revente est strictement interdite. Consultez le fichier [LICENSE](LICENSE) pour plus de détails.

<a href="https://hiddenswap.com/pay/AgRPwfFe" target="_blank" rel="noopener"><img src="https://hiddenswap.com/pay/AgRPwfFe/button.svg" alt="Donate with any coin" width="247" height="44"></a>
