# EXERCICES HTML, CSS & JS - Débutant

## ✨ EXERCICE 1 : HTML de base  

Voici comment se compose une page `html` :

```html
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Nom de la page</title>
</head>
<body>
</body>
</html>
```
### Explications

`<!DOCTYPE html>`\
→ Indique au navigateur que le document est écrit en HTML5, la version actuelle du HTML.

`<html lang="fr">`\
→ Cette balise englobe tout le contenu de la page web.\
→ L’attribut lang="fr" précise que la langue principale de la page est le français.

`<head>`\
→ Cette section contient les métadonnées du document (des informations utiles mais non visibles directement sur la page).

`<meta charset="UTF-8">`\
→ Ce méta-tag définit l'encodage des caractères en UTF-8, permettant d'afficher correctement les accents et caractères spéciaux.

`<title>Nom de la page</title>`\
→ Définit le titre affiché dans l’onglet du navigateur.

`<body>`\
→ Cette section contient le contenu visible de la page (textes, images, liens, etc.).

## Instructions :

Crée un fichier `index.html`.

Copier/coller dans le fichier `index.html` le code qui compose une page `html`.

Ajoute les éléments suivants dans la balise `<body>` :

* Un titre principal

* Un sous-titre

* Un paragraphe

* Un lien vers une autre page

* Une image avec une source vers une image en ligne ou locale

## ✨ EXERCICE 2 : CSS de base 

Le CSS (Cascading Style Sheets) permet de styliser une page HTML en définissant l'apparence des éléments.

Créer un fichier nommé `style.css` dans le même dossier que le fichier `index.html`.

Dans le fichier `index.html`, ajouter la ligne suivante dans la section `<head>` pour lier le fichier CSS :

`<link rel="stylesheet" href="style.css">`

### Explications

`<link>`\
-> Est la balise utilisée pour inclure une feuille de style externe.

`rel="stylesheet"`\
-> Indique qu'il s'agit d'un fichier CSS.

`href="style.css"`\
-> Précise l'emplacement du fichier CSS.

Ouvrir le fichier style.css et ajouter le code suivant :

```css
body {
    background-color:rgb(255, 213, 164);
    font-family: Arial, sans-serif;
}

h1 {
    color: #333;
    text-align: center;
}

p {
    font-size: 16px;
    line-height: 1.6;
}
```
**Tu peux maintenant personnaliser les styles de ton site ! 🚀**