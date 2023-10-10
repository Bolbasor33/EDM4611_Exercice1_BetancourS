Crop Circles par Betancour, Santiago dans le cadre du cours EDM4611 ex.1 

Je me suis toujours intéressé à la création de ces objets curieux. C'est des créations dites extraterrestres qui apparaissent en quelques secondes dans les champs de foin ou autre endroit éloigné en région. Afin de présenter ces objets et les mettre en valeur dans le logiciel Touch Designer, il a fallu faire des recherches sur le web pour trouver des exemples en svg, mais sans succès. Avec l'aide du livre de Philippe Messina - Crop Circles Mandalas des Champs. 

J'ai donc décidé de scanner les pages qui ont déjà ces impressions en mode blanc et noir et ainsi, j'ai pu les intégrer dans le logiciel avec le folder DAT/select et le chop execute vu en classe. 

Ensuite, il fallut transformer les images avec le TOP crop pour essayer de centrer le tout, puis transformer la couleur blanche avec un chromakey TOP. 

Par la suite, vient deux différents feedbacks inspirés d'exercices vus en classe. 

L'idée initiale était de créer des crop circles de style morphing entre eux avec une trainée vers l'arrière. Je n'ai pas réussi à transformer les images 2D en objets 3d pour leurs donner d'autres propriétés. 

J'ai finalement placé le résultat TOP dans un phong qui peut ensuite être posé sur un cercle SOP à l'aide du phong dans le Geo. 

Pour donner un effet de mouvement, j'ai animé le TOP transform des crop circles pour qu'il tourne avec le temps. 

Afin d'ajouter d'autres items, à l'aide d'un exercice vu en classe d'un cercle SOP qui bouge dans un géo en laissant une trainée en arrière, je l'ai transformé pour qu'il n'y ait que des mouvements de grosseur avec l'aide de quelques noises CHOP. Pour donner plus de dimension, j'ai créé un oscillement sur le x,y du transform de ce SOP afin qu'il bouge avec un effet naturel. 

Encore une fois pour ajouter d'autres dimensions au résultat final, avec l'aide d'un patch d'un exercice vu en cours, j'ai modifié une chaine de SOP qui crée des amas de lignes qui font des tours dans l'espace GEO. 

Afin d'importer un SVG d'une cocotte de pin, j'ai utilisé le webrender et quelques modifications sur celui-ci, ensuite tracé avec un SOP et ajouté du bruit pour animer l'objet. Celui-ci représente le fruit du savoir qui est au centre de la création des Crop Circles. Objets naturels dont on ne connait toujours pas l'origine, ni leur fonctionnement ni leur message. 

Le son des notes d'un Steel Tongue drum sont importés dans le projet et j'ai appliqué le même fonctionnement d'activation des fichiers à l'aide d'un lfo pour passer à travers les fichiers dans le temps. 

Ce son est un coup de drum créant une onde de son presque pur qui va dans le même sens que la création d'un cercle de champs. La création de cet objet, en un seul moment créé à partir d'une énergie pure et inconnue. 

Ce bruit de drum fait animer l'opacité d'un feedback sur le rendu final et sur l'animation du SOP de la cocotte de pin. 