# Know-How Website - Export Files

Toto sú kompletné HTML/CSS/JS súbory pre webstránku Know-How.

## Súbory v balíčku:

1. **index.html** - Hlavný HTML súbor so všetkými sekciami
2. **styles.css** - Kompletné CSS štýly
3. **script.js** - JavaScript pre interaktivitu
4. **README.md** - Tento súbor s inštrukciami

## Inštalácia a použitie:

### 1. Skopírujte súbory
Skopírujte všetky tri súbory (index.html, styles.css, script.js) do jedného priečinka.

### 2. Pridajte logo
Uložte vaše logo ako **logo.png** do rovnakého priečinka. 

Ak má vaše logo iný názov alebo formát, zmeňte v **index.html**:
```html
<img src="logo.png" alt="Know-How">
```
na:
```html
<img src="vase-logo.png" alt="Know-How">  <!-- alebo .jpg, .svg, atď. -->
```

### 3. Otvorte v prehliadači
Jednoducho dvakrát kliknite na **index.html** alebo ho otvorte cez váš webový prehliadač.

### 4. Pre VS Code
- Otvorte priečinok v VS Code
- Nainštalujte rozšírenie "Live Server" od Ritwick Dey
- Pravým kliknutím na index.html vyberte "Open with Live Server"
- Stránka sa otvorí na localhoste s automatickým načítaním zmien

## Štruktúra webstránky:

### Sekcie:
1. **Header** - Navigácia a logo
2. **Hero Section** - Úvodná sekcia s CTA tlačidlami
3. **About Section** - Kto sme
4. **Expertise Section** - Naše odborné znalosti (4 bloky)
5. **Projects Section** - Vybrané projekty (3 projekty)
6. **Partners Section** - Partneri (EUBA, NÚDCH, TsMP)
7. **News Section** - Aktuality (3 články)
8. **CTA Banner** - Výzva k akcii
9. **Footer** - Kontakt a quick links

### Funkcie:
- ✅ Plne responzívny dizajn (mobile, tablet, desktop)
- ✅ Mobilné menu s animáciou
- ✅ Smooth scrolling
- ✅ Fade-in animácie pri scrollovaní
- ✅ Prepínač jazykov (SK/EN)
- ✅ Hover efekty na kartách a linkách
- ✅ Sticky header

## Prispôsobenie:

### Zmena farieb
V **styles.css** nahraďte tieto farby:
- Primárna modrá: `#2563eb`
- Tmavá modrá: `#1e40af`
- Zelená: `#059669`
- Fialová: `#9333ea`
- Oranžová: `#ea580c`

### Zmena obrázkov
V **index.html** nahraďte URL adresy od Unsplash vašimi vlastnými obrázkami:
```html
<img src="https://images.unsplash.com/..." alt="...">
```
zmeňte na:
```html
<img src="vas-obrazok.jpg" alt="...">
```

### Zmena textov
Všetky texty sú priamo v **index.html** - jednoducho nájdite sekciu a zmeňte text.

### Pridanie/odobratie sekcií
Každá sekcia je ohraničená `<section>` tagom. Môžete kopírovať, presúvať alebo mazať celé sekcie.

## Kontaktné údaje

Nezabudnite aktualizovať:
- Email: `info@know-how.sk` 
- Telefón: `+421 XXX XXX XXX`
- Sociálne siete linky v footeri

## Poznámky:

- Používa Font Awesome ikony (načítané cez CDN)
- Responzívne breakpointy: 640px (mobile), 768px (tablet), 1024px (desktop)
- Logo v footeri má biely filter pre tmavé pozadie
- Všetky obrázky majú hover efekt (zoom)

## Podpora:

Ak potrebujete pomoc s prispôsobením, kontaktujte vášho webového vývojára.

---
**Know-How © 2026** - Research, Innovation, Regional Development
