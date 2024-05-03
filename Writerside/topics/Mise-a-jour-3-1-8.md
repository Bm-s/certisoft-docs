# Mise à jour v3.1.8


## Ajout de champs dans les documents
Nous avons ajouté la possibilité de renseigner deux nouveaux champs par version de document :
- **Auteur** : Permet de renseigner l'auteur du document inséré
- **Date de fin de validité** : Permet de renseigner la date de fin de validité de la version du document
 

## Statut archivé pour les Audits
Les status des audits ont maintenant un statut "archivé". Les audits ayant un statut considéré comme "archivé" ne sont plus modifiables.

![3-1-8-01.png](3-1-8_01.png)

Un audit ayant un statut considéré "archivé" peut être changé par un Admin, il lui sera demandé une confirmation avant de changer le statut.  


## Amélioration de la gestion des Risques et Opportunités 
 Il est possible de limiter l'accès à un risque/opportunité en fonction du "Processus" lié. Seul l'équipe du processus pourra le voir si la case correspondante est cochée.

![3-1-8-02.png](3-1-8_02.png)


## Amélioration des notifications
Le design des notifications mail a été amélioré. Elles sont désormais plus claires et plus faciles à lire.

Les notifications incluent également les documents


## Diverses corrections de bugs
- Le login de la WebApp ne prend plus en compte les espaces insérés avant ou après le nom d'utilisateur
- Le téléchargement de documents depuis la WebApp renvoyait parfois des erreurs 404
- L'envoi de documents avec le formulaire d'annonce de la WebApp se fait désormais correctement
- Lors du chargement du module "Point de la norme" dans l'Application, la norme sélectionnée est désormais indiquée.
- Les comptes Admin n'ont plus de problèmes de droits sur certains éléments 
