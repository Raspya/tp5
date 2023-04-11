**Nom :** BERNOUY Matthias

**Groupe :** D

**Année :** 2023

**IUT Le Havre - Cours GIT**

### Compte-rendu TP1 Introduction GIT


// A REFAIRE 

Dans ce TP on apprend à travailler avec git.

La configuration de git se fait par la commande : "git config"
On peut taper "git config --list" pour afficher les paramètres de configuration
Pour mettre à jour une configuration comme le nom on fait la commande "git config --global user.name "Donovan Lefevre"

On peut ensuite créer un dépot git, pour cela il faut se placer dans le dossier souhaité et faire la commande "git init"
Pour vérifier les modifications apportées aux fichiers on exécute la commande "git status"

Ensuite, on exécute la commande "git add nom_fichier" pour ajouter un fichier à notre dépot
Pour valider cette inclusion on tape la commande "git commit -m "Message qu'on souhaite afficher"

Un dépot GIT contient 3 états différents : 
Modifié (modified), Sélectionné (staged), Validé (commited)

Ce qui correspond à 3 zones : 
La copie de travail (directory), La zone de sélection (staging area), Le dépôt où les modifications sont enregistrées sous forme de validations (commits).

Le passage entre les états se fait par 3 actions :
Sélection (stage), Validation (commit), Récupération (checkout) 
