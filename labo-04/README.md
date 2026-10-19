# Labo 4 - reflecties

Naam: Varun Singh

## 1. Drie kolommen

- display: flex staat op main. flex staat op de drie div-kolommen.
- Ze staan niet op hetzelfde element omdat main de layout regelt en de divs bepalen hoeveel ruimte ze krijgen.

## 2. Navigatiebalk

- justify-content verdeelt de ruimte langs de hoofdas. align-items lijnt elementen uit op de kruisas.
- Met gap komt er alleen ruimte tussen de links. Met margin-right krijgt ook de laatste link nog extra ruimte rechts. Daarom is gap meestal netter.

## 3. Mondriaan

- De vlakken lila en olijf moesten expliciet geplaatst worden met grid-column, omdat ze meerdere kolommen breed zijn. De andere vier vlakken vullen automatisch de eerstvolgende vrije cel in het grid, waardoor expliciete plaatsing niet nodig is.
- Met gap ontstaan de blauwe lijnen doordat de achtergrond van het raster zichtbaar blijft tussen de vakken. Met een border krijgt elk vlak een eigen rand, wat moeilijker te beheren is en minder overeenkomt met het ontwerp.

## 4. Trap

- Dan komen de treden niet meer diagonaal te staan. Grid plaatst ze automatisch in de eerstvolgende vrije cel, waardoor ze naast elkaar op de eerste rij terechtkomen. De grid-row-declaraties zorgen ervoor dat elke trede in een andere rij staat.
- grid-column: 4 / -1 betekent dat de trede begint op lijn 4 en eindigt op de laatste gridlijn. In een raster met 4 kolommen is de laatste lijn lijn 5. Daarom werkt dit hetzelfde als grid-column: 4 / 5. -1 verwijst altijd naar de laatste gridlijn van het raster.

## 5. Dierenasiel Zonnehoek

- Hoeveel layoutcontainers telt deze pagina, en welk gereedschap koos je voor elk?
- Verklein het venster tot de helft: wat breekt er, en in welk hoofdstuk wordt dat opgelost?

## Thuis: B4.1 (met AI of zonder AI)

Welke route koos je? Bij de AI-route: prompt en onbewerkte output staan in `site/review/`, en dit corrigeerde ik (met verwijzing naar de sectie of het foutnummer):

1. 
2. 
3. 
