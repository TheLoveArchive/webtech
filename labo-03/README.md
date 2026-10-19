# Labo 3 - reflecties

Naam: Varun Singh


## 1. Kleurenstalen

- Welke twee waarden uit de user agent stylesheet moest je op de lijst wegwerken, en waar las je ze af?

De margin en padding van de ul. Ik kon deze zien in de DevTools bij de user agent stylesheet.

- Wat verandert er aan de banden als je het venster hoger maakt, en wat verandert er niet?

De banden worden hoger omdat de hoogte met vh is ingesteld. De breedte blijft de volledige breedte van het scherm.


## 2. Slogan

- Welke property centreerde de tekst, en welke de kolom?

text-align: center centreerde de tekst. Met margin: auto werd de kolom zelf gecentreerd.

- Waarom werkte de padding op de knop pas na display: inline-block?

Omdat de link standaard inline is. Met display: inline-block werkt de padding beter als een blok rond de knop.


## 3. Tabblad

- Wat is de visuele breedte van het tabblad, en waarom is dat exact 15rem en geen 15rem plus padding plus border?

De visuele breedte is 15rem. Dit komt door box-sizing: border-box. Daardoor zitten de padding en border al in die 15rem.


## 4. Donut

- Waarom werkt height: 70% op de cirkel, terwijl F3.2 zegt dat een procentuele hoogte meestal niets doet?

Omdat de ouder een vaste hoogte heeft. Daardoor kan de browser berekenen hoeveel 70% van die hoogte is.

- Tegen welke maat van de ouder rekende de browser margin: 15%: de breedte of de hoogte?

Tegen de breedte van de ouder.


## 5. Landingspagina

- Gaf je main een height of een min-height, en waarom?

Ik gebruikte min-height. Zo heeft main een minimale hoogte, maar kan het nog groter worden als er meer inhoud in staat.

- Wat gebeurt er met de twee helften als je een regeleinde zet tussen </article> en <div class="afbeelding">?

Er komt whitespace tussen de twee inline-block elementen. Die whitespace neemt ook plaats in waardoor de twee helften mogelijk niet meer mooi naast elkaar passen.


## Thuis: B3.1 (met AI of zonder AI)

Welke route koos je?

Ik koos de AI-route.

Bij de AI-route: prompt en onbewerkte output staan in site/review/, en dit corrigeerde ik:

1. Ik controleerde de gebruikte CSS-properties met de leerstof.
2. Ik paste stukken CSS aan die niet overeenkwamen met wat we in de cursus hadden gezien.
3. Ik testte het resultaat zelf in de browser en gebruikte DevTools om fouten te vinden.