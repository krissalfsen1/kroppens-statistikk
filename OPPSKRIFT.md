# Kroppens Statistikk — fra filer til app-ikon på iPhonen din

## Del 1 · Legg appen på nett (engangsjobb, ~10 min)

1. Gå til **github.com** og opprett en gratis konto (om du ikke har).
2. Øverst til høyre: **+** → **New repository**. Navn: `kroppens-statistikk`. Velg **Public**. Trykk **Create repository**.
3. På den nye siden: **uploading an existing file** (lenke i midten). Dra inn ALLE filene fra denne mappen
   (`index.html`, `manifest.json`, `sw.js`, `ikon-180.png`, `ikon-192.png`, `ikon-512.png`). Trykk **Commit changes**.
4. Gå til **Settings** (fanen øverst) → **Pages** (venstremeny) → under «Branch»: velg **main** og **/ (root)** → **Save**.
5. Vent 1–2 minutter. Adressen din vises øverst på Pages-siden:
   `https://DITTBRUKERNAVN.github.io/kroppens-statistikk/`

## Del 2 · Installer på iPhonen (~1 min)

1. Åpne adressen i **Safari** på iPhonen.
2. Trykk **Del-knappen** (firkanten med pil opp, midt på bunnlinjen).
3. Bla ned og velg **«Legg til på Hjem-skjerm»** → **Legg til**.
4. Ferdig! Ikonet ligger på hjemskjermen, appen åpner i fullskjerm og virker uten nett.

## Oppdatere appen senere

1. Be Claude om endringen — du får en ny `index.html`.
2. På github.com: åpne repoet → klikk `index.html` → blyant-ikonet (**Edit**) → lim inn alt nytt → **Commit changes**.
   (Eller: last opp filen på nytt via **Add file → Upload files** — den erstatter den gamle.)
3. Åpne appen på telefonen med nett — den henter ny versjon selv. Versjonsnummeret står nederst på Framgang-siden.

## Verdt å vite

- **Dataene bor kun på telefonen din** (ingen server, ingen konto, ingen sporing).
  Derfor: trykk **«Eksporter til Claude»** på Framgang-siden jevnlig — det er både analysen og sikkerhetskopien din.
- Sletter du appen fra hjemskjermen, slettes dataene — eksporter først.
- Claude er fortsatt hjernen: eksporten limes inn i Claude-appen, som fører hovedloggen,
  kjører korrelasjonene og oppdaterer dashbordet.
