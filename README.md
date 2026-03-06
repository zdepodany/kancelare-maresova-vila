# Kanceláře Marešova vila – web k pronájmu

Jednoduchý jednoduchý web pro nabídku pronájmu kanceláří v přízemí Marešovy vily ve Znojmě.

## Struktura webu

- **Hero** – úvodní sekce s hlavním sdělením
- **Prostory** – galerie fotografií (3 kanceláře, kuchyňka, chodba)
- **Informace** – popis prostor a technické parametry
- **Cena a podmínky** – orientační cena a podmínky pronájmu
- **Lokalita** – popis umístění a mapa
- **Kontakt** – kontaktní údaje a formulář

## Co je potřeba doplnit

1. **Fotografie** – nahraďte URL v `index.html` vlastními fotkami prostor
2. **Cena** – upravte částku v sekci Cena (aktuálně 15 000 Kč/měsíc)
3. **Technické parametry** – plocha, vytápění atd.
4. **Mapa** – vložte embed z Google Maps (Share → Embed map) pro přesnou adresu
5. **Kontakt** – telefon, e-mail, adresa
6. **Formulář** – připojte backend nebo službu pro odesílání (např. Formspree, Netlify Forms)

## Spuštění

Otevřete soubor `index.html` v prohlížeči nebo použijte lokální server:

```bash
# Python
python -m http.server 8000

# Node.js (npx)
npx serve .
```

## Soubory

- `index.html` – hlavní HTML
- `styles.css` – styly
- `script.js` – mobilní menu, formulář
