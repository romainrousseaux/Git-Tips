# Git squash

## Description
Tip sur la commande Git squash.

**Attention, les modifications en cours doivent être commitées mais pas pushées.**

- Créer une branche de backup
```bash
git checkout -b backup
```

- Retourner sur la branche concernée
```bash
git checkout -
```

- Rassembler les x deniers commits (x dépend  du nombre de commits de la branche)
```bash
git rebase -i HEAD~X
```

- Remplacer les "pick" par des "squash" sauf le premier commit

- Supprimer ensuite toutes les lignes et ajouter un message de commit

- Pusher la branche
```bash
git push --force
```

- S'assurer que c'est OK et supprimer la branche de backup
```bash
git branch -d backup
```
