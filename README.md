# MITRA Posadzki

Strona internetowa firmy **MITRA Posadzki** — profesjonalne usługi posadzkarskie na terenie Poznania i okolic.

## O firmie

MITRA Posadzki specjalizuje się w wykonawstwie:

- **Posadzek anhydrytowych** — nowoczesne podkłady podłogowe idealne do ogrzewania podłogowego
- **Posadzek przemysłowych** — beton zacierany na gładko dla hal, garaży i obiektów przemysłowych
- **Pianobetonu** — lekka piana mineralna zastępująca tradycyjną izolację styropianową
- **Mas samopoziomujących** — cienkowarstwowe wylewki do wyrównywania powierzchni
- **Żywicy epoksydowej** — estetyczne i trwałe wykończenie posadzki w garażu

## Technologie

- [Astro](https://astro.build/) — framework do budowy statycznych stron
- [Lenis](https://lenis.darkroom.engineering/) — płynne przewijanie strony
- [Sharp](https://sharp.pixelplumbing.com/) — optymalizacja obrazów

## Uruchomienie

```bash
# Instalacja zależności
npm install

# Tryb deweloperski
npm run dev

# Build produkcyjny
npm run build

# Podgląd buildu
npm run preview
```

## Struktura projektu

```
src/
├── components/       # Komponenty Astro (Header, Footer, Hero, Gallery, ...)
├── layouts/          # Layouty stron (BaseLayout, ServicePageLayout)
├── pages/            # Podstrony serwisu
│   ├── index.astro
│   ├── realizacje.astro
│   ├── kontakt.astro
│   ├── posadzka-anhydrytowa.astro
│   ├── posadzka-przemyslowa.astro
│   ├── pianobeton.astro
│   ├── masy-samopoziomujace.astro
│   └── zywica-epoksydowa.astro
└── styles/           # Globalne style CSS
public/
└── images/           # Zdjęcia z realizacji
```

## Kontakt

- **Telefon:** 666-610-404 / 504-946-580
- **Email:** biuro@mitraposadzki.pl
- **Adres:** Os. Bolesława Chrobrego, 60-681 Poznań
