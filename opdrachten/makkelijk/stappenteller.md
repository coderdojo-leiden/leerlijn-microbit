---
title: Stappenteller
layout: tutorial
thumbnail: stepcounter.png
---

Je gaat van de micro:bit een stappenteller maken, die bijhoudt hoeveel stappen jij hebt gezet!

# Hoe werkt het?

De micro:bit heeft een sensor waarmee hij **beweging** kan voelen. Dat wordt ook wel een versnellingsmeter genoemd (of *accelerometer* in het Engels).

In de code tel je hoe vaak de micro:bit is geschud. Dat aantal sla je op in een **variabele** genaamd `stappen`{: .inlineblock.variables }. 
Met een variabele kun je een stukje data bewaren terwijl je programma draait. Bijvoorbeeld een getal.

Je kunt de micro:bit en het batterijtje vastbinden aan je schoen. Of je kunt hem in je broekzak dragen.

# Maak het

* In je `bij opstarten`{: .inlineblock.basic } blok, zet je een blok `stel stappen in op 0`{: .inlineblock.variables }.
* Gebruik een `bij schudden`{: .inlineblock.input } blok en zet daarin...
* Een `verander stappen met ...`{: .inlineblock.variable } blok, die het aantal stappen verhoogt met 1.
* Een `toon nummer`{: .inlineblock.basic } blok die de 'stappen' variabele gebruikt.

De oplossing kun je <a href="https://makecode.microbit.org/S90021-35476-74788-26796" target="_blank">hier</a> vinden.

# Verder programmeren

* Verander de code zodat hij het aantal stappen laat zien wanneer je op een knop drukt.
* Vermenigvuldig het aantal stappen met de afstand die jij over één stap doet. Kun je uitrekenen hoe ver je hebt gelopen? En hoe nauwkeurig is dat?
* Kun je de stappenteller nauwkeuriger maken? Tip: gebruik daarvoor het blok: `versnelling (mg) kracht`{: .inlineblock .input }. Vergelijk of dit groter is dan een getal, zoals 1500.
