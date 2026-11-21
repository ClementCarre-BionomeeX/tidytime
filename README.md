# ⏰ TidyTime

Le rituel de rangement quotidien de la famille : **5 minutes par pièce, tous les jours**.

Appli web installable (PWA), qui marche **hors ligne** une fois installée. Toutes les données restent sur le téléphone.

👉 **Ouvrir l'appli : https://clementcarre-bionomeex.github.io/tidytime/**

## Fonctionnement
- Liste ordonnée des pièces (nom, icône, couleur, photo en fond, durée), modifiable.
- « C'est parti ! » lance le minuteur sur la 1re pièce, avec la pièce en fond.
- À la fin : l'écran clignote, l'alarme sonne et le téléphone vibre. On touche pour arrêter, on retouche pour lancer la pièce suivante.
- « Fini ! » pour passer à la suite en avance, « Passer » pour sauter une pièce, « Pause », « Tout arrêter ».
- Stats par personne et pour la famille : série de jours, minutes, pièces, calendrier, courbes, classement de la semaine, niveaux, étoiles et badges.
- Synchro optionnelle entre téléphones via un dépôt GitHub privé (`tidytime-sauvegardes`) et une clé limitée à ce dépôt, configurée dans Réglages (même principe que livre-hero).
- Export / import d'une sauvegarde JSON.

## Installer sur le téléphone
- **Android (Chrome)** : ouvrir le lien, menu ⋮ → « Installer l'application » / « Ajouter à l'écran d'accueil ».
- **iPhone (Safari)** : ouvrir le lien, bouton Partager → « Sur l'écran d'accueil ».

Ensuite l'appli fonctionne sans connexion.

## Limites
- Le navigateur arrête les minuteurs quand le téléphone est verrouillé : l'appli garde l'écran allumé pendant le rangement. Si on verrouille quand même, l'alarme sonne au rallumage.
- Sur iPhone, le bouton silencieux coupe le son de l'alarme (le clignotement reste).

## Fichiers
`index.html` (toute l'appli), `sw.js` (cache hors ligne), `manifest.webmanifest`, icônes.
