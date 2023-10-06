# User journey

## Définition

Un diagramme de user journey decrie à un haut niveau de détail les étapes que les différents utilisateurs prennent pour compléter une tâche spécifique dans un système, une application ou un site web. Cette technique montre le workflow actuel et révèle les zones d'amélioration à aller chercher.

```mermaid
journey
    title Application GrePhoto
    section Accueil Demo
      Affichage: 5
      Click sur une photo: 3
      Affichage de l'image seule: 1
    section Création d'un compte
      Formulaire de saisie: 5
      Validation du formulaire: 3
      Envoyer le formulaire: 5
```

## Objectif

Avoir une vision rapide des étapes réalisées par les utilisateurs et donc découvrir des zones non utilisées ou des étapes inutiles.
Avoir un aperçu rapide du ressenti des utilisateurs.

## En complément

Un user journey pourra être complété par une description écrites des étapes, des captures d'écran, des vidéos, des interviews utilisateurs, des données d'analyse, des données de performance, des données de satisfaction, etc.

## Projet QCM_Orientation

```mermaid
journey
    title Application QCM_ORIENTATION
    section Accueil
      Choix repondre a un questionnaire: 5: Me
      Choix aller au forum de discussion: 3: Me
      Choix se renseigner sur les entreprises: 1: Me, Cat
    section QCM
      Formulaire d'inscription: 5: Me
      Choix du QCM: 3: Me
      Répondre au QCM: 1: Me, Cat
      Télécharger CV de compétences: 1: Me, Cat
    section Forum de discussion
      Poster un message: 5: Me
    section Liste d'entreprises
      Lire descriptif: 5: Me
      click sur le lien vers le site web: 5: Me
```

