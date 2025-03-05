# Mise à jour v250317

## Refonte complète du module d'indicateurs

### Création d'un indicateur

Un nouvel indicateur peut être créé avec le bouton "+" en haut à droite du tableau. Une nouvelle ligne avec un identifiant auto-assigné est créée.

![250317_cs_indicator_new.png](250317_cs_indicator_new.png)

En cliquant sur l'indicateur souhaité, la page détail s'ouvre et affiche ses informations. 

La moitié haute de la page permet de modifier les informations de base : le nom, la description, les droits.

La partie basse contient deux onglets : Relevés et Paramètres

### Modification d'un indicateur

Dans l'onglet paramètres, on retrouve différentes options :

#### Périodicité

La périodicité permet de sélectionner un instant où une période, cette option permet de choisir si les mesures seront ajoutée avec uniquement une date (instant T) ou une date de début et une date de fin (période).  

![250317_cs_indicator_edit_period_type.png](250317_cs_indicateur_edit_period_type.png)

#### Période d'analyse

La période d'analyse propose plusieurs choix de récurrence ainsi qu'une date de début des mesures.   

![250317_cs_indicator_edit_period_selection.png](250317_cs_indicator_edit_period_selection.png)

Les choix de récurrence peuvent avoir une spécificité : 

*Quotidien, Trimestriel, Semestriel, Annuel* - Nombre de jours avant l'alerte

*Hebdomadaire* - Sélection du jour de la semaine

*Mensuel* - Jour du relevé : premier ou dernier parmi les jours de la semaine

*Libre* - Aucun

#### Cases à cocher

Deux cases à cocher sont disponibles pour marquer l'indicateur comme archivé et pour choisir de ne pas envoyer de rappel pour cet indicateur (de manière globale) 

![250317_cs_indicator_edit_checkboxes.png](250317_cs_indicator_edit_checkboxes.png)

#### Modèles de mesures

Au moins un modèle est obligatoire pour pouvoir ajouter un relevé de mesures dans l'indicateur. 

Le modèle de relevé et l'unité sont des champs textes libres pour laisser le choix de paramétrage. Le type est Oui/Non, nombre ou texte et défini ce que l'utilisateur devra rentrer comme mesure.
<br/> 
Il est possible de supprimer un modèle en cliquant sur la corbeille rouge à droite. Attention cette action est irreversible. 

![250317_cs_indicator_edit_modeles.png](250317_cs_indicator_edit_modeles.png)

### Insertion de mesures

Dans l'onglet "Relevés", un nouveau relevé peut être inséré au clic sur le "+" en haut à droite du tableau.

![250317_cs_indicator_measure_new.png](250317_cs_indicator_measure_new.png)

La ou les dates sont pré-insérées automatiquement en fonction des dernières valeurs trouvées. Elles peuvent être modifiées en cas de besoin.

Les mesures sont préparées selon le ou les modèles définis dans les paramètres. Seule la valeur doit être remplie.

Un commentaire peut être ajouté avant de fermer la fenêtre. 

### Suppression de relevé

Un relevé supprimé l'est définitivement avec toutes ses mesures ! 

