## Website-Einstellungen (Settings)

### Grundeinstellungen

- Name der Website
- Slogan
- E-Mail-Adresse
- Startseite
- Fehlerseiten (403/404)

### Entwicklung

- Cache-Einstellungen
- Aggregation von Stylesheet- und JavaScript-Ressourcen
- Protokollierung und Fehler (Anzuzeigende Meldungen, zu behaltende
  DB-Protokolleinträge)
- Wartungsmodus

### Medien

- Dateisystem
- Bild-Toolkit (GD2, Imagemagick)

### Lokalisierungs-Einstellungen

- Standard-Land, Standard-Sprache, Standard-Zeitzone, Benutzerdefinierte
  Zeitzoneneinstellungen
- Sprachauswahl/-erkennung

## Sprachen

- Definieren verfügbare Sprachen
- Erlauben Übersetzungen
    - der Benutzeroberfläche (Zeichenketten-basiert)
    - von Inhalten (konfigurierbar pro Entitätstyp, falls verfügbar)
    - von Konfigurationsobjekten (konfigurerbar pro Entitätstyp, falls
      vorhanden)
        - auch von Einstellungen (falls verfügbar), z.B. Name der Website,
          Slogan, etc.

### Benutzeroberflächen-Übersetzungen

- Definieren Ersetzungen für (im Code) als übersetzbar markierte Zeichenketten
  für aktivierte Sprachen
- Werden in der Datenbank abgelegt
- Können über eine Benutzeroberfläche editiert werden
- Können im-/exportiert werden

### Spracherkennung und -auswahl

- Methoden zur Spracherkennung (Browser-Sprache, Benutzereinstellung, URL,
  Sitzung, Standardsprache)
- Reihenfolge der Auswahl (z.B. Benutzereinstellung vor Browsersprache)
- Ggf. Einstellungen pro Erkennungsmethode, z.B.
    - URL: Subdomain oder Pfadpräfix
    - benutzerdefinierte Zuordnungen für Browsersprachen

## Textformate (Text formats)

- Definieren Einstellungen für die Darstellung von Textfeld-Inhalten
- Bestehen aus Textfiltern und deren Einstellungen, z.B. HTML-Filter, Bilder
  ausrichten, Zeilenumbrüche umwandeln, URLs in Links umwandeln, Fehlerhaftes
  HTML korrigieren
- Werden bei der Anzeige angewendet, nicht bei der Eingabe
- Können auf Basis von Benutzerrollen eingeschränkt werden

## Bildstile (Image styles)

- Definieren Einstellungen für die Darstellung von Bildern (z.B. in Feldern)
- Bestehen aus Effekten und deren Einstellungen, z.B. Skalieren, Skalieren und
  Zuschneiden, Drehen, Entsättigen, Konvertieren
- Werden bei der Anzeige angewendet, nicht bei der Eingabe

## URL-Aliase

- Definieren HTTP-Umleitungen für Systempfade
- Können auf bestimmte Sprachen festgelegt werden
- z.B. `ueber-uns` und `about-us` für `node/123` in den jeweiligen Sprachen

## Datums-/Zeitformate

- Definieren Anzeigeformate für Datum/Uhrzeit-Angaben (z.B. in Feldern)
- Können auf bestimmte Sprachen festgelegt werden
- z.B. _Standard-Datum (lang)_ mit dem Format `Dienstag, 1. Juni 2021 - 12:34`
  für Deutsche Datumsangaben

## Menüs

- Definieren Gruppierungsmöglichkeiten für Verknüpfungen (Links)
- Name, Titel, Beschreibung, Sprache
- Anordnung von Links in Baumstruktur
- Aktivierung/Ausklappstatus von Eltern-Links konfigurierbar
- Stellen einen Block für die Anzeige des jeweiligen Menüs zur Verfügung
