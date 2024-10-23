# ceci seras ma référance Git bash

Sorry pour les faute de frappe Parfois mes phrases/Mot serons pas énormément compréhensible le but est que je me comprenne moi meme et rapidement et non que passe 8 heure a comprendre mes note.

git clone permet de cloner un repertoire de github avec un https 

commme ceci `git clone https://github.com/libgit2/libgit2`

git init permet de crée un depot ou de vider un depot existant 
 `` git init`` <br>
`` git init --quiet`` n'affiche que les erreure et alerte le reste est surpimé

 git add  ajoute le contenue de fichier a l'index 
 ``git add``

 git commit permet d'enregistrer 
 ``git commit`` ou ``git commit -m 'Text' `` pour ajouter un comentaire 

 git status permet de voir l'etat du travail sur github 
 ``git status``

 git log afficher les journaux de validation
 ``git log``

git pull rapatrier et integrer un autre depot ou une branche locale 
``git pull``

git push permet de mettre a jour 
``git push``

git fetch  telecharger les ojbet  et references depuis un autre depot
``git fetch``

git merge fusionne plusieur historique de developpement ensemble 
``git merge``

git rebase écrase tout les commit fait dans le projet 
``git rebase``

git remote gère en ensemble de depot 
``git remote ``
``git remote -v `` voir les pull possible 
``git remote add upstream urlGithub`` pour lié en upstream un repo github  un autre depot<br>
``git remote remove upstream`` surpimer upstream

on peut aussi utiliser les comande comme 
``mkdir`` pour créer un repertoire 


``rmdir`` pour suprimé un repertoire


et ``cd nomDuRepertoire`` pour avancer dans ce repertoire
Pour changer directmeent d'un repertoire a un autre sans devoir faire TOUT le chemin tu peut taper un truc comme 
``cd C:\Users\decdu\Onedrive\Documents\Code`` cette comande seras beaucoup utliser pour moi pour acceder a mon code 
``cd ..``te permet de retourner dans le dossier précédent 
``cd`` te permet de retourner a C:


``nano NomDuFichier`` <https://raspberrytips.fr/raccourcis-nano-raspberry-pi/> se site explique son utilisation je vais m'y pencher plus tard

``code NomDuFichier`` et sa m'ouvre une page vscode une nouvelle qui na aucun rapport avec la page ou je suis

``code .`` fonctionne 
``code nomVoulueDuFichier.js`` ouvre une page avec une page vscode qui fonctionne avec le .html .css .js ect

``notepad nomDuFichier`` permet de créer un fichier

``touch nomDuFichier`` a la meme fonction que notepad sa créer un fichier de préférence utiliser touch sur gitbash

``mv nomDuFichier nomDuRepertoire`` sa c'est déplacer des fichier dans différent dossier  
autre exemple tu peut utiliser mv comme ceci 

``mv nomDuRepertoire/nomDufichier .`` pour dire déplace le fichier de ce repertoire ICI 

si par exemple tu souhaite déplacer TOUT le contenue d'un répertoire a un autre tu peut utiliser <br>
``mv nomDuRepertoire/* nomDuRepertoire`` l'étoile permet de selectionner TOUT ce que contient le contenue du repertoire que tu souhaite déplacer 

``cp nomDufichier nomDuRepertoire`` cp permet de copier un fichier et de déplacer la copie dans un autre dossier 

si par exemple tu souhaite copier un repertoire avec son contenue  tu peut utiliser <br>
``cp -r nomDuRepertoire nomDeLaCopieDuRepertoire``
sa va copier tout le continue du repertoire a l'emplacement ou tu es <br>
le ``-r`` permet de dire que tu souhaite interagir  avec un repertoire

si tu ne te souvien pas de la comande entiere tu peut taper <br>
``m*`` en appuyant sur ``tab`` a plusieur reprise tu peut voir que différente commande comencant par ``m`` vont s'afficher continue a appuyer sur tab jusqu'a tomber sur celle qui t'interesse

Avec ``rm nomDuFichier`` tu peut suprimer des fichier <br>
avec ``rm -r nomDuRepertoire`` tu peut surpimer un repertoire

``cat nomDuFichier`` permet de voir le contenue d'un fichier

``less nomDuFichier`` permet de voir le contenue d'un fichier MAIS dans une "autre fenetre" et avec les fleche vers le bas et vers le haut vous pouvez aller vers le haut et le bas pour voir le contenue.<br> pour revenir en arriere press ``q`` une fois suffis

``ls > nomDuFichier`` cette permet que ce que montre la comande ``ls`` ne le montre pas mais sois transférer dans le fichier ``nomDuFichier`` Si le fichier en question n'est pas créer la comande le créer et metras le contenue a l'interieur

``ls`` permet de voir le contenue du repertoire ou tu te trouve 











 









