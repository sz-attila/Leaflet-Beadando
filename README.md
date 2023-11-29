# Leaflet-Beadando

A beadandómban a budapesti sportlétesítményeket gyűjtöttem össze és jelenítettem meg. Minden létesítmény saját, egyedi markerrel jelöltem be, illetve geo.json segítségével bejelöltem mindegyiknek a területét különböző színnel. A polygonok színei az adott létesítmény befogadóképsségének a nagyságát jelölik. Továbbá az olyan létesítményekre, amelyekben NB1-es vagy NB2-es futball van, raktam köröket. A körök sugarának nagysága a befogadóképesség nagyságával függ össze. Minnél nagyobb a kör sugara annál jobban ki van használva a létesítmény befogadóképessége.  A markerekhez csatoltam pop-up buborékokat is, amelyben a létesítmény nevét, átlagos nézőszámát, illetve befogadóképességét tüntetem fel. Továbbá használtam egy Image Overlay-t a Puskás Aréna területén, ahol megfigyelhető az aréna kezdeti állapota.

## Térképek

A munkám során három féle alaptérképet használtam fel, melyek az alábbiak:
- OSM alaptérkép
- MapTiler Streets V2
- MapTiler Satellite

## Rétegkezelés

A bejelölt sportlétesítményeket különböző rétegekbe csoportosítottam:
- NB1-es csapatok szerint
- NB2-es csapatok szerint
- Egyéb sporttevékenységek szerint

## Hivatkozások

Nézőszám adatok:
https://www.magyarfutball.hu/hu/merkozesek/bajnoki_merkozesek/nb_i/2022_2023/nezoszamok
https://www.magyarfutball.hu/hu/merkozesek/bajnoki_merkozesek/nb_ii/2022_2023/nezoszamok

Az alaptérképeket biztosította:
https://www.maptiler.com
