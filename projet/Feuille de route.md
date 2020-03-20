---
Projet : Chemins de la Transition
Equipe : Feuille de route
Contributeur : Pierre Bouvier-Muller
Crédit : CC-BY
Version : 1
---

Ce document a pour vocation à partager la feuille de route du développement de la plateforme des [Chemins de la Transition](http://lescheminsdelatransition.org/).

## Périmètre
La plateforme des Chemins de la Transition a pour vocation à rendre visible des lieux en transition et leurs activités, à faciliter le cheminement des apprenants, leur mise en lien avec des expériences en transition existantantes et à créer des parcours de découverte, d'apprentissage et de formation sur des thématiques spécifiques (découverte, régionale/géographique, métier, etc...) => pas clair ce qui est entre parenthèse.

Nous adoptons une stratégie de développement dite agile, avec une feuille de route itérative dont la création se fait par le développement de versions successives.

## Fonctionnalités
La caractéristique principale (qui est aussi une des principales contraintes) est que cette plateforme est fondée sur des technologies intéropérables. C'est à dire qu'on aura la possibilité d'héberger plusieurs instances de la plateforme (une par région par exemple) et que celles-ci pourront dialoguer les unes avec les autres.
Cette caractéristique permet à chaque région d'exprimer sa singularité (charte graphique, valeur) et donc de mettre en valeur son activité, sans pour autant travailler en vase clos dans un environnement fermé.

### Version 1: Rendre visible
Cette première version, c'est la base, les fonctionnalités sans lesquelles on ne pourrait pas développer les suivantes.
Grâce à cette version :
- En tant qu'accueillant, je peux rendre visible mon lieu sur la carte et y renseigner les informations qui le décrivent, concernent mon accueil, les activités et événements (découverte, apprentissages, formations) que je propose et leur modalités.
- En tant que chemineur, je peux renseigner des lieux. Ceux-ci ne m'appartiennent pas, mais je peux les cartographier pour participer. => Pas clair, cela dit on comprend : Les chemineurs peuvent contribuer à la documentation des lieux ... A mon avis, ca suppose des mécanismes de contribution de type pull request, ce qui serait topissime. 

MR: Idem, pas clair, que le chemineur puisse commenter un lieu (ou proposer des ajouts - à valider par lieu ou par modérateur) me semble intéressant, qu'il puisse créer des fiches lieux, il ne me semble pas que ca fasse partie de la V1 ni des priorités de développement (?). En revanche, mais je crois qu'on avais mis ça de coté sur le V1, mais qu'on puisse avoir un profil utilisateur pour les chemineurs avec possibilité pour lui d'avoir une "fiche perso"  avec ses compétences et ses "envies / recherches" me semblerait intéressant. On reste dans le rendre visible, coté chemineur - et on prépare la création de "portefeuille de compétences" évolutifs et l'intégration d'Open Badges (ce qui peut aussi intéresser des "financeurs").  

Cette version est assez similaire à ce que propose TWIZA, sauf que ce ne sont pas des lieux de chantiers participatifs qui sont référencés mais des lieux formations.
Il y 2 profils types :
- Chemineurs (carto)
- Accueillant

### Version 2: Agenda
Dans cette seconde version, on ajoute la fonctionnalité Agenda, qui permet aux accueillants de renseigner leurs formations / événements dans une base de données spécifiques (et pas dans des champs textes comme le propose la première version). 

MR: et/ou calendrier de disponibilité pour accueil du public (qui peut être indépendant des "formations") - jours et horaires + "modalité de disponibilité" ? Est-ce que dans cette version il y a possibilité d'intégrer outil genre bus sémantique qui permet d'aller scroller les sites des accueillants et aspirer les éventuelles foramtions/événements proposés 

### Version 3: Réservation
Dans cette troisième version, les chemineurs ont la possibilité de réserver directement leur formation et donc de se faire un calendrier en ligne. MR: + possibilité de payer en ligne le cas échéant // Est-ce que cela intègre du coup des "modules de discussion / échange" entre accueillant et chemineur? + validation de réservation...
Ce qui pose les briques  de la version suivante : la création de parcours de formation

### Version 4: Parcours de formation
Dans cette nouvelle version, il est possible de créer des parcours thématiques (ou géographique en mode découverte par exemple).

### Version 5: A définir
Ajouter des fonctionnalités sociales, recueil de feedback, notes, messagerie, etc... à conceptualiser en fonction des retours. Gamifier la plateforme ;)
