## Objectifs
L’objectif est de développer 2 pages avec navigation entre elles.
La première page est une simple fiche produit présentant :
- nom du produit
- description
- 1 image fixe
- 1 bouton « Ajouter au panier »
- 1 bouton « Voir mon panier » qui conduit vers la 2e
page

La deuxième page est une page permettant de faire un récapitulatif du produit
ajouté au panier. Elle présente :
- nom de la page
- le détail du produit ajouté (image, nom – avec lien vers la fiche produit,
quantité, actions)
- les actions pour le produit sont :
- Supprimer : supprime le produit du panier
- Ajouter : augmente la quantité de 1
- Diminuer : baisse la quantité de 1
- 1 bouton fictif « Commander »
Attention : si aucun produit n’est ajouté, le récapitulatif doit afficher un simple
message « Aucun produit dans le panier », et le bouton fictif doit être
désactivé.


## Règles
Si on ajoute plusieurs fois le produit depuis la fiche produit, la quantité
augmente de 1 à chaque fois.
La quantité maximale du produit dans le panier est de 12, l’utilisateur ne doit
pas pouvoir aller au-dessus.
Si l’utilisateur diminue la quantité jusqu’à 0, le produit est considéré comme
supprimé du panier.


## Contraintes techniques
Vous devez utiliser un framework JS moderne (VueJS, React, Svelte, Angular).
Pour la partie style, vous devez aussi vous appuyer sur un framework CSS
(Bootstrap, Tailwind...).
Vous devez pousser votre code sur un répertoire Github public.


## Les plus
Sans rentrer dans une intégration poussée, il est attendu une certaine
cohérence de style (couleur des boutons, organisation des pages...).
Idéalement proposer une persistance du panier (cookies, localStorage).
Proposer une robustesse du code en passant par un store (Redux, VueStore...).
