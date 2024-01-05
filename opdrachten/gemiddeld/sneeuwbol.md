---
title: Sneeuwbol
layout: tutorial
thumbnail: snowglobe.png
---

# Hoe werkt het?

Wanneer je een glazen sneeuwbol schudt, dwarrelen de vlokjes sneeuw langzaam naar beneden.
Dat effect kun je namaken op de micro:bit!

# Maak het

Zorg er eerst voor dat je alle LED-jes aan zet met een `toon lichtjes`{: .inlineblock.basic } blokje.
Wanneer je de micro:bit schudt, moeten de lichtjes langzamerhand allemaal weer uit gaan.

Dat kan op 2 manieren gedaan worden:

### 1. De makkelijke manier!

Je kunt een simpele animatie maken die steeds lichtjes weghaalt om een animatie te maken. (Met `toon lichtjes`{: .inlineblock.basic } blokjes.)

### 2. De iets lastiger manier!

Je kunt een lus gebruiken om steeds een paar lichtjes uit te doen (met `... keer herhalen`{: .inlineblock.loops } en `wis x ... y ...`{: .inlineblock.led } blokjes).
Voor de `x` en `y` kun je een willekeurig nummer ophalen met een `kies willekeurig 0 tot 4`{: .inlineblock.math } blok.

Gebruik een `pauzeer (ms) ...`{: .inlineblock.basic } blok om de animatie zo snel/langzaam te laten lopen als jij mooi vindt.

De oplossing kun je <a href="https://makecode.microbit.org/S95917-42214-17744-03311" target="_blank">hier</a> vinden.

# Verder programmeren

* Wat voor animaties zou je nog meer kunnen maken met **lussen** en de blokken `teken x ... y ...`{: .inlineblock.led } `wis x ... y ...`{: .inlineblock.led }?
