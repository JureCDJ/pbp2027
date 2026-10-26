# PBP 2027 – načrt

Statična aplikacija za GitHub Pages. Brez zunanjih knjižnic.

## Datoteke
- `index.html` – aplikacija (nadgradnje funkcij)
- `pbp-data.json` – podatki (tvoji vnosi)
- `sw.js` – offline delovanje na telefonu

## Postavitev (enkrat)
1. Nov repozitorij na GitHubu (npr. `pbp2027`), naloži vse tri datoteke.
2. Settings → Pages → Source: Deploy from a branch → `main` / root → Save.
3. Čez minuto: `https://<uporabnik>.github.io/pbp2027/`

## Posodabljanje podatkov
Uredi → spremembe → Podatki → Izvozi pbp-data.json → na GitHubu Add file → Upload files → Commit.

## Nadgradnja aplikacije
Zamenjaj samo `index.html`. Podatki ostanejo. Ob spremembi strukture podatkov se poveča `schemaVersion` in doda korak v funkcijo `migrate()`.

## Opomba
Repozitorij na GitHub Pages je javen (brezplačni račun). Ne vpisuj osebnih podatkov, ki jih ne želiš javno.
