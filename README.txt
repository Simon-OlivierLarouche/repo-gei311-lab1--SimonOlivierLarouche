
LABORATOIRE 1 (6GEI311)
Étudiant : Abdramane Dramé
Code permanent : DRAA04070300
Rôle : Membre B

Résumer d'apprentissage : 

Ce premier laboratoire m'a permis d'apprendre à bien travailler en équipe avec Git et GitHub.  
J'ai compris l'utilité des branches pour travailler sur nos propres modifications sans risquer de casser la branche principale (main). 
Les exercices m'ont aussi montré pourquoi il est important d'écrire des messages de commit clairs pour garder une trace propre de chaque étape du projet.  
En manipulant les commandes push et pull, j'ai appris à garder mon dossier local et le projet sur GitHub bien synchronisés. 
Enfin, la deuxième partie m'a appris deux choses très utiles : comment envoyer un projet fait sur mon ordinateur directement vers GitHub pour le partager, 
et comment annuler une erreur pour revenir facilement à une ancienne version qui fonctionne.


Concernant l'utilisation des issues, ils servent à signaler et à documenter un problème au sein du projet. 
J'ai appris qu'une issue doit être rédigée de manière claire et précise afin qu'un membre de l'équipe puisse comprendre rapidement la situation :
- Titre : Doit être explicite et résumer le problème en quelques mots.
- Description : Doit préciser la source du problème, les étapes pour reproduire le comportement inattendu ainsi qu'un résumé du comportement attendu vs observé.
- Traçabilité : Doit mentionner la version (commit hash) ayant introduit l'erreur ainsi que la dernière version stable fonctionnelle pour faciliter l'investigation et le rollback.


Aide-mémoire Git (Cheat-Sheet) :
Configuration & Initialisation :
- git config --global user.name "..."  : Permet d'enregistrer l'identité de l'auteur des commits.
- git config --global user.email "..." : Associe une adresse de contact aux contributions.
- git init                            : Crée un nouveau dépôt Git local dans le répertoire courant.
- git clone <URL>                     : Télécharge localement l'intégralité d'un projet distant avec son historique.
- git remote add origin <URL>         : Établit le lien réseau entre le dossier local et le serveur GitHub distant.

Suivi & Validation des modifications :
- git status                          : Contrôle l'état des fichiers (modifiés, indexés ou non suivis).
- git add -A (ou --all)               : Place la totalité des modifications en zone de préparation (staging area).
- git commit -m "..."                 : Fige les fichiers préparés dans un nouvel instantané horodaté et commenté.
- git log --oneline --graph           : Génère une vue synthétique et visuelle de la chaîne des commits.

Branches & Fusion :
- git branch                          : Affiche l'inventaire des branches locales actives.
- git switch <branche>                : Bascule sur l'espace de travail de la branche cible.
- git switch -c <branche>             : Crée une branche dérivée et s'y positionne immédiatement.
- git merge <branche>                 : Intègre les modifications de la branche indiquée dans la branche courante.

Synchronisation & Dépannage :
- git push -u origin <branche>        : Transfère la branche locale vers GitHub et configure le suivi distant.
- git pull                            : Rapatrie et applique les nouveaux commits distants sur la branche locale.
- git reset --hard <commit_id>        : Réinitialise l'arbre de travail et l'index à l'état exact du commit visé.
- git revert <commit_id>              : Génère un commit inverse pour annuler proprement les changements ciblés.
Commandes d'environnement (CLI & Shell) :
- mkdir <nom>                         : Génère un nouveau répertoire sur le système de fichiers.
- echo "texte" > fichier.txt          : Crée ou écrase un fichier avec la chaîne de caractères fournie.
- Add-Content fichier.txt "texte"     : Concatène du texte en fin de fichier existant (PowerShell).
- Get-Content fichier.txt             : Lit et affiche l'intégralité d'un fichier dans la console (PowerShell).

