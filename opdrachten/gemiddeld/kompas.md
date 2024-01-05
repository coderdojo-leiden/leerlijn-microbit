---
title: Kompas
layout: tutorial
thumbnail: compass.png
---

## Hoe werkt het?

Een van de sensoren die de micro:bit heeft, is een **kompas sensor**. Dat wordt ook wel een magnetometer genoemd. Daarmee voelt de micro:bit het magnetisch veld van de aarde. En daarmee kunnen wij een kompas programmeren!

Wanneer je voor het eerst het kompas op de micro:bit gebruikt, dan zal hij je vragen om het kompas te **ijken**. Je moet dan de micro:bit ronddraaien totdat alle lichtjes branden.
Dan heeft de micro:bit genoeg van het magnetisch veld van de Aarde "gevoeld" om te weten in welke richting hij wijst!

Je gaat programmeren dat de micro:bit een letter op het scherm laat zien, op het moment hij richting het noorden wijst.

## Maak het

Met het blok `kompasrichting (°)`{: .inlineblock.input } uit de `invoer` lade, kun je de kompasrichting ophalen. \
Dat is de richting in **graden**. De laagste waarde is 0 en de hoogste waarde is 360. Bij 0 graden wijst de micro:bit precies naar het magnetische noorden.

![Een kompasroos, met daarop noord, oost, zuid en west. Het noorden is 0 graden, het oosten is 90 graden, het zuiden is 180 graden en het westen is 270 graden.](kompas.svg)

Gebruik een `als ... dan`{: .inlineblock.logic } blok om te kijken of de `kompasrichting (°)`{: .inlineblock.input } kleiner is dan 15 graden, en groter is dan 345 graden. In dat geval wil je de letter **N** op het scherm laten zien.

Tip: uit de lade "**logisch**" kun je de volgende blokken gebruiken: `... < ...`{: .inlineblock.logic }, `... of ...`{: .inlineblock.logic }, `... > ...`{: .inlineblock.logic }.

De oplossing kun je <a href="https://makecode.microbit.org/S05502-60203-28176-46136" target="_blank">hier</a> vinden.

## Verder programmeren

* Kun je het programma uitbreiden zodat hij de andere windrichtingen ook laat zien?
* Voeg een knop toe om het kompas opnieuw te ijken.

En je kunt proberen wat er gebeurt als je een magneet in de buurt van de micro:bit houdt.
