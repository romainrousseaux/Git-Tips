# Git amend

## Description
Tip sur la commande Git amend.

**A ne faire que si on a déjà un premier commit au préalable sur la branche de dev.**

**Les modifications doivent être rajoutées à l'index.**

- Utiliser la commande `git commit --amend`

```bash
# Sans modification du message du commit
git commit --amend --no-edit

# Avec modification du message du commit
git commit --amend
```

- Pusher la branche

```bash
git push origin/name_branch --force
```
