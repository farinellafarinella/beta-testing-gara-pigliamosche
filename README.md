# Gara Pigliamosche

Prototipo web mobile-first ispirato alla Gara Pigliamosche di Pokémon Crystal.

## Avvio locale

Apri `index.html` nel browser.

Per testarlo in modo più simile a GitHub Pages puoi usare un server locale, ad esempio:

```bash
python3 -m http.server 8000
```

poi apri `http://localhost:8000`.

## Pubblicazione su GitHub Pages

1. Crea un repository GitHub.
2. Carica **tutto il contenuto di questa cartella** nella root del repository.
3. Vai in **Settings → Pages**.
4. In `Build and deployment`, scegli **Deploy from a branch**.
5. Seleziona il branch `main` e la cartella `/ (root)`.
6. Salva.

Il file principale è `index.html`.

## Struttura

```text
index.html
assets/
  map/
    national_park.png
  sprites/
    player/
      chris.png
    npc/
      ...
    pokemon/
      ...
source-data/
  NationalPark.blk.b64
  park_collision_table.txt
THIRD_PARTY_NOTICES.md
.nojekyll
```

## Funzioni presenti

- layout smartphone
- D-pad touch con pressione continua
- sprite animato di Chris
- National Park ricostruito su griglia 40×54
- collisioni del tileset Park
- riconoscimento `TALL_GRASS` / `LONG_GRASS`
- NPC del Bug-Catching Contest alle coordinate del gioco
- incontri casuali
- battaglia 1v1 semplificata
- 20 Sport Ball
- sostituzione del Pokémon tenuto
- giudizio finale

## Nota

Questa è una base di sviluppo. Prima di usarla pubblicamente o commercialmente,
controlla i diritti relativi agli asset Pokémon/Nintendo.
