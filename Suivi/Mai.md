# Mai 

## Lundi 3 Mai
- Nathan : 
  - Mise en place d'une page covid, contenant les dernières informations sur la covid en France ou par région

- Baptiste
    - Finalisé le netoyage de mes branches et de la refacto pour le merge (branche : feat/improvment_and_refactor )
    - fix sur un cmposant : Medicine
    - commencé a travailler sur le suivi de l'imc et prise en mains de VueChartJs/chartJS.
    - avancé sur la page de l'imc : list avec un pannel et un selecteur de la durée

- Binome
    - Fait les merges du jour

## Mardi 4 Mai
- Nathan : 
  - Continuation de la page covid, utilisation de [CoronavirusAPI-France](https://github.com/florianzemma/CoronavirusAPI-France) , pour les données journalières de la covid.

## Lundi 10 Mai
- Nathan :
  - Merge de la page covid,
  - Mise en place d'une page de notification, qui a pour but de rappeler l'utilisateur de suivre les traitements de son pillulier si celui-ci est actif.

## Mardi 11 Mai
- Nathan :
  - Finalisation de la page notification,
  - Utilisation de [BASE DE DONNÉES PUBLIQUE
DES MÉDICAMENTS](https://base-donnees-publique.medicaments.gouv.fr/telechargement.php) , pour récolter les données sur les médicaments. 

## Lundi 17 Mai
- Baptiste
  - travaillé sur la partie follow up

- Nathan
  - travaillé sur la mise en place d'une traduction du site web en englais 

## Mardi 18 Mai
- Baptiste
  - Urgent -> refacto de la page Medicine : Découverte d'un bug, certaines données n'était pas les bonnes en fonctione des élément de la listes. Il doit y avoir un chargement spécial pour ce composant liste car il ne semblait pas tout charger. Donc j'ai enlever mon composant medicine Detail de la liste, je ne l'utilise plus que sur la page éponyme, et j'ai récréé un affichage d'un details du medicament sur l a liste sans sous composant

- Binome
  - merge de certaines branche Notification -> develop

- Nathan
  - Utilisation après recherche de i18n (Internationalization and localization) pour commencer la traducation du site web, découverte d'un bug dans la page Medicine.

## lundi 24
  Pentecote

## Mardi 25 Mai
  - Baptiste
    - Travaillé sur le front pour le suivi : je suis en train d'implementer mon composant "facade" qui fait l'intermediaire entre le LineChart et le composant FollowUp
  - Nathan
    - Traduction de chaque page en anglais sur le site. 

## Mercredi 26 Mai
  - Baptiste
    - travaillé sur le back : reflexion pour les calcul pour la récupération de certaines données

  - Binome 
    - Merge de traduction -> develop

  - Nathan
    - Finalisation de la traduction de chaque page du site. 

## Lundi 31 Mai
  - Baptiste
    - Créé un page spécifique pour manipuler et tester ma "facade" pour l'utilisation de vue chart js
    - Continué et réussi a faire un axe d'abscisse variable en fonction des : semaine, mois, semestre, année et un nombre de jour variable
    - réussi a afficher deux axe d'ordonnées avec des legende différentes

  - Nathan
    - Mise en place d'une version docker du front
    - Début de la mise en place d'une version docker du back 
