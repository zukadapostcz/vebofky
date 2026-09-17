# Z-Audio — web

Prezentační web pro **Z-Audio** (David Zukal) — ozvučení a osvětlení kulturních akcí, plesů, koncertů a svateb v okolí Blanska, Brna a Boskovic.

Web běží na doméně **[z-audio.cz](https://www.z-audio.cz)**, hostovaný přes GitHub Pages přímo z tohoto repozitáře (větev `main`).

## Struktura repozitáře

```
├── index.html        hlavní stránka
├── dekujeme.html      děkovací stránka po odeslání poptávkového formuláře
├── css/
│   └── style.css      veškeré styly webu
├── img/                obrázky použité na webu (hero, logo, favicon, reference)
├── CNAME               nastavení vlastní domény pro GitHub Pages
├── robots.txt
└── sitemap.xml
```

## Technologie

- čisté HTML + CSS, bez buildovacího procesu
- [Font Awesome](https://fontawesome.com/) (ikony, přes CDN)
- Google Fonts — font Inter
- kontaktní formulář odesílaný přes [Formspree](https://formspree.io/)

## Úpravy obsahu

Většinu textového obsahu (technika, reference, ceník, kontakt) lze upravit přímo v `index.html`. Obrázky pro sekci Reference se přidávají do `img/` a odkazují se v HTML jako `img/nazev.webp`.

## Nasazení

Jakýkoliv commit na větev `main` se automaticky nasadí přes GitHub Pages (workflow *pages build and deployment*). Stav posledního nasazení lze zkontrolovat v záložce [Actions](../../actions).
