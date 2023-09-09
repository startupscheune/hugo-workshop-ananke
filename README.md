# hugo-workshop-ananke
Hugo Website Starter-Workshop

Verwendete Hugo Version: 
- hugo v0.106.0-e08ce30fe4779e7d8a8395d7021314b915648cb4+extended
- https://github.com/gohugoio/hugo/releases/tag/v0.106.0
- Anleitung unter: https://web.archive.org/web/20221127214724/https://gohugo.io/getting-started/quick-start/

Setup:
1. Posts erstellen mit `hugo new posts/my-first-post.md`
- bauen von drafts mit `hugo server --buildDrafts` oder `hugo server -D`
2. Anpassen der config.toml
- baseURL auf die URL der Produktivseite anpassen
- siehe themes\ananke\exampleSite\config.toml als Orientierung
3. Seite publishen mit `hugo`

Git Setup:
- git config --global user.email "DEINEMAIL"
- git config --global user.name "DEINNAME"

# Markdown Basics

Maillink: E-Mail: [deine@mail.de](mailto:deine@mail.de) 

Bilder einbinden: ![Alternativtext](images/dein-bild.jpg)
- Bild muss unter static/images/ liegen

Tabellen: https://markdown-syntax.de/Syntax-GFM/Tabellen/

# Hilfreiche Links

Hintergrund von PNG entfernen: https://www.remove.bg/de

PNG zu SVG umwandeln: https://convertio.co/de/png-svg/

Icons für Namen erstellen: https://namelix.com/

HTML Templates: https://html5up.net/