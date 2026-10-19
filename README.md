# Ma_Jestikk — Setup interactif

Site statique pour GitHub Pages : une **seule image du setup** avec 12 zones invisibles et cliquables. Un clic sur la tour PC ouvre `config-pc.html`, où chaque composant possède son lien affilié.

## Mise en ligne sur GitHub Pages

1. Créer le dépôt **public** `setup-ma-jestik` sous le compte `maroo1103` et ajouter un README.
2. Placer les fichiers de ce dossier à la racine du dépôt, en conservant le fichier `assets/setup-ma-jestikk.png`.
3. Dans **Settings → Pages → Build and deployment**, choisir **Deploy from a branch**, branche **main**, dossier **/(root)**, puis **Save**.
4. L'adresse du site sera `https://maroo1103.github.io/setup-ma-jestik/` après la publication.
5. Dans le panneau Twitch "MON SETUP / CONFIG", ajouter cette adresse comme lien de l'image du panneau.

## Important

- L'image est la version finale validée, non modifiée.
- Les zones restent transparentes jusqu'au survol ou à la navigation clavier. Elles sont écrites dans `index.html` sous la classe `hotspot`.
- Les liens affiliés fournis sont repris à l'identique. **Le clavier et la souris ont actuellement le même lien Amazon**, comme fourni ; à confirmer/corriger.
- Les 2 ventilateurs inférieurs Arctic P14 Pro Reverse ARGB sont listés sans lien, car le lien n'a pas été fourni.
- Toute la page et les fichiers déposés dans ce dépôt public seront consultables publiquement ; ne jamais y placer de secrets.

Le site n'a pas besoin de serveur, d'API, de script d'installation, ni de dépendance externe.