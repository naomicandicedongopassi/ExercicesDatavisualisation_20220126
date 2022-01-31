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
<svg xmlns="http://www.w3.org/2000/svg" width="805" height="600"><rect width="805" height="600" x="0" y="0" fill="#FFFFFF" id="backgorund"/><g transform="translate(10,10)" id="viz"><g id="leaves"><g transform="translate(8,8)"><rect id="path0" fill="#1f77b4" width="107" height="68"/><clipPath id="clip0"><use xmlns:ns1="http://www.w3.org/1999/xlink" ns1:href="#path0"/></clipPath><text clip-path="url(#clip0)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">14</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Bibliothèque François Mitterrand</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g><g transform="translate(8,86)"><rect id="path1" fill="#1f77b4" width="107" height="67"/><clipPath id="clip1"><use xmlns:ns2="http://www.w3.org/1999/xlink" ns2:href="#path1"/></clipPath><text clip-path="url(#clip1)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">14</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Cour Saint-Émilion</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g><g transform="translate(125,8)"><rect id="path2" fill="#1f77b4" width="108" height="68"/><clipPath id="clip2"><use xmlns:ns3="http://www.w3.org/1999/xlink" ns3:href="#path2"/></clipPath><text clip-path="url(#clip2)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">14</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Saint-Lazare</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g><g transform="translate(125,86)"><rect id="path3" fill="#1f77b4" width="108" height="67"/><clipPath id="clip3"><use xmlns:ns4="http://www.w3.org/1999/xlink" ns4:href="#path3"/></clipPath><text clip-path="url(#clip3)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">14</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Bercy</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g><g transform="translate(243,8)"><rect id="path4" fill="#1f77b4" width="107" height="68"/><clipPath id="clip4"><use xmlns:ns5="http://www.w3.org/1999/xlink" ns5:href="#path4"/></clipPath><text clip-path="url(#clip4)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">14</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Gare de Lyon</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g><g transform="translate(243,86)"><rect id="path5" fill="#1f77b4" width="107" height="67"/><clipPath id="clip5"><use xmlns:ns6="http://www.w3.org/1999/xlink" ns6:href="#path5"/></clipPath><text clip-path="url(#clip5)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">14</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Olympiades</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g><g transform="translate(360,8)"><rect id="path6" fill="#1f77b4" width="48" height="145"/><clipPath id="clip6"><use xmlns:ns7="http://www.w3.org/1999/xlink" ns7:href="#path6"/></clipPath><text clip-path="url(#clip6)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">14</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Pyramides</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g><g transform="translate(418,8)"><rect id="path7" fill="#1f77b4" width="49" height="145"/><clipPath id="clip7"><use xmlns:ns8="http://www.w3.org/1999/xlink" ns8:href="#path7"/></clipPath><text clip-path="url(#clip7)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">14</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Madeleine</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g><g transform="translate(8,167)"><rect id="path8" fill="#1f77b4" width="169" height="94"/><clipPath id="clip8"><use xmlns:ns9="http://www.w3.org/1999/xlink" ns9:href="#path8"/></clipPath><text clip-path="url(#clip8)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">A</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Charles-de-Gaulle - Étoile</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g><g transform="translate(8,271)"><rect id="path9" fill="#1f77b4" width="110" height="146"/><clipPath id="clip9"><use xmlns:ns10="http://www.w3.org/1999/xlink" ns10:href="#path9"/></clipPath><text clip-path="url(#clip9)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">A</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Gare de Châtelet – Les Halles</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g><g transform="translate(124,271)"><rect id="path10" fill="#1f77b4" width="53" height="146"/><clipPath id="clip10"><use xmlns:ns11="http://www.w3.org/1999/xlink" ns11:href="#path10"/></clipPath><text clip-path="url(#clip10)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">A</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Gare de Châtelet – Les Halles</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g><g transform="translate(8,427)"><rect id="path11" fill="#1f77b4" width="169" height="41"/><clipPath id="clip11"><use xmlns:ns12="http://www.w3.org/1999/xlink" ns12:href="#path11"/></clipPath><text clip-path="url(#clip11)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">A</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Nanterre-Préfecture</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g><g transform="translate(8,478)"><rect id="path12" fill="#1f77b4" width="81" height="94"/><clipPath id="clip12"><use xmlns:ns13="http://www.w3.org/1999/xlink" ns13:href="#path12"/></clipPath><text clip-path="url(#clip12)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">A</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Noisy-le-Grand – Mont d'Est</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g><g transform="translate(95,478)"><rect id="path13" fill="#1f77b4" width="82" height="94"/><clipPath id="clip13"><use xmlns:ns14="http://www.w3.org/1999/xlink" ns14:href="#path13"/></clipPath><text clip-path="url(#clip13)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">A</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Noisy-le-Grand – Mont d'Est</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g><g transform="translate(187,167)"><rect id="path14" fill="#ff7f0e" width="62" height="118"/><clipPath id="clip14"><use xmlns:ns15="http://www.w3.org/1999/xlink" ns15:href="#path14"/></clipPath><text clip-path="url(#clip14)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">A</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Saint-Maur – Créteil</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">oui</tspan></text></g><g transform="translate(259,167)"><rect id="path15" fill="#1f77b4" width="63" height="118"/><clipPath id="clip15"><use xmlns:ns16="http://www.w3.org/1999/xlink" ns16:href="#path15"/></clipPath><text clip-path="url(#clip15)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">A</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Val d'Europe</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g><g transform="translate(332,167)"><rect id="path16" fill="#1f77b4" width="62" height="118"/><clipPath id="clip16"><use xmlns:ns17="http://www.w3.org/1999/xlink" ns17:href="#path16"/></clipPath><text clip-path="url(#clip16)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">A</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Auber</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g><g transform="translate(404,167)"><rect id="path17" fill="#1f77b4" width="63" height="118"/><clipPath id="clip17"><use xmlns:ns18="http://www.w3.org/1999/xlink" ns18:href="#path17"/></clipPath><text clip-path="url(#clip17)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">A</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Gare de Nanterre – Université</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g><g transform="translate(187,295)"><rect id="path18" fill="#1f77b4" width="151" height="47"/><clipPath id="clip18"><use xmlns:ns19="http://www.w3.org/1999/xlink" ns19:href="#path18"/></clipPath><text clip-path="url(#clip18)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">A</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Rueil-Malmaison</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g><g transform="translate(187,352)"><rect id="path19" fill="#1f77b4" width="151" height="50"/><clipPath id="clip19"><use xmlns:ns20="http://www.w3.org/1999/xlink" ns20:href="#path19"/></clipPath><text clip-path="url(#clip19)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">A</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Saint-Germain-en-Laye station</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g><g transform="translate(187,408)"><rect id="path20" fill="#1f77b4" width="151" height="49"/><clipPath id="clip20"><use xmlns:ns21="http://www.w3.org/1999/xlink" ns21:href="#path20"/></clipPath><text clip-path="url(#clip20)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">A</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Saint-Germain-en-Laye station</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g><g transform="translate(187,467)"><rect id="path21" fill="#1f77b4" width="151" height="48"/><clipPath id="clip21"><use xmlns:ns22="http://www.w3.org/1999/xlink" ns22:href="#path21"/></clipPath><text clip-path="url(#clip21)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">A</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Gare de Lyon</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g><g transform="translate(187,525)"><rect id="path22" fill="#1f77b4" width="151" height="47"/><clipPath id="clip22"><use xmlns:ns23="http://www.w3.org/1999/xlink" ns23:href="#path22"/></clipPath><text clip-path="url(#clip22)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">A</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Gare de Marne-la-Vallée - Chessy</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g><g transform="translate(348,295)"><rect id="path23" fill="#1f77b4" width="55" height="134"/><clipPath id="clip23"><use xmlns:ns24="http://www.w3.org/1999/xlink" ns24:href="#path23"/></clipPath><text clip-path="url(#clip23)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">A</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Nogent-sur-Marne (Paris RER)</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g><g transform="translate(413,295)"><rect id="path24" fill="#1f77b4" width="54" height="134"/><clipPath id="clip24"><use xmlns:ns25="http://www.w3.org/1999/xlink" ns25:href="#path24"/></clipPath><text clip-path="url(#clip24)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">A</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Nanterre – Ville</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g><g transform="translate(348,439)"><rect id="path25" fill="#1f77b4" width="55" height="133"/><clipPath id="clip25"><use xmlns:ns26="http://www.w3.org/1999/xlink" ns26:href="#path25"/></clipPath><text clip-path="url(#clip25)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">A</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">La Défense</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g><g transform="translate(413,439)"><rect id="path26" fill="#1f77b4" width="54" height="133"/><clipPath id="clip26"><use xmlns:ns27="http://www.w3.org/1999/xlink" ns27:href="#path26"/></clipPath><text clip-path="url(#clip26)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">A</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Nation</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g><g transform="translate(481,8)"><rect id="path27" fill="#1f77b4" width="34" height="186"/><clipPath id="clip27"><use xmlns:ns28="http://www.w3.org/1999/xlink" ns28:href="#path27"/></clipPath><text clip-path="url(#clip27)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">13</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Les Agnettes</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g><g transform="translate(481,204)"><rect id="path28" fill="#1f77b4" width="34" height="185"/><clipPath id="clip28"><use xmlns:ns29="http://www.w3.org/1999/xlink" ns29:href="#path28"/></clipPath><text clip-path="url(#clip28)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">13</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Les Courtilles</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g><g transform="translate(529,8)"><rect id="path29" fill="#1f77b4" width="76" height="97"/><clipPath id="clip29"><use xmlns:ns30="http://www.w3.org/1999/xlink" ns30:href="#path29"/></clipPath><text clip-path="url(#clip29)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">B</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Gare d'Antony</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g><g transform="translate(615,8)"><rect id="path30" fill="#ff7f0e" width="76" height="97"/><clipPath id="clip30"><use xmlns:ns31="http://www.w3.org/1999/xlink" ns31:href="#path30"/></clipPath><text clip-path="url(#clip30)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">B</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">gare d'Arcueil - Cachan</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">oui</tspan></text></g><g transform="translate(701,8)"><rect id="path31" fill="#1f77b4" width="76" height="97"/><clipPath id="clip31"><use xmlns:ns32="http://www.w3.org/1999/xlink" ns32:href="#path31"/></clipPath><text clip-path="url(#clip31)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">B</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Gare de Bourg-la-Reine</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g><g transform="translate(529,115)"><rect id="path32" fill="#1f77b4" width="76" height="97"/><clipPath id="clip32"><use xmlns:ns33="http://www.w3.org/1999/xlink" ns33:href="#path32"/></clipPath><text clip-path="url(#clip32)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">B</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Gare de Cité Universitaire</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g><g transform="translate(615,115)"><rect id="path33" fill="#ff7f0e" width="76" height="97"/><clipPath id="clip33"><use xmlns:ns34="http://www.w3.org/1999/xlink" ns34:href="#path33"/></clipPath><text clip-path="url(#clip33)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">B</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Gare de Massy-Palaiseau</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">oui</tspan></text></g><g transform="translate(701,115)"><rect id="path34" fill="#ff7f0e" width="76" height="97"/><clipPath id="clip34"><use xmlns:ns35="http://www.w3.org/1999/xlink" ns35:href="#path34"/></clipPath><text clip-path="url(#clip34)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">B</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Gare de Saint-Rémy-lès-Chevreuse</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">oui</tspan></text></g><g transform="translate(529,222)"><rect id="path35" fill="#1f77b4" width="93" height="79"/><clipPath id="clip35"><use xmlns:ns36="http://www.w3.org/1999/xlink" ns36:href="#path35"/></clipPath><text clip-path="url(#clip35)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">B</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Gentilly</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g><g transform="translate(529,311)"><rect id="path36" fill="#1f77b4" width="93" height="78"/><clipPath id="clip36"><use xmlns:ns37="http://www.w3.org/1999/xlink" ns37:href="#path36"/></clipPath><text clip-path="url(#clip36)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">B</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Robinson</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g><g transform="translate(632,222)"><rect id="path37" fill="#ff7f0e" width="68" height="108"/><clipPath id="clip37"><use xmlns:ns38="http://www.w3.org/1999/xlink" ns38:href="#path37"/></clipPath><text clip-path="url(#clip37)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">B</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Laplace (Paris - RER)</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">oui</tspan></text></g><g transform="translate(710,222)"><rect id="path38" fill="#1f77b4" width="67" height="108"/><clipPath id="clip38"><use xmlns:ns39="http://www.w3.org/1999/xlink" ns39:href="#path38"/></clipPath><text clip-path="url(#clip38)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">B</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Gare de Denfert-Rochereau</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g><g transform="translate(632,340)"><rect id="path39" fill="#1f77b4" width="145" height="49"/><clipPath id="clip39"><use xmlns:ns40="http://www.w3.org/1999/xlink" ns40:href="#path39"/></clipPath><text clip-path="url(#clip39)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">B</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Gif-sur-Yvette Station</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g><g transform="translate(481,403)"><rect id="path40" fill="#1f77b4" width="89" height="78"/><clipPath id="clip40"><use xmlns:ns41="http://www.w3.org/1999/xlink" ns41:href="#path40"/></clipPath><text clip-path="url(#clip40)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">5</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Bobigny – Pablo Picasso</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g><g transform="translate(481,495)"><rect id="path41" fill="#1f77b4" width="89" height="77"/><clipPath id="clip41"><use xmlns:ns42="http://www.w3.org/1999/xlink" ns42:href="#path41"/></clipPath><text clip-path="url(#clip41)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">6</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Trocadéro</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g><g transform="translate(584,403)"><rect id="path42" fill="#1f77b4" width="90" height="78"/><clipPath id="clip42"><use xmlns:ns43="http://www.w3.org/1999/xlink" ns43:href="#path42"/></clipPath><text clip-path="url(#clip42)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">1</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Charles de Gaulle – Étoile</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g><g transform="translate(584,495)"><rect id="path43" fill="#ff7f0e" width="90" height="77"/><clipPath id="clip43"><use xmlns:ns44="http://www.w3.org/1999/xlink" ns44:href="#path43"/></clipPath><text clip-path="url(#clip43)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">7</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Villejuif - Louis Aragon</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">oui</tspan></text></g><g transform="translate(688,403)"><rect id="path44" fill="#1f77b4" width="89" height="78"/><clipPath id="clip44"><use xmlns:ns45="http://www.w3.org/1999/xlink" ns45:href="#path44"/></clipPath><text clip-path="url(#clip44)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">10</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Cluny – La Sorbonne</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g><g transform="translate(688,495)"><rect id="path45" fill="#1f77b4" width="89" height="77"/><clipPath id="clip45"><use xmlns:ns46="http://www.w3.org/1999/xlink" ns46:href="#path45"/></clipPath><text clip-path="url(#clip45)" font-family="Arial, sans-serif" font-size="10" dominant-baseline="text-before-edge" class="txt"><tspan x="3" y="0.2em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: bold;">12</tspan><tspan x="3" y="1.3em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal;">Concorde</tspan><tspan x="3" y="2.4000000000000004em" style="font-family: Arial, sans-serif; font-size: 10px; fill: black; font-weight: normal; font-style: italic;">non</tspan></text></g></g></g></svg>

