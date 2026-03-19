---
layout: home
title: Acasă
---

# 🌱 Creștere Continuă

> *"Calea este scopul."*

Bine ai venit în jurnalul meu de dezvoltare personală. Aici scriu despre:

- 📚 **Învățare** — ce descopăr nou
- 🧠 **Reflecții** — ce înțeleg despre mine și lume
- 🎯 **Progres** — obiective și realizări
- 💡 **Idei** — gânduri care merită păstrate

---

## Ultimele postări

{% for post in site.posts limit:5 %}
### [{{ post.title }}]({{ post.url }})
{{ post.date | date: "%d %B %Y" }}
{{ post.excerpt }}
{% endfor %}

---

## Despre acest blog

Acesta este un spațiu de reflecție și creștere. Nu un tutorial, nu un ghid — doar însemnări pe drumul devenirii.

[Despre mine →](/about/)