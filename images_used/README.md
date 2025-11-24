# images_used

Denna katalog innehåller ENDAST de bildfiler som används av aktuell jämförelsesida (`index.html`).
Original och historiska filer finns kvar under `../images/` och `../mac/` och rörs inte.

## Struktur
```
images_used/
  iphone/   # iPhone-modeller och färgvarianter som refereras i products-arrayen
  mac/      # Mac-modeller
  ipad/     # iPad-modeller (för närvarande placeholder JPEGs)
```

## Underhåll
- Lägg till nya filer i respektive undermapp och uppdatera `products` arrayen med rätt sökväg.
- Ta bort oanvända filer här när modellen inte längre visas.
- Om du vill byta till retina/1x kombination: behåll filnamn och ersätt bilden.

## Lista över refererade filnamn (uppdaterad automatiskt senast: 2025-10-14)
### iPhone
- compare_iphone_17_pro_max_orange_large_2x.png
- compare_iphone_17_pro_max_blue_large_2x.png
- compare_iphone_17_pro_max_silver_large_2x.png
- compare_iphone_17_pro_orange_large_2x.png
- compare_iphone_17_pro_blue_large_2x.png
- compare_iphone_17_pro_silver_large_2x.png
- compare_iphone_17_air_sky_blue_large_2x.png
- compare_iphone_17_air_gold_large_2x.png
- compare_iphone_17_air_white_large_2x.png
- compare_iphone_17_air_black_large_2x.png
- compare_iphone_17_lavender_large_2x.png
- compare_iphone_17_sage_large_2x.png
- compare_iphone_17_blue_large_2x.png
- compare_iphone_17_white_large_2x.png
- compare_iphone_17_black_large_2x.png
- compare_iphone_16e_white_large_2x.png
- compare_iphone_16e_black_large_2x.png

### Mac
- compare_macbook_air_m3_13_midnight_large_2x.png
- compare_macbook_air_m3_15_midnight_large_2x.png
- compare_macbook_pro_m3_14_spaceblack_large_2x.png
- compare_macbook_pro_m3_16_spaceblack_large_2x.png
- compare_mac_mini_m2_2port_silver_large_2x.png
- compare_imac_24_m3_2023_twoport_blue_large_2x.png

### iPad
- ipad-compare-header-pro-202405.jpeg
- ipad-compare-header-202405.jpeg
- ipad-compare-header-air-202405.jpeg
- ipad-compare-header-pro-202405.jpeg (duplicerad i array – behåll tills ersättning sker)
- ipad-compare-header-mini-202410.jpeg

## Tips
För att städa ytterligare, säkerställ att inga filer i `images_used` saknar referens i `index.html` genom en enkel sökning.

