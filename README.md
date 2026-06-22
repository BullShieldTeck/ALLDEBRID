<div align="center">

# 🚀 AllDebrid Manager by EkHo

[![Release](https://img.shields.io/badge/Release-v1.1.3-brightgreen.svg)](https://github.com/BullShieldTeck/Alldebrid_code/releases)
[![Platform](https://img.shields.io/badge/Platform-Android-blue.svg?logo=android)](https://developer.android.com)
[![Kotlin](https://img.shields.io/badge/Kotlin-Compose-purple.svg?logo=kotlin)](https://kotlinlang.org)

---

<a id="lang"></a>

### 🌐 Langue / Language

[![Français](https://img.shields.io/badge/Lire_en-Français-blue?style=for-the-badge)](#fr)
&nbsp;&nbsp;
[![English](https://img.shields.io/badge/Read_in-English-red?style=for-the-badge)](#en)

</div>

---

<!-- ============================================================ -->
<!-- ===================== SECTION FRANÇAISE ===================== -->
<!-- ============================================================ -->

<a id="fr"></a>

## 📘 AllDebrid Manager - Français

**AllDebrid Manager** est un client Android moderne, fluide et performant conçu pour gérer votre compte AllDebrid de manière intuitive. Que vous souhaitiez débrider des liens, gérer vos torrents ou streamer vos contenus directement sur votre téléviseur ou votre smartphone, l'application centralise tous vos besoins premium dans une interface utilisateur soignée.

---

### ✨ Fonctionnalités Clés

#### ⚡ Débridage Instantané & Multi-Liens Parallèle
- **Débridez en 1 Clic** : Collez n'importe quel lien d'hébergeur compatible (Uptobox, 1fichier, Rapidgator, etc.) et obtenez instantanément le lien premium haut débit.
- **Saisie Multi-Liens** : Collez plusieurs liens à la fois (un par ligne) dans la zone de saisie optimisée (hauteur fixe avec défilement vertical).
- **Résolution Parallèle** : Vos liens sont traités simultanément en arrière-plan grâce aux coroutines Kotlin.
- **Actions Globales (Bulk)** : Lancez le téléchargement natif de tous les liens résolus, copiez-les tous en un clic, ou ouvrez-les tous dans un navigateur/téléchargeur externe.
- **Actions Individuelles** : Streamez directement via vos lecteurs externes préférés (VLC, MX Player, Nova Player, Kodi, etc.), téléchargez, copiez ou partagez chaque fichier résolu.

#### 🧲 Gestionnaire Avancé de Torrents & Magnets
- **Ajout Multi-Source** : Ajoutez vos fichiers `.torrent` locaux ou collez simplement des liens Magnet.
- **Suivi en Temps Réel** : Visualisez l'état de conversion (téléchargement par AllDebrid, seeders, vitesse, progression).
- **Explorateur de Fichiers** : Parcourez l'arborescence des dossiers et fichiers de vos torrents terminés, puis débridez et streamez les fichiers individuels de votre choix.

#### 🤖 Intelligence Artificielle (Gemini AI)
- **Résumés & Synopsis Enrichis** : Un bouton étincelles (`AutoAwesome`) vous permet de générer à la demande un résumé intelligent et un synopsis complet pour vos torrents, fichiers ou liens débridés.
- **Sélection du Modèle** : Choisissez parmi **Gemini 3.5 Flash** (le modèle par défaut de dernière génération, rapide et intelligent), **Gemini 2.5 Flash** (analyses riches) et **Gemini 2.5 Flash-Lite** (ultra-rapide et économe en quota).
- **Prompt Multilingue** : Les résumés et synopsis s'adaptent automatiquement à la langue courante de l'application (Français ou Anglais).
- **Optimisation du Quota & Cache local** : Vos clés API personnelles sont stockées localement de manière sécurisée. Les résumés générés sont sauvegardés dans la base de données locale Room (`GeminiSummaryCache`) pour éviter les requêtes API réseau inutiles.

#### 📺 Dialogue Cast Dédié (Chromecast)
- **Bouton Cast Universel** : Diffusez facilement vos vidéos depuis n'importe quel onglet grâce au bouton Cast (`Icons.Filled.Cast`) disponible sur les liens débridés (*Débrider*), les fichiers de torrents (*Torrents*) et l'historique de téléchargements.
- **Interface de Contrôle Dédiée** : Un dialogue interactif de Cast (`CastDialog`) vous permet de vous connecter rapidement à votre Smart TV / Android TV, de démarrer la diffusion, de mettre en pause ou d'arrêter la lecture directement depuis votre smartphone.
- **Conversion Dynamique (MIME-Type)** : Détection intelligente des formats vidéo (`.mp4`, `.mkv`, `.ts`, `.m3u8`) pour assurer une compatibilité et une lecture optimale sur les récepteurs Chromecast.

#### 🎨 Design Premium & Ergonomie
- **Thème Sombre & AMOLED** : Thème noir pur adapté aux écrans AMOLED afin d'économiser la batterie tout en profitant d'un superbe design moderne.
- **Verrouillage Portrait** : L'orientation de l'écran est verrouillée en mode portrait pour garantir une interface stable et sans désalignement.
- **Copie Rapide du Code PIN** : Lors de l'association, cliquez simplement sur le code PIN affiché pour le copier instantanément dans votre presse-papiers.
- **Paramètres Plein Écran** : Intégration fluide de la page des paramètres directement dans l'onglet Profil avec transitions animées (`Crossfade`), tout en conservant la barre de navigation.
- **Sélecteur de Langue** : Choisissez manuellement la langue de l'application (Système, Français, Anglais) avec persistance après redémarrage.
- **Personnalisation de l'Avatar** : Modifiez et chargez votre photo de profil à la volée.

#### 💖 Soutien & Espace Donateur
- **Bannière d'Invitation** : Bannière non bloquante et fermable temporairement au démarrage pour soutenir le projet.
- **Espace Donateur Dédié** : Écran dédié pour enregistrer ses coordonnées et valider son statut de donateur par rapport à un registre distant sécurisé, permettant de masquer définitivement la bannière de don.
- **Bouton Buy Me a Coffee** : Accès direct pour soutenir le développeur.

---

### 🛠️ Comment ça Marche ?

1. **Association Ultra Simple** :
   - Au premier lancement, connectez-vous instantanément en générant un code PIN d'association à valider sur votre compte AllDebrid, ou saisissez votre clé API manuellement.
   - Si vous n'avez pas de compte, un lien de création rapide est intégré.
2. **Utilisation** :
   - **Débrider** : Collez un ou plusieurs liens dans l'onglet *Débrider*.
   - **Torrents** : Ajoutez et suivez vos fichiers magnétiques ou torrents dans l'onglet *Torrents*.
   - **Historique** : Retrouvez l'historique complet de tous vos liens débridés pour les re-télécharger ou les re-streamer à tout moment.

---

### 📸 Aperçus & Design

*Interface moderne et épurée respectant les lignes directrices de Material Design 3 :*

| Connexion & Association PIN | Gestionnaire de Torrents | Mode AMOLED Noir Pur |
|:---:|:---:|:---:|
| <img src="img/Setup_Screen.jpg" width="250" alt="Setup Screen"/> | <img src="img/torrents_Screen.jpg" width="250" alt="Torrents Screen"/> | <img src="img/AMOled%20Dark%20Mode.jpg" width="250" alt="AMOled Dark Mode"/> |

*(Images d'illustration à titre de démonstration de l'interface utilisateur)*

---

### 📥 Téléchargements

Rendez-vous dans la section **[Releases](https://github.com/BullShieldTeck/ALLDEBRID/releases)** pour télécharger la dernière version stable de l'application au format APK :

1. Téléchargez le fichier `AllDebrid_Manager_release.apk`.
2. Autorisez l'installation d'applications de sources inconnues dans les paramètres de votre appareil si nécessaire.
3. Installez l'APK et profitez de vos contenus !

---

### 🔒 Confidentialité & Sécurité
- L'application communique exclusivement et directement avec les API sécurisées d'**AllDebrid** (`api.alldebrid.com`).
- Vos identifiants, clés API AllDebrid et Gemini sont stockés localement sur votre appareil de façon chiffrée via les préférences système Android et ne sont **jamais** partagés avec des serveurs tiers.

---

### 💖 Soutenir le projet

Si vous appréciez cette application et souhaitez soutenir son développement, vous pouvez faire un don :

- [Soutenir sur Buy Me a Coffee](https://buymeacoffee.com/ekho974) ☕

---

### ⚖️ Clause de Non-Responsabilité (Disclaimer)
*Cette application est un projet indépendant et n'est pas affiliée à, ni approuvée par AllDebrid. Vous devez posséder un compte AllDebrid valide pour pouvoir utiliser les fonctionnalités de cette application.*

### 📄 Licence et Droits d'auteur
Tous droits réservés.
Il est interdit de modifier ou décompiler cet APK sans autorisation préalable.

<p align="center"><a href="#lang">🔝 Retour au sélecteur de langue / Back to language selector</a></p>

---

<!-- ============================================================ -->
<!-- ===================== ENGLISH SECTION ======================= -->
<!-- ============================================================ -->

<a id="en"></a>

## 📕 AllDebrid Manager - English

**AllDebrid Manager** is a modern, smooth, and high-performance Android client designed to manage your AllDebrid account intuitively. Whether you want to unrestrict links, manage your torrents, or stream your content directly to your TV or smartphone, the app centralizes all your premium needs in a polished user interface.

---

### ✨ Key Features

#### ⚡ Instant Unrestricting & Parallel Multi-Links
- **1-Click Unrestrict** : Paste any compatible file host link (Uptobox, 1fichier, Rapidgator, etc.) and instantly get the premium high-speed download link.
- **Multi-Link Input** : Paste multiple links at once (one per line) in the optimized input area (fixed height with vertical scrolling).
- **Parallel Resolution** : Your links are processed simultaneously in the background using Kotlin coroutines.
- **Bulk Actions** : Launch the native download for all resolved links, copy them all in one click, or open them all in an external browser/downloader.
- **Individual Actions** : Stream directly via your favorite external players (VLC, MX Player, Nova Player, Kodi, etc.), download, copy, or share each resolved file.

#### 🧲 Advanced Torrent & Magnet Manager
- **Multi-Source Input** : Add your local `.torrent` files or simply paste Magnet links.
- **Real-Time Tracking** : Monitor the conversion status (AllDebrid download, seeders, speed, progress).
- **File Explorer** : Browse the folder and file tree of your completed torrents, then unrestrict and stream individual files of your choice.

#### 🤖 Artificial Intelligence (Gemini AI)
- **Enriched Summaries & Synopses** : A sparkle button (`AutoAwesome`) lets you generate on demand an intelligent summary and a complete synopsis for your torrents, files, or unrestricted links.
- **Model Selection** : Choose from **Gemini 3.5 Flash** (the latest-generation default model, fast and smart), **Gemini 2.5 Flash** (rich analysis), and **Gemini 2.5 Flash-Lite** (ultra-fast and quota-friendly).
- **Multilingual Prompts** : Summaries and synopses automatically adapt to the current application language (French or English).
- **Quota Optimization & Local Cache** : Your personal API keys are stored locally and securely. Generated summaries are saved in the local Room database (`GeminiSummaryCache`) to avoid unnecessary network API calls.

#### 📺 Dedicated Cast Dialog (Chromecast)
- **Universal Cast Button** : Easily cast your videos from any tab using the Cast button (`Icons.Filled.Cast`) available on unrestricted links (*Unrestrict*), torrent files (*Torrents*), and download history.
- **Dedicated Control Interface** : An interactive Cast dialog (`CastDialog`) allows you to quickly connect to your Smart TV / Android TV, start playback, pause, or stop playback directly from your smartphone.
- **Dynamic Conversion (MIME-Type)** : Smart detection of video formats (`.mp4`, `.mkv`, `.ts`, `.m3u8`) to ensure optimal compatibility and playback on Chromecast receivers.

#### 🎨 Premium Design & Ergonomics
- **Dark & AMOLED Theme** : Pure black theme optimized for AMOLED screens to save battery while enjoying a stunning modern design.
- **Portrait Lock** : Screen orientation is locked in portrait mode to ensure a stable, properly aligned interface.
- **Quick PIN Copy** : During pairing, simply tap the displayed PIN code to instantly copy it to your clipboard.
- **Full-Screen Settings** : Seamless integration of the settings page directly into the Profile tab with animated transitions (`Crossfade`), while keeping the navigation bar visible.
- **Language Selector** : Manually choose the application language (System, French, English) with persistence after restart.
- **Avatar Customization** : Edit and load your profile picture on the fly.

#### 💖 Support & Donor Space
- **Invitation Banner** : Non-blocking, temporarily dismissible banner at startup to support the project.
- **Dedicated Donor Space** : Dedicated screen to register your details and validate your donor status against a secure remote registry, allowing you to permanently hide the donation banner.
- **Buy Me a Coffee Button** : Direct access to support the developer.

---

### 🛠️ How Does It Work?

1. **Ultra Simple Pairing** :
   - On first launch, connect instantly by generating a pairing PIN code to validate on your AllDebrid account, or enter your API key manually.
   - If you don't have an account, a quick account creation link is built in.
2. **Usage** :
   - **Unrestrict** : Paste one or more links in the *Unrestrict* tab.
   - **Torrents** : Add and track your magnet or torrent files in the *Torrents* tab.
   - **History** : Access the complete history of all your unrestricted links to re-download or re-stream them at any time.

---

### 📸 Screenshots & Design

*Modern, clean interface following Material Design 3 guidelines:*

| Login & PIN Pairing | Torrent Manager | Pure Black AMOLED Mode |
|:---:|:---:|:---:|
| <img src="img/Setup_Screen.jpg" width="250" alt="Setup Screen"/> | <img src="img/torrents_Screen.jpg" width="250" alt="Torrents Screen"/> | <img src="img/AMOled%20Dark%20Mode.jpg" width="250" alt="AMOled Dark Mode"/> |

*(Illustrative images for UI demonstration purposes)*

---

### 📥 Downloads

Head over to the **[Releases](https://github.com/BullShieldTeck/ALLDEBRID/releases)** section to download the latest stable version of the application as an APK:

1. Download the `AllDebrid_Manager_release.apk` file.
2. Allow installation from unknown sources in your device settings if needed.
3. Install the APK and enjoy your content!

---

### 🔒 Privacy & Security
- The application communicates exclusively and directly with **AllDebrid**'s secure APIs (`api.alldebrid.com`).
- Your credentials, AllDebrid & Gemini API keys are stored locally on your device in encrypted form via Android system preferences and are **never** shared with third-party servers.

---

### 💖 Support the Project

If you enjoy this application and want to support its development, you can make a donation:

- [Support on Buy Me a Coffee](https://buymeacoffee.com/ekho974) ☕

---

### ⚖️ Disclaimer
*This application is an independent project and is not affiliated with or endorsed by AllDebrid. You must have a valid AllDebrid account to use the features of this application.*

### 📄 License & Copyright
All rights reserved.
Modification or decompilation of this APK without prior authorization is prohibited.

<p align="center"><a href="#lang">🔝 Retour au sélecteur de langue / Back to language selector</a></p>
