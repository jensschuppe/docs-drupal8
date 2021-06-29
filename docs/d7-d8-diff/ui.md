# Benutzeroberfläche

## Entitäten

* nicht nur Nodes: Kommentare, Blöcke, etc.
* Felder für alle Entitäten


## Blöcke

* beliebig viele Instanzen
* Übersichtlichere Blockkonfiguration
* Benutzerdefinierte Blöcke als Entitäten mit Typen und Feldern


## Views

* im Kern
* immer noch genial


## Felder

* neue Feldtypen im Kern:
    * DateTime
    * Entity Reference
    * Link
    * Telephone


## Administrationsoberfläche

* Responsive
* neue Werkzeugleiste (noch besser mit Modul *Admin Toolbar*)
* Viele Administrationsoberflächen sind Ansichten und somit konfigurierbar


## Editor

* CKEditor im Kern


## Ansichts- und Formularmodi

* Ansichtsmodi für alles, was eine Entität ist (also z.B. auch Blöcke)
* Formularmodi für Entitäts-Formulare
    * Felder neu sortieren
    * Steuerelemente auswählen
    * Felder verstecken
* weniger Notwendigkeit für `hook_form_alter()`-Implementierungen


## Quick Edit

* Drupal 7: Kontext-Links zum Bearbeiten-Formular
* Drupal 8: direkte Bearbeitung ohne neue Seite zu laden


## Medien

* Medienverwaltung im Kern
* Wiederverwendbarkeit von Mediendaten (Bilder, Videos, etc.)
* Responsive Images im Kern (mehrere Bildstile pro Bild)


## Mehsprachigkeit

* alles übersetzbar: Nodes, Blöcke, Menüs, Benutzerprofile, Taxonomie,
    Ansichten, Bildstile, Textformate, Kommentare, Feeds
* Content Translation, Configuration Translation, Interface Translation


## Barrierefreiheit/-armut

* im Kern: WAI-ARIA


## HTML 5

* bessere Formulare im Kern
* weniger JavaScript
* IE 6, 7, 8 nicht mehr unterstützt (das ist gut!)


## Layout Builder

* Kern-Modul
* konfigurierbare Layouts statt "Anzeige verwalten" der Field API
* Überschreibbar nach Kontext (z.B. für separate Inhaltsseite)


## Content Moderation / Workflows

* Kern-Module
* Zustände und -deren Übergänge für Inhalts-Entitäten
* z.B. Veröffentlichungsstatus
* beliebige Zustände durch andere Module


## Experimentelle Funktionalität

* experimentelle Module
* werden in späteren Minor-Versionen stabil
* z.B. Big Pipe (stabil), Field Layout (experimentell)
