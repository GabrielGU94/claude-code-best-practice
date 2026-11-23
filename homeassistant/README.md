# Home Assistant Dashboard

Startversion eines Dashboards mit eingebauten Karten (Sections-View, `tile`, `heading`, `grid`). Es braucht weder HACS noch eigene Resources.

## Status

- **Syntax:** per YAML-Parser geprüft.
- **Gegen echte HA-Instanz getestet:** nein.
- **Entity-IDs:** alle sind Platzhalter. Jede Zeile trägt einen `# TODO`-Kommentar.

## Einspielen

1. Einstellungen → Dashboards → *Dashboard hinzufügen*. Die URL braucht einen Bindestrich, z. B. `zuhause-main`.
2. Dashboard öffnen → Stift → Drei-Punkte-Menü → *Rohkonfigurationseditor*.
3. Inhalt von `dashboard.yaml` einfügen und Entity-IDs ersetzen. Die IDs findest du unter Einstellungen → Entitäten.

## Offene Entscheidungen

- Zielgerät: Wand-Tablet, Smartphone oder Desktop.
- Gewünschte Räume und Bereiche.
- Optik: Standard-Theme oder eigenes Theme.
