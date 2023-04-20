# Snippets Emmet pour Visual Studio Code

Collection de snippets pour Emmet. La plupart surchargent [les snippets par défaut](https://github.com/emmetio/snippets/blob/master/html.json) proposé, notamment pour ajouter automatiquement les éléments nécessaires pour l'accessibilité (role, aria-label...).

## Accessibilité
- header: ajout du rôle *banner*
- main: ajout de l'id *main*, du rôle *main* et de *tabindex=-1*
- footer: ajout du rôle *contentinfo*
- nav: ajout du rôle *navigation*
- nav:skip: permet de créer un lien d'accès rapide
- form: ajout du rôle *form*
- form:get: ajout du rôle *form*
- form:post: ajout du rôle *form*
- table:mef: permet de créer un table de mise en forme
- table:simple: permet de créer un tableau simple
- table:complexe: permet de créer un tableau complexe
- embed: ajout de l'attribut *title* pour les lecteurs d'écran
- iframe: ajout de l'attribut *title* pour les lecteurs d'écran

Pour rappel:
- les balise `<header>` `<nav>` `<main>` et `<footer>` sont obligatoires sur une page.
- `<main>` est unique dans la page.
- `<nav>` est réservé aux zones de navigation. De plus, le bouton burger ou autre doit être inclus dans l'élément `<nav>`.

## Autre
- !: changement de la langue pour fr-FR et ajout du lien vers feuille de style
- address:mailtel: ajout d'une balise `<address>` avec deux liens, un pour le mail et l'autre pour le téléphone
- bdi: ajout de la balise html `<bdi>`
- blockquote: ajout d'une balise html `<p>` au sein du bloc de citation
- blockquote:cite: ajout d'une balise html `<p>` au sein du bloc de citation et de la source de celle-ci
- cite:link: ajout d'un lien vers la référence
- data: ajout de la balise html `<data>`
- dl:def: ajout des balises `<dt>` et `<dd>` à la balise `<dl>`
- details:summary: ajout de la combinaison `<details>` et `<summary>`
- dialog: ajout de la balise html `<dialog>`
- figure: ajout du role *figure*, de l'aria-label; ainsi que des balises image et figcaption
- mark: ajout de la balise html `<mark>`
- meter: ajout de la balise html `<meter>`
- ol:4: liste ordonnée avec quatre entrées
- q:cite: ajout de la source de la citation en ligne
- rp: ajout de la balise html `<rp>`
- rt: ajout de la balise html `<rt>`
- ruby: ajout de la balise html `<ruby>`
- select:options: ajout d'une liste d'option pour la balise `<select>`
- svg: ajout de la balise html `<svg>`
- svg:info: ajout de la balise html `<svg>` quand le svg est porteur de sens
- svg:deco: ajout de la balise html `<svg>` quand le svg sert de décoration
- time: ajout de la balise html `<time>`
- track: ajout de la balise html `<track>`
- ul:4: liste non-ordonnée avec quatre entrées
- ul:links: liste de liens
- wbr: ajout de la balise html `<wbr>`

