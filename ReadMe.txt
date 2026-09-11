Bonjour,
Dans ce laboratoire, j'ai appris à utiliser GitHub pour gérer des travaux d’équipe. Ce laboratoire m'a permis de comprendre comment 
partager un projet avec un coéquipier ainsi que comment créer un environnement de travail séparé à l’aide des branches. La création de dossiers et de 
fichiers texte m'a appris à mieux comprendre l’utilité des commits afin de bien documenter les différentes étapes d’un travail. J'ai
également appris à utiliser la commande push, qui permet de déployer sur GitHub les mises à jour effectuées localement. La partie 2 m'a 
permis de pratiquer la gestion des erreurs, le retour à une version fonctionnelle ainsi que la création d’un repository local avant de le rendre
accessible sur GitHub.

Git Cheat-Sheet:

Git config --global user.name "" : Permet de définir un nom

Git config --global user.email "" : Permet de définir l’adresse courriel

Git clone URL : Permet de copier un repository distant à partir de l'URL

Git init   : Initialise le dossier courant comme un repository Git local

Git status : Affiche l'état d'un repository

Git remote add origin URL : Relie un repository local à un repository distant

Git add --all : Ajoute tous les changements 

Git commit -m "message" : Crée un commit avec les changements effectués. Permet de documenter un changement

Git push origin main : Envoie les commits de la branche main vers le repository distant

Git pull : Synchronise les changements du repository distant à la branche locale

Git branch : Donne la liste des branches existantes

Git checkout Nom_branche : Permet de changer de branche 

Git checkout -b Nom_branche : Permet de créer une nouvelle branche

Git merge Nom_Branch : Permet de fusionner une branche avec la branche active

Git log : Affiche l'historique des commits

Git reset --hard Numero_commit : Permet de revenir à l’état d'un commit précédent

Git switch Nom_Branch : Permet de changer de branche


Pas des commandes Git mais important pour nos futurs projets : 

mkdir Nom_Dossier : Crée un dossier

echo "texte" > text.txt : Crée un fichier texte contenant le texte indiqué

Add-Content text.txt "texte" : Ajoute du contenu à un fichier existant

Get-Content text.txt : Affiche le contenu d’un fichier

Issue : 

Une issue sert à signaler et à documenter un problème. J'ai appris qu'une issue doit être claire et précise afin qu'un autre membre puisse comprendre le problème facilement.
Une issue doit avoir un titre clair. La description doit contenir la source du problème et une courte description du problème observé. Une description doit également contenir la version du commit
erroné ainsi que la dernière version utilisable. Une issue doit toujours être bien structurée et claire pour faciliter la communication entre les membres de l'équipe.


