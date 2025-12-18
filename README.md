# Helianas Items Compendium

Dieses Modul bringt die Harvesting-Komponenten aus *Heliana's Guide to Monster Hunting* als Foundry VTT Kompendium fuer das aktuelle D&D5E-System (5.2.3) mit Foundry V13.

## Installation

1. Oeffne in Foundry VTT den Reiter **Add-on Modules**.
2. Klicke auf **Install Module** und trage die Manifest-URL ein:
   ```
   https://raw.githubusercontent.com/Elzakin/Helianas-Items-Module/main/module.json
   ```
3. Nach der Installation das Modul in deiner Welt aktivieren.

## Inhalt

* Alle Komponenten-Tabellen aus dem Kochsystem (Aberrations bis Untote) sind als einzelne Items umgesetzt.
* Komponententypen haben passende Ordnerstruktur, Preise und Gewichte gemaess der Common-Richtlinien (0.1–5 gp, 0.05–3 lb).
* Die Essenzen-Tabelle (Frail bis Deific Essence) ist als separates Unterverzeichnis enthalten.
* Beschreibungen beinhalten die Ernte-DC und Regelhinweise (essbar, volatil, Ersatzkategorien usw.).

## Nutzung

* Oeffne in deiner Welt das Kompendium **Helianas Kochkomponenten**.
* Importiere einzelne Items via Drag & Drop oder nutze **Import All Content**, um alle Ordner zu uebernehmen.
* Beim Crafting oder Kochen kannst du die Items in Inventaren verwalten, Preise anpassen oder eigene Notizen ergaenzen.

## Erweiterung

1. Exportiere eigene Komponenten oder Rezepte aus deiner Welt als Kompendium und speichere die `.db`-Datei im Ordner `packs/`.
2. Erstelle bei Bedarf weitere Packs und traage sie in `module.json` unter `packs` ein.
3. Halte dich bei neuen Harvesting-Items an die Preis-/Gewichtsrichtlinien, damit das Balancing konsistent bleibt.

## Kompatibilitaet

* Foundry VTT 13 (getestet mit 13.351)
* D&D5E System 5.2.3

Bei anderen Versionen pruefe die Kompatibilitaet und passe die Angaben in `module.json` entsprechend an.
