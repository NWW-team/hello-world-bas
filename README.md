# hello-world-bas

viben met Jan

Een piepkleine "Hello World"-pagina over vibecoden: één `index.html`, zonder
build, zonder dependencies, zonder backend.

## Bekijken

**Live:** https://nww-team.github.io/hello-world-bas/

**Lokaal:** download `index.html` en dubbelklik het. Dat is alles — er is geen
server nodig.

## Publiceren

De site wordt door GitHub Pages rechtstreeks vanaf de `main`-branch geserveerd.
Er is geen build-stap: wat in `index.html` staat, is wat er online komt.

Instellen (eenmalig): **Settings → Pages → Source: Deploy from a branch →
Branch: `main` / `/ (root)` → Save**.

Daarna publiceert elke merge naar `main` zichzelf, meestal binnen een minuut.

Het lege bestand `.nojekyll` zet GitHub's Jekyll-verwerking uit, zodat de
bestanden onbewerkt worden geserveerd.
