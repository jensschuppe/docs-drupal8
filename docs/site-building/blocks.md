## Regionen (Regions)

- Werden vom Theme definiert
- Erlauben die Platzierung von Blöcken

## Block-Kategorien (Categories)

- Gruppen von Blöcken (lediglich für Administration)

## Block-Typen (Block Types)

- Werden durch Module bereitgestellt
- Können beliebige Inhalte/Funktionen haben
- Können für Block-Entitätstypen, die das unterstützen, beliebig
  angelegt/konfiguriert werden (z.B. Custom Blocks)

## Block-Instanzen (Block Instances)

- Werden durch Platzieren eines Blocks in einer Region erzeugt
- Es kann mehrere Instanzen eines Blocks geben (anders als in Drupal 7)
- Können individuell konfiguriert werden

## Block-Konfiguration (Block Configuration)

- Beinhaltet Basiskonfiguration für alle Blocktypen:
    - Sichtbarkeit (Inhaltytypen, Seiten, Rollen, etc.)
    - Titel
    - Region
- Beinhaltet Blocktyp-spezifische Einstellungen
    - z.B. für Blocktyp _Menu_: Anzuzeigende Menüebenen
    - z.B. für Blocktyp _Branding_: Site-Name, Slogan, Logo anzeigen oder nicht
