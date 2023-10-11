# Diagramme de Gantt
Le diagramme de Gantt, couramment utilisé en gestion de projet, est l'un des outils les plus efficaces pour représenter visuellement l'état d'avancement des différentes activités (tâches) qui constituent un projet. La colonne de gauche du diagramme énumère toutes les tâches à effectuer, tandis que la ligne d'en-tête représente les unités de temps les plus adaptées au projet (jours, semaines, mois etc.). Chaque tâche est matérialisée par une barre horizontale, dont la position et la longueur représentent la date de début, la durée et la date de fin. Ce diagramme permet donc de visualiser d'un seul coup d'œil :

Les différentes tâches à envisager
_ La date de début et la date de fin de chaque tâche
_ La durée escomptée de chaque tâche
_ Le chevauchement éventuel des tâches, et la durée de ce chevauchement
_ La date de début et la date de fin du projet dans son ensemble

En résumé, un diagramme de Gantt répertorie toutes les tâches à accomplir pour mener le projet à bien, et indique la date à laquelle ces tâches doivent être effectuées (le planning).

## Diagramme de Gantt : Suivi des études


```mermaid
gantt
    title Gantt Diagram Suivi des études
    dateFormat  YYYY-MM-DD
    excludes weekends
    section Accueil
    Page d'accueil           :a1, 2024-01-15, 1d
    section QCM
    Types de QCM     :b1, 2024-01-15, 1d
    Questions aléatoires : 2d
    Demande d'inscription : 1d
    Envoi du CV par mail : 1d
    section Connexion
    Connexion      :a3, 2024-03-11  , 1d
    Inscription      : 1d
    Mise en place de la connexion: 3d
    Mise en place de la connexion: 5d
    section CV de compétences
    CV      :a4, 2024-03-26 , 2d
    Téléchargement du CV      : 1d
    Envoi par mail du CV : 2d
```
2024-03-11
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