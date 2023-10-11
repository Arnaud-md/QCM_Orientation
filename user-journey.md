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
      Choix se connecter: 5: Me
      Choix Télécharger un CV: 3: Me
      Choix Liste d'entreprise: 1: Me, Cat
      Choix Répondre à un QCM: 1: Me, Cat
    section Connexion
      Ajout d'un nouvel utilisateur: 5: Me
      Valider l'inscription: 1: Me, Cat
      Se connecter à partir d'un email et d'un mot de passe: 3: Me
    
```
```mermaid
journey
    title Application QCM_ORIENTATION
    section QCM
      Affichage de la coupe obtenue pour chacun des QCM: 5: Me
      Choix du QCM: 5: Me
      Affichage qui dit si l'utilisateur est connecté: 5: Me
      Validation des réponses: 5: Me
      Demande d'inscription: 5: Me
      Envoi du CV par mail: 5: Me
    section Liste d'entreprises
      Affichage des logos: 5: Me
      click sur le lien vers le site web: 5: Me

```
```mermaid
journey
    title Application QCM_ORIENTATION
    section Téléchargement du CV
      Affichage de la coupe obtenue pour chacun des CV: 5: Me
      click sur le CV à télécharger: 5: Me

```
