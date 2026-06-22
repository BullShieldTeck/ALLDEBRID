# 🚀 AllDebrid Manager by EkHo

[![Release](https://img.shields.io/badge/Release-v1.1.1-brightgreen.svg)](https://github.com/BullShieldTeck/Alldebrid_code/releases)
[![Platform](https://img.shields.io/badge/Platform-Android-blue.svg?logo=android)](https://developer.android.com)
[![Kotlin](https://img.shields.io/badge/Kotlin-Compose-purple.svg?logo=kotlin)](https://kotlinlang.org)

**AllDebrid Manager** est un client Android moderne, fluide et performant conçu pour gérer votre compte AllDebrid de manière intuitive. Que vous souhaitiez débrider des liens, gérer vos torrents ou streamer vos contenus directement sur votre téléviseur ou votre smartphone, l'application centralise tous vos besoins premium dans une interface utilisateur soignée.

---

## ✨ Fonctionnalités Clés

### ⚡ Débridage Instantané & Multi-Liens Parallèle
- **Débridez en 1 Clic** : Collez n'importe quel lien d'hébergeur compatible (Uptobox, 1fichier, Rapidgator, etc.) et obtenez instantanément le lien premium haut débit.
- **Saisie Multi-Liens** : Collez plusieurs liens à la fois (un par ligne) dans la zone de saisie optimisée (hauteur fixe avec défilement vertical).
- **Résolution Parallèle** : Vos liens sont traités simultanément en arrière-plan grâce aux coroutines Kotlin.
- **Actions Globales (Bulk)** : Lancez le téléchargement natif de tous les liens résolus, copiez-les tous en un clic, ou ouvrez-les tous dans un navigateur/téléchargeur externe.
- **Actions Individuelles** : Streamez, téléchargez (interne/externe), copiez, partagez ou ouvrez dans un lecteur externe (VLC, MX Player, etc.) chaque fichier résolu.

### 🧲 Gestionnaire Avancé de Torrents & Magnets
- **Ajout Multi-Source** : Ajoutez vos fichiers `.torrent` locaux ou collez simplement des liens Magnet.
- **Suivi en Temps Réel** : Visualisez l'état de conversion (téléchargement par AllDebrid, seeders, vitesse, progression).
- **Explorateur de Fichiers** : Parcourez l'arborescence des dossiers et fichiers de vos torrents terminés, puis débridez et streamez les fichiers individuels de votre choix.

### 🤖 Intelligence Artificielle (Gemini AI)
- **Résumés de Fichiers à la Demande** : Un bouton étincelles (`AutoAwesome`) vous permet de générer à la demande un résumé intelligent pour vos torrents, fichiers ou liens débridés.
- **Sélection du Modèle** : Choisissez entre **Gemini 2.5 Flash** (analyses riches) et **Gemini 2.5 Flash-Lite** (ultra-rapide et économe en quota).
- **Prompt Multilingue** : Les résumés s'adaptent automatiquement à la langue courante de l'application (Français ou Anglais).
- **Optimisation du Quota & Cache local** : Vos clés API personnelles sont stockées localement de manière sécurisée. Les résumés générés sont sauvegardés dans la base de données locale Room (`GeminiSummaryCache`) pour éviter les requêtes API réseau inutiles.

### 📺 Support Natif Google Cast (Chromecast)
- **Diffusion Grand Écran** : Diffusez vos vidéos en haute définition directement sur votre TV en utilisant l'icône Cast intégrée.
- **Conversion Dynamique (MIME-Type)** : Détection intelligente des formats vidéo (`.mp4`, `.mkv`, `.ts`, `.m3u8`) pour assurer une compatibilité et une lecture optimale sur les récepteurs Chromecast.
- **Contrôles Intégrés** : Gérez la lecture (Play, Pause, position de lecture) depuis le panneau de contrôle de votre smartphone.

### 🎨 Design Premium & Ergonomie
- **Thème Sombre & AMOLED** : Thème noir pur adapté aux écrans AMOLED afin d'économiser la batterie tout en profitant d'un superbe design moderne.
- **Verrouillage Portrait** : L'orientation de l'écran est verrouillée en mode portrait pour garantir une interface stable et sans désalignement.
- **Copie Rapide du Code PIN** : Lors de l'association, cliquez simplement sur le code PIN affiché pour le copier instantanément dans votre presse-papiers.
- **Paramètres Plein Écran** : Intégration fluide de la page des paramètres directement dans l'onglet Profil avec transitions animées (`Crossfade`), tout en conservant la barre de navigation.
- **Sélecteur de Langue** : Choisissez manuellement la langue de l'application (Système, Français, Anglais) avec persistance après redémarrage.
- **Personnalisation de l'Avatar** : Modifiez et chargez votre photo de profil à la volée.

### 💖 Soutien & Espace Donateur
- **Bannière d'Invitation** : Bannière non bloquante et fermable temporairement au démarrage pour soutenir le projet.
- **Espace Donateur Dédié** : Écran dédié pour enregistrer ses coordonnées et valider son statut de donateur par rapport à un registre distant sécurisé, permettant de masquer définitivement la bannière de don.
- **Bouton Buy Me a Coffee** : Accès direct pour soutenir le développeur.

---

## 🛠️ Comment ça Marche ?

1. **Association Ultra Simple** :
   - Au premier lancement, connectez-vous instantanément en générant un code PIN d'association à valider sur votre compte AllDebrid, ou saisissez votre clé API manuellement.
   - Si vous n'avez pas de compte, un lien de création rapide est intégré.
2. **Utilisation** :
   - **Débrider** : Collez un ou plusieurs liens dans l'onglet *Débrider*.
   - **Torrents** : Ajoutez et suivez vos fichiers magnétiques ou torrents dans l'onglet *Torrents*.
   - **Historique** : Retrouvez l'historique complet de tous vos liens débridés pour les re-télécharger ou les re-streamer à tout moment.

---

## 📸 Aperçus & Design

*Interface moderne et épurée respectant les lignes directrices de Material Design 3 :*

| Connexion & Association PIN | Gestionnaire de Torrents | Mode AMOLED Noir Pur |
|:---:|:---:|:---:|
| <img src="img/Setup_Screen.jpg" width="250" alt="Setup Screen"/> | <img src="img/torrents_Screen.jpg" width="250" alt="Torrents Screen"/> | <img src="img/AMOled%20Dark%20Mode.jpg" width="250" alt="AMOled Dark Mode"/> |

*(Images d'illustration à titre de démonstration de l'interface utilisateur)*

---

## 📥 Téléchargements

Rendez-vous dans la section **[Releases](https://github.com/BullShieldTeck/ALLDEBRID/releases)** pour télécharger la dernière version stable de l'application au format APK :

1. Téléchargez le fichier `AllDebrid_Manager_release.apk`.
2. Autorisez l'installation d'applications de sources inconnues dans les paramètres de votre appareil si nécessaire.
3. Installez l'APK et profitez de vos contenus !

---

## 🔒 Confidentialité & Sécurité
- L'application communique exclusivement et directement avec les API sécurisées d'**AllDebrid** (`api.alldebrid.com`).
- Vos identifiants, clés API AllDebrid et Gemini sont stockés localement sur votre appareil de façon chiffrée via les préférences système Android et ne sont **jamais** partagés avec des serveurs tiers.

---

## 💖 Soutenir le projet

Si vous appréciez cette application et souhaitez soutenir son développement, vous pouvez faire un don :

- [Soutenir sur Buy Me a Coffee](https://buymeacoffee.com/ekho974) ☕

---

## ⚖️ Clause de Non-Responsabilité (Disclaimer)
*Cette application est un projet indépendant et n'est pas affiliée à, ni approuvée par AllDebrid. Vous devez posséder un compte AllDebrid valide pour pouvoir utiliser les fonctionnalités de cette application.*

## 📄 Licence et Droits d'auteur
Tous droits réservés.
Il est interdit de modifier ou décompiler cet APK sans autorisation préalable.
