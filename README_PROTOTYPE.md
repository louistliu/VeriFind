# VeldVerkenner - Interactief Educatief Prototype (SIFT Framework)

Dit prototype is ontwikkeld op basis van de beleidsaanbeveling voor de **Birdwatcher Group** om de Nederlandse samenleving weerbaarder te maken tegen desinformatie via een interactieve, realistische simulatieomgeving.

## Doel van de Prototyping
- **Kritisch denken stimuleren** zonder dat er sprake is van betuttelende "goed/fout" beoordelingen.
- **Lateral reading** en bronverificatie aanmoedigen via klikbare profielen en vereenvoudigde bronnen (zoals titels met kleine steekproeven `n = ...` en samenvattingen).
- **Geen echte entiteiten of personen** gebruiken om neutraliteit te waarborgen.

---

## Hoe te starten

1. **Installeer afhankelijkheden:**
   ```bash
   npm install
   ```

2. **Start de lokale server:**
   ```bash
   node server.js
   ```

3. **Open in je browser:**
   Ga naar `http://localhost:3000` om de interactieve simulatie te starten.

---

## Structuur van de Code
- `server.js`: Eenvoudige Node.js/Express server die de statische webpagina serveert.
- `public/index.html`: Volledig self-contained frontend (Tailwind CSS, FontAwesome, interactieve tijdlijn, profiel- en broninspectie, SIFT-handleiding en reflectiescherm).
