# Lecture musique

## Fonctionnalités obligatoires
* Jouer, arrêter, reprendre un morceau
* Gérer des playlists
    * Il faut pouvoir créer une playlist, lui ajouter/supprimer des chansons, la jouer
    * Le player doit pouvoir jouer un titre ou une playlist
* Gérer une mascotte
    * Possibilité de changer de mascotte et de la désactiver
    * L'affichage de la mascotte doit être isolé de la logique de la mascotte
* Gamification
    * Achievement, crédit pour acheter dans une boutique des éléments (musique, fonctionnalités, mascottes, skin, customisation de la mascotte...), etc.
    * Ce doit être une fonctionnalité transverse à la logique de l'application, pas complètement isolée
* Fonctionnalités implémentées (2 autres fonctionnalités significative en plus des fonctionnalités obligatoires ci-dessus).

## Notation
* Fonctionnalités correctement isolées, SOLID, etc..
    * La gestion de la mascotte et la gestion de son affichage est isolé par exemple.
    * L'ui principale sait qu'elle doit afficher des composants (la mascotte par exemple) mais elle n'a pas à savoir comment l'afficher. 
    * Un élément, une responsabilité. Pas de fonctions qui contiennent l'implémentation de plusieurs fonctionnalité par exemple.
* Autres :
    * Qualité du code: nomage des variables, des fonctions, des classes, etc. Commentaire pertinents, pas de code mort, pas de code dupliqué, etc.
    * Qualité globale du repo : on met le code dans le repo', pas le dossier de build, la base de données, etc.
    * Organisation du projet : fichiers correctement nommés, correctement organisés, etc.
    * Utilisation correct du C++ :
        * Smart pointer et pas new/delete.
        * Conteneurs de la bibliothèque standard et pas des tableaux.
        * Etc.

## Autres
* La partie UI n'a pas à être réalisée en Qt, de l'affichage console suffit. Attention, ça ne veut pas dire mettre des affichages partout dans l'appli', il faut bien avoir une partie UI et une partie métier.
* Le projet doit être réalisé en C++ mais par forcément avec cmake.

## Milestones
* Semaine du 17 mai: partager un repository avec un readme qui explique comment compiler et lancer l'application.
* Min(20 juin et 2,5 semaines avant l'arrêt des notes): récupération finale du projet

Le rendu finale est le répo git contenant la solution. S'il ne faut pas utiliser la branche par défaut du répo, le préciser par email.

Le README du projet doit contenir :
- Les instructions pour compiler et lancer l'application.
- La liste des fonctionnalités implémentées.

