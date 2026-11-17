# Skladač promptů na plakáty

Webový nástroj, který z několika voleb (styl, barvy, motiv, text) poskládá anglický prompt pro generátor obrázků. Je určený pro začátečníky, kteří chtějí plakát bez typického „AI vzhledu“.

Živá verze: https://promptovacplakatu.evirtualniasistentka.workers.dev/

## Jak to funguje
- Celá stránka je jeden soubor `public/index.html` (HTML, CSS a JavaScript), nic se neinstaluje.
- Běží na Cloudflare Workers jako statické soubory, nastavení je v `wrangler.jsonc`.
- Po každé změně na větvi `main` Cloudflare stránku sám znovu nasadí.

Autorka: Eva Cenklová · [cenklova.cz](https://cenklova.cz)
