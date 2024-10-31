Nom : Khadoum Amaboua
Prenom : Khamis Ahmat
Licence 1 Génie Informatique
SUPDECO/ ESITEC

EXAMEN DE VERSIONING DU PREMIER SEMESTRE :

Description : L'examen consiste en la pratique des commandes git qu'il nous a été de voir durant le cours et en la réponses aux questions présentes dans 
le document Word. Avant tout, l'on devra télécharger le zip présent sur le lien Drive du Word, initialiser un repo git dans notre dossier courant puis
l'on devra créer un fichier README.md et le remplir selon les indications du document Word.

Question 1 : Quel sera l'effet de la première commande (initialisation) sur le dossier ?
--> L'effet de la premiere commande 'git init' sera l'initialisation d'un repo git dans notre dossier courant et la création d'un dossier .git qui va nous
permettre de stocker les différentes versions de nos fichiers.

Question 2 : Que se passe-t-il si on oublie d'ajouter le fichier avant de faire un commit ?
--> Si on oublie d'ajouter un fichier avant d'effectuer un commit le fichier n'étant pas dans la staging area ne sera pas pris en compte lors du commit 

Question 3 : Si vous faites une modification sans la committer, que se passera-t-il si vous fermez le projet et le réouvrez plus tard ?
--> Si on fait une modification sans la committer et que l'on ferme le projet et que l'on le réouvre plus tard, les modifications effectuées ne seront pas prises en compte dans l'historique. Mais, elles resteront intacte dans le répertoire local.

Question 4 : Comment afficher l'historique de manière plus concise (résumé d'une ligne par commit) ?
--> Pour afficher l'historique de manière plus concise, on peut utiliser la commande 'git log --oneline'. Dans le cas où m'on ne veut pas l'afficher de manière plus
concise, on peut utiliser la commande 'git log'.

Question 5 : Si vous êtes sur une branche et que vous commitez, est-ce que ce commit affecte les autres branches ? Pourquoi ?
--> Si on est sur une branche et qu'on effectue un commit, ce commit n'affecte pas les autres branches car les branches sont indépendantes les unes des autres
la modification de l'une d'elle n'affecte pas les autres.

Question 6 : Quelle est la syntaxe de la commande qui permet d’afficher ces différences ?
--> La syntaxe de la commande qui permet d’afficher ces différences est 'git diff'.

Question 8 : Pourquoi est-il important d’utiliser un fichier .gitignore ?
--> Il est important d'utiliser un fichier .gitignore car il permet de spécifier les fichiers ou les dossiers qui ne doivent pas être suivis par Git. Les fichiers sensibles.
*La différence entre un fichier tracker et un fichier non tracker ?
--> Un fichier tracker est un fichier qui est suivi par Git et qui est donc pris en compte dans l'historique. Un fichier non tracker est un fichier qui n'est pas suivi par Git et qui n'est donc pas pris en compte dans l'historique.

*Comment vérifier si un fichier est tracker ?
--> Pour vérifier si un fichier est tracker, on peut utiliser la commande 'git ls-files' qui va nous afficher la liste des fichiers suivis par Git.

Question 9 : Que se passe-t-il si un conflit de fusion survient ?
--> Si un conflit de fusion survient, Git va nous demander de résoudre le conflit manuellement en modifiant le fichier de manière à ce qu'il soit cohérent avec les deux versions.

*Comment fusionner deux branches ?
--> Pour fusionner deux branches, on peut utiliser la commande 'git merge'.
