# Mise à jour v240709

## Modification de la notation de version

Passage sur un système basé sur la date

## Refonte complète du module annonces

### Création et éditions des formulaires web (types d'annonces)

Ajout d'un menu spécifique pour la configuration des différents types d'annonces dans les réglages.

![cs_settings_menu_complaint_types.png](cs_settings_menu_complaint_types.png)

L'ajout, la récupération d'ID et la suppression des types sont désormais déplacés dans ce menu spécifique.
<br/>
Un indicateur de statut a été ajouté pour une meilleure visualisation de la disponibilité publique des types d'annonces.

![cs_settings_complaint_types_listing.png](cs_settings_complaint_types_listing.png)

Lors du clic sur un type, ses informations s'affichent sur la droite.
<br/>
Il est possible de définir un secteur d'annonce, qui sera non modifiable lors du remplissage du formulaire.

![cs_settings_complaint_types_sector_dropdown.png](cs_settings_complaint_types_sector_dropdown.png)

Le listing des questions permet de définir la structure du formulaire de manière dynamique et complète.

![cs_settings_complaint_types_questions_listing.png](cs_settings_complaint_types_questions_listing.png)

L'ordre des questions correspond à l'ordre dans lequel elles apparaîtront dans le formulaire web. 

L'icone ![cs_settings_complaint_types_questions_example.png](cs_settings_complaint_types_questions_example.png) montre un exemple d'affichage du type de question.

Le bouton d'édition permet de modifier des options spécifiques, comme un complément à la question, rendre la question obligatoire, une note maximum, les choix de réponses, etc.

### Création d'une annonce

La création d'annonce se fait maintenant uniquement via un formulaire web. Le bouton "Nouvelle annonce" ouvre la page dans le navigateur par défaut.

![cs_complaint_new.png](cs_complaint_new.png)

### Exportation d'annonces

Le comportement du bouton d'exportation a été modifié pour une meilleure expérience utilisateur et pour correspondre à la nouvelle structure des annonces.
Désormais, un fichier .xlsx est généré avec une page par type d'annonce, contenant toutes les questions remplies pour ce type.

![cs_complaint_export.png](cs_complaint_export.png)

## Modification du formulaire web d'annonces

Le type d'annonces doit maintenant être sélectionné avant l'affichage du formulaire. Le formulaire est généré dynamiquement en fonction de la configuration dans Filemaker.

![cs_web_formular_complaint_type_selection.png](cs_web_formular_complaint_type_selection.png)

## Correction de bugs

- Correction d'un bug de la webapp qui empêchait la récupération du mot de passe. 