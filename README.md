# Examen_ACourtin_2022_datavisualisation

## INTRODUCTION

Dans le cadre de notre cours portant sur l'Analyse des données et Datavisualisation, j'ai choisi de travailler sur les établissement cinématographiques français actifs au 31.12.2020. Le but dérriere ce travail est de pouvoir mettre en exergue via une visualisation (carte, graphique etc.) certaines données liées à ces établissement.   
Ainsi, nous nous sommes concentrés à visualiser les données tellesque le nombre de ces établissemnts sur une région donnée par exemple voire une vue par département (ceux de l'île-de-france) ainsi que leurs emplacements, mais aussi de ressorir certaines informations utiles comme les établissements qui sont des multiplexe(plusde 8 écrans) ainsi que leurs coordonnées ou encore celles relatives aux parts de marchés sur une année par type de films (français, européens, américains).   
De prime abord, il convient de noter que ce travail a été réalisé à l'aide d'un jeu de données sur les établissements cinématographiques en France. En outre, j'ai beaucoup joué sur le filtrage de ce fichier afin de pouvoir travailler sur les données d'une région en l'occurence celles des établissements se trouvant en Ile-de-France. En effet, la majeure partie de mon travail s'est concentré sur cette région.  
Ce jeu de donnée est disponible sur le portail opendata du Ministère de la culture [Géolocalisation des établissements cinématographiques en France](https://data.culture.gouv.fr/explore/dataset/etablissements-cinematographiques/information/?dataChart=eyJxdWVyaWVzIjpbeyJjaGFydHMiOlt7InR5cGUiOiJjb2x1bW4iLCJmdW5jIjoiQ09VTlQiLCJzY2llbnRpZmljRGlzcGxheSI6dHJ1ZSwiY29sb3IiOiIjOGRhMGNiIn1dLCJ4QXhpcyI6InJlZ2lvbl9hZG1pbmlzdHJhdGl2ZSIsIm1heHBvaW50cyI6NTAsInNvcnQiOiIiLCJjb25maWciOnsiZGF0YXNldCI6ImV0YWJsaXNzZW1lbnRzLWNpbmVtYXRvZ3JhcGhpcXVlcyIsIm9wdGlvbnMiOnt9fX1dLCJ0aW1lc2NhbGUiOiIiLCJkaXNwbGF5TGVnZW5kIjp0cnVlLCJhbGlnbk1vbnRoIjp0cnVlfQ%3D%3D&location=5,46.53754,2.40395)  
Par ailleurs, dans une démarche comparative des données, j'ai un peu travaillé aussi sur un autre jeu de donné traitant uniquement les établissements cinématographiques se trouvant en Ile-de-France. Ce dernier est disponible sur le portail opendata de la région [les salles de cinéma en Ile-de-France ](https://data.iledefrance.fr/explore/dataset/les_salles_de_cinemas_en_ile-de-france/information/?location=10,49.07117,2.34764&basemap=jawg.streets)   
******
### Visualisation des salles de cinéma en Ile-de-France    
- Aperçu des salles de cinéma en île-de-France selon leur situation géographique  
``<iframe src="https://data.opendatasoft.com/chart/embed/?dataChart=eyJ0aW1lc2NhbGUiOiIiLCJxdWVyaWVzIjpbXSwiYWxpZ25Nb250aCI6dHJ1ZX0%3D&static=false&datasetcard=false" width="400" height="300" frameborder="0"></iframe> ```  

- Explication  
Dans cette carte j'ai essayé de représenté les salles de cinéma à travers de leur situation géographique en Ile-de-France. Ici, la situation géographique est établie par trois (3) zones : *Paris*, *la Petite couronne* et *la Grande couronne*. Ainsi, les marqueurs en bleu representent les établissemnets situés à Paris (75), ceux en vert représentent les salles qui sont localisées sur la Grande couronne et enfin les marqueurs en violet sont ceux de la Petite couronne.  

###Visualisation   
![Part de marché des films pour les cinémas localisés en Ile-de-France](https://github.com/BA199/examen_BA_infoviz_2022/blob/main/PdmFilms_2020_IDF.jpg)   

```html
<iframe frameborder="0" width="800" height="600" src="https://data.opendatasoft.com/map/embed/sallescinematographiques_iledefrance/?&static=false&scrollWheelZoom=false"></iframe>``
