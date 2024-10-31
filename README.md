# Question 1 :

L'effet de la première commande git init dans le dossier est de transformer ce dossier en un dépôt Git local. Cela crée un sous-dossier caché .git où seront stockés tous les fichiers et configurations de suivi de version nécessaires pour gérer les versions du projet.

# Question 2 : 

Si on oublie d'ajouter le fichier à la staging area avant de faire un commit, le fichier ne sera pas inclus dans le commit. Le commit ne contiendra que les modifications qui ont été ajoutées à la staging area avec git add. Les changements non ajoutés resteront inchangés et pourront être ajoutés dans un futur commit.

# La nouvelle description 

Ce projet vise à démontrer les compétences de gestion de version avec Git.

# Question 3 

Si une modification est effectuée sans être commitée, elle restera dans l'état de "modifications non sauvegardées". En réouvrant le projet plus tard, ces modifications seront toujours présentes, visibles comme des changements non sauvegardés dans l'état de travail actuel, et prêtes à être stagées ou commitées.

# Question 4 

Pour afficher l'historique de manière concise avec un résumé d'une ligne par commit, on peut utiliser la commande :

git log --oneline




