# Audit klicovecentrum.cz — Interaktivní dashboard

Analytický audit a nápravný plán pro klicovecentrum.cz (říjen 2025 – duben 2026).

## Obsah

- `dashboard.html` — interaktivní dashboard s 30 nálezy (priority, akce, časová osa)
- `data/campaigns.json` — agregovaná kampaňová data (Google Ads / Sklik / Heuréka)
- `data/products.json` — výkon top 50 produktů napříč 5 prodejními kanály

## Kategorie nálezů

| Kategorie | Počet |
|-----------|-------|
| 📊 Měření & analytika | 5 |
| 🎯 Google Ads | 5 |
| 🔵 Sklik | 5 |
| 📦 Feedy & srovnávače | 5 |
| 📍 Lokální & pobočky | 5 |
| 🛒 Alza marketplace | 5 |

## Auditované kanály

GA4 · Search Console · Google Ads · Sklik (drak + Fénix API) · Merchant Center · Google Business Profile · Heuréka · Zboží.cz · Firmy.cz · Mergado (produktový feed) · ERP data · Alza Marketplace

## Klíčové metriky

- **Skutečný obrat** (ERP + Alza): 1 300 000 Kč / 7 měsíců
- **Identifikované ztráty**: ~190 000 Kč přímé plýtvání
- **Odhadovaný roční dopad nápravy**: +1 100 000 Kč
- **16 kritických nálezů (P0)**

## Spuštění lokálně

```bash
python -m http.server 8080
# Otevři http://localhost:8080/
```

## GitHub Pages

Dashboard je publikován přes GitHub Pages. Relativní cesty k `data/*.json` fungují přímo.
