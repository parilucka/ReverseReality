Reverse Reality – jednoduchý statický prototyp

Soubor index.html obsahuje celý web v jednom souboru: HTML, CSS i JavaScript.
Web je navržený jako jedna stránka se záložkami a bez klasického posouvání stránky.

Vizuál vychází z logomanuálu Pernica:
barvy #38474E, #D8C8B6, #EFE9E2, #000000 a #FFFFFF,
písmo Manrope.

Lokální obrázek ze složky assets/ je použitý jen jako doplněk v úvodní kartě Princip služby.
Lokální assets/contour-texture.svg je použitá jako jemná textura vnějšího pozadí, ne v obsahovém panelu.
Decentní linkové ikony jsou vložené přímo v index.html jako inline SVG symboly.
Záložka Nabídky obsahuje statický formulář napojený přes mailto; pro ostrý provoz bude vhodné doplnit backend nebo formulářovou službu.

Poznámka k logu a vzoru pozadí:
V prototypu jsou pro rychlý náhled načítány přímo z aktuálního webu petrpernica.cz.
Pro ostré nasazení doporučuji uložit logo a případný background pattern lokálně do složky assets/ a přepsat cesty v HTML/CSS.
