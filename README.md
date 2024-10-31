reponse 1: l'effet de la premiere commande permet d'initialiser un dépôt Git dans un dossier en créant un sous-dossier caché .git qui contient toutes les informations nécessaires pour suivre les versions des fichiers du projet.

reponse 2:  Si un fichier n'est pas ajouté à la staging area  avant de faire un commit, les modifications apportées sur ce fichier ne seront pas enregistrées dans le commit. Le commit ne sauvegardera que les fichiers ajoutés dans la staging area.

reponse 3: Si on modifie un fichier sans effectuer de commit et on  ferme le projet, les changements resteront dans notre espace de travail,a la réouverture les modifications seront toujours présentes

reponse 4: Pour afficher l'historique des commits de manière plus concise on peut utiliser la commande : git log 

reponse 5: Non, un commit effectué sur une branche ne modifie que cette branche spécifique. Les autres branches restent inchangées jusqu'à ce qu'elles soient  fusionnées ou mises à jour avec la branche contenant les nouveaux commits.

reponse 6: la syntaxe de la commande qui permet d'afficher les differences: git diff design

reponse 8: Le fichier .gitignore est important car il permet d'ignorer les fichiers sensibles comme des mots de passe empêchant ainsi qu'ils ne soient accidentellement partagés ou suivis par Git.

reponse 9: Si un conflit de fusion survient, Git signalera les fichiers en conflit. Il faudra résoudre manuellement les différences dans les fichiers concernés avant de pouvoir terminer la fusion.



