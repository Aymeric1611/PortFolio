Guide simple pour améliorer ton portfolio

But : expliquer simplement comment le site est structuré et comment modifier les éléments de base.

1) Où sont les fichiers importants :
- `portFolio.HTML` : page d'accueil
- `Projets.HTML`, `Passions.HTML`, `Certifications.HTML`, `Stage_et_experiences_professionnelles.HTML`, `Veille technologique.HTML` : autres pages
- `CV.HTML` : page CV (ne pas modifier si demandé)
- `style.css` : feuille de style commune (modifie les couleurs et la mise en page ici)

2) Comment modifier le titre du site :
- Ouvre `portFolio.HTML` et cherche `<h1 class="site-title">`. Change le texte ou le lien qui est entre les balises `<a>`.

3) Changer les couleurs :
- Ouvre `style.css` et recherche `.site-header` (ligne avec `background: #0b5cff;`). Remplace la valeur hex (ex: `#0b5cff`) par une autre couleur (ex: `#2a9d8f`).
- Tu peux aussi modifier `.site-footer` pour changer le fond du pied de page.

4) Ajouter une nouvelle page :
- Crée un nouveau fichier HTML (par ex. `NouvellePage.HTML`). Copie le contenu d'une page existante et modifie le `<title>` et le contenu dans `<main>`.
- Ajoute un lien vers ta nouvelle page dans la navigation (`<nav class="site-nav">`) dans toutes les pages pour que la navigation soit cohérente.

5) Conseils pour les images :
- Place les images dans le dossier `image/`.
- Utilise une balise `<img src="image/monimage.jpg" alt="description">` et évite d'utiliser width/height fixes dans les balises; le CSS `max-width:100%` rend les images responsive.

6) Besoin d'aide ?
- Dis-moi ce que tu veux changer (couleurs, polices, structure) et je t'explique pas à pas avec du code simple.

Bonne pratique : fais toujours une copie du fichier avant de le modifier pour pouvoir revenir en arrière si besoin.