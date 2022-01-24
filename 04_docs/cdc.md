# Exigences fonctionnelle pour le réseau social 
 Mention "Réseau social" doit apparaître à l'arrivée de la page.

1. Inscription d’un utilisateur
2. Connexion
3. Déconnexion
4. Ajouter un utilisateur à la liste d’amis
5. Valider une demande d’ajout à la liste d’amis
6. Ignorer une demande d’ajout à la liste d’amis
7. Recommander un ajout à la liste d’amis
8. Valider une recommandation d’ajout à la liste d’amis
9. Publier un message sur le profil d’un utilisateur
10. Démarrer une discussion instantanée
11. Accéder à une discussion instantanée
12. Possibilité de chercher des utilisateurs enregistrés
13. Espace particulier pour chaque utilisateur enregistré dans lequel peuvent
être publiés des messages et qui est consultable par d’autres personnes.
14. Gestion des liens entre les utilisateurs enregistrés : ajout ou retrait d’un
utilisateur de sa liste de connaissances et recommandation d’un
utilisateur enregistré à une connaissance.
15. Espace de dialogue en temps réel entre les utilisateurs (chat).
16. Messagerie privée permettant l’échange de messages entre les
utilisateurs enregistrés.
17.Notification par mail lorsqu’un utilisateur enregistré envoie un message
public ou privé à un autre utilisateur enregistré.
18. Interface de gestion permettant aux administrateurs de gérer les
comptes des utilisateurs ainsi que les messages publics et privés.
19. Affichage dans cette même interface des statistiques en temps réel :
connexions, messages reçus et envoyés.

Gestion de l’affichage lors de la gestion des utilisateurs 
20. La publication sur le profil, la réponse à un message et la suppression se
feront sans rafraîchissement de la page (méthode asynchrone).
21. La suppression d’un ami se fera sans rafraîchissement de la page (méthode
asynchrone).
22. La recherche des utilisateurs : 
Cette recherche d’utilisateur peut se faire par nom et/ou prénom et/ou
pseudonyme
Il sera possible de filtrer la liste des amis pour afficher uniquement ceux qui
correspondent à la chaîne de caractère saisie dans le champ de filtrage.

Exigences techniques :
1. Compatible Mobile First et Desktop.
2. Utiliser CSS3 et les animations Javascript.

# Idées de réseau social :
1. Réseau social sur la lecture 
=> Réseau avec inscription 
=> Objectif : 
Réseau de partage de livres, de ressenti, de point de vue global 
=> Fonctionnalités :
> Pouvoir créer des groupes 
> partager ses dernières lectures 
> Feed : Livre /  Première page / émotion ressentie / Compréhension du livre
> Salle de débat sur un livre ou une thématique
> Abonnements aux auteurs 
> S'abonner à des gens et aimer leur partage 
> Boutons dispos :
   - Read 
   - Pin
   - Share
   - Debate
> Possibilité de recommander des livres
> Ajouter des amis ou recevoir des demandes d'ajouts
> Possibilité de s'abonner à des écrivains.
> Avoir une salle de débat sur une thématique
> Publier des photos de livres


# Etape 1 : Les besoins 

> Domaine avec serveur web
> Espace de stockage pour stocker des données utilisateur
> Programme côté serveur et côté client pour gérer les comptes utilisateur
> Gérer les publications des personnes 
> Vous avez besoin d'un moyen d'attirer les utilisateurs et de les conserver sur votre site

# Etape 1 : Back-end 
1. Stack :
 Back-end
 > Node Js
 > Express Js
 > Penser à NextJs
 > On parle de Firebase avec React  : Store the images and store in the firestore (database provided by firebase). = ens de services d'hebergement pour nimp quel type d'app.
 >

 Front-end
 > React Native pour les applis iOs/ Android : 
   - Redux : Store current user data 

Styling :
 > CSS:
  - Tailwind / Sass / Bootstrap / Chakra-UI 
  - Pour facebook Clone : je vais utiliser Material UI (utilisable pour CSS) => brings really clean icons on the project.


