# Explicatif de mise à jour v3.1.9


## Modifications sur les paramètres utilisateur
- Le symbole de changement de mot de passe a été revu pour une meilleure compréhension dans la gestion des utilisateurs.
- Ajout d'une option par utilisateur pour choisir si le lien de notification email ouvre l'Application dans FileMaker ou depuis le navigateur web par défaut, offrant plus de flexibilité.
![3-1-9_01_1.png](3-1-9_01_1.png)
 

## Tris et filtres des activités et annonces

Il est désormais possible de trier les activités ainsi annonces par colonne en cliquant sur le titre de la colonne. Un symbole de flèche indique le sens du tri.

![3-1-9-02.png](3-1-9_02.png) 

Le symbole de filtre permet d'ajouter ou de supprimer des filtres sur différents éléments. Les filtres sont cumulables.

![3-1-9-04.png](3-1-9_04.png)


## Cartographie interactive sur navigateur web
La cartographie interactive est désormais fonctionnelle depuis un navigateur web. Il est maintenant possible de l'utiliser et de la configurer comme sur l'Application.


## Panneau "commentaires" - module annonce
Le panneau "commentaires" pour le traitement d'une annonce est désormais fonctionnel sur navigateur Web.


## Amélioration de la WebApp
Le tri des activités de la WebApp pour les viewers a été modifié pour correspondre au tri de l'application administrateur.


## Archivage des audits internes
Il est désormais possible de définir une option "archivée" sur un statut d'audit interne. Dès lors qu'un audit passera dans ce statut, il sera verrouillé complètement et ne pourra être déverrouillé que par un administrateur.

![audit_parameter.png](audit_parameter.png)


## Améliorations des notifications par email
Les notifications par email indiquent désormais plus d'informations pertinentes et offre une meilleure lisibilité.


## Diverses corrections de bugs
- Ajout de document en favori dans la WebApp pour un compte admin
- Suppression de l'affichage d'un document expiré dans la WebApp si l'utilisateur l'a ajouté en favori
- L'erreur "login déjà utilisé" n'apparaît plus lors du changement de mot de passe dans l'Application
- L'Application charge correctement après le changement de mot de passe forcé au lancement
- Modification du message d'erreur en cas d'envoi d'annonce depuis la WebApp si aucun mail n'est associé au compte


## Mise à jour sécuritaire de la WebApp
Le framework et les librairies de la WebApp ont été mis à jour pour assurer une navigation sûre et protégée.

