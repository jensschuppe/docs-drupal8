- Bereitstellung weiterer Funktionalitäten
- Kernfunktionalität: Sammlung von Kern-Modulen
    - System: eigentlicher Kern
    - User: Benutzer
    - alle anderen Module optional

## Metainformationen/Aufbau

- Projekt (ggf. mit Kategorie)
- Modul(e)
- Versionen: `7.x-x.y`, `8.x-x.y`, bevorzugt: `x.y.z` (Semantic Versioning)
  - Core-Kompatibilität in Metainformationen (`8.x`, `9.x`)
- Abhängigkeit (ggf. nach Version)
- Voraussetzungen (bei Installation geprüft; `hook_requirements()`)
- optionale Integration (`module_exists()`)

## Lebenszyklus

- Nicht installiert
- Installiert
- Unterschied Drupal 7:
    - nicht installiert
    - aktiviert
    - deaktiviert

## Optionale Kern-Module (Auswahl)

- Node, Taxonomy
- Automated Cron
- Block, Custom Block
- Text Editor, CKEditor
- Contextual Links
- Menu, Menu UI, Custom Menu Links
- Field, Field UI, Module für Feldtypen
- Filter
- Internal Page Cache, Internal Dynamic Page Cache
- Media, Media Library
- Path
- Toolbar
- Update Manager
- Views, Views UI
- Language, Übersetzungsmodule
- Experimentelle Kern-Module (Workspaces, Field layout; Big Pipe, Layout
  Manager)

## Contributed Modules

- aus der Drupal-Entwicklergemeinschaft
- wohnen auf [drupal.org](https://www.drupal.org/project/project_module)
- derzeit ca. 47.500, zzgl. Sandbox-Projekte
- lösen fast jedes Problem (zumindest teilweise)
- oft sehr modular (abstrakt denken!)
- Beispiele für Drupal 8:
    - Chaos Tool Suite, Search API, Inline Entity Form
    - Token, Redirect
    - Admin Toolbar, Module Filter
    - Pathauto, Metatag, Simple XML Sitemap
    - Webform, CAPTCHA, Better Exposed Filters

## Custom Modules

- selbstgeschriebene Module, technisch kein Unterschied
- Lösen konkreter Randfälle
- bestehende Konzepte wiederverwenden!
- zur Entwicklergemeinschaft beitragen!

## Modulübersicht

- Projekt-Kategorien
- Kernmodule sind immer alle in Version des Kerns (auch ohne Änderungen)
- Links zu Berechtigungen und Konfiguration
- Modul _Module Filter_ für bessere Übersicht
