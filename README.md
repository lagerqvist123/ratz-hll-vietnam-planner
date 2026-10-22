# Ratz HLL Vietnam Planner

Taktisk planerare för Hell Let Loose: Vietnam – rita, placera ikoner (garrison, outpost, tunnel m.m.), mät avstånd och välj aktiva strongpoints på alla sex kartor (CAM, DAK, HUE, QUA, THA, VAN).

Inofficiellt fanverktyg, inte kopplat till utvecklarna av Hell Let Loose: Vietnam. Planer sparas lokalt i webbläsaren.

## Innehåll

Detta är den byggda (statiska) versionen av appen:

- `index.html` – startsida
- `assets/` – byggd JS/CSS
- `icons/` – ikoner och `icons.json`
- `maps/<KOD>/` – kartbilder (terrain/tactical) och `meta.json` med capture points och sektorer

## Köra lokalt

Kräver en webbserver (ES-moduler laddas inte via `file://`):

```
python -m http.server 8000
```

Öppna sedan http://localhost:8000
