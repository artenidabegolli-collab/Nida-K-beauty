# Si ta vësh online dhe ta instalosh në telefon

## Hapi 1 — Krijo llogari GitHub (nëse s'ke)
Shko te github.com dhe regjistrohu falas (2 min).

## Hapi 2 — Krijo një "repository" të ri
1. Shtyp "+" lart djathtas → "New repository"
2. Emërto p.sh. `kbeauty-app`
3. Zgjidh "Public"
4. Shtyp "Create repository"

## Hapi 3 — Ngarko skedarët
1. Në faqen e repository-t, shtyp "uploading an existing file"
2. Zvarrit brenda: `index.html`, `manifest.json`, `sw.js`, `icon-192.png`, `icon-512.png`
   (të gjithë nga zip-i `kbeauty-pwa.zip` që të dhashë — çaje/ekstraktoje fillimisht)
3. Shtyp "Commit changes"

## Hapi 4 — Aktivizo GitHub Pages
1. Shko te "Settings" (në repository) → "Pages" (majtas)
2. Te "Branch" zgjidh `main`, dhe folderin `/ (root)`
3. Shtyp "Save"
4. Prit 1-2 minuta — do të marrësh një adresë si:
   `https://<username>.github.io/kbeauty-app/`

## Hapi 5 — Instaloje në telefon
**iPhone (Safari):** hap adresën lart → shtyp ikonën "Share" (katror me shigjetë) → "Add to Home Screen" → "Add".

**Android (Chrome):** hap adresën → shtyp tri pikat lart djathtas → "Install app" (ose "Add to Home Screen") → konfirmo.

Tani do të kesh një ikonë në ekranin kryesor që hapet si app i vërtetë, punon edhe pa internet (pas hapjes së parë), dhe fotot ruhen direkt në telefon.

## Shënim
Të dhënat (profili + fotot) ruhen vetëm lokalisht në atë shfletues/telefon (localStorage). Nëse fshin app-in ose pastron të dhënat e shfletuesit, ato humbasin — nuk sinkronizohen në cloud.
