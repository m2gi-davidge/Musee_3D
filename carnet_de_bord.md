# Musée 3D
## Plan de travail établi
    - Première partie : Décrire en 3D des salles avec des objets arbitraires (pour commencer) sur des présentoirs, naviguer dans ces salles 3D avec la souris, faire le tour des présentoirs,  passer dans la salle suivante par la porte.
    S'inspirer du prototype de Damien Boureille ci-dessus. Lui demander son source.
    - Deuxième partie : peupler dynamiquement ces salles avec les objets des 22 salles de la galerie informatique d'ACONIT (https://db.aconit.org/dbgalerie/galerie.php?fgal=galerie0).
    Pour cela on adaptera le code écrit par Philippe Denoyelle , avec son aide, qui génère la description 2D d'une salle en HTML, pour l’adapter à une salle 3D.

## Carnet de Bord
### 11 Mars 2023
#### 2 heures
    - Objectif : S'approprier le code récupéré
    - Mise en place du code récupéré
    - Lecture du code
    - Coder en : JavaScript (inconnu), HTML (inconnu) et CSS (inconnu)
    - Utiliser Blender (inconnu) ou Three.js (inconnu)
    - Synthèse de la structure du code :
        * Soit un code en JS, et la salle générée directement en three.js => apprendre la 3D avec three.js
        * Soit un code en JS, et la salle créée avec Blender mais liée avec un fichier .fbx et three.js => apprendre à
        lier le fichier 3D et JS
    - Conclusion : Seule la partie 1 semble réalisable en environ 36 heures

### 14 Mars 2023
#### 4 heures
    - Objectif : Apprendre à utiliser Java script et les imports
    - Appropriation des imports et de l'utilisation de loader pour charger les modèles 3D depuis Blender
    - Conclusion : Je peux créer les salles en 3D sur Blender et les importer ensuite sur mon doc JS afin de les
    animer
    Plan potentiel :
    Etape 1 :
        1) Faire 1 salle en Blender
        2) Pouvoir naviguer dans cette salleà l'aide de la souris
        3) Faire une autre salle
        4) Pouvoir naviguer entre les deux salles à la souris
    Fin Etape 1
    Etape 2 :
        A définir
    Fin Etape 2

### 21 Mars 2023
#### 2 heures
    - Objectif : Faire une salle simple pour s'approprier three.js
    - Finalement on n'utilisera pas Blender car les modèles sont simples
    - Déplacer un objet dans la monde
    - Placer de la lumière...
    - Conclusion : cats_room.html

### 22 Mars 2023
#### 4 heures
    - Objectif : Commencer une bibliothèque "museum.js" qui permet de créer
    le musée, par des primitives comme createRoom()...
    - createRoom() en cours, murs et présentoirs posés dynamiquement selon la seule
    configuration possible pour le moment (Simple)
    - Commentaire du code
    - Conclusion : Pour le 26 Mars, on veut une fonction createRoom() opérationnelle
    pour au moins la configuration simple. C'est à dire que l'on peut tester avec
    des objets venant directement de la galerie (renseignés dans un tableau).
    Plan pour le 26 :
        1) Dans createRoom() : placer les images des objets en 2 dimensions sur 
            les présentoirs
        2) Inclure l'animation
        3) Ajouter un tableau pour l'image du protagoniste de la salle
        4) Ajouter des textures et travailler l'aspect esthétique (c'est super moche)
        5) Ajouter le texte relatif aux objets

    /* function :
        Description here with pre-conditions and possibly edge effects
            Input  : ...
            Output : ...
    */