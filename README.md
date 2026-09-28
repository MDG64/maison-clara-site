# Maison Clara — site vitrine

Site statique d'une page (`index.html` + `img/`), sans build ni dépendance :
tout est dans le HTML, la police Cormorant Garamond vient de Google Fonts.

- Français par défaut, anglais par le bouton en haut à droite (mémorisé dans le navigateur).
- Le bandeau d'ouverture montre une seule photo, le salon (`img/hero-interieur.jpg`).
- Textes repris du flyer et de la présentation « L'art de l'intendance ».
- Photos : Unsplash (licence Unsplash, crédits en pied de page), portrait et
  monogramme fournis par Maison Clara, salon issu du flyer.

## Modifier

Éditer `index.html` directement. Chaque texte existe en deux versions,
`<span class="fr">` et `<span class="en">`, à garder côte à côte.

Pour voir le site en local :

    python -m http.server 8790

puis ouvrir http://127.0.0.1:8790/.
