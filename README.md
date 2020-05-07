
# astahtwberlin.github.io 
![deploy](https://github.com/astahtwberlin/astahtwberlin.github.io/workflows/deploy/badge.svg)

Webseite des AStA der HTW Berlin

## Aufbau der Website

### _includes
Enthält HTML-Code-Snippets, die einen eigenständigen Teil der Website abbilden (z.B. Events, Members, ...)

### _layout
Enthält HTML-Code-Snippets, die die Struktur der Website abbilden. Diese können als Vorlage für neue Seiten verwendet werden.

### _data
Enthält Daten für die Webseite im yml wie Referate oder Gremien. Diese werden dann in den entsperchenden Bereichen der Seite eingefügt.

### assets
Hier können Dateien abgelegt werden, die auf der Website eingebunden werden sollen (z.B. Bilder, Stylesheets, ...).

## Lokale Installation

ACHTUNG: Um das Projekt unter Windows testen zu können, muss zuerst Ruby installiert werden (siehe [ruby-lang.org](https://www.ruby-lang.org/en/))

- Projekt von GitHub klonen
- Terminal im Projekt-Root-Ordner öffnen
- `bundle install` ausführen

Um die Website lokal zu testen, kann nach der Installation `bundle exec jekyll serve` im Terminal ausgeführt werden
