# TP-git

## Nettoyer l'espace de travail
- Supprimer les changements depuis le dernier commit : `git restore`

- Supprimer les fichiers inconnus de Git (définitivement) : `git clean`
![ alt text](/TP-git/getout.gif)

- Supprimer les fichiers inconnus de Git (retrouvables) : `git stash`

## Modification de l'historique
- Pour changer ou modifier le dernier commit, rien de plus simple. Il suffit d'utiliser : `git --amend`  
Par exemple, si je veux modifier le commentaire associé à mon dernier commit, je peux procéder comme suit : `git --amend -m "commentaire modifié"`  
![ alt text](/TP-git/giphy.gif)

- Pour se retourner à un commit précédent, il faut utiliser : `git reset <id>`  
Il est donc nécessaire d'utiliser le id/hash du commit à partir duquel on souhaite repartir, tout en conservant les changements en cours.

- Enfin, pour que le commit actuel prenne la place d'un commit précedent : `git revert <id>`    

![Texte alternatif](https://github.com/KirahhY/TP-git/blob/main/revert_vs_reset.jpg?raw=true)


