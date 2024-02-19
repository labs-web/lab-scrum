---
layout: default
order: 5
---
# Plan 
- [Plan](#plan)
- [Product backlog](#product-backlog)
  - [Introduction](#introduction)
  - [Définition](#définition)
  - [Cahier des charges vs product backlog](#cahier-des-charges-vs-product-backlog)
  - [Responsable](#responsable)
  - [Caractéristiques](#caractéristiques)
  - [La liste des items du product backlog](#la-liste-des-items-du-product-backlog)
  - [L’importance des items dans le product backlog](#limportance-des-items-dans-le-product-backlog)
  - [L’estimation initiale](#lestimation-initiale)
  - [Démonstration et notes](#démonstration-et-notes)
  - [En complément](#en-complément)
  - [Étapes de construction](#étapes-de-construction)
  - [1. Identifier les besoins](#1-identifier-les-besoins)
  - [2. Rédiger les user stories](#2-rédiger-les-user-stories)
  - [3. Prioriser le product backlog](#3-prioriser-le-product-backlog)
  - [4. Vérifier le niveau de qualité des user stories](#4-vérifier-le-niveau-de-qualité-des-user-stories)
  - [Quels outils peut-on utiliser pour gérer un product backlog ?](#quels-outils-peut-on-utiliser-pour-gérer-un-product-backlog-)
  - [Références](#références)



# Product backlog
![Exposé Markdown](/lab-scrum/Exposé-Product-backlog/images/productbacklog.jpg)
<!-- new slide -->
## Introduction

![Différences entre le cahier des charges et le product backlog ](/lab-scrum/Exposé-Product-backlog/images/scrum-sprint-progress.png)*Figure 1: introduction*


<!-- note -->

Le Product Backlog est le point central de tout projet Scrum


<!-- new slide -->
## Définition
  
- Un backlog produit est une liste hiérarchisée de tâches destinées à l'équipe de développement. 
- Il est créé à partir de la feuille de route et de ses exigences. 
- Les éléments les plus importants figurent en tête du backlog produit. 
- C’est à partir de ce document que les sprints seront planifiés .
  
<!-- new slide -->
## Cahier des charges vs product backlog 


![Différences entre le cahier des charges et le product backlog ](/lab-scrum/Exposé-Product-backlog/images/Cahier-des-charges-versus-backlog-1536x864.png)*Figure3 : Cahier des charges vs product backlog*


<!-- new slide -->
## Responsable

![Différences entre le cahier des charges et le product backlog ](/lab-scrum/Exposé-Product-backlog/images/PO.png)*Figure3 : Responsable*

<!-- note -->
- Le **Product Owner** est le responsable du backlog et affine généralement ce dernier avec l’ensemble de l’équipe qui va faire maturer les **users story** pour qu’elles soient prêtes à être prises en charge par les développeurs. 
  - Il se peut que l’équipe de développement rédige les **users stories techniques** mais c’est toujours le Product Owner qui va prioriser l’ensemble des items.

<!-- new slide -->
## Caractéristiques


![Différences entre le cahier des charges et le product backlog ](/lab-scrum/Exposé-Product-backlog/images/product-backlog-DEEP.png)*Figure3 : Caractéristiques*

<!-- note -->
- Le product backlog possède quelques caractéristiques remarquables.
  - Publique : toute l’organisation doit avoir accès à ce product backlog, c’est une question de visibilité.
  - Réduit : le product backlog doit être assez court, entre 40 et 60 items en général.
  - Ordonné : les items sont ordonnés par valeur décroissante, c’est à dire que l’item qui représente le plus de valeur se retrouve en premier. 
    - Le PO peut utiliser diverses techniques agile pour ordonner le backlog
  - Unique : un seul product backlog par produit !
  - Vivant : le Product Owner peut très bien ré-ordonner le product backlog à sa guise en fonction des besoins émergent du produit.
  - Émergent : le backlog n’est jamais complet, il est dynamique, il change constamment et il est toujours possible de rajouter de nouveaux items, de nouvelles fonctionnalités.

<!-- new slide -->
## La liste des items du product backlog


![Différences entre le cahier des charges et le product backlog ](/lab-scrum/Exposé-Product-backlog/images/backlog-component.png)*Figure3 : La liste des items du product backlog*

<!-- note -->
- Vous avez sans doute déjà rencontré le terme de “users stories”, notamment si vous avez une expérience avec d’autres méthodes agiles. 
  - Dans Scrum, ces users stories sont appelés items. 
  - Chaque item est une exigence du client rédigé selon une terminologie métier et non technique.

- Il appartient au Product Owner de s’assurer que l’item pourra être compris par l’équipe. 
  - Le Product Owner créera donc cette liste avec le client et les utilisateurs de l’application. 
  - Après s’être assuré qu’il n’y a pas de doublons ou d’items qui se chevauchent, le Product Owner pourra attribuer un ID à chaque item et les disposer dans un tableau avant de procéder à un premier classement.
  <!-- new slide -->

## L’importance des items dans le product backlog

![Différences entre le cahier des charges et le product backlog ](/lab-scrum/Exposé-Product-backlog/images/priorite.png)*Figure3 :L’importance des items dans le product backlog*

<!-- note -->
- À ce stade, le Product Owner va attribuer une valeur d’importance à chaque item. 
  - Cette valeur représentera l’attente du client et son besoin de chaque fonctionnalité. 
  - Il est fréquent de voir le terme **priorité** être utilisé à la place d’importance. 
  - Il est toutefois recommandé de l’éviter car la priorité exclut totalement certaines notions, comme la dépendance entre les items.

- Cette valeur d’importance n’est pas figée et elle évoluera au fur et à mesure des feedbacks utilisateurs. 
  - Il est important de noter que seul le Product Owner est en droit d’attribuer ou modifier cette valeur.

<!-- new slide -->
## L’estimation initiale

- L’estimation initiale représente la quantité de travail nécessaire au développement de l’item déterminée par l’équipe elle-même. 
  - Elle prend en compte le temps de développement et la complexité de celui-ci. 
  - Il ne s’agit ici que d’une estimation qui, par définition, ne peut pas être exacte. 
  - Pour éviter toute mauvaise interprétation, il est courant d’utiliser une valeur étalon et non une valeur temporelle. 
  - Très souvent, l’estimation est faite grâce à la méthode du **Planning Poker**. 

<!-- new slide -->
## Démonstration et notes

- La colonne démonstration indique la démarche à suivre pour présenter l’item lors de la réunion de fin d’itération. 
  - Elle peut également faciliter la conception des tests par le Product Owner et donc servir de référence quant à l’acceptation ou non de l’item développé durant l’itération. 
  - Vous trouverez sans doute des Product Backlogs dans lesquels cette section sera absente, mais elle est fréquemment utilisée. 
  - Il en va de même pour la colonne note. 
  - Bien que très générique, elle permet souvent d’indiquer de manière très succincte les dépendances et autres informations pouvant influer sur l’importance et le développement de l’item.
<!-- new slide -->
## En complément
- Le guide Scrum préconise un maximum de 150 items dans un backlog : au-delà de ce nombre, certains items auront été détaillés de manière anticipée et pourront être la source d’une perte d’efficacité dans la mise en place de Scrum.



<!-- new slide -->
## Étapes de construction  

- Les 5 étapes les plus importantes :
  1. Identifier les besoins 
  2. Rédiger les user stories
  3. Prioriser le product backlog
  4. Vérifier la qualité des user stories
  5. Ajouter des critères d’acceptation
<!-- new slide -->
## 1. Identifier les besoins 

![Différences entre le cahier des charges et le product backlog ](/lab-scrum/Exposé-Product-backlog/images/Besoin2.png)*Figure3 :L’importance des items dans le product backlog*

<!-- note -->
- Avant tout, il est nécessaire d’établir la vision du projet, c’est-à-dire de définir clairement l’objectif que le projet doit atteindre et de **lister les différents acteurs**. 
  - ll est important que cette vision soit acceptée et comprise de tous, elle doit faire consensus puisque l’équipe va devoir se rallier derrière le PO pour réaliser ce projet selon cet objectif.
<!-- new slide -->
## 2. Rédiger les user stories

![Différences entre le cahier des charges et le product backlog ](/lab-scrum/Exposé-Product-backlog/images/User_story.png)*Figure3 :LRédiger les user stories*

<!-- note -->
- Ensuite vient le moment de rédiger les users stories en gardant à l’esprit les questions : 
  - Quelles seront les fonctionnalités à créer ? 
  - Dans quel ordre devront-elles être livrées ? À qui sont-elles destinées ?
  - On peut organiser son product backlog par :
    - **thème** : regroupement logique d’un certain nombre de sujets définis par le Product Owner. 
      - Il n’y a pas de règle absolue tant que l’organisation est optimale. 
      - Ces fameux thèmes sont ensuite découpés par **feature**.
    - **feature** (ˈfēCHər) : regroupement de user stories. 
      - Chaque feature va représenter un gros bloc fonctionnel, c’est-à-dire une grosse fonctionnalité sur le produit. 
      - Ces fonctionnalités vont être découpées en **items**, aussi appelés user stories.
    - **user story** : 
      - les user stories – items – tâches ou encore éléments du backlog 
      - sont différentes appellations qui représentent des améliorations, des évolutions, des fixes, des fonctionnalités, des fonctions ou encore des bugs.
    - **sous-tâche** : l’équipe de développement, en scrum par exemple, va découper l’ensemble des items en sous-tâches techniques lors du **sprint planning**, ou encore en **sous-tâches anomalie**.
<!-- new slide -->
## 3. Prioriser le product backlog



![Différences entre le cahier des charges et le product backlog ](/lab-scrum/Exposé-Product-backlog/images/backlog.jpg)*Figure3 :Prioriser le product backlog*

<!-- note -->
- Lorsque le PO priorise le product backlog, il se heurte souvent à un problème commun : 
  - un processus de priorisation vague et incohérent. 
  - En tant que Product Owner, vous recevez quotidiennement des commentaires, de nouvelles idées et des demandes de fonctionnalités de la part de nombreuses parties prenantes et vous ne pouvez pas dire oui à tout le monde. 
  - Vos parties prenantes peuvent être confuses sur le fait que vous ayez choisi de prioriser un item plus qu’un autre et pourraient avoir le sentiment de ne pas avoir assez d’influence sur votre processus de priorisation. 
  - Une étape importante pour résoudre ces problèmes, consiste à standardiser le processus de hiérarchisation. Pour cela, il existe différentes techniques :
    - Moscow
    - Value vs EffoRT
    - ICE
    - RICE
    - WSJF
  - Ces techniques créent une approche reproductible, plus transparente et moins aléatoire de votre priorisation.

## 4. Vérifier le niveau de qualité des user stories

- Le Product Backlog Refinement, aussi connu sous le nom de Backlog grooming, est une pratique Scrum qui a le rôle comme son nom l’indique d’affiner le contenu du product backlog. 
  - C’est un moment idéal pour vérifier la qualité d’une user story avec toute l’équipe et de les remettre en question. 
  - Grâce aux inputs de chacun, le Product Owner pourra affiner les user stories sélectionnées pour le sprint.
  - Avant de lancer une itération (cycle de 1 à 4 semaines), le Product Owner et l’équipe doivent s’assurer que les user stories soient réalisables par une personne et dans une itération.

<!-- new slide -->

## Quels outils peut-on utiliser pour gérer un product backlog ?

![Différences entre le cahier des charges et le product backlog ](/lab-scrum/Exposé-Product-backlog/images/Trello-vs-Jira-2-1.webp)*Figure 10 :outils*

<!-- note -->
- Le product backlog peut être réalisé sur un simple fichier excel mais certains outils facilitent le suivi des user stories comme par exemple JIRA, Trello ou encore Projectboard.
<!-- new slide -->
## Références 
- https://www.unow.fr/blog/le-coin-des-experts/product-backlog-projet-scrum/
- https://www.qrpinternational.fr/blog/glossaire/quest-ce-quun-backlog-definition-etapes-caracteristiques-et-outils/