## SHS Hagen

Vereinswebseite des SHS Hagen-Selbsthilfe Sucht https://www.shs-hagen.de

### Verwendete Tools

Erstellt mit https://jekyllrb.com/, basierend auf dem minima Theme https://github.com/jekyll/minima

### Texte

- Die aktuelle Texte der Webseite: https://github.com/shs-hagen/shs-hagen/tree/master/_sections
- Die Datenschutz-Seite: https://github.com/shs-hagen/shs-hagen/blob/master/datenschutz.md
- Die Texte nutzen Markdown, z. B. für Fettdruck, Überschriften, etc. Ein Markdown-Editor zum Testen: https://dillinger.io/

### Aktuelle Funktionsweise

- Die Index-Seite (https://github.com/shs-hagen/shs-hagen/blob/master/index.md) enthält eine Schleife um alle Seiten aus dem Ordner `_sections` (https://github.com/shs-hagen/shs-hagen/tree/master/_sections) anzuzeigen
- Jede `_section` definiert ihren eigenen `title`, `order`, `background-color` und `foreground-color` oben im Frontmatter der jeweiligen Seite

### Deployment

Über GitHub Pages. Hier konfiguriert: https://github.com/shs-hagen/shs-hagen/settings/pages
