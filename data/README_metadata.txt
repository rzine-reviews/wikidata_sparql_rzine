----------------------------------------------------------------------------------------------------------------
# Données associées à la fiche Rzine : "Spatio-temporal Wikidata. Exploration de données collaboratives du web 3.0"
----------------------------------------------------------------------------------------------------------------

Le code R utilisé pour télécharger (requêter) ces données est présenté dans la fiche Rzine (DOI : )
Trois types de données sont mis à disposition :  

1. Fichiers CSV (séparateur virgule) qui contiennent des données extraites de Wikidata à partir des requêtes explicitées dans la fiche,  
2. Images JPG extraites de Wikidata à partir des requêtes explicitées dans la fiche
3. Couche géographique Natural Earth (fond de carte pays) récupérée via la package rnaturalearth, 



1. Les fichiers csv

1.a. 'data1_WR.csv' contient :  
- l'identifiant de l'artiste Johannes Vermeer (Q41264) - chaîne de caractères

1.b. 'data1_WQSR.csv' contient :  
- "identifiant" : URL de la page wikidata de Johannes Vermeer (Q41264) - chaîne de caractères

2.a. 'data2_WR.csv' contient :  
- "oeuvre" : identifiant wikidata des oeuvres - chaîne de caractères,
- "musee" : identifiant wikidata des musées - chaîne de caractères,
- "coord" : coordonnées des lieux d'exposition - chaîne de caractères au format WKT.  

2.b. 'data2_WQSR.csv' contient :  
- "oeuvreLabel" : intitulé des œuvres de Johannes Vermeer - chaîne de caractères,  
- "museeLabel" : nom des différents lieux d'exposition (musées) des œuvres - chaîne de caractères,  
- "coord" : coordonnées des lieux d'exposition - chaîne de caractères au format WKT.  

3. 'data3_WQSR' contient :
- "museeLabel" :  nom des différents lieux d'exposition (musées) des œuvres - chaîne de caractères,
- "dated" et "datef" : dates respectivement de début et de fin de l'exposition de l’œuvre - chaîne de caractères au format date 'JJJJ-MM-AA',  
- "coord" : coordonnées du lieu d'exposition - chaîne de caractères au format WKT.  



2. Les images

Le répertoire 'images' contient deux images issues Wikimédia :
a. Image du portait de l'artiste Johannes Vermeer (portrait_artiste.jpg),
b. Image de l'œuvre "A Young Woman Seated at the Virginals" de Johannes Vermeer (Q4660880.jpg) : 




3. La couche géographique 

Le répertoire 'world' contient une couche géographique Natural Earth (fond de carte pays) au format shapefile, nommée 'ne_50m_admin_0_countries'.
Cette couche géographique a directement été récupérée avec R en utilisant la package rnaturalearth. Elle peut également être téléchargée depuis le site de Natural Earth à cette url : https://www.naturalearthdata.com/downloads/50m-cultural-vectors/50m-admin-0-countries-2/




