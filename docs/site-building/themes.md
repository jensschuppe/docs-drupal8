## Theme-Komponenten

- Informationen (Name, Beschreibung)
- Bibliotheken (Stylesheets, JavaScript, externe Ressourcen)
    - Vorhandene Bibliotheken können überschrieben/erweitert werden
- Regionen
- Logo
- Favicon
- Funktionen (konfigurierbares Ein-/Ausschalten von Komponenten wie Logo,
  Benutzerbildern, etc.)
- CKEditor-Stylesheets

## Basis-Themes (Base Themes)

- Ableitung/Vererbung von Basis-Themes (beliebig tiefe Hierarchie)
- für geringfügige Änderungen an bestehenden externen Themes
- für Implementierungen von Theme-Frameworks (z.B. Bootstrap)

## Regionen (Regions)

- Definition von Inhaltsbereichen, in die Blöcke platziert werden können
- Ausgabe in Vorlagen

## Bibliotheken (Libraries)

- Stylesheets, JavaScript, etc. des Themes selbst
- externe Ressourcen (z.B. Webfonts, Frameworks aus CDNs)
- Erweitern, Überschreiben oder Deaktivieren bestehender Bibliotheken, z.B. für
  alternierende Implementierung von Kontextlinks, Ausklapp-Elementen, etc.

## Vorlagen (Templates)

- In Template-Sprache _Twig_
- Definieren Ausgabe für alle Elemente der Website
- Werden durch das bereitstellende Modul definiert und können überschrieben
  werden
- Rendern von innen nach außen (übergeordnete Elemente beinhalten gerenderte
  Ausgabe beinhalteter Elemente), z.B. _Feld_ in _Entität_ in _Ansicht_ in
  _Block_ in _Region_ in _Seite_

### Template Suggestions

- Zum Überschreiben von Templates in bestimmten Kontexten
- Werden von Modulen oder Themes bereitsgestellt, bzw. können im Theme selbst
  definiert werden
- Beispiele:
    - abweichendes Template für Inhalte eines bestimmten Inhaltstyps oder mit
      einer bestimmten ID
    - abweichende Darstellung für Felder eines bestimmten Typs in einem
      bestimmten Ansichtsmodus

### Präprozessoren (Preprocessors)

- Implementierung von Template-Hooks im Theme (im Code)
- Aufbereitung der Variablen, die in das Template gegeben werden
- Erlaubt Anpassungen der Ausgabe, für die keine Konfiguration vorhanden ist,
  oder unter bestimmten Voraussetzungen, die eine komplizierte Logik erfordern
