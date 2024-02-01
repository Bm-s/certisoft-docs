# Notes de mise à jour

### v3.1.9

***Viewer***

Affichage optimisé : 
  - Les documents expirés ne seront plus affichés dans les favoris, garantissant une expérience utilisateur plus fluide

Tri intelligent : 
  - L'ordre de tri des activités a été harmonisé avec celui de l'application, offrant une cohérence accrue

Sécurité renforcée : 
  - Mise à jour importante de la sécurité pour la WebApp, assurant une navigation sûre et protégée


***User***

Personnalisation des annonces : 
- Nouvelle fonctionnalité permettant de trier les annonces par colonne et de les filtrer selon divers critères pour une recherche facilitée

Correction de bugs : 
- Le message d'erreur "login déjà utilisé" lors du changement de mot de passe n'apparaît plus
- L'application charge correctement après le changement de mot de passe forcé au lancement

Expériences enrichies : 
- Introduction de la cartographie interactive sur WebDirect
- Amélioration des informations et notifications par email

***Admin***

Gestion des favoris : 
- Correction d'un bug lié à l'ajout de documents en favoris via la WebApp.

Messages d'erreur explicites : 
- Les messages d'erreur ont été clarifiés pour les cas d'envoi d'annonce sans email associé au compte depuis la WebApp.

Interface utilisateur améliorée : 
- Le symbole de changement de mot de passe a été revu pour une meilleure compréhension dans la gestion des utilisateurs. 
- Une nouvelle option permet désormais à chaque utilisateur de choisir si le lien de notification email doit ouvrir l'app FileMaker ou WebDirect, offrant plus de flexibilité.

---

### v3.1.8

***Viewer***
- Amélioration du téléchargement de documents qui renvoyait parfois des erreurs 404
- Les espaces sont maintenant automatiquement enlevés avant et après le login pour réduire les erreurs de connexion
- Correction de l'envoi de documents depuis le formulaire d'annonce

***User***
- Les notifications indiquent désormais les documents qui ont été mis à jour
- Vous pouvez désormais renseigner l'auteur et la date de fin de validité d'un document (par version)
- Il est possible de limiter l'accès à un risque/opportunité en fonction du "Processus" lié. Seul l'équipe du processus pourra le voir
- Nous avons rajouter un statut "archivé" dans les réglages du module "Audit interne". Les audits archivés ne sont plus modifiables
- Les notifications ont un nouveau design pour les rendre plus lisibles
- Lors du chargement du module "Point de la norme", la norme sélectionnée est désormais indiquée.

***Admin***
- Les comptes "Admin" peuvent désormais correctement tout voir et ne sont plus bloqués pour certains éléments

---

### v3.1.7

***Viewer***
- Le mot de passe et le login sont désormais insérés automatiquement
- La version de document téléchargée est désormais la bonne quand un document est en cours de validation

***User***
- Déploiement d'un correctif qui ne permets plus aux comptes "Viewer" de tenter de se connecter sur l'application complète
- Ajout du lien direct vers l'application Web dans les notifications pour les viewers
- Ajout de notifications liées à certains évènements tel que :
    - Demande de validation d'un document
        - Création d'une annonce depuis la WebApp
        - Attribution d'une annonce à un responsable
        - Envoi email quand annonce

---

### Anciennes versions

- Les changements des anciennes versions ne sont pas documentées ici.