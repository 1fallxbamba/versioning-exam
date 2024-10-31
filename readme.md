
Description:
Ceci est un projet permettant de creer un repo local
apres avoir initier le repo local on enregistre des fichiers apres modifications






 










Réponses:
1)le git init permet d'initier un repo local 
2)il y'aura un message d'erreur car sans ajouter le fichier à la staging area mais le commit passe 
3)si on fait une modification sans commiter le fichier et puis on ferme le projet et on réouvre rien ne change mais le fichier
  ne sera pas enregistrer dans le repo local
4)pour afficher l'hhistorique de maniere concise il faut taper dans le terminal git log --oneline
5)oui ce commit affecte les autres branches car c'est le meme repo local
6)git diff <nom de la branche qu'on veut comparer avec la branche actuelle>
8)le .gitignore permet de mettre des données sensibles des mots de passe etc pour que personne à part la machine locale ne puisse y avoir 
  acces c'est a dire git ignore ce fichier et le fichier n'apparait pas dans la liste des fichiers trackés
9)si un conflit de fusion survient il signile les fichiers en conflits alors il faudra les réparer manuellement
