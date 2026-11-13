# Karting Analysis — version installable (PWA)

Cette version reprend l'application HTML et ajoute les éléments nécessaires à une installation sur téléphone : manifeste PWA, icônes, bouton d'installation et cache hors-ligne.

## Publication sur GitHub Pages

1. Créer un compte GitHub si nécessaire, puis un dépôt public nommé par exemple `alfano-karting-coach`.
2. Décompresser cette archive et envoyer **le contenu** du dossier à la racine du dépôt (en particulier `index.html`, `manifest.webmanifest`, `service-worker.js` et le dossier `icons`).
3. Dans GitHub : **Settings → Pages → Build and deployment**.
4. Choisir **Deploy from a branch**, branche `main`, dossier `/ (root)`, puis **Save**.
5. Attendre la publication. GitHub affichera une adresse du type `https://VOTRE-PSEUDO.github.io/alfano-karting-coach/`.

GitHub Pages fournit le HTTPS nécessaire à l'installation PWA. Il n'est pas possible d'installer proprement l'application depuis un simple fichier HTML local : elle doit être servie en HTTPS (ou localhost).

## Installation sur Android

Ouvrir l'adresse publiée dans Chrome, puis utiliser le bouton **Installer l'application** s'il apparaît, ou le menu ⋮ → **Installer l'application** / **Ajouter à l'écran d'accueil**.

## Installation sur iPhone

Ouvrir l'adresse dans Safari → bouton Partager → **Sur l'écran d'accueil**.

## À savoir

- La mise en cache permet de relancer l'application hors connexion après une première visite en ligne.
- Les données de sessions sont conservées selon le mécanisme de stockage déjà utilisé par l'application et restent propres au navigateur/appareil : prévoir des sauvegardes/exportations.
- Cette archive ne publie pas elle-même le site sur ton compte GitHub : il faut effectuer les étapes ci-dessus ou me donner accès à un flux de publication adapté.
