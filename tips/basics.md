# **Comment utiliser Git**

​	Pour cloner un projet :

​	`git clone <lien_du_projet>`

#### Procédure pour **chaque** développement:

- Se mettre sur la branche **Master**

  `git checkout master`

- Mettre à jour le projet

  `git pull`

- Créer une nouvelle branche pour faire votre développement dessus

  `git checkout -b <nom_de_la_branche>`

#### Procédure pour envoyer son code sur Github avec git

- Pour voir les fichiers modifiés

  `git status`

  À partir de là vous allez avoir la liste des fichiers que vous avez modifiés, vous pouvez choisir le(s)quel(s) vous voulez ajoutez au prochain commit

- Pour ajouter un fichier au prochain commit :

  `git add <chemin_du_fichier>`

  Si vous voulez tout ajouter, utiliser un `.` pour le chemin du fichier

- Pour commit les fichiers que l'on à ajouté :

  `git commit`

  On va vous demander de choisir un message de commit, une fois qu'il est choisi, enregistrez le fichier (`:wq` par défaut sur Vim)

- Ensuite  pour envoyer votre code sur git

  `git push`

#### Commandes utiles

- Pour modifier le précédent commit en cas d'erreur ou d'ajout:

  `git commit --amend`

- Mettre à jour le projet

  `git pull`
