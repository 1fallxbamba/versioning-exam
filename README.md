Description du projet:
le versioning 
Question 1 : Initialise un nouveau repo Git dans le répertoire actuel
Question 2 : Si le fichier n'est pas ajouté avec git add, Git ne l'inclut pas dans le commit. Le commit enregistrera uniquement les fichiers qui étaient dans la "staging zone". Le fichier non ajouté restera dans le dépôt.
Nouvelle ligne de description:
Question 3: Si la modification n'est pas commise, elle reste dans l'état de travail. Lorsque vous réouvrez le projet, le fichier contient toujours les modifications non enregistrées.
Question 4 : on utilise la commande git --oneline
Question 6 : git diff
Question 8: Le fichier .gitignoreest est crucial pour exclure des fichiers sensibles, volumineux, ou générés automatiquement (comme des mots de passe, des fichiers de configuration, ou des fichiers de build) afin de ne pas les ajouter au dépôt, ce qui peut réduire les risques de fuite d 'informations sensibles.