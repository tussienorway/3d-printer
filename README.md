# 3d-printer

Prosjektside for min Creality Ender-3 V3 KE: **https://tussienorway.github.io/3d-printer/**

Innhold: om printeren (og hvordan V3, SE, KE og Plus kjennes fra hverandre), feilsøking av termistor og hotend, kabelføring ved montering, bytte av hotend steg for steg, reservedeler, vedlikehold og kalibrering, prosjektlogg og nyttige lenker.

## Oppdatere loggen
Åpne `index.html` og rediger lista `LOGG` helt øverst (i den første `<script>`-blokken). Hver oppføring:

```js
{ dato: "2026-10-12", tittel: "Byttet hotend", status: "ferdig", tekst: "Kjørte PID etterpå." },
```

Status kan være `ferdig`, `pågår`, `plan` eller `problem`. Slett oppføringene med `eksempel: true` når du har lagt inn dine egne.

## Filer
- `index.html` – hele siden (CSS og JS ligger i fila)
- `*.jpg` og `kabelforing-ender-3-v3-ke.png` – offisielle bilder og monteringstegning fra Creality
- `.nojekyll` – slår av Jekyll på GitHub Pages

## Publisere
Lag et offentlig repo som heter `3d-printer`, last opp alt i denne mappa, og velg Settings → Pages → `main` / `(root)`.
