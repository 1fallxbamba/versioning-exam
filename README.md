Description de mon projet : ce projet est un site de e-commerce en ligne.
Le ecommerce  est un site web qui permet aux utilisateurs de commander des produits en ligne et de les recevoir

Question 1 : 
    L'effet de la commande git init est de créer un nouveau dépôt Git dans le dossier actuel. Cela signifie qu'un sous-dossier caché nommé .git sera créé, contenant tous les fichiers nécessaires pour gérer le dépôt, y compris l'historique des commits, les références aux branches et les configurations du dépôt. Le dossier devient alors un dépôt Git, ce qui permet de suivre les modifications et d'effectuer des opérations de versioning.

Question 2 :
    Si vous oubliez d'ajouter le fichier à la staging area (avec la commande git add) avant de faire un commit, le fichier ne sera pas inclus dans ce commit. En conséquence, les modifications apportées à ce fichier seront perdues dans l'historique de versioning, et seules les modifications des fichiers qui ont été ajoutés à la staging area seront enregistrées. Pour inclure ce fichier dans un commit ultérieur, vous devrez d'abord l'ajouter à la staging area et ensuite effectuer un nouveau commit.

Question 3 :
    Si vous faites une modification sans la committer et que vous fermez le projet, ces modifications non enregistrées dans Git seront généralement perdues si vous n’avez pas sauvegardé le fichier de manière externe. En revanche, si vous avez simplement quitté l'éditeur ou l'application sans fermer le fichier, les modifications resteront dans l'état où vous les avez laissées lorsque vous rouvrirez le fichier.

Question 4 : 

    Pour afficher l'historique de manière plus concise, nous pouvez utiliser la commande suivante :> git log --oneline

Question 5 :
    Non, un commit effectué sur une branche n'affecte pas les autres branches. Chaque branche dans un dépôt Git est une ligne indépendante d'historique de commits. Lorsqu'un commit est réalisé, il est ajouté uniquement à la branche active (celle sur laquelle vous êtes actuellement).

    Les autres branches restent inchangées jusqu'à ce que vous les fusionniez ou que vous y appliquiez des commits. Cela permet de travailler sur différentes fonctionnalités ou corrections de bugs simultanément sans interférer avec le travail effectué sur d'autres branches. C'est une des principales forces de Git, car cela facilite le développement parallèle et le travail collaboratif.

Question 6 : 
    La syntaxe pour afficher les différences entre ma branche et la branche design est :> git diff design

Question 8 : 

    Il est important d’utiliser un fichier .gitignore pour éviter de suivre dans Git des fichiers qui ne devraient pas être versionnés. Cela inclut des fichiers temporaires, des fichiers de configuration spécifiques à un environnement local (comme env.txt), des fichiers de build, ou d'autres fichiers générés qui ne sont pas pertinents pour le projet. En les ignorant, on réduit le bruit dans l’historique des commits, protège des informations sensibles et préserve l'intégrité du dépôt.
Question 9 : 
    Si un conflit de fusion survient, Git arrête le processus de fusion et vous informe des fichiers concernés. Cela se produit lorsque des modifications incompatibles ont été apportées aux mêmes lignes d’un fichier dans les deux branches. Vous devrez alors résoudre manuellement les conflits en modifiant les fichiers concernés pour choisir quelles modifications conserver. Une fois les conflits résolus, vous devrez ajouter les fichiers modifiés à la staging area et effectuer un commit pour finaliser la fusion.

    