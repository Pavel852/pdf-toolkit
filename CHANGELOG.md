# Changelog

## 2.4.1 — 2025-08-17
- Fix: znovu vytvořen **ZIP** a artefakty po resetu kernelu.

## 2.4.0 — 2025-08-16
- Nové tlačítko **5) INFO**: metadata PDF, rozměry stránek, přílohy se stažením.

## 2.3.2 — 2025-08-15
- **Miniatury** zvětšeny na 84×84 px (~+40 %).
- **Popisek** (název souboru) přesunut **pod** miniaturu, velikost písma zmenšena (~−50 %) a zkracuje se pomocí ellipsy.

## 2.3.1 — 2025-08-14
- Oprava **miniatur/štítků v seznamu**: odebrány chybné `\${...}` escape sekvence v šablonách, nyní se hodnoty správně vyhodnocují a náhledy se zobrazují.

## 2.3 — 2025-08-12
- Tmavý/Světlý režim s persistentní volbou (localStorage).
- Miniatury zvětšeny z ~46 px na 60 px.

## 2.3 — 2025-08-12
- **Tmavý/Světlý režim** s persistentní volbou (localStorage), úprava barevných proměnných.
- **Miniatury** zvětšeny z ~46 px na **60 px** (≈+30 %).
- Drobné úpravy stylů a přechodů, zvětšená výška seznamu pro pohodlnější scroll.

## 2.2 — 2025-08-10
- Volitelná **ochrana heslem** (AES-256/AES-128) pro výstup u voleb **1) Sloučit** a **2) Komprimovat** (qpdf-wasm).
- **Přílohy (Attachments)**: nová drag-&-drop zóna, soubory se vkládají do výsledného PDF přes `PDFDocument.attach`.
- UI: sekce „Zabezpečení“, logování stavu qpdf, drobné úpravy stylů.
- Zachována podpora **SVG** (rasterizace), DWG dál ignorováno bez knihovny.

## 2.1 — 2025-08-08
- Přidána podpora **SVG** (náhled + sloučení; SVG se rasterizuje do PNG před vložením do PDF).
- Rozšířen `accept` vstupu o `image/svg+xml`, `.svg` a náznak `.dwg` (DWG se, bez dostupné knihovny, ignoruje).
- Vylepšené protokolování a štítky položek (SVG/PNG/JPG).
- Aktualizace metadat: **verze 2.1**, autor **PB**.

## 1.0 — původní verze
- Základní funkcionalita: sloučení PDF/obrázků, komprese PDF (rasterizace), rozdělení PDF, PDF→JPG.

