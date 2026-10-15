# Validation de levé ArpentNord

Outil web pour valider un levé Leica (méthode string CS20, liste de codes ArpentNord), corriger les codes,
inverser des points, compléter des rectangles (point `CALCUL`) et exporter `_modif.txt` et `.dxf` (couches du gabarit NouvLR).

Tout se fait dans le navigateur : aucun fichier de levé n'est envoyé sur Internet.

## Publication sur GitHub Pages
1. Copier le contenu de ce dossier à la racine du dépôt (ou dans un sous-dossier, ex. `/leve/`).
2. Settings → Pages → Source : *Deploy from a branch*, branche `main`, dossier `/` (root).
3. L'adresse sera `https://<organisation>.github.io/<depot>/`.

## Installation sur iPhone
Ouvrir l'adresse dans **Safari** → bouton Partager → **Sur l'écran d'accueil**.
L'outil s'ouvre ensuite comme une application et fonctionne hors ligne au terrain.
« Ouvrir un levé… » → **Parcourir** donne accès à Fichiers, iCloud, OneDrive et à la clé USB.

## Mise à jour
Remplacer `index.html`, puis changer `VERSION` dans `sw.js` pour forcer le rafraîchissement du cache.

Version : 2026-10-15
