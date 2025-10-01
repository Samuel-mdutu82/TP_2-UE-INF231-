
README.md

markdown
Projet C - Liste Doublement Chaînée

Ce projet implémente la gestion d'une liste doublement chaînée en langage C avec insertion à une position donnée.

° Fonctionnalités

- Insertion d’un élément à une position spécifique
- Affichage de la liste dans les deux sens (grâce aux pointeurs precedent et `suivant`)
- Menu interactif via la console

° Fichiers

- main.c : Contient tout le code du projet



° Structure utilisée

 
typedef struct NoeudDouble {
    int data;
    struct NoeudDouble* precedent;
    struct NoeudDouble* suivant;
} NoeudDouble;


✍️ Auteur

- Mdutu Yougoum Marc Samuel 
- Matricule: 24G2779
— INF 231