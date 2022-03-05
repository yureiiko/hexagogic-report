<img src="D:\etude_sup\IUT_info\IUT_2\hexagogic_projet_tutore\rapport_projet\analyse_besoins\recueil_des_besoins\page_rdb.jpg" width="650">

<div style="page-break-after: always"></div>

# Table des Matières

- Chapitre 1 : Objectif et portée <p style='text-align: right;'> **page 3** </p>
---
- Chapitre 2 : Terminologie employée / Glossaire <p style='text-align: right;'> **page 4** </p>
---
- Chapitre 3 : Les Cas d'Utilisation <p style='text-align: right;'> **page 5** </p>
---
- Chapitre 4 : La Technologie employée <p style='text-align: right;'> **page 6** </p>
---
- Chapitre 5 : Autres exigences <p style='text-align: right;'> **page 7** </p>
---
- Annexes <p style='text-align: right;'> **page 9** </p>
---

<div style="page-break-after: always"></div>

| Projet Hexagogic                 | Version 1.0       |
|----------------------------------|-------------------|
| Document : Recueil des exigences | Date : 17/12/2021 |
|Responsable de la rédaction : Ensemble de l'équipe du projet hexagogic |

# Chapitre 1 : Objectif et portée

L'objectif est de créer un jeu video éducatif dont le but est de créer un système de circuit logique semblable à ceux que l'on peut observer dans des exercices de logique élémentaire.

Dans une première version le jeu sera sous la forme d'un programme exécutable.

Les personnes concernées sont donc l'ensemble des personnes pouvant s'échanger le code source du jeu.

<div style="page-break-after: always"></div>

| Projet Hexagogic                 | Version 1.0       |
|----------------------------------|-------------------|
| Document : Recueil des exigences | Date : 17/12/2021 |
|Responsable de la rédaction : Ensemble de l'équipe du projet hexagogic |

# Chapitre 2 : Terminologie employée / Glossaire

**Hexagoteam :** Surnom donné à l'équipe travaillant sur le projet hexagogic

**Tuile :** Forme hexagonale représentant une opération, une variable ou l'affichage d'une variable dans le circuit. Elles possèdent plusieurs entrées et plusieurs sorties.

**Grille :** Dans le jeu auquel se réfère la présente, il s'agit d'une grille constituée d'hexagones.

**Variable :** Les valeurs d'entrée et de sortie de chaques niveaux sont stockées dans des variables d'entrée et de sortie. La ou les variables d'entrée sont modifiées par le circuit et l'objectif du joueur est que la ou les valeurs en fin de circuit soient égales à la ou aux variables de sortie. Les différentes variables peuvent prendre les valeurs 0 ou 1 (true ou false).

**Expression :** Correspond à la valeur d'une variable en sortie d'une tuile.

**Circuit logique :** Un circuit logique réalise une ou plusieurs fonction logiques. Il est composé de portes logiques interconnectées entre elles (le lien de cette définition se trouve dans la bibliographie du rapport de projet). Il s'agit d'une notion de logique élémentaire vue en première année d'IUT informatique.

<div style="page-break-after: always"></div>

| Projet Hexagogic                 | Version 1.0       |
|----------------------------------|-------------------|
| Document : Recueil des exigences | Date : 17/12/2021 |
|Responsable de la rédaction : Ensemble de l'équipe du projet hexagogic |

# Chapitre 3 : Les Cas d'Utilisation

L'ensemble des Cas d'utilisation sont fournis en annexe. Il s'agit d'une liste qui sera complétée dans de futures version du recueil des besoins.

<div style="page-break-after: always"></div>

| Projet Hexagogic                 | Version 1.0       |
|----------------------------------|-------------------|
| Document : Recueil des exigences | Date : 17/12/2021 |
|Responsable de la rédaction : Ensemble de l'équipe du projet hexagogic |

# Chapitre 4 : La technologie employée

Les exigences technologiques que nous avons sont d’utiliser UML comme langage de conception avec le logiciel StarUML, Java et JavaFX pour la programmation du logiciel et de son interface graphique avec les IDE Eclipse et IntellliJ IDEA. 

<div style="page-break-after: always"></div>

| Projet Hexagogic                 | Version 1.0       |
|----------------------------------|-------------------|
| Document : Recueil des exigences | Date : 17/12/2021 |
|Responsable de la rédaction : Ensemble de l'équipe du projet hexagogic |

# Chapitre 5 : Autres exigences

Actuellement, il y a cinq membres faisant partie du projet : BONIFACIO Timothé ; CASALOTTI Celeste ; FLEURY CALAIS Pierre ; KOSIN Alexandre ; LEROY Camille. De plus, Monsieur OSTER Alain fait parti du projet en tant que client et commanditaire de celui-ci.

Après concertation avec le client, ainsi que les membre du groupe, nous avons décidé que les valeurs suivantes sont à privilégier :
- Nous désirons  que le projet ainsi que sa conception fasse preuve de souplesse pour qu'il puisse être modifiable selon la demande du client, ou selon les difficultés que nous pourrions rencontrer lors de l'implémentation des fonctionnalités.
- Nous souhaitions aussi rester disponibles et joignables entre les membres du groupe et avec M.OSTER.
- Enfin, nous voulions pouvoir faire preuve de réactivité face aux imprévus, de toutes nature qu'ils soient.

Il a été convenu avec le client que le projet devra être rendu à celui-ci sous la forme d'un livrable contenant un exécutable et/ou du code compilable en fonction de son avancement. Le commanditaire et les autres utilisateurs potentiels auront cet exécutable en plus du code source et pourront le voir et le modifier. En plus du rendu final, M.OSTER aura fréquement un retour sur l'avancement ud projet via des réunion organisées collégiales.

Ce projet ne nécessite aucun achat de la part de l'équipe de développement mais en raison des technologies utilisées (voir Chapitre 4), nous devons faire l'acquisition de la librairie JavaFX. Afin de pouvoir réaliser les opérations logiques, il sera nécessaire de créer des listes de variables booléennes ainsi que des algorithmes pour les parcourir. 

Dans l'optique de la réalisation du projet, les membres du groupe vont devoir se former afin de pouvoir utiliser la librairie et interface JavaFX. Nous devons également l'installer sur nos environnement de développement respectifs afin de pouvoir l'utiliser.

Etant donné que le logiciel est destiné à être utilisé par des personnes jouant aux jeux video ou désirant progresser en logique, la seul règle métier à laquel doit obéir le livrable final est d'être simple à utiliser tout en procurant de la satisfaction au joueur.

Les performances globales du jeu tel que sa rapidité sont variables en fonction de l'ordinateur utilisé. Toutefois, les algorithmes de parcours de liste de booleen serons créés de façon à limiter l'utilisation de la mémoire vive de l'ordinateur des utilisateurs.

Les opérations les plus courantes à réaliser sur le logiciel sont les rajouts de niveaux de jeu dans les fichiers du jeu. Pour cela, des dossiers seront créés contenant des fichiers textes indiquant les variables d'entré et de sortie ainsi que leur position pour chaque niveau.

L'utilisateur lance le programme, une fenêtre s'ouvre et il accède au menu du jeu. Il peut alors jouer au jeu en sélectionnant son niveau. Il peut également apprendre comment jouer grâce à un tutoriel sous la forme de texte explicatif avec des images.

Le jeu se présente avec des **tuiles**(voir chapitre 2) représentant des portes logiques que le joueur doit placer sur une **grille**(voir chapitre 2) pour créer un circuit logique et obtenir une **expression**(voir chapitre 2) en sortie de circuit égale à la valeur imposée par le jeu.

A l'heure de la rédaction de ce document, l'équipe cherche la meilleur façon de créer les structures de variables booléennes, de les parcourir ainsi que comment créer des niveaux à partir de fichiers texte.

<div style="page-break-after: always"></div>

| Projet Hexagogic                 | Version 1.0       |
|----------------------------------|-------------------|
| Document : Recueil des exigences | Date : 17/12/2021 |
|Responsable de la rédaction : Ensemble de l'équipe du projet hexagogic |

# Annexes

- Diagramme des Cas d'Utilisation <p style='text-align: right;'> **page 10** </p>
---
- Cas d'Utilisation - Niveau Stratégiques <p style='text-align: right;'> **page 11** </p>
---
- Cas d'Utilisation - Niveau Utilisateur <p style='text-align: right;'> **page 12** </p>
---

<div style="page-break-after: always"></div>

| Projet Hexagogic                 | Version 1.0       |
|----------------------------------|-------------------|
| Document : Recueil des exigences | Date : 17/12/2021 |
|Responsable de la rédaction : Ensemble de l'équipe du projet hexagogic |

# Diagramme des Cas d'Utilisation

<img src="D:\etude_sup\IUT_info\IUT_2\hexagogic_projet_tutore\rapport_projet\CU\diagramme_cu.jpg">

<div style="page-break-after: always"></div>

| Projet Hexagogic                 | Version 1.0       |
|----------------------------------|-------------------|
| Document : Recueil des exigences | Date : 17/12/2021 |
|Responsable de la rédaction : Ensemble de l'équipe du projet hexagogic |

# Cas d'Utilisation - Niveau Stratégiques

<img src="D:\etude_sup\IUT_info\IUT_2\hexagogic_projet_tutore\rapport_projet\CU\1_strat\cu_1.jpg">

<div style="page-break-after: always"></div>

| Projet Hexagogic                 | Version 1.0       |
|----------------------------------|-------------------|
| Document : Recueil des exigences | Date : 17/12/2021 |
|Responsable de la rédaction : Ensemble de l'équipe du projet hexagogic |

# Cas d'Utilisation - Niveau Utilisateur

<img src="D:\etude_sup\IUT_info\IUT_2\hexagogic_projet_tutore\rapport_projet\CU\2_user\cu_2.jpg">

<img src="D:\etude_sup\IUT_info\IUT_2\hexagogic_projet_tutore\rapport_projet\CU\2_user\cu_4.jpg">

<div style="page-break-after: always"></div>

| Projet Hexagogic                 | Version 1.0       |
|----------------------------------|-------------------|
| Document : Recueil des exigences | Date : 17/12/2021 |
|Responsable de la rédaction : Ensemble de l'équipe du projet hexagogic |

<img src="D:\etude_sup\IUT_info\IUT_2\hexagogic_projet_tutore\rapport_projet\CU\2_user\cu_5.jpg">

<div style="page-break-after: always"></div>

| Projet Hexagogic                 | Version 1.0       |
|----------------------------------|-------------------|
| Document : Recueil des exigences | Date : 17/12/2021 |
|Responsable de la rédaction : Ensemble de l'équipe du projet hexagogic |

# Cas d'Utilisation - Niveau Sous-fonction

<img src="D:\etude_sup\IUT_info\IUT_2\hexagogic_projet_tutore\rapport_projet\CU\3_under_fonction\cu_3.jpg">

<img src="D:\etude_sup\IUT_info\IUT_2\hexagogic_projet_tutore\rapport_projet\CU\3_under_fonction\cu_6.jpg">

<div style="page-break-after: always"></div>

| Projet Hexagogic                 | Version 1.0       |
|----------------------------------|-------------------|
| Document : Recueil des exigences | Date : 17/12/2021 |
|Responsable de la rédaction : Ensemble de l'équipe du projet hexagogic |

<img src="D:\etude_sup\IUT_info\IUT_2\hexagogic_projet_tutore\rapport_projet\CU\3_under_fonction\cu_7.jpg">

<img src="D:\etude_sup\IUT_info\IUT_2\hexagogic_projet_tutore\rapport_projet\CU\3_under_fonction\cu_8.jpg">

<img src="D:\etude_sup\IUT_info\IUT_2\hexagogic_projet_tutore\rapport_projet\CU\3_under_fonction\cu_9.jpg">

<div style="page-break-after: always"></div>

| Projet Hexagogic                 | Version 1.0       |
|----------------------------------|-------------------|
| Document : Recueil des exigences | Date : 17/12/2021 |
|Responsable de la rédaction : Ensemble de l'équipe du projet hexagogic |

<img src="D:\etude_sup\IUT_info\IUT_2\hexagogic_projet_tutore\rapport_projet\CU\3_under_fonction\cu_10.jpg">

<img src="D:\etude_sup\IUT_info\IUT_2\hexagogic_projet_tutore\rapport_projet\CU\3_under_fonction\cu_11.jpg">