# Nettobedarf
[⬅ Zurück zur Übersicht](../index.md)
## Einleitung

- **Zweck**  
  Die Funktion **Nettobedarf** dient zur Analyse der zukünftigen Verfügbarkeit eines bestimmten Artikels.  
  Auf Basis von aktuellem **Lagerbestand**, geplanten **Zugängen** sowie reservierten oder geplanten **Abgängen** berechnet das System den **Netto-Bedarf** zu verschiedenen Zeitpunkten in der Zukunft.  
  Ziel ist es, frühzeitig Engpässe zu erkennen und gezielte Dispositionsvorschläge (Produktion oder Einkauf) vorzubereiten.  

- **Einsatzbereich**  
  Diese Funktion wird im Modul **PPS** genutzt und unterstützt insbesondere Produktionsplaner:innen, Disponent:innen und Lagerverantwortliche.  

- **Voraussetzungen**  
  - Zugriff auf das Modul **PPS > Nettobedarf**  
  - Berechtigung zum Anzeigen und Exportieren von Bestands- und Bewegungsdaten  
  - Der analysierte Artikel muss im System vorhanden sein  

---

## Schritt-für-Schritt-Anleitung

### Filter setzen
1. Öffnen Sie **PPS > Nettobedarf**.  
2. Geben Sie die gewünschte **Artikelnummer** ein (**Pflichtfeld**).  
3. Optional: Wählen Sie im Feld **Bewegung** einen Bewegungstyp (z. B. Kommissionierung, Dispo-Vorschlag).  
4. Aktivieren Sie ggf. **Filter invertieren**, um bestimmte Bewegungen auszuschließen.  
5. Geben Sie bei Bedarf einen **übergeordneten Artikel** ein.  
6. Wählen Sie das **Ausgabeformat**: **HTML** für Anzeige im System oder **XLSX** für Excel-Export.  
7. Klicken Sie auf **Abfrage starten**.  

---

### Ergebnisanzeige in HTML
1. Nach der Abfrage sehen Sie eine chronologische Liste aller relevanten Bewegungen.  
2. Prüfen Sie die angezeigten Spalten:  
   - **Datum / KW** (Datum und Kalenderwoche)  
   - **Zugang / Abgang** (eingehende oder ausgehende Mengen)  
   - **Kumuliert** (fortlaufender Bestand nach der Bewegung)  
   - **Basiseinheit** (Mengeneinheit, z. B. Stück)  
   - **Bewegung** (z. B. Kommissionierung, Vorabreservierung)  
   - **Ref.Nr.** (z. B. Fertigungsauftragsnummer)  
   - **Kunde / Lieferant** (beteiligte Parteien)  
   - **Übergeordneter Artikel** (falls Teil einer Baugruppe)  
   - **Stückliste** (zugehörige BOM-Struktur)  
   - **Lagerbestand übergeordneter Artikel** (falls zutreffend)  
3. Analysieren Sie die Werte in **Kumuliert**, um Engpässe frühzeitig zu erkennen.  

---

### Ergebnisexport in XLSX
1. Wählen Sie im Filter **Ausgabeformat = XLSX**.  
2. Starten Sie die Abfrage über **Abfrage starten**.  
3. Die Ergebnisse werden in eine Excel-Datei exportiert.  
4. Nutzen Sie diese Datei für tiefere Auswertungen, Präsentationen oder Vergleiche zwischen Artikeln.  

---

## Zusammenfassung

Die Funktion **Nettobedarf** ermöglicht eine vorausschauende Planung des Materialbedarfs.  
Durch die Analyse von Bewegungen und kumulierten Beständen lassen sich Engpässe frühzeitig identifizieren, Dispositionsvorschläge prüfen und Lagerbestände transparent überwachen.  
Dies unterstützt eine effiziente Produktions- und Materialplanung.  