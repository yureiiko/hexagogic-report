<img src="D:\etude_sup\IUT_info\IUT_2\hexagogic_projet_tutore\rapport_projet\Conception\page_conception.jpg" width="650">

<div style="page-break-after: always"></div>

# Table des Matières

- Introduction <p style='text-align: right;'> **page 3** </p>
---
- Spécification détaillé de la structure du système <p style='text-align: right;'> **page 4** </p>
---
- Spécification détaillé des interfaces utilisateur <p style='text-align: right;'> **page 5** </p>
---
- Choix des outils à utiliser <p style='text-align: right;'> **page 6** </p>
---
- Conclusion et points ouverts <p style='text-align: right;'> **page 7** </p>
---
- Annexes <p style='text-align: right;'> **page 8** </p>
---

<div style="page-break-after: always"></div>

|**Projet Hexagogic**                |Version 1.0
|------------------------------------|-------------------|
|Document : Dossier de conception    |Date : 16/12/2021
|Responsable de la rédaction : FLEURY CALAIS Pierre

# Introduction

Ce document est le dossier de concepteur du projet hexagogic. Il contient des explication sur la structure du code source du projet incluant un ou plusieurs diagrammes UML founis en annexe.

<div style="page-break-after: always"></div>

|**Projet Hexagogic**                |Version 1.0
|------------------------------------|-------------------|
|Document : Dossier de conception    |Date : 16/12/2021
|Responsable de la rédaction : FLEURY CALAIS Pierre

# Spécification détaillée de la structure du système

Remarque : 
- voir plus de détails sur les diagrammes UML présents en annexes
- pour toutes les références à la librairie JavaFX, voir la bibliographie du rapport de projet

La majorité des classes du logiciel sont controlées ou implémentées, directement ou indirectement par la classe ```Controller```. Celle-ci possède un attribut mainStage de type ```Stage``` ainsi que les méthodes ```start(Stage parStage)``` permettant de lancer la création de l'interface graphique, ```setMenuStage()``` et ```setGameStage()``` permettant respectivement la mise en place de la scène ```MenuScene``` et de la scène ```GameScene``` toutes deux héritant de la classe ```Scene```.

Toute les classe héritant de la classe ```Scene``` possèdent un attribut de type ```Controller``` ainsi qu'un attribut héritant de la classe ```BorderPane```. Ces classes comportent alors les différents éléments graphiques permettant les interactions avec l'utilisateur.

Le package modèle du projet comporte la classe ```LogicalCell``` possédant un attribut opération de type ```LogicalOperation```. Cette première est un prototype de la structure permettant la réalisation d'opérations semblables à celles des circuits logiques (voir Recueil des Besoins - Chapitre 2 : Glossaire).

<div style="page-break-after: always"></div>

|**Projet Hexagogic**                |Version 1.0
|------------------------------------|-------------------|
|Document : Dossier de conception    |Date : 16/12/2021
|Responsable de la rédaction : FLEURY CALAIS Pierre

# Spécification détaillée des intefaces utilisateur

Dans sa version final, l'interface de jeu aura au minimum les composants suivants :
- une colonne contenant les tuiles opérations qu'il est possible de placer.
- une grille hexagonale (voir Recueil de Besoins - Chapitre 2 : Glossaire) sur laquelle le joueur peut placer les tuiles d'opération comportant avec des variables d'entrée prédéfinies.
- un bouton "Break" permettant d'accéder au menu du jeu.

L'interface de menu est constituée de différents boutons ayant différentes fonctions. Ils permettent de :
- Poursuivre le niveau en cours (RESUME)
- Recommencer le niveau en cours (RESTART)
- Sélectionner un niveau (SELECT LEVEL)
- Voir la page de tutoriel (TUTORIEL)
- Sélectionner le niveau suivant (NEXT LEVEL)
- Retourner au menu principal (MAIN MENU)
- Quitter le jeu et fermer la fenêtre graphique (EXIT)

Le bouton RESUME permet d'accéder au plateau de jeu. Celui ci présente une colonne à droite comportant des boutons pour sélectionner les opérations logiques. En bas ce trouve un bouton BREAK permettant de revenir au menu du jeu. Au milieu ce trouve la grille hexagonal constituant le plateau de jeu. Pour le moment, cliquer sur une tuile du plateau affiche la position de cette dernière dans la console.

Le bouton TUTORIEL permet de modifier la fenêtre pour visualiser les tables de vérité des différentes opérations logiques, ainsi qu'une notice d'utilisation du logiciel. On peut voir les différentes pages en utilisant les flèches en bas de fenêtre et revenir au menu principal avec le bouton MENU, également en bas de fenêtre.

Un prototype de circuit réalisable dans le jeu est disponible en annexe.

Les tuiles (voir Recueil de Besoins - Chapitre 2 : Glossaire) représentant la ou les variables d'entrée et celles représentants la ou les variables de sortie doivent avoir des couleurs différentes. En plus du nom de l'opération logique affiché en leur centre, les tuiles d'opérations doivent avoir chacune de couleurs qui diffèrent et qui sont différentes des tuiles d'entrée et de sortie.

<div style="page-break-after: always"></div>

|**Projet Hexagogic**                |Version 1.0
|------------------------------------|-------------------|
|Document : Dossier de conception    |Date : 16/12/2021
|Responsable de la rédaction : FLEURY CALAIS Pierre

# Choix des outils à utiliser

L'ensemble des éléments graphiques du logiciel doivent être codés avec en langage java avec la librairie JavaFX afin de ne pas créer de dysfonctionnement avec les classes déjà crées.

La structure permettant la réalisation des opérations logiques a été conçue selon une version adaptée au projet du Design Pattern Etat (voir bibliographie du rapport de projet). Cela permet d'ajouter de nouvelles opérations logiques en modifiant la méthode ```execute``` de la classe ```LogicalOperation``` sans changer le code de la classe ```LogicalCell```. Aussi, grâce à ce Design Pattern, les opérations des cellules diffèrent en fonction du nom de l'instance de la classe ```LogicalOperation```. Cette structure est conçu selon le modèle d'une liste chaînée avec des cellules possédant deux "cellules suivantes" afin de pouvoir créer un bifurcation dans le circuit logique.

<div style="page-break-after: always"></div>

|**Projet Hexagogic**                |Version 1.0
|------------------------------------|-------------------|
|Document : Dossier de conception    |Date : 16/12/2021
|Responsable de la rédaction : FLEURY CALAIS Pierre

# Conclusion et point ouverts

Actuellement, l'équipe de projet n'a pas encore conçu la mécanique du jeu. En effet, la librairie utilisé n'est que peu connue au sein du groupe et la concevoir prend donc du temps. Une documentation sur celle-ci sera donc fournie dans de futures version du dossier concepteur.

<div style="page-break-after: always"></div>

|**Projet Hexagogic**                |Version 1.0
|------------------------------------|-------------------|
|Document : Dossier de conception    |Date : 16/12/2021
|Responsable de la rédaction : FLEURY CALAIS Pierre

# Annexes

- Annexes 1 : Prototype de circuit <p style='text-align: right;'> **page 9** </p>
---
- Annexes 2 : Diagramme UML <p style='text-align: right;'> **page 10** </p>
---

<div style="page-break-after: always"></div>

|**Projet Hexagogic**                |Version 1.0
|------------------------------------|-------------------|
|Document : Dossier de conception    |Date : 16/12/2021
|Responsable de la rédaction : FLEURY CALAIS Pierre

# Annexe 1 : Prototype de circuit

<img src="D:\etude_sup\IUT_info\IUT_2\hexagogic_projet_tutore\rapport_projet\Conception\prototype_circuit.jpg">

<div style="page-break-after: always"></div>

|**Projet Hexagogic**                |Version 1.0
|------------------------------------|-------------------|
|Document : Dossier de conception    |Date : 16/12/2021
|Responsable de la rédaction : FLEURY CALAIS Pierre

# Annexe 2 : Diagramme UML

<img src="D:\etude_sup\IUT_info\IUT_2\hexagogic_projet_tutore\rapport_projet\Conception\diagramme_classes.jpg">

Pour obtenir le diagramme au format mdj veuillez envoyer un mail à un membre de l'Hexagoteam. Les contacts sont en première partie du rapport de projet.