# Benchmark
En informatique, un benchmark est un banc d'essai permettant de mesurer les performances d'un système pour le comparer à d'autres.
## Benchmark Suivi des études
_ L'application utilise NodeJS.

Node.js est une plateforme logicielle libre en JavaScript, orientée vers les applications réseau évènementielles hautement concurrentes qui doivent pouvoir monter en charge.

_ Le langage de programmation est TypeScript.

TypeScript est un langage de programmation libre et open source développé par Microsoft qui a pour but d'améliorer et de sécuriser la production de code JavaScript. Il s'agit d'un sur-ensemble syntaxique strict de JavaScript (c'est-à-dire que tout code JavaScript correct peut être utilisé avec TypeScript). Le code TypeScript est transcompilé en JavaScript, et peut ainsi être interprété par n'importe quel navigateur web ou moteur JavaScript. TypeScript a été cocréé par Anders Hejlsberg, principal inventeur de C#.

_ L'application n'utilise pas Vite.

Vite-Vanilla est un outil Frontend.

_ La partie Back-end est séparée de la partie Frontend

_ Le système de gestion de base de donnée est SQLite

### Les besoins de l'application (objectifs quantifiables)

_ page d'accueil qui redirige vers les différentes interfaces développant les fonctionnalités de l'application (répondre à un QCM, s'inscrire en répondant à un formulaire, générer un CV de compétences, participer au forum de discussion et se documenter sur une liste d'entreprises)

_ interractions avec la base de donnée pour les parties QCM et forum

_ choix de l'application :
Le formulaire d'inscription est généré après avoir répondu à un QCM. Une adresse mail est demandée.

_ le CV généré est envoyé à l'adresse mail saisie.

_ des statistiques sont générées à partir des informations de la base de donnée.

### Critères de performance

_ La partie : interractions avec la base de donnée est utile pour les statistiques de la page d'accueil. Elle sert aussi à générer une liste de 10 questions aléatoires pour chaque QCM. Les questions sont enregistrées en base de donnée.

--> Discussion en cours : Faut-il enregistrer les messages postés en base de donnée ou juste le nombre de messages ?


