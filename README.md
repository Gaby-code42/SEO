# Nina Carducci : audit et optimisation SEO

Audit, puis optimisation du site existant d'une photographe professionnelle, sur
trois axes : les performances, le référencement et l'accessibilité. C'est un
projet de la formation Développeur Web d'OpenClassrooms.

🔗 [Voir le site](https://gaby-code42.github.io/SEO/)

## Optimisations réalisées

### Performances
- Redimensionnement et compression des images de la galerie et du carrousel.
- Chargement des scripts en `defer`.
- `preconnect` vers Google Fonts.
- Suppression des styles inline au profit de la feuille de style.

### Référencement
- Une balise `title` et une meta description rédigées avec des mots-clés ciblés
  (photographe, événementiel, mariage, portrait…).
- Une hiérarchie des titres corrigée : un seul `h1` et des niveaux cohérents.
- Des balises Open Graph et Twitter Card pour le partage sur les réseaux
  sociaux.
- Des données structurées Schema.org (microdata) :
  - `LocalBusiness`, avec l'adresse et les horaires d'ouverture ;
  - `Service`, avec les prix (`price`, `priceCurrency`), pour obtenir des rich
    snippets.

### Accessibilité
- Les attributs `lang` et `alt` décrivent réellement chaque image.
- Les libellés `aria-label` sont ajoutés sur les contrôles du carrousel.
- Une opacité qui nuisait à la lisibilité du texte a été corrigée.

## Stack

HTML5 · CSS3 · Bootstrap 5 · jQuery (plugin de galerie filtrable)

## Lancer le projet

```bash
git clone https://github.com/Gaby-code42/SEO.git
cd SEO
# puis ouvrir index.html
```

## Auteur

Raphaël Bonacina, [portfolio](https://gaby-code42.github.io/portfolio/)
