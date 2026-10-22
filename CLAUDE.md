# Feet First Fair

Sito statico in Markdown, pubblicato con GitHub Pages (Jekyll, tema minima).
- Online: https://feet-first-fair.github.io/ · repo pubblico Feet-First-Fair/feet-first-fair.github.io (organizzazione)
- Pagine nel menu (`header_pages` in `_config.yml`): About, Registration Forms, Shop, Archive. Sito in inglese.
- Shop non è una pagina: `redirect_to` (plugin jekyll-redirect-from) porta a Vinted.
- Font: Arial Narrow, con Archivo Narrow da Google Fonts dove manca (`assets/main.scss`). Arial Narrow non si può servire come web font: licenza.
- Ogni push aggiorna il sito in circa un minuto; verifica con `gh api repos/Feet-First-Fair/feet-first-fair.github.io/pages/builds/latest`.
- NON lasciare file interni pubblicabili: Jekyll rende ogni .md, quindi CLAUDE.md sta in `exclude`.
