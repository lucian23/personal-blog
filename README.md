# Creștere Continuă

> Jurnal de dezvoltare personală

## Structură

```
personal-blog/
├── _config.yml       # Configurare Jekyll
├── _posts/           # Postări
├── _layouts/         # Layout-uri HTML
├── _sass/            # Stiluri SCSS
├── assets/           # CSS compilat
├── index.md          # Pagina principală
├── about.md          # Despre mine
└── archives.md       # Arhiva postărilor
```

## Publicare pe GitHub Pages

1. Creează repo nou pe GitHub: `lucian23.github.io` (sau alt nume)
2. Push la acest folder
3. Settings → Pages → Source: main branch
4. Așteaptă câteva minute

## Scrie o postare

Creează fișier în `_posts/` cu format: `YYYY-MM-DD-titlu.md`

```yaml
---
layout: post
title: "Titlul postării"
date: 2026-03-19 08:00:00 +0200
categories: [reflecții]
tags: [etichetă1, etichetă2]
---

Conținutul postării...

<!--more-->

Text după break (pentru excerpt).
```

## Build local (opțional)

```bash
bundle install
bundle exec jekyll serve
# → http://localhost:4000/personal-blog/
```

## Licență

MIT - folosește cum vrei.