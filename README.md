# 41st Légion d'Elite — site

## Navigation
- Accueil
- Présentation
- Histoire
- Unités
- Grades
- Membres
- Règlement
- Recrutement

## Membres
La page `membres.html` contient une fiche simple par personnage.
Pour ajouter un membre, duplique un bloc `<article class="character">` et change :
- l'image
- le matricule
- le nom
- le grade
- l'unité
- la spécialité
- le statut

Les images sont dans `assets/personnages/`.

## Grades
`grades.html` contient un organigramme en colonnes inspiré de l'image fournie. Les noms de grades se changent directement dans les blocs `.rank`.

## Règlement
`reglement.html` utilise des catégories horizontales. Chaque catégorie est un `<article class="rule">`.
Les règles 1.1 à 8.3 présentes dans les captures fournies ont été intégrées dans cette version.

## Accueil
La vidéo `assets/space-bg.mp4` est utilisée comme fond de l'accueil.

## CSS
Tout le design est regroupé dans `assets/style.css` et volontairement écrit de façon simple pour faciliter les modifications.
