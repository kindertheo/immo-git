# SPRINT 0

## Choix des techno à utiliser

Backend : Symfony5

Front : VueJS

DB : Postgres


## Découpages de tâches

Tâche 1 : Création du Repository sur Github

Complexité : 0.5

Tâche 2 : Création du projet Symfony avec Symfony Flex

Complexité : 0.5

Tâches 3 : Création des utilisateurs 

- Création de l'entité UserEntity
- Création du controller UserController
- Création de l'authentificator
- Mise en place du CRUD pour l'administrateur
- Mise en place des droits(CRUD, changer les droits d'un utilisateur)
    - Les visiteurs
    - Les acheteurs
    - Les vendeurs
    - Les conseillers
    - Les administrateurs
- Lors de la création du compte, le mot de passe n'est pas choisi par l'utilisateur mais généré automatiquement et envoyé par mail
- Mise en place d'un service de changement de mot de passe
- Mise en place d'un service de mot de passe oublié

Complexité : 55

Tâches 4 : Création du module d'annonces

- Création de l'entité AnnonceEntity
- Une annonce doit contenir : 
    - Adresse
    - Photos (max 6)
    - Description
    - Données quantitatives
        - Taille m2
        - Nombre de pièces
        - Nombre de chambres
        - Nombre de salles de bain
    - Liste d'éléments important du bien
    - Avis du conseiller
- Permettre plusieurs états à l'entité Annonce (En vente/Vendu)
- Création du controller AnnonceController
- Ajouter le CRUD dans AnnonceController
- Mise en place du système des droits
- Adapter l'entité UserEntity

Complexité : 45


Tâches 5 : Création du module de facturation

- Création de l'entité FactureEntity
- Création du controller FactureController
- Lié l'entité Facture à l'entité Annonce
- Création du générateur de PDF

Complexité : 75

Tâches 6 : Création de suivi 

- Création d'une liste avec tout les projets liés à un vendeur/conseiller
- Mise en place d'un suivi avec une barre de chargement pour expliquer à l'utilisateur le déroulement de la vente

Complexité : 35

Tâches 7 : Système de messagerie
- Mise en place de pages de contacts sur chaque annonces/suivi pour contacter le conseiller/vendeur qui gère l'annonce
- Création du controller MessageController
- Création de l'entité MessageEntity
- Ajout de méthodes pour gérer l'envoi des messages
- Mise à jour des vues
- Ajout d'une icon de notification pour afficher les nouveaux messages

Complexité : 50

Tâches 8 : Création de proposition de vente
- A l'aide du système de messagerie, le modifier afin de créer des propositions de vente et contacter la personne qui gère le bien.
- Ajouter une option "Proposer une offre" sur la page des annonces
- Création du controller PropositionController
- Création de l'entité PropositionEntité

Complexité : 30


## Organisation des sprints

Chaque sprint durera 1 semaine

A la fin de chaque sprint, nous ferons une reviews afin d'améliorer le dérouelement du prochain sprint


SPRINT1 : Tâche 1, 2 et 3

SPRINT2 : Tâche 4, 5

SPRINT3 : Tâches 6, 7, 8