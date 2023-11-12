[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/6epMQcoo)
# Angular : rendu n°2
Repository où déposer le projet n°2 Angular

### Nom[^1] : BORREANI

### Prénom[^2] : Théo

## A faire[^3]
- [X] Suivre le cours jusqu'à la page 180
- [X] Intégrer toolbar et navbar du rendu n°1
- [X] Identification par **login/password**
  - ajouter un tableau de login/password/role (avec rôle qui est soit **user** soit **admin**) dans le service d'authentification
  - modifier le code pour avoir `isLogged()` **ET** `isAdmin()` au lieu de juste `isAdmin()`
- [X] Au lieu du slider `LogIn`, ajouter un bouton connecter (avec une *mat-icon* adaptée) qui amène à un composant avec un formulaire de connexion
- [X] Gestion des droits :
  - L'admin peut éditer et effacer les assignment
  - Le user peut voir le détail des assignment
  - Si on n'est pas logué on ne peut ni voir le détail, ni éditer


[^1]: à remplir
[^2]: à remplir
[^3]: vous pouvez cocher les tâches qui ont été faites en utilisant la syntaxe `[x]` dans le markdown


# Notes supplémentaires

Quelques explications sur le fonctionnement de certains contenus dans la Sidenav :

- 'Modification d'un devoir' et 'Supression d'un devoir' accède à la page voulu en chargeant le premier élément du tableau de devoirs.
- 'Génération de données de test' ajoute juste une donnée dans le tableau de devoirs facilement identifiable est non rendu

Les noms de connections et les mots de passes sont les suivants: 
- nom:admin mdp:123
- nom:toto mdp:helloWorld
- nom:soso mdp:31/12/2017

Pour les rôles j'utilise des booléens 'true' associés a administrateur 'false' sinon.