# mouchez-projet
 Mouchez Alexandre
 Regle css complexe :
.imgT : il s'agit d'une classe qui me permet de faire un bloc composé d'une image et de texte. On la retrouve dans les pages 1/2/3

.ville:il s'agit d'une classe qui me permet de faire un bloc composé d'une image et de texte(en position absolute).On la retrouve dans la page index.

footer div.container : Ce sélecteur cible les éléments <div> qui sont situés à l'intérieur de l'élément <footer> de la page et qui ont la classe "container". Il permet de définir des styles spécifiques pour les conteneurs dans la section de pied de page.

transition : 
img:hover : Ce sélecteur cible toutes les images (<img>) de la page et spécifie un style qui s'applique lorsqu'un utilisateur survole l'image avec le curseur. Cela peut être utilisé pour créer des effets au survol, tels que le changement de taille ou de couleur.

img:not(.imgT img, table img):hover : Ce sélecteur cible toutes les images (<img>) de la page, sauf celles qui sont situées à l'intérieur d'éléments avec la classe "imgT" ou d'éléments <table>. L'effet spécifié s'applique lorsqu'un utilisateur survole ces images non incluses dans les exceptions. Cela permet de créer des transitions au survol pour la plupart des images de la page, à l'exception de celles dans les situations spécifiques mentionnées.
J'utilise cette règle pour que seul mon image de #presentation de la ville puisse subir le hover (en concervant le hover sur les images de mon header). Ne sont donc pas conserné:Les images/blasons dans le tableau , ainsi que les images de présentation des armées. 

Règles media queries et leur effet :
@media screen and (min-width: 1001px), @media screen and (max-width: 1000px) and (min-width: 601px), @media screen and (max-width: 600px) : Ces règles définissent différents styles en fonction de la largeur de l'écran, pour une mise en page adaptative sur les écrans larges, les tablettes et les appareils mobiles.
Le header sera redéfini pour chaque format, de même que le main des pages non index pour avoir un rendu plus harmonieux.
