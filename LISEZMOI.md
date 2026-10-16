# Système 2

Appli web de budget, à installer sur l'écran d'accueil de l'iPhone.

## Mettre en ligne
Site statique : il suffit de publier ce dossier tel quel (Vercel, Netlify ou GitHub Pages).
Il doit être servi en HTTPS pour que l'icône et le mode hors connexion fonctionnent.

## Installer sur l'iPhone
1. Ouvrir le lien dans Safari.
2. Bouton Partager, puis « Sur l'écran d'accueil ».

## Données
Tout est enregistré sur le téléphone (localStorage). Supprimer l'icône efface les données :
penser à l'export CSV dans Réglages.

## Mettre à jour
Après une modification, changer `systeme2-v1` en `systeme2-v2` dans `sw.js` avant de republier.
