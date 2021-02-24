TP media queries

## TP media queries

* * *
Ajouter un media queries avec des css venant contredire les instructions initiales afin d'obtenir la copie d'écran ci-dessous (On ne touche pas au CSS initial contenu dans la page livrée, on rajoute du CSS sous un conditionnement de media-queries). Voici quelques conseils :

    
- la div #main devra avoir cette fois une largeur auto et non plus fixe
- les div de classe .entry_preview (chaque vignette) devront aussi être de largeur libre, ainsi que la hauteur, elle ne devront plus flotter. Elle devront prendre la largeur de l'écran en étant de display block.
- Les photos (.entry_preview .thumb) devront cette fois être flottante gauche et d'un largeur maximale de 50% de son container (.entry_preview)
- On pourra affiner en ajuster partout les padding