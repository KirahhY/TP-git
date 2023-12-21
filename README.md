# TP-git
## Initialisation de repo
### Ignorer des fichiers :
    .gitignore (mettre dans le .gitignore le nom des fichiers à ignorer)
    Pour : les fichiers d'environnement, les dépendances...

### Initialisation projet : 
    git init (une seule fois par projet!)

### Cloner un projet :
    git clone <urlDuProjet> (crée un dossier avec le nom du projet et clone dedans tout le projet).
### Consulter l'état de l'espace de travail (où on se trouve):
    git status

### Commit :
    -git add `nom du fichier` ou  * (pour tout commit)
    -git status (montre les fichiers modifiés qui vont être commit)
    -git commit -m **"commentaire sur le commit"**

>## **Branch section** 
>
>> Création d'une **branche** (en local):
>>- git checkout -b `nom de la branche`
>>
>
>> Se déplacer de branches en branches :
>>- git checkout `nom de la branche` 
>    
>> Afficher les **branches** existantes : 
>- git branch 
>    
>> Incorporer une branche dans la branche principale (main) : 
>- git checkout `main` 
>- git merge `nom de la branche à fusionner`
>
>> Supprimer branche(s) :
>- git branch -D  `nom de la branche`
>
>> Voir les branches de manière visuelle :
>- git log --all --graph

## Modification de l'historique
- Pour changer ou modifier le dernier commit, rien de plus simple. Il suffit d'utiliser : `git --amend`  
Par exemple, si je veux modifier le commentaire associé à mon dernier commit, je peux procéder comme suit : `git --amend -m "commentaire modifié"`  
![ alt text](https://github.com/KirahhY/TP-git/blob/main/giphy.gif?raw=true)

- Pour se retourner à un commit précédent, il faut utiliser : `git reset <id>`  
Il est donc nécessaire d'utiliser le id/hash du commit à partir duquel on souhaite repartir, tout en conservant les changements en cours.

- Enfin, pour que le commit actuel prenne la place d'un commit précedent : `git revert <id>`    

![Texte alternatif](https://github.com/KirahhY/TP-git/blob/main/revert_vs_reset.jpg?raw=true)


## 🤝 Contributing:
    Enzo QUELENIS, Marius OUDIN, BEN NEJMA Mohamed Adam

