# Site web de Data for Good

Ce dépôt héberge le code derrière le site http://dataforgood.fr/. Vous pouvez le modifier pour mettre à jour les informations sur vous-mêmes et sur les projets auxquels vous avez participé.

# Contribution

## Projets
La liste des projets est disponible dans le dossier [_projects](https://github.com/dataforgoodfr/dataforgoodfr.github.io/tree/master/_projects).

À titre d'exemple, voici la structure d'une page décrivant un projet :
```
---
layout: project
title: Adoptez-moi
description: Un bot Twitter qui diffuse des informations sur des animaux à adopter.
season: 1
repository: https://github.com/dataforgoodfr/batch1_adoptez-moi
image: adoptez-moi.jpg
---

Pour augmenter la visibilité des animaux qui attendent d'être adoptés, le bot [Adoptez-moi](https://twitter.com/Adoptez_Moi) récupère les informations de chiens et de chats qui patientent sur le site de la SPA puis les partage sur Twitter.
```

Les images doivent être stockées dans le dossier [/img/projects](https://github.com/dataforgoodfr/dataforgoodfr.github.io/tree/master/img/projects), idéalement en deux formats : 450x300 px et 900x600 px dans les dossiers correspondants.

## Membres
La liste des volontaires est disponible le dossier [_members](https://github.com/dataforgoodfr/dataforgoodfr.github.io/tree/master/_members).

À titre d'exemple, voici la structure de la présentation d'un membre :
```
---
fullname: Frédéric Bardolle
twitter: seiteta
linkedin: fbardolle
github: seiteta
role: Data Scientist
avatar: frederic-bardolle.jpg
projects:
    - 0_algotransparency
    - 1_adoptez-moi
---
```

Les images doivent être stockées dans le dossier [/img/members](https://github.com/dataforgoodfr/dataforgoodfr.github.io/tree/master/img/members), idéalement en format 400x400 px.

Les projets doivent être nommés comme les fichiers du dossier [_projects](https://github.com/dataforgoodfr/dataforgoodfr.github.io/tree/master/_projects) pour que Jekyll puisse retrouver qui a fait quoi.
