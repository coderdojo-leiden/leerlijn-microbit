---
title: Steen, papier, schaar
layout: tutorial
thumbnail: rock-paper-scissors.png
---

# Hoe werkt het?

Het spel **steen, papier, schaar** wordt heel vaak gespeeld als je moet loten. Bijvoorbeeld: wie is er aan de beurt met tikkertje of verstoppertje.

De twee spelers tellen af en steken tegelijkertijd een hand uit in de vorm van:

* een vuist (steen) wint van twee gespreide vingers (de steen maakt de schaar bot)
* een vlakke hand (papier) wint van een vuist (het papier bedekt de steen)
* twee gespreide vingers (schaar) winnen van een vlakke hand (de schaar verknipt het papier)

Dat spel kun je ook maken op twee micro:bits!

# Maak het

- Zorg er eerst voor dat je bij 3 verschillende inputs verschillende dingen selecteert (bijvoorbeeld bij A kies je steen, bij B kies je papier, bij A+B kies je schaar).
- Zorg ervoor dat je je keuze niet meer kan veranderen.
  - **Tip**: gebruik een variabele en `als ... dan`{: .inlineblock.logic }.
- Zorg ervoor dat je keuze verstuurd wordt naar de andere micro:bit met `Radio verzend ...`{: .inlineblock.radio } en `wanneer de radio ontvangt ...`{: .inlineblock.radio }.
- Maak een systeem dat laat zien wie gewonnen heeft door de verschillende inputs te vergelijken.
  - **Tip**: gebruik een `de hele tijd`{: .inlineblock.basic } lus en `als ... dan`{: .inlineblock.logic } erin met de twee getallen van de keuzes.
- Zorg dat het spel een score bijhoudt en zichzelf herhaalt.

De oplossing vind je <a href="https://makecode.microbit.org/_hDMcD4Wy3Ru0" target="_blank">hier</a>.
