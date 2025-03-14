# Mise à jour v240722

## Modification de la notation des versions

Passage sur un système basé sur la date.

## Refonte complète du module d'annonces

### Paramètres : Création et édition des formulaires web (types d'annonces)

Ajout d'un menu spécifique dans les réglages de CertiSoft pour la configuration des différents types d'annonces.

![cs_settings_menu_complaint_types.png](cs_settings_menu_complaint_types.png)

Pour chaque ancien type d'annonce existant, un formulaire a été recréé dans la nouvelle version.

Une mention du statut (point vert) a été ajoutée pour visualiser si le formulaire est actif (mis en ligne) ou non.

![cs_settings_complaint_types_listing.png](cs_settings_complaint_types_listing.png)

Lors du clic sur un type d'annonces, les informations y relatives s'affichent sur la droite.

![imagefull.png](imagefull.png)

Un formulaire est constitué des éléments suivants :
- Un titre
- Un secteur lié automatiquement (optionnel)
- Un état (publié ou non publié)
- Un état
    - Interne : L'identifiant de l'employé est automatiquement saisi
    - Externe : Les coordonnées complètes doivent être saisies
- Une durée en minutes
- Une description
- Des questions
- 

Si le secteur lié est saisi, il sera rempli d'office et ne sera pas modifiable lors de la saisie d'une annonce.

![cs_linked_sektor.png](cs_linked_sektor.png)

Le listing des questions permet de définir la structure du formulaire de manière dynamique et complète.

![cs_panel_questions.png](cs_panel_questions.png)

Il est possible d'indiquer un numéro à chaque question pour définir l'ordre dans lequel elles apparaîtront dans le formulaire web.

L'icône ![cs_icone_fav1](cs_icone_fav1.png) permet de définir quelle rubrique définira le titre de l'annonce dans le listing.
L'icône ![cs_settings_complaint_types_questions_example.png](cs_settings_complaint_types_questions_example.png) montre un exemple d'affichage pour chaque type de question.
Enfin, l'icône ![cs_icon_modify](cs_icon_modify.png) permet de modifier des options spécifiques selon le type de question choisie, telles que :
- Ajouter un complément à la question
- Rendre la question obligatoire
- Indiquer une note max
- Définir les réponses à choix multiples

### Création d'une annonce

La création d'annonces se fait dorénavant uniquement via un formulaire web (version légère). Le bouton "Nouvelle annonce" ouvre la page dans le navigateur par défaut.

![cs_complaint_new.png](cs_complaint_new.png)

### Création d'annonce depuis la version légère

En cliquant sur le bouton ![cs_web_new_complaint_button.png](cs_web_new_complaint_button.png), vous serez désormais invité à choisir le type d'annonce désiré. La description et la durée en minutes sont disponibles.

![cs_web_new_complaint](cs_web_new_complaint.png)

Une fois votre choix effectué, vous pourrez répondre aux différentes questions et ajouter les documents liés en cas de besoin.

![cs_formulaire_complaint](cs_formulaire_complaint.png)

### Exportation d'annonces

L'action déclenchée par le bouton d'exportation a été modifiée afin d'apporter une meilleure expérience utilisateur et correspondre à la nouvelle structure des annonces.
Désormais, un fichier .xlsx est généré avec une feuille par type d'annonces contenant toutes les questions remplies pour ce type.

![cs_complaint_export.png](cs_complaint_export.png)

### Refonte graphique du listing et de l'affichage des annonces

Le visuel du listing et de l'affichage des annonces a été retravailler afin d'apporter une meilleure lisibilité, un design plus moderne et une utilisation plus agréable.

![cs_listing_complaint](cs_listing_complaint.png)

## Correction de bugs

- Correction d'un bug de l'application web qui empêchait la récupération du mot de passe sur la version légère.