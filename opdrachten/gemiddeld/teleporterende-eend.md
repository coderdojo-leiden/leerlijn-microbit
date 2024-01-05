---
title: "Teleporterende eend"
layout: tutorial
thumbnail: duck.png
---

Bij deze opdracht ga je een eend draadloos door de lucht laten vliegen van de ene micro:bit naar de andere! Je hebt twee micro:bit's nodig. Je kunt er nog eentje van ons lenen, of je kunt samenwerken met een klasgenoot.

 <iframe src="https://www.youtube-nocookie.com/embed/rwPHpD6Vmus?rel=0&amp;cc_load_policy=1" allow="encrypted-media" frameBorder="0" title="Teleporterende eend introductievideo" width="400" height="300"></iframe>

# Hoe werkt het?

De micro:bit kan via radio berichten sturen en ontvangen naar andere micro:bits.

Iedere micro:bit zit in een bepaalde **radio groep**. De radio groepen zijn genummerd. Een micro:bit zal alleen berichten sturen en ontvangen naar andere micro:bits die in **dezelfde groep** zitten.

Iedere micro:bit die in dezeflde groep zit, en binnen **bereik** is, zal het bericht ontvangen en kan kiezen om daar iets mee te doen.

# Maak het

In een `bij opstarten`{: .inlineblock.basic } blok, stel de de radio groep in met een blok `Radio instellen groep ...`{: .inlineblock.radio }.\
Kies een nummer dat nog niemand anders gebruikt.

In een `bij schudden`{: .inlineblock.input } blok zet je:

* Een `wis scherm`{: .inlineblock.basic } blok om het scherm van deze micro:bit leeg te maken.
* Een `Radio verzend zin 'EEND'`{: .inlineblock.radio } blok om het woord te verzenden naar de andere micro:bit.

Tegelijkertijd willen we dat deze micro:bit het pictogram van een eend laat zien wanneer hij de zin 'EEND' ontvangt.

Gebruik een `wanneer de radio ontvangt 'receivedString'`{: .inlineblock.radio } blok, met daarin een `toon pictogram ...`{: .inlineblock.basic } blok.

Zet hetzelfde programma op twee micro:bits en probeer het uit!

De oplossing vind je <a href="https://makecode.microbit.org/_DDLfm62VbLs6" target="_blank">hier</a>.

# Verder programmeren

* Onderzoek eens hoe ver je van elkaar vandaan kunt gaan om dit nog te laten werken.
* Kun je het programma uitbreiden om meer verschillende dieren dan alleen een eend te laten teleporteren?
* Wat gebeurt er als meer dan 2 micro:bits dezelfde radiogroep gebruiken? Hoe kun je dit oplossen?

### Bronvermelding

Bron: [micro:bit projects](https://microbit.org/nl/projects/make-it-code-it/teleporting-duck/) (microbit.org).
