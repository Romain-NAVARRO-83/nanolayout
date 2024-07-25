## Container et colonnes

### .nano container

Tous éléments ayant la classe *nano* devient un container flex, wrap, justify-content: space-between.

### Colonnes

Tout élément enfant direct d'un container *nano* peut s'étaler sur *x 12<sup>èmes</sup>* de la largeur de son parent en fonction de sa classe.

- **S1** : 1/12 de la largeur du parent
- **S2** : 2/12 de la largeur du parent
- **S3** : 3/12 de la largeur du parent
- ...
- **S12** : *Inutile*, par défaut les enfants de *nano* prennent toute la largeur du container

### Breakpoints

Un framework responsive minimaliste avec 3 largeurs d'écran gérées.

- **.sX** : Les règles *sX* s'appliquent par défaut ![mobile icon](fa-solid fa-mobile-screen)
- **.mX** : Les règles *mX* s'appliquent à partir de 800px ![tablet icon](fa-solid fa-tablet-screen-button)
- **.lX** : Les règles *lX* s'appliquent à partir de 1200px ![desktop icon](fa-solid fa-desktop)

Approche *mobile first* : si aucune classe n'est donnée pour les tailles d'écran *medium* et *large*, les dimensions *small* s'appliquent pour toutes les tailles.

---

## Exemples d'utilisation

### Section avec colonnage spécifié

- Élément sans colonnage spécifié : *flex-basis : 100%*
- Élément `.s6` : 50% de la largeur du parent
- Élément `.s6` : 50% de la largeur du parent
- Élément `.s6.m4.l3` : Largeur adaptative avec 50% en petit écran, 33% en moyen et 25% en grand écran
- Élément `.s6.m4.l3` : Largeur adaptative avec 50% en petit écran, 33% en moyen et 25% en grand écran
- Élément `.s6.m4.l3` : Largeur adaptative avec 50% en petit écran, 33% en moyen et 25% en grand écran
- Élément `.s6.m4.l3` : Largeur adaptative avec 50% en petit écran, 33% en moyen et 25% en grand écran

---

## Surcharges

### Padding

### Gap

### Nogrow
