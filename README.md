# Creștere Continuă

> Jurnal de dezvoltare personală

🌐 **Live:** https://vreau.id

## Structură

```
personal-blog/
├── _config.yml       # Configurare Jekyll
├── _posts/           # Postări
├── _layouts/         # Layout-uri HTML
├── _sass/            # Stiluri SCSS
├── assets/           # CSS compilat
├── index.html        # Pagina principală
├── about.md          # Despre mine
├── archives.md       # Arhiva postărilor
└── CNAME             # Domeniu custom (vreau.id)
```

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
# → http://localhost:4000/
```

## Licență

MIT - folosește cum vrei.