# cours-et-exempless-flexbox

## Les sources

https://developer.mozilla.org/fr/docs/Learn/CSS/CSS_layout/Flexbox

https://css-tricks.com/snippets/css/a-guide-to-flexbox/

https://www.w3schools.com/css/css3_flexbox.asp

https://fr.w3docs.com/apprendre-css/the-ultimate-guide-to-flexbox.html

## Les grands principes des FlexBox

### Flex container = conteneur flexible

Un élément parent dans lequel chaque élément (aussi appelé item) sera contenu. Un conteneur flex est défini dès lors que sa propriété display a la valeur "flex"

### flex item = item flexible

Chaque élément enfant d'un conteneur flexible devient un item flexible sur lequel on va pouvoir agir via des propriétés flex spécifiques. 

### Les axes

Tout conteneur flexible suit 2 axes : un axe principal et un axe secondaire. C'est en fonction de ces axes que mes items flex vont se positionner.

- la propriété flex-direction me permet d'établir l'axe principal
- la propriété justify-content me permet de définir comment mes enfants flex sont positionnés sur mon axe principal
- la propriété align-items me permet de définir comment mes enfants flex sont positionnés sur mon axe secondaire