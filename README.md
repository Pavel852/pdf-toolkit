# PDF & Image Toolkit

**Verze / Version:** 2.4.1  
**Autor / Author:** PB  
**Email:** pavel.bartos.pb@gmail.com

---

## 🇨🇿 Český popis

Lehký nástroj pro práci s PDF a obrázky postavený na čistém HTML/JS. Běží **plně v prohlížeči** – žádné nahrávání souborů na server.

### Hlavní funkce
1. **Sloučit** – spojí více PDF a obrázků (JPG/PNG/**SVG**) do jednoho PDF.  
2. **Komprimovat** – zmenší PDF převzorkováním stránek do JPEG s nastavitelnou kvalitou.  
3. **Rozdělit** – rozdělí vícestránkové PDF na samostatné PDF po stránkách (ZIP).  
4. **PDF → JPG** – převede všechny stránky PDF na JPG (ZIP).  
5. **INFO** – při nahrání **jednoho PDF** zobrazí metadata (title/author/producer…), rozměry stránek a **přílohy (attachments)** se **stažením**.

### Další možnosti
- **Přílohy do výsledného PDF**: libovolné soubory přetáhněte do zóny „Přílohy“ – vloží se jako *attachments* do výstupního PDF.  
- **Zabezpečení (volitelně)**: u voleb **1) Sloučit** a **2) Komprimovat** lze nastavit **heslo** (AES‑256/AES‑128; QPDF/WASM).  
- **Tmavý/Světlý režim** s uložením volby (localStorage).  
- **Miniatury** souborů zvětšené pro pohodlnější náhledy.  

### Podporované vstupy
- **PDF**, **JPG**, **PNG**, **SVG** (SVG se před vložením rasterizuje).  
- **DWG** je detekován; bez dostupné knihovny je **bezpečně ignorován**.

### Jak používat
1. Otevřete `index.html` v moderním prohlížeči.  
2. Přetáhněte nebo vyberte soubory.  
3. Zvolte operaci 1–5.  
4. (Volitelně) Přidejte přílohy do PDF přetažením do sekce **Přílohy**.  
5. (Volitelně) V sekci **Zabezpečení** zapněte „Zaheslovat PDF“ a zadejte hesla.

### Poznámky
- Vše probíhá lokálně. U vektorových PDF může komprese vést ke ztrátě ostrosti.  
- INFO zobrazuje přílohy PDF včetně tlačítek **Stáhnout**.

---

## 🇬🇧 English Description

A lightweight, client‑side PDF & image toolkit in plain HTML/JS. Runs **entirely in the browser** – no uploads.

### Core features
1. **Merge** – combine PDFs and images (JPG/PNG/**SVG**) into a single PDF.  
2. **Compress** – rebuild pages as JPEG with adjustable quality to shrink PDFs.  
3. **Split** – split a multi‑page PDF into single‑page PDFs (ZIP).  
4. **PDF → JPG** – export all pages to JPG (ZIP).  
5. **INFO** – when **a single PDF** is loaded, shows detailed metadata (title/author/producer…), page sizes and **PDF attachments** with **download** buttons.

### Extras
- **Attachments**: drop any files into the **Attachments** area to embed them into the output PDF.  
- **Security (optional)**: for **1) Merge** and **2) Compress**, set an **open password** (AES‑256/AES‑128 via QPDF/WASM).  
- **Dark/Light mode** with persistent choice.  
- **Larger thumbnails** for clearer previews.

### Supported inputs
- **PDF**, **JPG**, **PNG**, **SVG** (SVG is rasterized before embedding).  
- **DWG** is detected but **ignored** unless a browser DWG library is available.

### How to use
1. Open `index.html` in any modern browser.  
2. Drag & drop or select files.  
3. Choose operation 1–5.  
4. (Optional) Drop extra files into **Attachments** to embed into the output PDF.  
5. (Optional) Enable **Security** and set passwords.

### Notes
- Everything is local to your browser. Compression of vector PDFs may reduce sharpness.  
- INFO lists PDF attachments with **Download** actions.

---

## What’s new (highlights)
- **INFO panel** for single‑PDF loads: metadata, page sizes, and downloadable attachments.  
- Optional **password protection** (AES‑256/128) for Merge/Compress; **Attachments** drag‑and‑drop.  
- **Dark/Light theme**, **larger thumbnails**, and assorted UI tweaks.  
- **SVG** input supported (rasterized before embedding); **DWG** is safely ignored without a library.

See `CHANGELOG.md` for full details.
