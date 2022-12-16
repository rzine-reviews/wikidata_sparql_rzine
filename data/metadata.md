3 types de jeux de données sont mis à disposition :  
- les données au format CSV (séparateur ","") extraites de Wikidata à partir des requêtes explicitées (data, data1 et data2.csv),  
- les données image au format JPG issues de ces requêtes,  
- les données géographiques nécessaires pour la jointure.  

data.csv contient les données suivantes :
- "image" : l'url de l'image de l'oeuvre, de type chaîne de caractères,  
- "nomLabel" : le nomen du lieu d'exposition de l'oeuvre, de type chaîne de caractères,  
- "dated","datef" : les dates respectivement de début et de fin de l'exposition de l'oeuvre, de type date au format JJJJ-MM-AA,  
- "coord" : les coordonnées géo-spatiales du lieu d'exposition, sous la forme d'un point(x,y).  

data1.csv contient l'identifiant Wikidata de Johannes Vermeer et l'url de l'image Wikimédia associée.  

data2.csv contient les données suivantes :  
- "oeuvreLabel" : le nomen de l'oeuvre, de type chaîne de caractères,  
- "museeLabel" : le nomen du lieu d'exposition, de type chaîne de caractères,  
- "coord" : la localisation du lieu, sous la forme d'un point(x,y).

Le dossier "images" contient les deux images issues Wikimédia du peintre et de l'oeuvre au format jpg.

Le dossier "world" contient les données géographiques nécessaires à la jointure cartographique.