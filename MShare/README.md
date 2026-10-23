# Fiche projet : MShare (à ajouter au portfolio mhd-almouchafaou.online)

## Instructions pour l'IA

Ajoute ce projet dans la table `projects` de la base Supabase du portfolio (ou remplis le formulaire de l'admin `admin.mhd-almouchafaou.online/projets`), en reprenant exactement les valeurs ci-dessous, champ par champ.

Règles de rédaction du portfolio à respecter si tu retouches un texte :
- ton naturel et direct ;
- n'ajoute aucune information extérieure (pas de chiffres, dates, clients ou résultats inventés) ;
- pas de tiret au milieu des phrases dans les textes (les tirets restent permis dans les titres et libellés).

Les champs `image` et `gallery` doivent contenir des captures d'écran réelles de l'application, envoyées dans le bucket Supabase `project-images` (via le bouton d'envoi d'image de l'admin).

---

## Champs généraux

| Champ | Valeur |
|---|---|
| slug | `mshare` |
| title | MShare |
| category | Application Mobile |
| year | 2026 |
| tags | React Native, Expo, TypeScript, Kotlin, Android |
| accent | `#FBE7A2` (couleur de fond de l'icône de l'app ; à foncer si le texte posé dessus manque de contraste) |
| role | Conception & développement mobile |
| client | Projet personnel |
| duration | (laisser vide, ou indiquer la durée réelle) |
| live_url | `https://github.com/MhdAlmouchafaou/MShare/releases/latest` |
| repo_url | `https://github.com/MhdAlmouchafaou/MShare` |
| image | capture d'écran principale (écran d'accueil de l'app) ; en attendant, icône : `https://raw.githubusercontent.com/MhdAlmouchafaou/MShare/main/assets/icon.png` |
| gallery | 3 à 5 captures : accueil, choix des fichiers, radar des appareils, transfert en cours, partage vers navigateur |
| published | true |
| position | à placer selon l'ordre voulu (0 = premier) |

---

## Textes en français

**description**
Application Android de partage de fichiers sans Internet et sans publicité. Les fichiers passent directement d'un téléphone à l'autre en Wi‑Fi Direct, à pleine vitesse.

**overview**
MShare permet d'envoyer photos, vidéos, musique, documents et applications d'un téléphone à un autre sans routeur ni forfait internet. L'envoi se fait en Wi‑Fi Direct, et l'autre appareil peut même recevoir les fichiers sans installer l'application, depuis son navigateur. L'application ne contient aucune publicité.

**challenge**
Transférer de gros fichiers rapidement et de façon fiable entre téléphones, sans aucune connexion Internet, tout en restant simple à utiliser et compatible avec les appareils qui n'ont pas l'application, comme un iPhone ou un PC.

**solution**
Une application React Native (Expo) en TypeScript, appuyée sur un moteur de transfert natif écrit en Kotlin. Le moteur ouvre plusieurs connexions en parallèle, utilise le Wi‑Fi Direct en 5 GHz quand c'est possible et écrit chaque morceau directement à la bonne position dans le fichier. La connexion se fait par radar des appareils proches, par QR code ou sur le même réseau Wi‑Fi. Un mode navigateur permet de partager avec un iPhone ou un PC sans application.

**result**
Une application Android complète, compilée automatiquement à chaque mise à jour, qui partage tous types de fichiers sans data et sans publicité, et dont l'interface suit le même design que les autres applications du développeur.

**features**
- Partage en Wi‑Fi Direct, sans Internet ni data
- Photos, vidéos, musique, documents et applications (installation directe des APK)
- Radar des appareils proches, connexion par QR code ou même réseau Wi‑Fi
- Partage vers iPhone et PC depuis le navigateur, sans application
- Transferts en pause et reprise à la reconnexion
- Historique des envois et réceptions, explorateur de fichiers intégré
- Verrouillage de l'app par empreinte, visage ou code du téléphone
- Thème clair ou sombre, interface en français et en anglais

---

## Textes en anglais (champs `_en`)

**title_en**
MShare

**category_en**
Mobile App

**description_en**
An Android app for sharing files with no Internet and no ads. Files go straight from one phone to another over Wi‑Fi Direct, at full speed.

**overview_en**
MShare lets you send photos, videos, music, documents and apps from one phone to another with no router and no data plan. Transfers run over Wi‑Fi Direct, and the other device can even receive files without installing the app, right from its browser. The app has no ads.

**challenge_en**
Move large files quickly and reliably between phones with no Internet connection at all, while staying simple to use and compatible with devices that don't have the app, such as an iPhone or a PC.

**solution_en**
A React Native (Expo) app written in TypeScript, built on a native transfer engine written in Kotlin. The engine opens several connections in parallel, uses 5 GHz Wi‑Fi Direct when available and writes each chunk directly at the right position in the file. Devices connect through a nearby device radar, a QR code or the same Wi‑Fi network. A browser mode shares files with an iPhone or a PC with no app needed.

**result_en**
A complete Android app, built automatically with every update, that shares any kind of file with no data and no ads, with an interface that follows the same design as the developer's other apps.

**features_en**
- Wi‑Fi Direct sharing, no Internet or data needed
- Photos, videos, music, documents and apps (direct APK install)
- Nearby device radar, QR code connection or same Wi‑Fi network
- Share to iPhone and PC from the browser, no app needed
- Pause transfers and resume on reconnection
- Send and receive history, built-in file browser
- App lock with fingerprint, face or phone passcode
- Light or dark theme, interface in French and English
