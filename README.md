# Description
Ceci est une description du projet.
Réponse a la premiere et a la derniére question.

# 1) L'effet de la premiére commande (initialisation) sur le dossier:
git init permet d'initialiser notre projet en local  en créant automatiquement une branche principal (main)

# 2) Que se passe t-il si on oublie d'ajouter le fichier avant de faire un commit 
Si l'utilisateur fait un commit (git commit) avant de faire un d'ajouter le fichier dans la staging area (git add), 
il y'aura erreur car ce fichier n'est pas ajouter dans la staging area. Avant de faire un commit , il faut d'abord faire un git add.

# 3) Si je fais des modifications sans la commiter , que se passera t-il si je ferme le projet et que je le réouvre plus tard
Les modifications faites seront enregistrés au niveau du working directory. Aucune perte ne sera noté.

# 4) Afficher l'historique des commits de maniére plus concise 
on fait git log --oneline

# 5) Est ce qu'un commmit affecte les autres branches
Non il n'affecte, Les modifications et les commits sur une branche reste sur une branche

# 6) La syntaxe qui permet d'afficher les differences est:
git diff

# 7) gitignore
Il permet de d'ignorer les fichiers sensibles contenant des nots de passes ou bien les lourds 

# 8) Fusion

On doit choisir manuellement entre les modifications.
