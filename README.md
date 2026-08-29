# Semi de Casteljaloux — préparation

Plan d'entraînement personnel de Benjamin Saint-Sever pour **les 21 km de Casteljaloux** (dimanche 22 novembre 2026, à confirmer). Objectif : sous 1h48, ambition 1h45.

Le plan est publié comme **PWA installable** (hors-ligne) via GitHub Pages. C'est le seul canal de diffusion.

## Canal unique : le PWA

- La page vivante du plan est **`index.html`**, servie par GitHub Pages et installable sur téléphone (`manifest.webmanifest` + `sw.js`).
- **`git push` sur `main` = publication.** GitHub Pages redéploie automatiquement, l'app se met à jour.
- Il n'y a **plus d'artifact claude.ai** : il faisait doublon et a été supprimé le 27/08/2026. Ne pas en recréer.

## Fichiers

| Fichier | Rôle |
|---|---|
| `index.html` | Plan vivant (page web / PWA). Source unique du plan affiché. |
| `Suivi_Semi_Toulouse.md` | Mémoire de passation : données brutes, méthode COROS, raisonnements, séances réalisées. À lire en début de session et à tenir à jour. |
| `renfo-moyen-fessier.html` | Fiche d'exécution du renforcement moyen fessier (schémas, erreurs). |
| `211_km_officiel_2025-*.gpx` | Trace GPX du parcours officiel. |
| `manifest.webmanifest`, `sw.js`, `icon-*.png` | Ressources PWA (installation, hors-ligne, icônes). |
| `Plan_Semi_Toulouse_Phase1_2.pdf` | **Obsolète** (visait Toulouse Expérience au 1er nov). Conservé pour la structure S1–S5 seulement. |
| `archive/` | Anciennes versions. |

## Suivi des données

Les données réelles viennent du connecteur **COROS** (montre Pace 4, lecture seule). Pilotage à la fréquence cardiaque avant l'allure. Après chaque séance analysée ou décision prise, mettre à jour `Suivi_Semi_Toulouse.md` **et** `index.html`, puis committer et pousser.
