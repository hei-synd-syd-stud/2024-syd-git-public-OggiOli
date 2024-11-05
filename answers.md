# Answers of Olivier Oggier OggiOli

## Basics

### Task 1

1) ".git" : il inclut des fichiers qui vont permettre de stocker les commits, branches, tags...

2) "img" : contient l'image présente dans ce fichier pour la task 7

3) "answers.md" : le fichier texte dans lequel on écrit nos réponse

### Task 2

Dans le "git status" il y a le nouveau fichier "README.md" qui est affiché comme "Untracked", car il vient d'être créé et n'a pas encore été ajouté à l'index. Git a donc détecté la présence de ce nouveau fichier, mais il ne fait pas encore partie de l'historique de suivi des versions

Dans le "git log --oneline", il n'y a aucun changement, car il montre uniquement les commits déjà enregistré dans l'historique Git. 

### Task 3

Cette fois, le "git status" affiche un nouveau fichier "README.md" et qu'il est prêt à être commité dans l'historique. Il est en attente de validation.

### Task 4

Le fichier "README.md" est listé dans la section "Changes not staged for commit" avec un état "modified". Cela veut dire que le fichier a été modifié depuis son dernier ajout et n'a pas encore été mis à jour pour un prochain commit.

### Task 5

1. La chaîne de caractères : représente l'identifiant unique du commit. En effet, chaque commit reçoit un identifiant unique qui les distingues des autres dans le dépôt.

2. HEAD et main : HEAD est un pointeur qui montre ma position actuelle dans l'historique. Dans notre cas, HEAD est pointé vers le dernier commit sur la branche main. Ce main est d'ailleurs le nom de la branche sur laquelle je travaille actuellement. 

3. après la paranthèses : C'est le message du commit qui décrit les changements. 

### Task 6

lorsque nous effectuons un checkout vers un commit antérieur, Git ajuste les fichiers du projet pour refléter cet instant précis, autrement dit il cache les commits qui suivent. En revenant sur le main, cela restaure les fichiers dans leur état du dernier commit de la branche main.

## Gitgraph

### Task 7

![Gitgraph](img/gitgraph.svg)