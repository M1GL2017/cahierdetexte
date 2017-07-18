# Liens utiles
Tutoriel pour débuter avec git
https://fr.wikipedia.org/wiki/Git
https://www.grafikart.fr/formations/git
https://services.github.com/on-demand/downloads/fr/github-git-cheat-sheet.pdf	
http://rogerdudler.github.io/git-guide/index.fr.html

#Commandes

#Configuration
cd c:/GITBEB
git init
git config --global user.name "mariendiayethinkpad"
git config --global user.email marie.ndiaye@univ-zig.sn
git config --global color.ui auto


#Initialisation
git clone https://github.com/M1GL2017/cahierdetexte.git

#Ajout du fichier README.txt dans "index"
git add [README.txt]

#Commit dans "head"
git commit -m "[message descriptif]"

#Récupère tout l'historique du dépôt
git pull origin

Envoie tous les commits de la branche locale vers GitHub [alias] [branche] 
#git push -u origin master 

