# Technische Aspekte

![Drupal Flow](https://www.drupal.org/files/drupal_flow_0.gif)

## Standards

* OOP
    * PHP 5.4+
    * Klassen, Interfaces, Traits
    * Dependency Injection
    * PSR
    * MVC-Muster
* Symfony 2
* Composer
* Yaml
* Twig
* u.v.m. ("Proudly invented elsewhere")


## Konfigurationsverwaltung

* Synchronisierung, Import/Export, Versionierung
* Konfigurations-Entitäten (für wiederkehrende Konfigurationsobjekte)
* Config API (für einmalige Konfigurationsobjekte)
* Settings API (umgebungsabhängig)


## Composer

* Installation und Verwaltung der Codebasis mit Composer
* Abhängigkeitsauflösung
* Versionsbedingungen
* eigene Module in Ablauf einbinden
* Aktualisierung: `composer update`
* Multi-Site-Installationen: (mindestens) schwierig


## Web-Dienste

* HAL, HTTP BasicAuth, RESTful, Serialisierung im Kern
* Daten als Dienst
* "Headless" Drupal


## Cache

* Cache-Tags
* vollständiger Entity-Cache
* Asset-Bibliotheken (JavaScript nur, wenn es gebraucht wird)
* Big Pipe


## Themes

* responsive im Kern (breakpoint media queries in Theme-Definition)


## Migration

* Kern-Module für Migration von Drupal 6/7
* Abhängigkeitsprüfung
* Oberfläche
