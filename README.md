# Site des 7èmes journées annuelles SO-MATé

Site Quarto pour les journées annuelles du réseau SO-MATé, thème
« le coût caché du libre et de l'open science ».
 **URL site** : [https://lecampiong.github.io/site_JA_somate2026/](https://lecampiong.github.io/site_JA_somate2026/)

## Contenu du dépôt

```
_quarto.yml              configuration du site et de la barre de navigation
styles.scss              palette et mise en forme (dérivées de l'affiche SO-MATé)
index.qmd                accueil
programme.qmd            programme
infos-pratiques.qmd      informations pratiques
inscription.qmd          inscription
images/logo-somate.png   affiche du réseau
.github/workflows/       publication automatique sur GitHub Pages
```

## Visualiser er en local

Installez [Quarto](https://quarto.org/docs/get-started/) puis, à la racine du
dépôt téléchargé:

```bash
quarto preview     # aperçu avec rechargement automatique
quarto render      # génération dans _site/
```

Le dossier `_site/` est ignoré par git : il est reconstruit à chaque publication.


