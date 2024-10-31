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