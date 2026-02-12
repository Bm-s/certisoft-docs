# Mise à jour v251208

## Modifications générales

### Modification de la manière d'affecter une valeur cible à un indicateur

Dans les indicateurs, nous avons repensé la manière de saisir les valeurs cibles. L'objectif est de pouvoir créer une période pour chaque modèle de relevé en indiquant la valeur cible à atteindre.

Ainsi, il est possible de paramétrer la valeur mois par mois ou année par année.

Enfin, il est possible d'actualiser la totalité des valeurs cibles par rapport aux mesures déjà saisies en cliquant sur le bouton lié. 

![indicators_target_value.png](indicators_target_value.png)

![indicators_target_value_2.png](indicators_target_value_2.png)

### Ajout d'un champ de recherche sur la sélection d'utilisateur

Dans l'ensemble du logiciel, lors de la sélection d'un utilisateur, vous avez la possibilité de filtrer la liste en fonction d'un critère de recherche.

![image.png](user_add_filter.png)

### Duplication d'audit

Vous avez désormais la possibilité de dupliquer un audit complet depuis le listing des audits internes en cliquant sur le bouton en fin de ligne.

![audit_duplicate.png](audit_duplicate.png)

### Terminer une action

Le statut d'une action était forcément dépendant des tâches liées.
Une action peut être terminée même si elle ne contient pas de tâches, ou que toutes les tâches ne sont pas terminées.

![terminate_action.png](terminate_action.png)

### Tâches visibles pour les utilisateurs liés

Les utilisateurs responsables d'une tâche, mais ne figurant pas dans l'action, ont désormais la possibilité de visualiser cette dernière depuis l'application web.

### Impression de la cartographie

La cartographie peut désormais être imprimée avec la date et l'heure de l'impression, ainsi que le nom de l'utilisateur ayant lancé l'impression.

![cartoghraphie_print.png](cartoghraphie_print.png)

### Notifications

Lors de la mise en ligne d'une nouvelle notification depuis le panneau "Gestion des dernières informations", une notification est automatiquement envoyée le lendemain matin en même temps que la notification journalière. 

### Bugs corrigés

- La récupération d'un mot de passe fonctionne à nouveau depuis l'application Web.
- Les utilisateurs se connectant en SSO (Single Sign-On) n'ont plus la possibilité de changer leur mot de passe.
