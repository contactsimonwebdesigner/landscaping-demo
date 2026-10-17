# ZÁHON. — demo web zahradního ateliéru

Kompletní ukázkový web v češtině, připravený pro GitHub Pages. Nejde o skutečnou firmu; fotografie jsou generované ilustrace a ceny jsou modelové.

## Použití

1. Rozbalte ZIP.
2. Otevřete `index.html` v prohlížeči.
3. Pro GitHub Pages nahrajte soubor `index.html` a složku `assets/images` do kořene repozitáře (nikoliv jen obrázky nebo jen HTML).
4. V nastavení repo zapněte Settings → Pages → Deploy from a branch → main / root.

## Funkce

- 24 lokálních obrázků WebP v `assets/images`
- 6 služeb a 24 položek orientačního ceníku
- Galerie 24 vizualizací s kategoriemi, lightboxem a navigací klávesami / swipem
- Kalkulačka orientačního rozpočtu
- FAQ, mobilní menu, animace, responzivní rozvržení
- Demo poptávka, kterou lze zkopírovat; žádné údaje se nikam automaticky neodesílají

## Úpravy

V souboru `index.html` ve spodní části JavaScriptu jsou přehledné konstanty:
- `services` — služby
- `gallery` — názvy obrázků, popisky a kategorie
- `prices` — orientační sazby a jednotky
- `calcRates` — sazby kalkulačky
- `faqs` — časté otázky

Fotografie a případné lokální náhledy přidávejte do `assets/images`.

## Poznámka

Načítání fontů z Google Fonts vyžaduje internet; pokud nejsou dostupné, stránka použije standardní systémové fonty. Všechny fotografie jsou součástí projektu a nevyžadují internet.
