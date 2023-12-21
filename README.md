>## **Branch section** 
>
>> Création d'une **branche** (en local):
>>- git checkout -b `nom de branche`
>>
>
>> Se déplacer de branches en branches :
>>- git checkout `nom de branche` 
>    
>> Afficher les **branches** existantes : 
>- git branch 
>    
>> Incorporer une branche dans la branche principale (main) : 
>- git checkout `main` 
>- git merge `nom de la branche à fusionner`
>
>> Supprimer branche(s) :
>- git branch -D  `nom de branche`
>
>> Voir les branches de manière visuelle :
>- git log --all --graph