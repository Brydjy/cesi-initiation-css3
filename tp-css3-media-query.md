# TP #

Les médias Query en CSS3

### Avant-propos ###

Il est important de savoir que les **Media Query** ne s’appliquent pas à la résolution de votre écran, mais bel et bien à la taille de votre fenêtre et même, à la taille de votre body de votre page web (toolbar, url et scrollbar en moins). 

Cependant, il est évident que si vous avez une résolution d’écran faible, votre fenêtre sera de toute évidence plus petite que sur une dalle haute résolution. 

### Préparation ###

Créer une page HTML avec un fichier CSS lié à celle-ci.  
Cette page devra se composer de :  
- Un titre h1  
- Un texte d’introduction  
- Plusieurs grandes images (taille originale de l’image attendu : 1920 x 1080 px)
  * Disposées à souhait  
  * L’affichage des images sur la page HTML se fera dans la résolution de votre choix

## Exercice 1 : Les tailles de fenêtres ##
Gérer différentes taille de fenêtre

- 1920 x 1080  
- 1600 x 900  
- 1366 x 768  
- 1280 x 1024  
- 1024 x 768  

**Travail à réaliser**  

- Changer la taille des images lorsque la taille de l’écran change (adapter à la page)
- Chaque image doit systématiquement rester entièrement visible, peu importe la résolution en cours  
- Changer la couleur du titre h1 pour chaque palier de résolution (définie ci-dessus)  
- Appliquer les différentes tailles ci-dessus pour l’ensemble de l’exercice

## Exercice 2 : L’orientation ##
Lorsque l’écran est en position **« Paysage »** (landscape) afficher le contenu de la page.

Lorsque l’écran est en position **« portrait »** (portrait) afficher un message incitant l’utilisateur à remettre en mode paysage. Empêche également l’utilisateur de continuer à naviguer sur le site.

**Indice :**  

- Attention, la majorité des navigateurs interprète le mode « orientation » même sur ordinateur

## Exercice 3 : Ripple ##

1. Si vous avez la possibilité de créer une connexion entre votre mobile et votre ordinateur, connectez-vous.
  * Le but de l’exercice est de pouvoir afficher sur son mobile la page actuelle.  

2.	Si ce n’est pas possible, téléchargez et installez la webApp Chrome « Ripple ». Elle permet d’émuler un device mobile. 
  * Avec Ripple, choisir Mobile Web (default)

**Travail à réaliser :**  

- Adapter votre page aux terminaux mobiles  
- Modifier le viewport et constater les changements  
- Le site doit être ergonomique et en plein écran

**Indice :**

- viewport et balise meta  
- scale  


## Exercice 4 : Créer un menu mobile ##

1. Ajouter un menu à votre page avec 6 liens
  * Le menu doit être en ligne et horizontale, donc les liens les uns à côté des autres. 

2.	Quand on rétrécie la fenêtre et que l'affichage passe en dessous des 768px de large, le menu doit subir une transformation
  * En dessous de 768px de large, si ce n'est pas déjà le cas, le menu doit changer de place et venir se positionner en haut de l'écran
  * Une fois la position du menu changée, il doit également n'afficher qu'un seul élément ou une seule information (pas tous les items du menu) afin d'optimiser l'espace
  * Par exemple : L'intitulé "Menu" peut apparaître ou encore un bouton / icone représentant un menu
  * Libre à vous de le placer à gauche, centré ou à droite
  * Idéalement pour l'exercice, il devra faire toute la largeur de la page
  * Au passage de la souris, le menu doit s'ouvrir et laisser apparaitre tous les items du menu
  * Les différents items du menu, ne seront plus affiché en ligne mais en bloc, chaque item prendra toute la largeur de la page
  
Pour mieux comprendre le résultat attendu, observez l'exemple suivant :  

Menu taille normal
![Menu full size](http://i.imgur.com/JXAMksm.png)
Menu taille optimisée (après redimensionnement)
![Menu mobile](http://i.imgur.com/r1oSITv.png)
Menu ouvert en version responsive (optimisé mobile)
![Menu mobile ouvert](http://i.imgur.com/yVkL8fJ.png)

**Travail à réaliser :**  

- Ajouter un menu horizontal à sa page
- Adapter le menu à la résolution de la page en temps réel
- Transformer le menu via les transition CSS3  
- Optimiser l'affichage du menu en modifiant sa taille et l'affichage des items en vertical

**Indice :**

- CSS3
- Transition
- Display none
- :hover
- height
- ! important



