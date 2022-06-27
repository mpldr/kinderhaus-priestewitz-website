# Neuigkeiten eintragen

Die Neuigkeiten werden aus TOML-Dateien im Verzeichnis `data/news/` generiert.
Eine Datei pro Eintrag, die Einträge sind nach ihrem Dateinamen sortiert.

Die Struktur dieser Dateien ist wie folgt:
```toml
Datum=2022-05-11
Inhalt='''
Willkommen auf unserer Website2
'''
```

## Eintrag erstellen

Um einen neuen Eintrag zu erstellen eine Datei im Verzeichnis `data/news/`
erstellen. Der Dateiname muss auf `.toml` enden.

Beispiel:
- Datei `data/news/2022-06-22.toml` erstellen ([klick mich](https://github.com/mpldr/kinderhaus-priestewitz-website/new/master/data/news))
- Beispieleintrag von oben einfügen
- Datum im Format Jahr-Monat-Tag angeben
- Inhalt zwischen den `'''` ändern (Markdown wird unterstützt)

## Eintrag bearbeiten

Um einen Eintrag zu bearbeiten einfach die entsprechende Datei in `data/news/`
bearbeiten.

# Seiten bearbeiten

Die Seiten können unter `content/` gefunden und bearbeitet werden.

# Bilder hinzufügen

Die Bilder einfach unter `static/` einfügen. Das Bild kann wie folgt
eingebunden werden:

(nimmt an, dass ein Bild mit dem Namen `gruppe.jpg` hochgeladen wurde)

```md
![kurze Beschreibung](/gruppe.jpg)
<!-- der Slash        ↑ ist wichtig! -->
```

