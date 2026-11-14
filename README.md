# Physik-Multimetersimulation / Multimeter-Simulation

Eine browserbasierte, interaktive Simulation analoger Multimeter. Die Seite eignet sich zum Üben des Ablesens von Messskalen und zum Erkunden verschiedener Messbereiche.

## Enthaltene Simulationen

- **Metrawatt MA 1H** – analoge Skalen und Messbereichs-Drehschalter.
- **Polytest 1 W** – eigene Skalen und Messbereiche sowie ein separater Drehschalter für Gleich- und Wechselspannung.

Beide Simulationen bieten eine Lösungsanzeige und eine Zufallsaufgabe. In der Kopfzeile kann zwischen den Geräten gewechselt und die Darstellung vom normalen Modus in den Darkmode umgeschaltet werden. Mit **Simulation downloaden** lässt sich das gerade ausgewählte Gerät als eigenständige HTML-Datei speichern.

## Verwendung

Die Seite benötigt keine Installation und keine zusätzlichen Pakete:

1. Repository herunterladen oder klonen.
2. `index.html` in einem aktuellen Webbrowser öffnen.
3. Ein Gerät auswählen, einen Messbereich einstellen und auf die Skala klicken, um den Zeiger zu setzen.
4. **Lösung** zeigt den abgelesenen Wert an; **Z** erstellt eine Zufallsaufgabe.

Alternativ kann die Seite über einen beliebigen statischen Webserver bereitgestellt werden. Es gibt keinen Build-Schritt.

## Technik

Die Anwendung ist in `index.html` enthalten und verwendet HTML, CSS, SVG und JavaScript ohne externe Laufzeitabhängigkeiten.

## Hinweis

Die Simulation dient Lern- und Übungszwecken. Sie ersetzt kein echtes Messgerät und ist nicht für elektrische Messungen geeignet.
