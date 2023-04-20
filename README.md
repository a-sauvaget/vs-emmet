# Snippets Emmet pour Visual Studio Code

Collection de snippets pour Emmet. La plupart surchargent [les snippets par défaut](https://github.com/emmetio/snippets/blob/master/html.json) proposé, notamment pour ajouter automatiquement les éléments nécessaires pour l'accessibilité (role, aria-label...).

## Accessibilité
- header: ajout du rôle *banner*
- main: ajout de l'id *main*, du rôle *main* et de *tabindex=-1*
- footer: ajout du rôle *contentinfo*
- nav: ajout du rôle *navigation*
- form: ajout du rôle *form*
- form:get: ajout du rôle *form*
- form:post: ajout du rôle *form*
- a:skip: permet de créer un lien d'accès rapide
- table:mef: permet de créer un table de mise en forme
- table:simple: permet de créer un tableau simple
- table:complexe: permet de créer un tableau complexe

Pour rappel:
- les balise `<header>` `<nav>` `<main>` et `<footer>` sont obligatoires sur une page.
- `<main>` est unique dans la page.
- `<nav>` est réservé aux zones de navigation. De plus, le bouton burger ou autre doit être inclus dans l'élément `<nav>`.

## Autre
- !: changement de la langue pour fr-FR et ajout du lien vers feuille de style
- time: ajout de la balise html `<time>`
- svg: ajout de la balise html `<svg>`
- svg:info: ajout de la balise html `<svg>` quand le svg est porteur de sens
- svg:deco: ajout de la balise html `<svg>` quand le svg sert de décoration
- figure: ajout du role *figure*, de l'aria-label; ainsi que des balises image et figcaption