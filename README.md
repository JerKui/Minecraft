<p align="center">
<img width="32" align="center" src="/dashboard/steam.png">
<h3 align="center">
  Steam Project
</h3>
<p align="center">
  Een interface met grafische weergaven van gaming gedrag.
</p>
<p align="center">
  <a style="text-decoration:none" href="https://store.steampowered.com/" target="_blank">
    <img src="https://img.shields.io/badge/Steam-Installeren-blueviolet" alt="Store link" />
  </a>
  <a style="text-decoration:none" href="https://store.steampowered.com/" target="_blank">
    <img src="https://img.shields.io/badge/Steam-Installeren-blueviolet" alt="Store link" />
  </a>
  <a style="text-decoration:none" href="https://store.steampowered.com/" target="_blank">
    <img src="https://img.shields.io/badge/Steam-Installeren-blueviolet" alt="Store link" />
  </a>


## Introductie
Steam wil haar klanten beter bedienen door meer grafische weergaves te maken van gaming gedrag naar verschillende klantsegmenten. 
Hiervoor heeft ze een consultancybedrijf ingehuurd. 
De hoofdopdracht luidt: 
"Maak een grafische weergave die inzicht geeft in het gaming gedrag van jouw vrienden op het platform Steam, ondersteund door een netwerk waarbij gebruik gemaakt wordt van een RaspberryPi."

<img width="1080" align="center" src="/dashboard/images/example.png">

## Hoe moet je hem installeren? (als eindgebruiker)

### Hardware eisen
- Windows 10 build 1903+ of later vereist.
- Een schermresolutie van 16:9 vereist.
- Een internetverbinding is vereist.

### Handleiding
- Download en extract de laatste `release`
- Rechtermuisknop op het `.zip` bestand en druk op hier uitpakken.

## Hoe gebruik je de grafische interface?

### Hoe run je de grafische interface source code
- Wees er zeker van dat je computer minstens draait op Windows 10 1903+
- Wees er zeker van dat [Python 3.9](https://www.python.org/downloads/release/python-390/) en [PyCharm 2021.3](https://www.jetbrains.com/pycharm/whatsnew/) is geinstalleerd.
- Wees er zeker van dat [Git](https://git-scm.com/) geinstalleerd is en in PyCharm  ([Git in Pycharm tutorial](https://clt.champlain.edu/kb/configuring-git-with-pycharm/)) werkend is.
- In Pycharm, installeer de nodige geimporteerde library's. Zie [file] om te zien welke dit zijn. 
- Open `dashboardv3.py` in PyCharm en selecteer Python Interpreter `Python 3.9`.
- Nu kan je met `Shift + F10` de app opstarten dit kan enkele seconden duren totdat de interface verschijnt.
### Het gebruik maken van de interface doormiddel van het startmenu
Het leuke van de grafische interface is dat je het programma met een `.exe` kan opstarten. Om dit te doen, open `Dashboard/Project/, druk op `dashboard.exe` en druk op `[Enter]`



## App Toestemming
SteamInterface werkt volledig online, alle data die opgehaald wordt in de app wordt van het internet / steam afgehaald doormiddel van een API of steam zelf. Daarom, de app heeft wel toestemming nodig van sommige andere apps om correct  te kunnen werken.

1. [Steam](https://store.steampowered.com/) - De toestemming van en het installeren van deze app is nodig om bijvoorbeeld `games op te starten` of `producten te kunnen aankopen / installeren`. De uitleg om Steam te kunnen installeren kunt u [hier](https://help.steampowered.com/nl/faqs/view/099E-F5D1-8780-4778) vinden.

## Algemene verordening gegevensbescherming
Bekijk [AVG](https://google.nl)

## Special Thanks
### Code contributors
- Waïl Idrissi (1812925)
- Joseph Tawiah (1820132)
- Olav Sajtos (1812355)
- Jerry Kuijper (1812355)

### Documentation contributors
- Waïl Idrissi (1812925)
- Mats Braster (1719515)
- Jerry Kuijper (1812355)

### Designers
- Olav Sajtos (1812355)
- Jerry Kuijper (1792255)
