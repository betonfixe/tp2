# Sae

**Nom :** Guelle clément

**Groupe :** 06

**Année :** 2024

**IUT Le Havre - Cours GIT**

### Compte-rendu TP1 Introduction GIT

Dans ce TP on apprend à travailler avec git.

La commande `git config --global user.name "GUELLE clement"` permet de changé son nom.

La commande `git config --global user.email [clement.guelle@bbox.fr](mailto:clement.guelle@bbox.fr)` permet de changé son email.

Puis `git config --list` pour voir les différents paramètres présent tel que son nom, email, etc.

**Commençons le TP git**

Création du TP git : `git init`

Pour voir les différents statut de notre projet git on peut entrez la commande : `git status` . Qui nous permet de voir si l’on à fait des modifications, envoyé ou mis en commit le projet.

La commande : `git add < fichier >` permet d’ajouter un élément au projet.

Après avoir ajouté un ou plusieurs éléments au projet git. Il faut l’envoyer pour ce faire utilisé la commande : `git commit -m "Ajoute du fichier README.md"`

Le fichier .gitignore permet d’ignorer tous ce qui est mis a l’intérieur du fichier, par exemple lors de la création du .gitignore nous avons mis les .class, ce qui nous a permis de les ignorer.


### Compte-rendu TP2 Introduction GIT

Dans ce TP on apprend à travailler avec git.

**Utilité de Github :**

Github à pour but de facilité les projets qu’ils soit en groupe ou en individuelle. En effet grâce à Github on peut plus aisément partager le projets avec les membres du groupe, mais également récupérer le projet même en n’étant pas sur le même espace de travail ( autre ordinateur ), Cela permet donc d’avoir une sauvegarde supplémentaire du projet.

**Connexion à Github**

Une **clé SSH** permet de sécurisé notre compte Github. De plus on peut le faire sur chaque ordinateur que l’on utilise.

**Utilisation Github**

Pour pouvoir donc utilisé Github ils nous faut pourvoir envoyer notre travail sur Github, l’espace commun pour le travail en groupe de la SAE, mais également pouvoir reprendre le travail mis par les autres membres du groupes. Pour cela on utilise :

`git remote` : La commande `git remote` permet de lier un compte Github avec le projet.

`git push`     : La commande `git push` nous permet après avoir validé l’envoie avec git commit -m de mettre le projet sur Github et de le partager avec les autres membres du groupe.

`git pull`     : Cette est complémentaire à `git push` car elle permet de récupérer le travail disponible sur Github.

**Création projet Github**

Pour créer un projet Github il suffit de créer un “ new repository “, lui mettre un nom puis choisir de le mettre en privé ou public.

Pour voir si un projet git est déjà lier il suffit de faire `git remote -v`.

Si le projet n’est pas encore lier, il faut simplement faire la commande `git remote add origin git@github.com:<votre_utilisateur>/<nom projet>.git.`

Pour finir de faire les liens pour le projet il faut connaitre le nom de la branche.

On peut obtenir les nom en faisant : `git branch`

Après avoir obtenue le nom des branches, ici *master, Il ne reste plus qu’à créer le lien de manière permanente et mettre à jour le dépôt distant avec la commande :`git push -u origin <nom de la branche>`

**Commande utile pour git**

Pour récupérer les travaux sur Github nous avons vu que c’était `git pull` , ça nous permet donc de télécharger et synchroniser la version la plus récente du dépôt distant vers notre dépôt local

`git log`   : Nous permet de voir les dernière modification effectué et par qui.

`git push` : Contrairement à  `git pull` cale nous permet d’envoyer de notre dépôt local vers le dépôt distant.