# Cour SQL
SQL (sigle de Structured Query Language, en français langage de requête structurée) est un langage informatique normalisé servant à exploiter des bases de données relationnelles. La partie langage de manipulation des données de SQL permet de rechercher, d'ajouter, de modifier ou de supprimer des données dans les bases de données relationnelles.
## Création d'une base de données
Les instructions de manipulation des métadonnées - description de la structure, l'organisation et les caractéristiques de la base de données - commencent avec les mots-clés CREATE, ALTER, DROP, RENAME, COMMENT ou TRUNCATE qui correspondent aux opérations d'ajouter, modifier, supprimer, renommer, commenter ou vider une métadonnée. Ces mots clés sont immédiatement suivis du type de métadonnée à manipuler - TABLE, VIEW, INDEX...  
Pour ouvrir mysql dans le cmd il faut se rendre dans le bon repertoire :  
C:\MAMP\bin\mysql\bin  
Il faut ensuite ecrire dans l'url la commade suivante : cmd  
Puis dans le terminal :  
```
mysql -u root -p
```
Le terminal me demande de saisir le mot de passe :  
![terminal](https://github.com/MessaliHadj/SQL/blob/main/img/Capture.PNG)

Pour créer une BDD il faut utiliser le mot clé CREATE :  

```
CREATE DATABASE mabdd;
```
Pour voir mes BDD la commande est la suivante :  
```
SHOW DATABASES;
```
Pour utilser et agir sur cette BDD j'utilise la commande :  
```
USE mabdd;
```