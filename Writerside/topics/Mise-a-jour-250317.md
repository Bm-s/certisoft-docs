# Mise à jour v250317

## Refonte complète du module d'indicateurs

Le module indicateur a été entièrement revu afin de fournir une plus grande palette de possibilités aux utilisateurs.

### Listing des indicateurs

La vue a été complètement refaite pour offrir un visuel plus épuré. Désormais, en entrant dans le module indicateur, l'utilisateur arrive sur une liste triable permettant rapidement de consulter si les indicateurs sont à jour. Un triangle de panne en fin de ligne signifie que des relevés sont manquants.

![ind_listing_element.png](ind_listing_element.png)

Une barre de recherche a également été ajoutée. La recherche s'effectue dans les champs désignation, numéro de l'indicateur et description.

Un nouvel indicateur peut être créé avec le bouton "+" en haut à droite de la liste des indicateurs. Une nouvelle ligne avec un identifiant auto-assigné est créée.

![250317_cs_indicator_new.png](250317_cs_indicator_new.png)

En cliquant sur l'indicateur souhaité, la page détail s'ouvre et affiche ses informations.

### Détail d'un indicateur

La vue de détail d'un indicateur est constituée de 2 parties. La partie du haut permet d'indiquer le nom de l'indicateur, son but ainsi que de régler les autorisations d'accès. L'utilisateur responsable sera le seul à recevoir les notifications par e-mail, mais tous les utilisateurs avec le droit de modification pourront ajouter des relevés.

La partie du bas permet de saisir un relevé (clic sur + à droite du tableau) ou de consulter les relevés déjà saisis. Si un relevé possède plusieurs mesures, le tableau indique uniquement le nombre de mesures effectuées.

![ind_detail_releves.png](ind_detail_releves.png)

Enfin, on retrouve un onglet "Paramètres" pour définir les réglages de l'indicateur.

![ind_detail_settings.png](ind_detail_settings.png)

#### Périodicité

La périodicité permet de sélectionner si un instant où une période, cette option permet de choisir si les mesures seront ajoutée avec uniquement une date (instant T) ou une date de début et une date de fin (période).  

![250317_cs_indicator_edit_period_type.png](250317_cs_indicateur_edit_period_type.png)

#### Période d'analyse

La période d'analyse propose plusieurs choix de récurrence et permet de paramétrer le début des relevés ainsi que le jour de rappel.

![ind_detail_setting_period.png](ind_detail_setting_period.png)

Les choix de récurrence peuvent avoir une spécificité : 

*Quotidien, Trimestriel, Semestriel, Annuel* - Nombre de jours avant l'alerte

*Hebdomadaire* - Sélection du jour de la semaine

*Mensuel* - Jour du relevé : premier ou dernier parmi les jours de la semaine

*Libre* - Aucun

Ces paramètres permettront au système de savoir quand créer le rappel par e-mail pour la saisie.

#### Cases à cocher

Deux cases à cocher sont disponibles pour marquer l'indicateur comme archivé et pour choisir de ne pas envoyer de rappel pour cet indicateur (de manière globale) 

![250317_cs_indicator_edit_checkboxes.png](250317_cs_indicator_edit_checkboxes.png)

#### Modèles de mesures

Désormais, plusieurs mesures peuvent être rattachées à un même indicateur.

Au moins un modèle est obligatoire pour pouvoir ajouter un relevé de mesures dans l'indicateur. 

Le modèle de relevé et l'unité sont des champs textes libres pour laisser le choix de paramétrage. Le type est Oui/Non, nombre ou texte et défini ce que l'utilisateur devra rentrer comme mesure.
<br/> 
Il est possible de supprimer un modèle en cliquant sur la corbeille rouge à droite. Attention, cette action est irreversible.

La valeur cible est optionnelle est permet d'indiquer l'objectif de la mesure.

![250317_cs_indicator_edit_modeles.png](250317_cs_indicator_edit_modeles.png)

### Insertion de mesures

Dans l'onglet "Relevés", un nouveau relevé peut être inséré au clic sur le "+" en haut à droite du tableau.

![250317_cs_indicator_measure_new.png](250317_cs_indicator_measure_new.png)

La ou les dates sont pré-insérées automatiquement en fonction des dernières valeurs trouvées. Elles peuvent être modifiées en cas de besoin.

Les mesures sont préparées selon le ou les modèles définis dans les paramètres. Seule la valeur doit être remplie.

Un commentaire peut être ajouté avant de fermer la fenêtre. 

### Suppression de relevé

Un relevé supprimé l'est définitivement avec toutes ses mesures ! 

## Module indicateur de la webapp

Le module indicateur a été modifié pour correspondre au nouveau système. La webapp permet l'insertion rapide et facile de mesures

### Dashboard

Le dashboard affiche la liste des indicateurs ayant des mesures en retard.

Dans le listing des indicateurs, ces indicateurs sont représentés par le nombre d'indicateurs en retard dans le cercle rouge

![250317_cs_web_indicator_list_late.png](250317_cs_web_indicator_list_late.png)

Lors du clic sur un indicateur, le formulaire d'ajout de mesure s'ouvre et pré-insère les dates en fonction des paramètres de cet indicateur et du dernier relevé effectué.
Sur la droite sont affichées les données du dernier relevé en date.

Sur la version mobile, les informations du dernier relevé sont disponibles en cliquant sur le bouton "Afficher les données du dernier relevé".
Les données apparaîtront en texte grisé au-dessus des champs d'insertion du relevé en cours d'insertion.

![250317_cs_web_indicator_new_measure_last_data.png](250317_cs_web_indicator_new_measure_last_data.png)

Des mesures peuvent également être saisies en cliquant en premier lieu sur le module "indicateur", puis en sélectionnant la mesure de son choix. Il n'est par contre plus possible de consulter les mesures saisies depuis la version Web.

## Modifications mineures

- Ajout de normes dans les paramètres
- Correction d'un bug lié aux notifications automatiques par e-mail
- Amélioration des exports en format .xlsx
- Les utilisateurs sont désormais triés par ordre alphabétique lors de leur ajout dans les secteurs d'annonce
- Divers autres corrections de bugs mineurs