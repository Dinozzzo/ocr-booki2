# Booki – Intégration responsive

Projet 2 du parcours OpenClassrooms : intégration en HTML et CSS de la page d'accueil de Booki, une agence de location d'hébergements à Marseille, à partir de maquettes Figma.

## Aperçu

La page présente :

- une barre de recherche par ville et des filtres (Économique, Familial, Romantique, Nos pépites) ;
- les hébergements à Marseille et les plus populaires ;
- les activités à Marseille ;
- un pied de page avec des liens utiles.

## Responsive

L'intégration respecte les trois maquettes :

| Format   | Largeur         |
| -------- | --------------- |
| Desktop  | 1440px          |
| Tablette | 1024px et moins |
| Mobile   | moins de 768px  |

## Technologies

- HTML5 sémantique (`header`, `nav`, `main`, `section`, `article`, `search`, `hgroup`, `footer`)
- CSS3 avec Flexbox et media queries, sans framework
- Convention de nommage BEM
- Accessibilité : `aria-label`, `aria-hidden`, textes réservés aux lecteurs d'écran (`.sr-only`)
- Polices et icônes : Raleway (Google Fonts) et Font Awesome 6

## Structure

    ├── index.html
    ├── css/
    │   └── style.css
    └── images/
        ├── logo/
        ├── hebergements/
        └── activites/

## Lancer le projet

Clonez le dépôt, puis ouvrez `index.html` dans un navigateur. Aucune installation n'est nécessaire.
