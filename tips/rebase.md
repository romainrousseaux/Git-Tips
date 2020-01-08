# Git rebase

## Description
Tip sur la commande Git rebase.

**Le rebase va récupérer tous les commits de la branche de développement pour fusionner avec les données à jour de la master par exemple.**

- Créer une branche de backup
```bash
git checkout -b backup
```

- Retourner sur la branche concernée
```bash
git checkout -
```

- S'assurer que la master (ou autre) est à jour
```bash
git checkout master
git pull
```

- Retourner sur la branche concernée
```bash
git checkout -
```

- Rebaser les données
```bash
git rebase master
```

- Si il y a des conflits, les résoudre et continuer le rebase
```bash
git rebase --continue
```

- Pusher les données
```bash
git push --force
```
