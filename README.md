## Description du projet

Ceci est une page web tout à fait normale.
Il n'y a rien de spécial à ce site, mais vraiment...

## Réponses aux questions

1 - La première commande (initialisation) crée un nouveau dossier caché ".git".

2 - Si on oublie d'ajouter le fichier avant de faire un commit, git nous signale les
fichiers non ajoutés pour le commit et nous incite à ajouter le fichier avant de commit.

3 - En cas de modification non commitée et que le projet est fermé pour être réouvert
plus tard, git sauvegarde les modifications en attendant qu'elles soient commitées.

4 - Pour affciher l'historique des commits de manière concise on utilise la commande "git log --oneline"

5 - Si nous sommes sur une branche et que nous commitons sur cette dernière, le
commit n'affecte pas les autres branches car une branche est tout simplement une version
parallèle du projet dont les modifications qui y sont effectuées n'affectent pas les
autres branches.

6 - La syntaxe qui permet d'afficher les différences entre les différentes branches est
"git diff".

8 - Le fichier .gitignore est important car il nous permet de cacher au grand puclic
des données sensibles et/ou personnelles.

9 - Lorsqu'un conflit de fusion survient, git signale le conflit et interrompt la fusion
puisqu'il ne sait pas quel changement supprimer. C'est donc à nous utilisateur de faire
ce choix.
