Projet Java - Sujet 11 - Gestionnaire d'albums de Musique

Merci d'avoir pris le temps de télécharger notre projet et de voir les résultats.
Dans le dossier, il y a :
- Un dossier contenant le projet NetBeans comme ça vous pourrez l'utiliser avec NetBeans

Dans le dossier contenant le projet NetBeans, il y a :
- Le driver JDBC sqlite pour faire fonctionner la BDD
- la base de données contenue dans un fichier nommé base.db
- Le compte-rendu du projet en pdf
- Les fichiers sources contenus dans le répertoire "src" et les fichiers .form pour éditer l'application depuis l'IDE
- Les images utiles dans l'application contenus dans le répertoire "images".
- Un dossier contenant les images utiles pour l'application
- Le doxyfile pour générer la documentation Doxygen
- Le dossier graphviz permettant de générer les diagrammes

Pour compiler à la main :
Placez vous dans le répertoire où se trouvent les fichiers java et éxécutez la commande javac -encoding utf8 *.java
Cela va créer les fichiers .class.
Puis vous devez faire la commande : java -classpath .;sqlite-jdbc-3.30.1.jar Main
Cela va exécuter le programme avec le driver JDBC

Pour avoir la documentation style javadoc :
Placer vous dans le répertoire précédant celui où se trouvent les fichiers java et éxécutez la commande : "javadoc -encoding utf8 -docencoding utf8 -charset utf8 -d doc src/*.java "cela va générer un dossier doc
L'encoding utf8 permettra d'afficher les accents dans la javadoc, ce qui est quand même un grand plus

Merci d'avoir lu !
BOUHENAF Irfan et MOLINA Romain