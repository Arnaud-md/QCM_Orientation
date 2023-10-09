# Diagramme de Gantt
Le diagramme de Gantt, largement utilisé en gestion de projet, est un outil efficace pour visualiser l'avancement des différentes activités d'un projet. La colonne de gauche énumère les tâches, tandis que la ligne d'en-tête représente les unités de temps (jours, semaines, mois). Chaque tâche est représentée par une barre horizontale indiquant la date de début, la durée, et la date de fin. Le diagramme offre une vue rapide de :

Les tâches à réaliser
Les dates de début et de fin de chaque tâche
La durée estimée de chaque tâche
Le chevauchement éventuel des tâches et sa durée
Les dates de début et de fin du projet dans son ensemble
En résumé, le diagramme de Gantt liste toutes les tâches nécessaires pour achever le projet et indique quand elles doivent être réalisées (le planning).

## Diagramme de Gantt : Suivi des études


```mermaid
gantt
    title Gantt Diagram Suivi des études
    dateFormat  YYYY-MM-DD
    excludes weekends
    section QCM
    Page d'accueil                  :a1, 2024-01-15, 1d
    Mise en place du QCM            :after a1  , 2d
    Mise en place du formulaire d'inscription : 2d
    Intégration à la base de données : a2, 2024-03-11, 5d
    Génération de CV de compétences : 3d
    section Forum de discussion
    Mise en place du forum          :a3, 2024-03-21  , 2d
    Participation au forum          : 1d
    section Liste des entreprises
    Descriptif des entreprises      :a4, 2024-03-26 , 3d
    Liens vers les entreprises       : 1d
```

```mermaid
gantt
    title Gantt Diagram Suivi des études
    dateFormat  YYYY-MM-DD
    excludes weekends
    section QCM
    Page d'accueil           :a1, 2024-01-15, 1d
    Mise en place du QCM     :after a1  , 2d
    Mise en place du formulaire d'inscription : 2d
```

```mermaid
gantt
    title Gantt Diagram Suivi des études
    dateFormat  YYYY-MM-DD
    excludes weekends
    section QCM
    Intégration à la base de donnée : a2, 2024-03-11, 5d
    Génération de CV de compétences : 3d
    section Forum de discussion
    Mise en place du forum      :a3, 2024-03-21  , 2d
    Mise en place du forum      : 1d
    section Liste des entreprises
    Descriptif des entreprises      :a4, 2024-03-26 , 3d
    Liens vers les entreprises      : 1d
```