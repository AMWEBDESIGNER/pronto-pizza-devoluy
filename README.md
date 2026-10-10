# Pronto Pizza — maquette indépendante

Vitrine statique pour **Pronto Pizza**, traiteur, snack et pizzeria de Superdévoluy.

## Vérification et sources

- Activité : le site de Pronto Pizza affiche sa carte et ses coordonnées à Superdévoluy ; la fiche Office de tourisme annonce les périodes 2026 et la livraison dans la station. Des avis Tripadvisor sont datés d’août 2026.
- Sources : [site Pronto Pizza](https://prontopizza-devoluy.fr/), [Office de tourisme](https://www.ledevoluy.com/zomer/touristic_sheet/pronto-pizza-superdevoluy-nl-zomer-4009122/), [Tripadvisor](https://www.tripadvisor.fr/Restaurant_Review-g10717361-d6485630-Reviews-Pronto_Pizza-Le_Devoluy_Hautes_Alpes_Provence_Alpes_Cote_d_Azur.html).
- Logo : faute d’un fichier logo à droit de réutilisation confirmé, la signature web est provisoire et à remplacer par la version autorisée.
- Photos : URLs Unsplash sous licence dans le HTML, non représentatives de l’établissement.

## Liens

- GitHub : https://github.com/AMWEBDESIGNER/pronto-pizza-devoluy
- Pages : https://pronto-pizza-devoluy.pages.dev

## Parcours livré

L’accueil est complété par `carte.html` et `infos.html`, avec commande directe, services emporter/livraison/traiteur, adresse et itinéraire. La carte, les prix, horaires, périmètre de livraison et les médias doivent être validés directement par Pronto Pizza. Maquette indépendante sans affiliation.

## Motion design et provenance du code

Animations réalisées en CSS vanilla, avec respect de `prefers-reduced-motion`, et une révélation progressive inspirée du pattern public [Scroll animation: IntersectionObserver and CSS](https://codepen.io/oscar-jite/pen/qBzwOVq). La logique reste locale, légère et adaptée à l’identité de chaque établissement ; aucune dépendance payante ni contenu généré n’est requis.

## Informations pratiques livrées

`site-enhance.js` ajoute sur l’accueil un bloc dédié à l’adresse, aux horaires, aux services, au téléphone et à l’itinéraire, ainsi qu’un footer local complet. Les informations signalées « à confirmer » doivent être validées par l’établissement avant mise en production commerciale.
