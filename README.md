## Data Story: Der Takt des Radverkehrs – Trends und Muster erkennen

In Google Colab öffnen: [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/byte-bayern/open-bydata-notebook-radverkehr/blob/main/radverkehr.ipynb) (Google-Konto notwendig)

Weitere Informationen zur Ausführung von Notebooks findet man in diesem [Repository](https://github.com/byte-bayern/open-bydata-notebooks).

### Was erwartet dich?

Dieses Notebook richtet sich an Einsteiger:innen und Interessierte, die mit offenen Mobilitätsdaten arbeiten möchten. Anhand der **Raddauerzählstellen der Landeshauptstadt München** (15-Minuten-Werte) lernt man, Metadaten von [open.bydata](https://open.bydata.de) zu nutzen, CSV-Daten mit **pandas** einzulesen und Ergebnisse mit **matplotlib** und **folium** darzustellen. Der Schwerpunkt liegt auf Zeitreihen und einfachen räumlichen Einblicken.

- **Daten finden und laden**: Download-URLs über die Search-API von open.bydata abrufen; Zählstellen-Standorte per **WFS/GeoJSON** aus dem Münchner Geoportal
- **Auswertungen**: Jahres- und Tageskennzahlen, Monatsmuster, Vergleich Werktag vs. Wochenende je Zählstelle
- **Visualisierungen**: Linien- und Balkendiagramme, interaktive Karte der Zählstellen

### Erworbenes Know-how

1. **API & Datenbezug**: Verteilungen eines Datensatzes per API ermitteln und CSV-Dateien einlesen
2. **Datenaufbereitung**: Arbeiten mit `pandas` (Gruppierungen, Zeitreihen, numerische Spalten)
3. **Explorative Analyse**: Trends über Jahre und Monate, plausibel interpretieren
4. **Karten im Notebook**: Zählstellen mit **folium** aus offiziellen Geodaten darstellen
5. **Einordnung**: Ergebnisse kritisch betrachten und Ideen für vertiefende Analysen sammeln

### Lizenz

Der Code des Notebooks ist mit der Apache-Lizenz versehen. Wichtig: die im Notebooks verwendeten Datensätze verwenden ggf. andere Lizenzen, die auf open.bydata einsehbar sind.
