.. _profil_service_consulte_interne:

########################
SERVICE CONSULTÉ INTERNE
########################

Description
===========

C'est le profil utilisé pour les services consultés internes à la commune. Il va leur permettre :

- de répondre directement depuis le logiciel aux consultations de service qui leurs sont adressés ;
- de voir les avis qui avaient été rendus ;
- de faire des exports CSV ;
- de visualiser les DA sur lesquels ils ont été consultés ;
- de visualiser les pièces sur lesquels ils ont été consultés.


L'utilisateur qui a ce profil doit forcément être rattaché à un ou plusieurs services pour pouvoir visualiser des dossiers et des demandes d'avis.


Fonctionnalités disponibles
===========================

Tableau de bord
---------------

Tableau de bord innaccessible : redirection automatique vers la liste des demandes d'avis en cours.

Menu
----

.. image:: menu_consuint.png

Rubrique *Autorisation*
-----------------------

*Dossiers d'autorisation*
#########################

- Visualiser la liste des dossiers d'autorisation de la commune.
- Accéder à la fiche de visualisation du dossier d'autorisation.

Actions identiques à celles du profil "service consulté" (cf :ref:`Rubrique autorisation<profil_service_consulte_rubrique_autorisation>`)

Rubrique *Instruction*
----------------------

Recherche
#########

- Visualiser la liste des dossiers d'instruction de la collectivité de l'instructeur connecté ou de toutes les collectivités si l'instructeur appartient à la collectivité multi.
- Rechercher des dossiers d'instruction en fonction de plusieurs critères.
- Accéder aux dossiers d'instruction dans le SIG.
- Accéder à la fiche de visualisation d'un dossier d'instruction.

.. sidebar:: Note :

    Les actions SIG sont disponibles si celui-ci est paramétré pour la collectivité du dossier d'instruction.

Action(s) disponible(s) par onglet :

  - *DI* :

    - Accéder au dossier d'instruction dans le SIG.
    - Afficher l'édition de récapitulatif du dossier d'instruction.

  - *Pièce(s)* :

    - Visualiser la liste des pièces du dossier d'instruction.
    - Télécharger le fichier d'une pièce.
    - Télécharger toutes les pièces du dossier d'instruction.

  - *Dossiers liés* :

    - Visualiser le dossier d'autorisation.
    - Visualiser la liste des dossiers d'instruction portant sur la même autorisation.
    - Visualiser la liste des dossiers d'instruction liés.
    - Visualiser la liste des dossiers sur lesquels un lien vers le dossier courant a été établi.
    - Visualiser la liste des dossiers d'instruction liés géographiquement.
    - Accéder à chacun de ces dossiers.

Rubrique *Contentieux*
----------------------

Tous Les Recours
################

Voir :ref:`Tous Les Recours<contentieux_tous_les_recours>` dans la section
contentieux.

Rubrique *Demandes D'avis*
--------------------------

Actions identiques à celles du profil "service consulté" (cf :ref:`Demandes d'avis<profil_service_consulte_rubrique_demande_avis>`)
