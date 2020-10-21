# Chat en ligne

Votre entreprise doit développer une application de discussion instantanée d’équipe.
L’accès utilisateur à l’application devra être authentifié avec un utilisateur et un mot de passe
L’inscription est libre, l’utilisateur devra valider son identité et donner une adresse email valide (serveur de mail configuré sur le serveur Internet).
Une complexité de mot de passe est demandée, l’utilisateur sera informé de la complexité de son mot de passe à la création de celui ci.
Les utilisateurs authentifiés auront la possibilité de créer des salons de discussion.
Ils auront ensuite la possibilité d’ inviter d’autres membres dans ce salon.
L’utilisateur aura la possibilité de changer de salon ( propriétaire ou invité uniquement
Les utilisateurs connectés à ce salon devront pouvoir communiquer (texte) de manière instantanée
Le salon affichera les membres actifs/absents/déconnectés.
L’envoi d’image est autorisé sur le salon, cependant, celles ci seront redimensionnées à 1024 px max. de côté ( sur le plus grand côté ). Elles seront également converties en JPEG.
A la connexion de l’utilisateur, celui récupèrera tous les messages « manqués » pendant son absence.
L’utilisateur aura la possibilité de se déconnecter, et de changer son mot de passe.

## Pour commencer

Allumer les deux datacenters

### Fonctionnalités

> chat en ligne
> notification de rédaction 
> affichage des messages précédents

### à venir

> identification
> mails
> redondance

### Installation

npm install

## Démarrage

node server.js

## Source

https://blog.bini.io/developper-une-application-avec-socket-io/

## Groupe

Flavien Bruet
Jean-Baptiste Calandreau

## Versions

0.1
