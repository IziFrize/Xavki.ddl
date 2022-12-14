# Notice GitHub - Qu'est-ce que GitHub ?


- Github est un site internet fondé par Linux Torvalds en 2005 permettant de partager des projets informatiques et de pouvoir les modifier simultanément partout dans le monde. Il destiné à un publique s'interessant aux langages informatiques et voulant le partager. Il est communément utilisé dans des équipes afin s'implifier le partage des données, tout est envoyé instantanement sans avoir besoin d'être côte à côte.
Le dépôt est notre espace de travail commun sur GitHub

## Création de compte

Pour créer un compte GitHub vous aurez besoin d'un nom d'utilisateur, d'une adresse mail et d'un mot de passe.
La page de création de compte est accessible directement via le lien suivant : https://github.com/join

## Ajout d'un membre

En tant que créateur du repository, vous avez l'option d'y ajouter des collaborateurs. Pour ajouter des collaborateurs à votre projet, vous devez vous rendre dans les paramètres de votre projet puis dans `Accès → Collaborators` puis dans la partie `Manage Access`. Vous y trouverez un bouton labellé `Add People` avec lequel vous pouvez rajouter des utilisateurs de GitHub qui auront le droit de modifier votre projet en utilisant leur nom d'utilisateur ou leur adresse mail.

## Commandes usuelles

`git clone` – Cette commande nous permet de créer une copie locale d'un repertoire en ligne.  

* Exemple : `git clone git@github.com:IziFrize/Xavki.ddl.git"`  

`git status` - Cette commande nous montre l'état actuel de l’arbre de travail.  

* Exemple : `git status`  

`git add` – Cette commande va ajouter le contenu de fichiers à l’index ce qui va nous permettre des créer des paquets à envoyer ensuite sur le dépôt.  

* Exemple : `git add xavki.fichier`  

`git commit` – Cette commande nous permet d’enregistrer nos modifications dans le dépôt.  

* Exemple : `git commit -a`  

`git push` – Cette commande permet d'envoyer le projet local que vous avez modifié directement sur le repository git en ligne.  

* Exemple : `git push`  

`git pull` – Cette commande rapatrie et intègre le contenu du repository en ligne dans le clone local.  

* Exemple : `git pull`  

`git merge` - Cette commande sert à fusionner deux branches et à pousser le résultat dans la branche principale.  

* Exemple : `git merge`  

`git config` - Cette commande sert à définir les paramètres de configuration qu'on va utiliser.  

* Exemple : `git config --global user.name "Your Name"`  

`git checkout` - Cette commande met à jour les fichiers dans l’arbre de travail pour correspondre à la version dans l’index ou dans l’arbre spécifié.  

* Exemple : `git checkout main`

## Staging  

![alt text](https://i.stack.imgur.com/qPcFI.png)

# Qu'est-ce que GitLab ?

GitLab est très similaire à GitHub dans son fonctionnement car en effet les deux utilisent Git. Cependant les deux ont tout de même des différences majeures.
Les principales étant:

- Le fait que GitLab nous permet d'avoir un dépôt privé gratuitement alors que sur GitHub, c'est payant ou alors le dépôt devient OpenSource
- La communauté de GitHub est beaucoup plus grande et active ce qui lui permet d'avoir le monopole et de s'améliorer en continue
- GitLab nous permet d'exporter des fichiers au format CSV au contraire de GitHub qui ne le permet pasce qui peut être pratique pour certaines entreprises

GitLab peut être aussi plus facile d'accès de premier abord car son interface graphique est plus compréhensible et développée.
