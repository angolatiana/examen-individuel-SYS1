
 	 Pour commencer le challenge débute par l’entrée du login donnée par le challenge WerChall suivie par le mot de passe de votre propre compte.
-	Le premier réflexe à avoir est de voir les fichiers contenue dans ce challenge en utilisant la commande ls
-	On y trouvera notamment les fichier WELCOME.md,  level,  www,  www_access.log,  www_error.log
-	Afficher le contenue du fichier en exécutant cat WELCOME.md
On y trouvera /home/level et /home/user/yournick/level
-	Entre dans répertoire /home/user/yournick/level à l’aide de la commande cd
-	Voir ce qu’il y a dans ce répertoire avec la commande ls
-	Puis exécuter la commande Cd 04_kwisatz pour accéder à se répertoire
-	Apres exécution de ls, on y trouvera README2.md dont on affichera le contenue avec la commande cat
-	Il s’y affichera que la permission n’est pas accordée
-	Pour remédier à cela, on doit exécuter Chmod 744 README2.md
-	Puis on y verra le mot de passe, flag : AndOfCourseIDoKnowChown

Après cela, revenir dans le répertoire personnel et refaire la commande ls pour afficher les deux choix possibles
-	Entrer dans le premier répertoire disponible en utilisant la commande cd
-	Voir les fichiers avec la commande ls
On y trouvera encore plusieurs répertoire 
-	Entre la commande cd pour aller dans le répertoire 00_welcome 
-	Voir les fichiers présents dans ce dernier 
-	On y trouvera README.md et on affichera le contenue avec la commande cat
-	On y trouvera le mot de passe : bitwarrior

En revenant au répertoire cd /home/level,
-	Voir ce qui se trouve dans 01_choice_tree avec la commande cd 
-	Voir les fichiers présents à l’aide de la commande ls, puis aller dans le répertoire blue par la commande cd
-	Faire la même chose en entrant dans les répertoires hats, grey, solution, patience
-	Arriver là, faire ls puis voire le contenue avec l’exécution de Cat SOLUTION.txt
-	On y trouvera notamment le mot de passe : patience

En revenant au répertoire /home/level,
-	Aller dans le répertoire 02 par la commande cd
-	Voir s’il y a des fichiers cacher par la commande ls –al
-	Entre la commande cd. porb
-	Cat .Solution
-	En y trouvera le mot de passe : HiddenIsConfig

De retour au répertoire  /home/level,
-	Faire cd 03 pour entrer dans le répertoire 03
-	A l’exécution de ls , on verra qu’il n’y a pas de fichier visible, donc voir s’il y a aussi présence de fichier cacher par la commande ls –al
-	Accéder au contenue du fichier . bash_history par la commande bash
-	On y trouvera le mot de passe du level : RepeatingHistory

En revenant dans /home/level 
-	Accéder au répertoire 05_privacy par la commande cd
-	Voir ce qu’il contient, toujours avec la commande ls
-	Utiliser la commande cat pour afficher ce que contient README .md
-	On y trouvera le mot de passe : OKPRIVATE

Après tout cela, pour valider le niveau, on entrera les mots de passe collecter dans la barre déjà fait pour cela dans le site de WeChall on est séparant par des virgules.

Voilà donc le write up de level 0 à 5
 

