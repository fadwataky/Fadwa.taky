# Fadwa Taky — Carte de visite digitale

Site statique prêt pour GitHub Pages, sans installation.

## Publication

1. Décompressez le ZIP sur votre appareil.
2. Créez un nouveau dépôt GitHub public, par exemple `fadwa-taky`.
3. Dans le dépôt, choisissez **Add file → Upload files**.
4. Ajoutez le CONTENU du dossier décompressé : `index.html`, `style.css`, `fadwa-taky.vcf`, le dossier `assets` et les autres fichiers. Le fichier `index.html` doit se trouver directement à la racine du dépôt. Ne téléversez pas le ZIP lui-même.
5. Cliquez sur **Commit changes**.
6. Ouvrez **Settings → Pages**. Choisissez **Deploy from a branch**, puis **main** et **/(root)**. Cliquez sur **Save**.
7. Attendez la fin de la publication, puis ouvrez le lien indiqué par GitHub Pages.

## Coordonnées et boutons

- Nom : Fadwa Taky
- Profession : Orthophoniste
- Téléphone : 06 32 23 82 69
- WhatsApp : +212 632238269
- Message prérempli exact : `prendre un rendez vous`
- Adresse : https://share.google/TdU2WiWUaamI2AExw

Le bouton WhatsApp ouvre la discussion et prépare le message. Le visiteur appuie ensuite sur Envoyer.
Le bouton Ajouter aux contacts ouvre une vCard. Sur iPhone, ouvrez le site dans Safari si le navigateur intégré d'une application n'affiche pas la fiche. Sur Android, le fichier peut être téléchargé : ouvrez-le puis importez le contact. L'enregistrement final est confirmé par le visiteur.
Le bouton d'adresse ouvre le lien Google fourni. Aucune adresse postale non vérifiée n'a été ajoutée.

## Ajouter la vraie photo

La photo actuelle est une silhouette, en attendant la vraie photo.
1. Téléversez un portrait carré nommé `profile.jpg` dans le dossier `assets` du dépôt.
2. Dans `index.html`, remplacez `assets/profile.svg` par `assets/profile.jpg`.
3. Remplacez le texte alternatif `Emplacement de la photo de Fadwa Taky` par `Fadwa Taky, orthophoniste`.
4. Enregistrez avec **Commit changes**. GitHub Pages republiera automatiquement.

## Modifier la carte

Les textes et les liens se trouvent dans `index.html`, les couleurs dans `style.css`.
Pour modifier le contact enregistré, modifiez également `fadwa-taky.vcf`.
Gardez le dossier `assets` avec les fichiers du site : aucune image ne dépend d'un lien temporaire.
