# teszt

Tesztrepó a GitHub és a Claude összekapcsolásának kipróbálásához.

- Létrehozva: 2026. november 3.
- Tulajdonos: Szalontai Jenő

## Tartalom

- [`ste-kalkulator/`](ste-kalkulator/public/index.html) – Okos STÉ Kalkulátor (2026. október 29-i változat), a KAP-RD09a-2-26 kisüzemi pályázat üzemméret-számításához. Önálló HTML-oldal, böngészőben megnyitva működik.

## Cloudflare

A `ste-kalkulator/wrangler.jsonc` köti a mappát a Cloudflare `cold-frog-3216` Workeréhez. A Worker 2026. november 4. óta össze van kötve ezzel a repóval (Cloudflare: Settings → Builds, gyökérmappa: `/ste-kalkulator`), így minden feltöltés után magától frissül.
