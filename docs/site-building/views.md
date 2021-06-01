## Konzept

- Konfigurierbare Datenbankabfragen
- Basistabelle mit Beziehungen (`FROM` in SQL)
- Semantische Gruppierung von Anzeigeoptionen (Vererbung/Übersteuerung), z.B.
  für leicht unterschiedliche Ansichten

## Felder (Fields)

- `SELECT` in SQL
- Definiert durch Basistabellendaten (meistens Felder an Entitäten)
- Können mehrfach hinzugefügt werden
- Können umfassend für die Anzeige konfiguriert werden

## Filter (Filters)

- `WHERE`/`HAVING` in SQL
- Können gruppiert und kombiniert werden mit `AND`/`OR`
- Können exponiert werden (mit spezifischen Einstellungen), z.B. für
  Suchformulare

## Sortierung (Sorts)

- `ORDER BY` in SQL

## Beziehungen (Relationships)

- `JOIN` in SQL
- Definiert Felder in Basisdaten (oder anderen Beziehungen), z.B. _Entity Reference_, _Node Author_

## Kontextfilter (Contextual Filters)

- `WHERE`/`HAVING` in SQL
- Werden der Ansicht zur Laufzeit übergeben (meistens als URL-Parameter)
- z.B. für hierarchische oder Glossar-Ansichten für Listen von Inhalten

## Anzeigen (Displays)

- Verschiedene Anzeigevarianten einer Ansicht
- Sind von einem spezifischen Typ (z.B. Seite, Block, Anhang)
- Haben typspezifische Einstellungsmöglichkeiten
- Können Einstellungen von der Ansicht vererben, bzw. diese überschreiben

### Seite (Page)

- Pfad
- Menüeintrag

### Block

- Blockname und -Kategorie (für Administration)
- Verfügbare Block-Instanz-Einstellungen

### Anhang (Attachment)

- Können anderen Anzeigen angehängt werden (z.B. Seiten)
- Einstellungen:
    - Anhängen an
    - Anhang-Position (davor, danach)
    - Kontextfilter-Vererbung

### Feed

- Pfad
- Anhängen an (Feed-Symbol)

## Formate (Formats)

- Unformatierte Liste
- HTML-Liste
- Tabelle
- Gitter

## Andere Einstellungen

- Zugriffsbeschränkungen (Rollen-/Berechtigungsbasiert)
- Kopf-/Fußbereich
- Verhalten bei keinen Ergebnissen
- Seitennavigation (Pager)
- Gruppierung (`GROUP BY` in SQL) – Umschalten in Gruppierungsmodus
- Weitere Einstellungen
    - Ajax
    - Datenbankabfrage-Einstellungen
    - Zwischenspeichern von Ergebnissen (Cache)

## Theming

- Design-Einstellungen für Felder und Anzeigen (HTML-Elementtypen und CSS-Klassen)
- Vorlagen (Templates) und _Template Suggestions_

## Moduleinstellungen

- Automatische Vorschau
- _Master_-Anzeige
- _Embed_-Anzeige
- SQL-Abfrage azeigen
- Cache deaktivieren
- SQL-Abfragen-Signatur
