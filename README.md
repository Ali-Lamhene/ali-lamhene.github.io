# ali-lamhene.github.io

Pages statiques de l'app [GPS](https://github.com/Ali-Lamhene/GPS), servies par GitHub Pages.

- `gps/lieu/` : page ouverte par un lien de partage de lieu quand l'app n'est pas installée. Sans texte, sans script, sans appel externe. Le lieu reste après `#` et n'est jamais envoyé au serveur.
- `.well-known/assetlinks.json` : relie le domaine à l'app Android (App Links), pour que les liens ouvrent l'app directement.
- `.nojekyll` : sert les fichiers tels quels, dossier `.well-known` compris.
- `robots.txt` : aucune indexation.
