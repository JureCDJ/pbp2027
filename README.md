# PBP 2027 – načrt

Statična aplikacija za GitHub Pages.

## Datoteke
- `index.html` – aplikacija
- `pbp-data.json` – podatki
- `sw.js` – offline delovanje (zemljevid potrebuje internet)

## Postavitev
1. Repozitorij `pbp2027` (Public), naloži vse datoteke v koren.
2. Settings → Pages → Deploy from a branch → `main` / root → Save.
3. Naslov: `https://<uporabnik>.github.io/pbp2027/`

## Žeton za shranjevanje (enkrat)
1. GitHub → profilna slika → Settings → Developer settings → Personal access tokens → Fine-grained tokens → Generate new token.
2. Expiration: po koncu PBP (npr. 30. 9. 2027).
3. Repository access: Only select repositories → `pbp2027`.
4. Permissions → Repository permissions → Contents: Read and write.
5. Generate, kopiraj žeton (prikaže se samo enkrat).
6. V aplikaciji: Uredi → Podatki → Povezava z GitHubom → prilepi žeton → Shrani nastavitve.

## Delo
Uredi → spremembe (sproti shranjene v brskalnik) → Shrani na GitHub.
Nova verzija aplikacije: na GitHubu zamenjaj samo `index.html`.

## Opomba
Repozitorij je javen: vse v `pbp-data.json` je vidno vsem.
