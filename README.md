# Portfolio de Jérémy Lasson

Site personnel de **Jérémy Lasson**, développeur web et web mobile en formation. Il présente mon parcours, mes compétences et mes projets, et indique ma disponibilité pour un stage du **22 mars au 21 mai 2027**.

**Voir le site : [www.lasson-jeremy.fr](https://www.lasson-jeremy.fr)**

## Contenu du site

Le site est une page unique, avec un menu qui mène à chaque section :

- **Accueil** : présentation, disponibilité de stage et accès au CV
- **Projets** : les projets réalisés pendant ma formation, avec les technologies utilisées
- **Compétences** : ce que j'utilise déjà et ce que j'apprends en ce moment
- **Parcours** : formation, expérience professionnelle et diplômes
- **Contact** : adresse e-mail et liens vers mes profils

## Technologies

- HTML5
- [Tailwind CSS](https://tailwindcss.com/) v4, pour le style
- Polices [Google Fonts](https://fonts.google.com/) : Merriweather (titres), Roboto et Source Sans 3 (texte)

Le site est statique : il n'y a ni serveur, ni base de données, ni framework JavaScript.

## Choix de conception

- **Responsive** : la mise en page s'adapte du mobile au grand écran grâce aux classes responsives de Tailwind.
- **Identité visuelle** : palette de tons pierre (`stone`) et d'accents orange, avec un dégradé sombre en en-tête.
- **Navigation** : défilement fluide entre les sections.
- **Composants réutilisables** : boutons et badges de technologies définis une seule fois (`btn-orange`, `btn-white`, `btn-b-blue`, `btn-neutral`...).

## Structure du projet

```
.
├── index.html
├── README.md
└── src
    ├── assets
    │   └── images        logo, captures des projets, icônes des technologies
    └── css
        ├── input.css     sources Tailwind (styles personnalisés)
        └── output.css    CSS généré par Tailwind
```
## Qualité

Audit Lighthouse du 26 novembre 2026 :

| Performance | Accessibilité | Bonnes pratiques | SEO |
|:-----------:|:-------------:|:----------------:|:---:|
| 99 | 100 | 100 | 100 |

Suite à cet audit, les contrastes de couleurs et la taille des zones cliquables ont été corrigés.
## Auteur

**Jérémy Lasson**, développeur web et web mobile

- Site : [www.lasson-jeremy.fr](https://www.lasson-jeremy.fr)
- E-mail : [contact@lasson-jeremy.fr](mailto:contact@lasson-jeremy.fr)

Formation en cours : titre professionnel Développeur Web et Web Mobile (niveau 5) chez M2i Formation, d'octobre 2026 à juin 2027.

---

© 2026 Jérémy Lasson. Tous droits réservés.
