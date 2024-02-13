# SUJET_4ETI_AdmCO_20232024 Thomas SANDIER

1/ Ce code permet de faire la somme de deux variables

2/ requirment.txt permet de communiquer à toute l’équipe les bibliothèque à installer afin de faire fonctionner correctement le code sur le pc du nouvel utilisateur.

3/ un package est un dossier contenant un ensemble de module python. Ces modules peuvent être importer dans un code python avec la commande « import mon_package.module » (ici mon_package est un package donc un dossier et module est un module). Dans un package on retrouve un fichier __init__.py qui renseigne python sur le fait que le dossier est un package 

4/ import addition.py 

5/ pip permet d’installer, de mettre à jour ou gérer des bibliothèques/modules python 

6/ pythonpath est une variable d’environnement utilisé par l’interpréteur python pour déterminer dans quels répértoires rechercher les module python lorsqu’ils sont importés dans un script.

7/ On retrouve les paquets installé par pip dans le dossier ou a été installé python.

8/ Cela permet d’installer des paquets python uniquement pour l’utilisateur courant

9/ cela permet de créer un environement virtuel. Un environnement virtuel créé avec venv est un environnement isolé au niveau du système d'exploitation où les bibliothèques Python sont installées. Cela permet d’éviter des conflits entre les différentes bibliothèque python.

10/ Une fois dans dans notre projet il suffit de créer l’environnement virtuel avec : 
python -m venv nom_de_votre_environnement
Il faut ensuite l’activer avec : source mon_environnement/bin/activate

11/ Docker est une plateforme open source qui automatise le déploiement d'applications dans des conteneurs logiciels. Les conteneurs sont des environnements légers et portables qui contiennent tout ce dont une application a besoin pour s'exécuter, y compris le code, les bibliothèques système, les dépendances et les fichiers système de base. Docker permet aux développeurs de packager une application avec toutes ses dépendances dans un conteneur, garantissant ainsi que l'application fonctionnera de la même manière sur n'importe quel environnement.

12/ Pour l’utiliser il faut d’abord l’installer. Il faut ensuite créer un Dockerfile dans le repertoire du projet. Après il faut créer une image Docker avec la commande docker build :
« docker build -t nom_de_votre_image chemin_vers_le_dockerfile »
Il ne reste plus qu’a éxecuter le conteneur docker grâce à la commande docker run :
« docker run nom_de_votre_image ».


Exercice 1 : https://gitlab.com/thomassandier/tp1_ex1

Exercice 2 : https://gitlab.com/thomassandier/tp1_ex2

Exercice 3 : https://gitlab.com/thomassandier/tp1_ex3

Exercice 4 : https://gitlab.com/thomassandier/tp1_ex4

Exercice 5 : https://gitlab.com/thomassandier/tp1_ex5

Exercice 6 : https://gitlab.com/thomassandier/tp1_ex6

Exercice 7 (contient également les fichier attendu dans l'exercice 8) : https://gitlab.com/thomassandier/tp1_ex7

Je n'ai pas réussi à aller au bout de l'exercice 9 car je n'ai pas réussi à faire fonctionner twine sur mon ordinateur personnel

