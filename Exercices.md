# Exercices

## Déménagmeent

Une entreprise de déménagment doit créer sa base de données. Voici les données qu'elle manipule :

- des camions
  - immatriculation
  - volume
  - date d'achat
- clients
  - nom
  - prenom
  - email
  - telephone
  - id
- localisation
  - adresse
  - etage
  - numero d'appartement
- cartons
  - id
  - poids
  - volume
  - est-ce que c'est fragile
- deplacer
  - date
  - id
  - est-ce que c'est fait
  - endroit départ
  - endroit arrivé

Grâce à des camions, des cartons sont déplacés d'une localisation à une autre. Une localisation est reliée à un seul client.

1. Faire le dictionnaire de données. Vous pourrez rajouter des clefs étrangères ou des clefs primaires si besoin
2. Faire le MCD
3. Faire le script sql pour créer cette base de données

## Arbre généalogique

Vous voulez reconstituer votre arbre généalogique. Vous avez besoin du nom, du prénom, de la date de naissance et de la possible date de décès de chaque membre de votre famille. Trouvez également un moyen de relier les enfants à leurs parents.

1. Faire le dictionnaire de données
2. Faire le MCD
3. Faire le script sql pour créer cette base de données

## Agence immobilière

Une agence immobilière souhaite digitaliser son calendrier de visites. Elle doit pour cela faire l'inventaire de tous les biens qu'elle gère. Un bien est identifié par un ID et se caractérise par une adresse et un code postal. Il peut avoir un numéro d'étage et un numéro d'appartement. Un bien est possédé par un propriétaire. Un propriétaire est une personne et est identifié par son adresse email. Son nom et son prénom seront aussi enregistrés. Pour enregistrer une visite, il faut une date et une heure de début de visite. Une visite ne concerne qu'un bien et qu'une seule personne, un client. Le client a les mêmes propriétés que le propriétaire. Il faut trouver un moyen de distinguer le client du propriétaire.

1. Faire le dictionnaire de données
2. Faire le MCD
3. Faire le script sql pour créer cette base de données

## Librairie steam

Steam doit refaire sa base de données. Il faudra gérer des jeux. Un jeu a un nom unique et un type de jeu. Chaque jeu a une liste de trophées, caractérisés par un id, un nom, une description et un degré de difficulté. Un trophée ne peut pas être distribué pour plusieurs jeux. Steam doit aussi gérer ses joueurs et joueuses, représenté.es par un pseudo et un email. Un.e joueur.se va acheter et collectionner des jeux.

1. Faire le dictionnaire de données
2. Faire le MCD
3. Faire le script sql pour créer cette base de données

## Blog

Vous décidez de créer un blog sur lequel des personnes peuvent s'inscrire pour poster des articles et commenter les articles existants. Une personne doit rentrer un pseudo, un email et un mot de passe pour pouvoir s'enregistrer. Un article est posté par une personne et doit comporterr une date de publication, un titre et un contenu. Il faut aussi un moyen de l'identifier, car plusieurs articles peuvent avoir le même titre. Un commentaire est posté par une personne sur un article. Il comporte une date de publication, un contenu et peut répondre à un commentaire existant.

1. Faire le dictionnaire de données
2. Faire le MCD
3. Faire le script sql pour créer cette base de données