<p align="center">
<img width="1080" align="center" src="https://i.imgur.com/dPX74Xc.jpg">
<h2 align="center">
  Project Steam
</h2>
<p align="center">
  Een interface met grafische weergaven van gaming gedrag.
</p>
<p align="center">
  <a style="text-decoration:none" href="https://store.steampowered.com/" target="_blank">
    <img src="https://img.shields.io/badge/Steam-Installeren-blueviolet" alt="Store link" />
  </a>




# Introductie
Steam wil haar klanten beter bedienen door meer grafische weergaves te maken van gaming gedrag naar verschillende klantsegmenten. 
Hiervoor heeft ze een consultancybedrijf ingehuurd. 
De hoofdopdracht luidt: 
"Maak een grafische weergave die inzicht geeft in het gaming gedrag van jouw vrienden op het platform Steam, ondersteund door een netwerk waarbij gebruik gemaakt wordt van een RaspberryPi."

# Hoe moet je hem installeren? (als eindgebruiker)

### Hardware eisen
- Windows 10 build 1903+ of later vereist.
- Een schermresolutie van 16:9 vereist.
- Een internetverbinding is vereist.

### Handleiding
- Download en extract de laatste `release`
- Rechtermuisknop op het `.zip` bestand en druk op hier uitpakken.

# Hoe gebruik je de grafische interface?

### Hoe run je de grafische interface source code
- Wees er zeker van dat je computer minstens draait op Windows 10 1903+
- Wees er zeker van dat [Python 3.9](https://www.python.org/downloads/release/python-390/) en [PyCharm 2021.3](https://www.jetbrains.com/pycharm/whatsnew/) is geinstalleerd.
- Wees er zeker van dat [Git](https://git-scm.com/) geinstalleerd is en in PyCharm  ([Git in Pycharm tutorial](https://clt.champlain.edu/kb/configuring-git-with-pycharm/)) werkend is.
- In Pycharm, installeer de nodige geimporteerde library's. Zie [file] om te zien welke dit zijn. 
- Open `dashboardv3.py` in PyCharm en selecteer Python Interpreter `Python 3.9`.
- Nu kan je met `[Shift + F10]` de app opstarten dit kan enkele seconden duren totdat de interface verschijnt.
### Het gebruik maken van de interface doormiddel van de launcher
Het leuke van de grafische interface is dat je het programma met een `.exe` kan opstarten. Om dit te doen, open `Dashboard/Project/`, druk op `dashboard.exe` en druk op `[Enter]`
- LET OP: Het SteamID dat u wilt inzien met de interface moet een openbaar steamprofiel hebben. Profielen die op prive staan zijn niet inzienbaar met de interface en kunnen NIET gebruikt worden. Om de privacyinstellingen van uw Steam profiel te kunnen aanpassen kunt u [hier](https://help.steampowered.com/nl/faqs/view/588C-C67D-0251-C276) vinden.
# App Toestemming
SteamInterface werkt volledig online, alle data die opgehaald wordt in de app wordt van het internet / steam afgehaald doormiddel van een API of steam zelf. Daarom, de app heeft wel toestemming nodig van sommige andere apps om correct te kunnen werken.
1. [Steam](https://store.steampowered.com/) - De toestemming van en het installeren van deze app is nodig om bijvoorbeeld `games op te starten` of `producten te kunnen aankopen / installeren`. De uitleg om Steam te kunnen installeren kunt u [hier](https://help.steampowered.com/nl/faqs/view/099E-F5D1-8780-4778) vinden.

# Functionaliteiten
### Inlog
Wanneer de interface opgestart is moet u uw Steam ID invullen, heeft u dit gedaan kunt u doormiddel van de `INLOG` knop inloggen. _Weet u niet hoe u uw Steam ID kunt vinden die gelinkt is aan uw Steam profiel? Dan kunt u doormiddel van deze website uw Steam ID vinden [SteamIDFinder](https://www.steamidfinder.com/).
Het laden van de interface kan enkele seconden duren.
### Recently Played Games (Last Two Weeks)
Zodra u met een correct profiel bent ingelogd krijgt u direct gegevens over u meest gespeelde recente spellen van de afgelopen 2 weken overzichtelijk en gesorteerd op speeltijd grafisch weergegeven. Het houd niet alleen op bij het overzichtelijke plaatje van uw recente gameactiveit. U kunt doormiddel van het drukken op de plaatjes ook uw spellen opstarten/installeren en als u het profiel van een ander bekijkt de games bekijken op steam om bijvoorbeeld de game te kopen. _Niet alleen leuk maar ook super handig dus!_ 
### Most Played Games (Alltime)
Net als de 'Recently Played Games (Last Two Weeks)' worden u meest gespeelde spellen overzichtelijk en gesorteerd op speeltijd grafisch weergegeven in de interface en kunt u gebruik maken van de plaatjes om de games te spelen/installeren of te bekijken in de steam store zelf.
### Offers
De interface heeft ook twee ruimtes benut voor reclame. Het blokje offers in het midden van het scherm laat verschillende klikbare aanbiedingen of aanbevolen games aan die wellicht interessant zijn voor u als gamer.
Linksonder in de interface is ook een blokje klikbare reclame voor de verschillende hardware die Steam aanbiedt, wellicht kan je met behulp van de weergegeven hardware uw game ervaring naar een ander niveau brengen. Wilt u de aanbieding bekijken? Dan kunt u doormiddel van het drukken op het plaatje de aanbieding bekijken op Steam zelf. Doormiddel van de knoppen onder `OFFERS` kunt u ook gewoon op uw eigen gemak de games bekijken.
### Store
In de lange lijst links in het scherm kunt u terecht om door de door Steam gevulde spellen heen te scrollen om te bekijken wat er allemaal beschikbaar is op Steam. Doormiddel van de zoekbalk en de `SEARCH` knop kunt u met steekwoorden of volledige namen van games de lijst iets aantrekkelijker en makkelijker vindbaar maken. U kunt de lijst ook op alfabetische volgorde zetten doormiddel van de knop `SORT A/Z`
### Statistics
Het leuke van de interface is dat u onder het kopje `STATISTICS` heel gemakkelijk kunt bekijken hoe de games die u recentelijk heeft gespeeld worden beoordeeld door andere mensen. Het blokje `min` het percentage positieve reviews laat zien wat het laagst beoordeelde percentage positieve reviews game is die u recentelijk heeft gespeeld of wat nou juist het hoogste `max` percentage populaire game is, het gemiddelde `mean` van u lijst en het totale aantal reviews. _Hiermee kunt u makkelijk bekijken of u gemiddeld populaire spellen speelt of juist spellen die gemiddeld minder worden ontvangen door andere spelers!_

### News
Rechtsonder in de interface is er een kopje `NEWS` waar het nieuws over uw meest recent gespeelde spellen samengevat wordt weergegeven. Wilt u nou het hele artikel bekijken? Dan kan dat simpelweg door op de knop `READ MORE` of op de afbeelding van het nieuws te drukken. Het artikel wordt dan in uw browser volledig geopend waardoor u zich helemaal kunt inlezen over de laatste nieuwtjes van uw favoriete games! _Schoot het nieuws iets te snel voorbij? U kunt doormiddel van de knoppen onder het nieuws de nieuwsberichten teruglezen of op uw eigen gemak bekijken._

# Algemene verordening gegevensbescherming
Bekijk [AVG](https://dev.azure.com/HU-HBO-ICT/_git/2021-Prop-B-KlasM-T5?path=/Project/AVG.md&_a=preview)


# Special Thanks
### Code contributors
- Waïl Idrissi (1812925)
- Joseph Tawiah (1820132)
- Olav Sajtos (1812355)
- Jerry Kuijper (1812355)
- Alae Aynaou (1814819)

### Documentation contributors
- Waïl Idrissi (1812925)
- Mats Braster (1719515)
- Jerry Kuijper (1812355)
- Alae Aynaou (1814819)

### Designers
- Olav Sajtos (1812355)
- Jerry Kuijper (1792255)
