# SPRINT1

## Tâches à réaliser 

Découpage de la tâche 5, 6 et 7

Ces tâches sont : 

    Tâches 5 : Création du module de facturation

    Tâches 6 : Création de suivi 

    Tâches 7 : Système de messagerie


---------------------------------------------------

Tâches 5 : Création du module de facturation

- Création de l'entité FactureEntity
- Création du controller FactureController
- Lié l'entité Facture à l'entité Annonce
- Lié l'entité facture à l'entité Utilisateur
- Création du générateur de PDF
- Création des méthodes renderPdf(), GeneratePdf(), SavePdf(), DownloadPdf(), 

Complexité : 75

---------------------------------------------------

Tâches 6 : Création de suivi 

- Création d'une liste avec tout les projets liés à un vendeur/conseiller
    - Création du controller suivi
    - Création de l'entité suivi
    - Ajout des différentes étapes à suivre dans la table Suivi
    - Conditions sur les documents requis pour terminer chaque étapes
    - Etapes de validation des documents

- Mise en place d'un suivi avec une barre de chargement pour expliquer à l'utilisateur le déroulement de la vente
    - Récupération de l'étape 
    - Création de la barre d'évolution de la vente


Complexité : 50

-----------------------------------------------------

Tâches 7 : Système de messagerie
- Mise en place de pages de contacts sur chaque annonces/suivi pour contacter le conseiller/vendeur qui gère l'annonce
    - Création du controller MessageController
    - Création de l'entité MessageEntity
    - Ajout de méthodes pour gérer l'envoi des messages
    - Mise à jour des vues
    - Ajout d'une icon de notification pour afficher les nouveaux messages

Complexité : 50

