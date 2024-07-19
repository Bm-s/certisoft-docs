# Mise à jour v240709

## Modification de la notation des versions

Passage sur un système basé sur la date.

## Refonte complète du module d'annonces

### Création et édition des formulaires web (types d'annonces)

Ajout d'un menu spécifique pour la configuration des différents types d'annonces dans les réglages.

![cs_settings_menu_complaint_types.png](cs_settings_menu_complaint_types.png)

L'ajout, la récupération d'ID et la suppression des types d'annonces sont désormais disponibles dans un menu spécifique.
<br/>
Une mention du statut a été ajoutée pour visualiser si le formulaire est visible par les utilisateurs ou non.

![cs_settings_complaint_types_listing.png](cs_settings_complaint_types_listing.png)

Lors du clic sur un type d'annonces, les informations y relatives s'affichent sur la droite.
<br/>
Il est possible de définir un secteur d'annonce, ceci impliquant un champ non modifiable au moment du remplissage du formulaire.

![cs_settings_complaint_types_sector_dropdown.png](cs_settings_complaint_types_sector_dropdown.png)

Le listing des questions permet de définir la structure du formulaire de manière dynamique et complète.

![cs_settings_complaint_types_questions_listing.png](cs_settings_complaint_types_questions_listing.png)

L'ordre des questions correspond à l'ordre dans lequel elles apparaîtront dans le formulaire web. 

L'icône ![cs_settings_complaint_types_questions_example.png](cs_settings_complaint_types_questions_example.png) montre un exemple d'affichage du type de questions.

Le bouton d'édition permet de modifier des options spécifiques, telles que : un complément à la question, rendre la question obligatoire, une note maximum, les choix de réponses, etc.

### Création d'une annonce

La création d'annonces se fait dorénavant uniquement via un formulaire web. Le bouton "Nouvelle annonce" ouvre la page dans le navigateur par défaut.

![cs_complaint_new.png](cs_complaint_new.png)

### Exportation d'annonces

L'action déclenchée par le bouton d'exportation a été modifiée afin d'apporter une meilleure expérience utilisateur et correspondre à la nouvelle structure des annonces.
Désormais, un fichier .xlsx est généré avec une feuille par type d'annonces, contenant toutes les questions remplies pour ce type.

![cs_complaint_export.png](cs_complaint_export.png)

### Refonte graphique du listing et de l'affichage des annonces

Le visuel du listing et de l'affichage des annonces a été retravailler afin d'apporter une meilleure lisibilité, un design plus moderne et une utilisation plus agréable.

## Modification du formulaire web d'annonces

Le type d'annonces doit être sélectionné avant l'affichage du formulaire. Le formulaire est généré de façon dynamique en fonction de la configuration dans la base de données.

![cs_web_formular_complaint_type_selection.png](cs_web_formular_complaint_type_selection.png)

## Correction de bugs

- Correction d'un bug de l'application web qui empêchait la récupération du mot de passe. 