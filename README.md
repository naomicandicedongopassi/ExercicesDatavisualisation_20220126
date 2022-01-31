## Exercice pour le 26 janvier 2022 

**Les lieux de conservation pour les sculptures d'Auguste Rodin uniquement conservées aux Etats-Unis**

Requête

```sparql
#Les sculptures d'Auguste Rodin 
#defaultView:Map
SELECT ?item ?image ?itemLabel ?lieuconservation ?lieuconservationLabel ?coordonneesgeo WHERE
{
  ?item wdt:P31 wd:Q860861 . # recherche des sculptures 
  ?item wdt:P170 wd:Q30755 . # les sculptures d'Auguste Rodin 
  
  OPTIONAL {
    ?item wdt:P18 ?image .
    ?item wdt:P276 ?lieuconservation .
    ?lieuconservation wdt:P625 ?coordonneesgeo . 
  }

SERVICE wikibase:label {bd:serviceParam wikibase:language "fr,en"}
  
}
```


Carte

<iframe style="width: 80vw; height: 50vh; border: none;" src="https://query.wikidata.org/embed.html#%23Les%20sculptures%20d'Auguste%20Rodin%20%0A%23defaultView%3AMap%0ASELECT%20%3Fitem%20%3Fimage%20%3FitemLabel%20%3Flieuconservation%20%3FlieuconservationLabel%20%3Fcoordonneesgeo%20%3Fpays%20WHERE%0A%7B%0A%20%20%3Fitem%20wdt%3AP31%2Fwdt%3AP279*%20wd%3AQ860861%20.%20%23%20recherche%20des%20sculptures%20%0A%20%20%3Fitem%20wdt%3AP170%20wd%3AQ30755%20.%20%23%20les%20sculptures%20d'Auguste%20Rodin%20%0A%20%20%0A%20%20OPTIONAL%20%7B%0A%20%20%20%20%3Fitem%20wdt%3AP18%20%3Fimage%20.%20%23%20les%20images%20%0A%20%20%20%20%3Fitem%20wdt%3AP276%20%3Flieuconservation%20.%20%23%20les%20lieux%20de%20conservation%20des%20sculptures%20%0A%20%20%20%20%3Flieuconservation%20wdt%3AP625%20%3Fcoordonneesgeo%20.%20%0A%20%20%7D%0A%0ASERVICE%20wikibase%3Alabel%20%7Bbd%3AserviceParam%20wikibase%3Alanguage%20%22fr%2Cen%22%7D%0A%20%20%0A%7D" referrerpolicy="origin" sandbox="allow-scripts allow-same-origin allow-popups"></iframe>


---------------


