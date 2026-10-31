# Reprise du genou — automne 2026

Plan de reprise de la course de Benjamin Saint-Sever après l'arrêt du genou gauche (20/10/2026). Le semi de Casteljaloux du 22/11/2026 a été **annulé le 31/10** : plus d'échéance, objectif récupérer et reprendre sans rechute. La prochaine cible est choisie vers le 15/11.

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
| `211_km_officiel_2025-*.gpx` | Trace GPX du parcours du semi annulé (conservée). |
| `manifest.webmanifest`, `sw.js`, `icon-*.png` | Ressources PWA (installation, hors-ligne, icônes). |
| `Plan_Semi_Toulouse_Phase1_2.pdf` | **Obsolète** (visait Toulouse Expérience au 1er nov). Conservé pour la structure S1–S5 seulement. |
| `archive/` | Anciennes versions, dont les sections du plan du semi retirées le 31/10. |

## Suivi des données

Les données réelles viennent du connecteur **COROS** (montre Pace 4, lecture seule). Pilotage à la fréquence cardiaque avant l'allure. Après chaque séance analysée ou décision prise, mettre à jour `Suivi_Semi_Toulouse.md` **et** `index.html`, puis committer et pousser.

`index.html` contient une section **Progression** (après "Aujourd'hui") avec des graphiques SVG faits main : allure/efficacité des footings, FC repos et ratio de charge, frise genou/hanche, allure au seuil. Pour les mettre à jour à chaque nouveau relevé — géométrie, critères d'inclusion, formules —, voir la section **« Mise à jour des graphiques de Progression (pour l'assistant) »** dans `Suivi_Semi_Toulouse.md`, juste après la section COROS.
