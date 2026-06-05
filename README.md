# Import catalog DoarBai — lot 2026-06 (40 produse)

Pachet de import WooCommerce pentru 40 de produse de baie de design (căzi, lavoare, mobilier, oglinzi).

## Conținut
- `products_doarbai.csv` — fișier de import WooCommerce (RO, UTF-8 cu BOM). 40 produse simple.
- `images/<SKU>/01..NN` — imagini per produs; **01 = imaginea principală** (produs izolat), apoi unghiuri. Servite prin GitHub raw, referențiate în coloana „Imagini" din CSV.
- `records_final.json` — date sursă (descrieri, atribute, SEO, ordine imagini).

## Cum se importă
WooCommerce → Produse → Importă → încarcă `products_doarbai.csv` → mapare automată (anteturi RO) → rulează.
Imaginile se descarcă automat de WooCommerce din URL-urile raw.

## Note
- Preț = preț vânzare cu TVA (RON). „Publicat"=1, „În stoc?"=1.
- Coloana „Branduri" e goală (fără producător expus).
- SKU = cod intern (se sincronizează cu Nexus pentru stoc).
