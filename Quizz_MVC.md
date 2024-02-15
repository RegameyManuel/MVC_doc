### Quiz sur l'Architecture MVC

#### Question 1
Quel est le rôle du **Modèle** dans l'architecture MVC ?
a) Gérer la logique de présentation et l'interface utilisateur
b) Recevoir et traiter les entrées de l'utilisateur
c) Représenter les données et la logique métier de l'application
d) Aucune des réponses ci-dessus

#### Question 2
Dans l'architecture MVC, quel composant est responsable de l'envoi des actions de l'utilisateur au modèle ?
a) Vue
b) Contrôleur
c) Modèle
d) Base de données

#### Question 3
Lequel des éléments suivants est un exemple de l'utilisation de la **Vue** dans une application web MVC ?
a) Exécution d'une requête SQL pour récupérer des données
b) Mise à jour des informations de l'utilisateur dans la base de données
c) Affichage d'une liste d'articles de blog récupérée depuis le modèle
d) Validation des données de formulaire saisies par l'utilisateur

#### Question 4
Quelle affirmation sur le **Contrôleur** est vraie ?
a) Le contrôleur met à jour directement la base de données.
b) Le contrôleur peut envoyer des commandes au modèle pour mettre à jour l'état de l'application.
c) Le contrôleur est un composant optionnel dans l'architecture MVC.
d) Le contrôleur stocke les données de l'application.

#### Question 5
Comment le modèle notifie-t-il la vue des changements dans les données ?
a) Le modèle envoie directement les données à la vue sans notification.
b) La vue interroge périodiquement le modèle pour détecter les changements.
c) Le contrôleur informe la vue des changements dans le modèle.
d) Le modèle utilise un mécanisme de notification ou d'observateur pour informer les parties intéressées.

#### Question 6 (Exemple Pratique)
Vous développez une application web de blog en utilisant l'architecture MVC. Où placeriez-vous la logique pour récupérer tous les articles de blog depuis la base de données ?
a) Dans le modèle
b) Dans la vue
c) Dans le contrôleur
d) Dans un service web externe

#### Question 7 (Exemple Pratique)
Si un utilisateur soumet un formulaire pour créer un nouvel article de blog, quel composant MVC traite initialement cette requête ?
a) Modèle
b) Vue
c) Contrôleur
d) Base de données

### Réponses
1. c) Représenter les données et la logique métier de l'application
2. b) Contrôleur
3. c) Affichage d'une liste d'articles de blog récupérée depuis le modèle
4. b) Le contrôleur peut envoyer des commandes au modèle pour mettre à jour l'état de l'application.
5. d) Le modèle utilise un mécanisme de notification ou d'observateur pour informer les parties intéressées.
6. a) Dans le modèle
7. c) Contrôleur
