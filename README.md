# TP-git
## Initiation de repo
### Ignorer des fichiers :
    .gitignore (mettre dans le .gitignore le nom des fichiers à ignorer)
    Pour : les fichiers d'environnement, les dépendances...

### Initialisation projet : 
    git init (une seule fois par projet!)

## Cloner un projet :
    git clone <urlDuProjet> (crée un dossier avec le nom du projet et clone dedans tout le projet).
## Consulter l'état de l'espace de travail (où on se trouve):
    git status

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