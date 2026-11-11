# KitVital : actualités officielles

Fichier public lu par la page https://kitvital.fr/actualites. Écrit deux fois par jour (vers 6 h et 14 h, heure de Paris) par la veille automatique de KitVital.

- `actualites.json` : les dernières publications officielles (France, Union européenne, pays voisins) sur la préparation aux crises, le risque de conflit, les pénuries, la météo et la santé. Chaque entrée est datée et renvoie à sa page officielle.
- `a-traiter.md` : ce que la veille propose de changer dans les guides du site.

Méthode et règles : `docs/actualites.md` du dépôt du site. Les textes sont des résumés neutres ; seule la page officielle liée fait foi.

## Baromètre KitVital : risque de guerre et de catastrophe

- `barometre.json` : le relevé quotidien du baromètre lu par la page https://kitvital.fr/barometre-des-risques et par l'accueil. Écrit chaque matin (vers 6 h, heure de Paris) par le script `npm run barometre:releve` du dépôt du site : valeurs de l'année en cours, actualité et analyse de chaque domaine, historique des scores, dernière alerte. Les scores sont toujours recalculés par le site avec sa méthode fixe.

Méthode : `docs/barometre.md` du dépôt du site.
