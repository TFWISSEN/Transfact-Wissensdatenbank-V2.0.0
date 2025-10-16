# Artikelstammdaten
[⬅ Zurück zur Übersicht](../index.md)
## Einleitung

### Zweck  
Die Artikelstammdaten bilden die zentrale Informationsbasis im Transfact-System.  
Sie definieren, wie ein Artikel beschrieben, klassifiziert, bepreist und in Prozessen (Produktion, Einkauf, Vertrieb) verwendet wird.  

### Einsatzbereich  
Dieses Kapitel gehört zum Modul **PPS**.  
Es unterstützt Anwender bei der strukturierten Pflege von Artikelinformationen, Stücklisten, Arbeitskarten, Parametern, Preisen, Einheiten und Zuständigkeiten.  

### Voraussetzungen  
- Zugriff auf das Modul **PPS > Artikel**  
- Berechtigung zum Anzeigen und Bearbeiten von Artikeldaten  
- Vorbereitete Stammdaten wie Nummer, Beschreibung, Konten, Parameter oder Preisinfos  

---

## Schritt-für-Schritt-Anleitung

### Erster Überblick der Artikelstammdaten
1. Öffnen Sie die Artikelstammdaten, z. B. über **PPS > Artikel > Abfrage starten > Artikel Nr.**.  
   Hinweis: Häufig genügt ein Klick auf eine mit Hyperlink versehene **Artikelnummer**, um direkt in die Stammdaten zu springen.  
2. Oben finden Sie eine **Schnellübersicht** zu Lagerbestand, Bestellungen und Kundenaufträgen.  
3. In der Detailansicht sehen Sie alle relevanten Informationen:  
   - links die **Allgemeinen Informationen**,  
   - in der Mitte die **Produktionsangaben** (z. B. Stückliste oder Arbeitskarte), 
   - und rechts die **buchhalterischen Daten**.  
#### Stückliste hinzufügen
1. Klicken Sie auf das **grüne Pluszeichen** neben „Aktuelle Stückliste“.  
2. Geben Sie eine **Beschreibung** ein.  
3. **Speichern** Sie die Eingaben.  
4. Die Stückliste erscheint in der Artikelseite.  
*Hinweis: Die inhaltliche Definition der Stückliste erfolgt separat im Kapitel Stücklisten.*  
#### Arbeitskarte hinzufügen
1. Klicken Sie auf das **grüne Pluszeichen** neben „Aktuelle Arbeitskarte“.  
2. Geben Sie eine **Beschreibung** ein.  
3. **Speichern** Sie die Eingaben.  
4. Die Arbeitskarte erscheint in der Artikelseite.  
*Hinweis: Die Ausgestaltung der Arbeitskarte erfolgt separat im Kapitel Arbeitskarte.*  

---

### Reiter Allgemein
1. Klicken Sie auf den Reiter **Allgemein**.  
2. Pflegen Sie grundlegende Artikelinformationen wie:  
   - **Beschreibung, Artikelart**  
   - **Produktionsbezogene Angaben** (Losgröße, Zeichnungen, Seriennummern)  
   - **Lagerparameter** (Lagerplatz, Mindestbestand, Wiederbeschaffungszeit)  
   - **Buchhalterische Daten** (Konten, Steuersätze)  
   - **Verknüpfte Dokumente/Bilder**  

#### Automatische Bestellungen
1. Aktivieren Sie das Feld **Automatische Bestellungen aktivieren**, wenn der Artikel automatisch disponiert werden soll.  
2. Hinterlegen Sie eine **Mindestbestellmenge**, die den Bestellvorschlag auslöst.  
3. Aktivieren Sie bei Bedarf **Reservierungen berücksichtigen**, damit auch reservierte Mengen in die Bedarfsberechnung einfließen.  

---

### Reiter Freigabeobjekte
1. Klicken Sie auf den Reiter **Freigabeobjekte**.  
2. Hier werden Stücklisten und Arbeitskarten angezeigt, die dem Artikel zugeordnet sind.  
3. Erst nach der **Freigabe** können diese Objekte in nachfolgenden Prozessen (z. B. Fertigungslos, Produktion) verwendet werden.  

---

### Reiter Artikelparameter / Klassifizierung
1. Klicken Sie auf den Reiter **Artikelparameter / Klassifizierung**.  
2. Erfassen Sie technische, physikalische oder funktionale Eigenschaften (z. B. Maße, Funktionsumfang).  
   - Parameter können direkt am Artikel erfasst oder aus Vorlagen übernommen werden.  
   - Über die Option **Losanzeige** legen Sie fest, welche Parameter auch in Fertigungslosen sichtbar sind.  
   - Mit Sprachfeldern können Sie Werte mehrsprachig pflegen.  
   - Hinweis: Ab **Version 20770** wird das Feld **Gewicht** nicht mehr hier, sondern in den **Artikeleinheiten** gepflegt.  

---
### Reiter Artikelpreise
1. Klicken Sie auf  den Reiter **Artikelpreise**.  
2. Verwalten Sie die Preisgestaltung für Verkauf (VK) und Einkauf (EK).  

- **Verkauf**  
  - Standard-Verkaufspreis hinterlegen  
  - Kundenbezogene **Preiskonditionen (VK)** pflegen  
  - Preisgruppenregeln nutzen (z. B. Vertriebspartner-Gruppe)  

- **Einkauf**  
  - Standard-EK-Festpreis hinterlegen  
  - Lieferantenspezifische **Preiskonditionen (EK)** pflegen  

- **Herstellkosten**  
  - **Cost-Roll durchführen**: vollständige Kalkulation inklusive Stücklistenstruktur  
  - **Partiellen Cost-Roll durchführen**: Kalkulation nur für Hauptartikel und direkt verknüpfte Komponenten  

- **Preis-Historie**  
  - Zeitliche Entwicklung von VK- und EK-Preisen grafisch und tabellarisch darstellen  
  - Filter (Zeitraum, Gruppierung) anwenden  
  - Mit **Abfrage starten** aktualisieren  

- **IST-Preis (Fertigung)**  
  - Tatsächliche Herstellkosten pro Zeitraum auf Basis realer Fertigungsdaten einsehen  

---

### Reiter Artikeleinheiten
1. Klicken Sie auf den Reiter **Artikeleinheiten**.  
2. Definieren Sie die **Basiseinheit** (z. B. Stück).  
3. Legen Sie bei Bedarf **alternative Mengeneinheiten** fest (z. B. Karton, Palette).  
4. Pflegen Sie die **Umrechnungsfaktoren** zur Basiseinheit.  
5. Bestimmen Sie, ob eine Einheit **teilbar** oder nur als Ganzes nutzbar ist.  
*Hinweis: Diese Einstellungen wirken sich auf Preisberechnung, Lagerverwaltung und Belegerstellung aus.*  

---

### Reiter Externe Artikelnummern
1. Klicken Sie auf den Reiter **Externe Artikelnummern**.  
2. Hinterlegen Sie pro Artikel die **externe Nummer** von Kunden oder Lieferanten.  
3. Ergänzen Sie optional eine Beschreibung sowie Erstell-/Änderungsdatum.  
4. Nutzen Sie diese Funktion für:  
   - eindeutige Artikelzuordnung im Belegdruck (Bestellung, Lieferschein, Rechnung),  
   - Vermeidung von Nummernverwechslungen,  
   - automatische Zuordnung im Kunden- oder Lieferantenstamm.  
5. Die Zuordnungen sind **wechselseitig sichtbar** – gepflegte externe Nummern erscheinen auch im Kunden- oder Lieferantenstamm.  

---

### Reiter Loshistorie
1. Klicken Sie auf den Reiter **Loshistorie**.  
2. Nutzen Sie die Filter links:  
   - **Anzahl Treffer** (leer lassen = alle Lose),  
   - **Status** (geplant, angelaufen, beendet usw.),  
   - **Ausgabeformat** (HTML, Excel),  
   - **Abfrage starten** zur Aktualisierung.  
3. Prüfen Sie rechts den **aktuellen Losstatus** (Geplant, Angelaufen, Beendet, Gesperrt, Gutteile, Ausschussteile, %-Ausbeute).  
4. Daneben sehen Sie die **Historie abgeschlossener Lose** mit Kennzahlen zu Stückzahl, Ausschuss und %-Ausbeute über Zeiträume.  

---

### Reiter Ansprechpartner
1. Klicken Sie auf den Reiter **Ansprechpartner**.  
2. Erfassen oder prüfen Sie Zuständigkeiten (z. B. QS-Verantwortlicher, Einkäufer, technischer Ansprechpartner).  
3. Beachten Sie: Eine Zuordnung im Artikelstamm erscheint automatisch auch im Kunden- oder Lieferantenstamm im Reiter **Artikelzuordnungen**.  
4. Beispiel: Ein QS-Verantwortlicher für einen Artikel ist sowohl im Artikelstamm als auch im Kundenstamm sichtbar.  

---

## Zusammenfassung
Die Artikelstammdaten verbinden technische, organisatorische und kaufmännische Informationen in einem zentralen Bereich.  
- Im Reiter **Allgemein** pflegen Sie Basisdaten und Dispositionslogik.  
- In **Freigabeobjekte** steuern Sie Stücklisten und Arbeitskarten.  
- Mit **Artikelparameter** dokumentieren Sie technische Eigenschaften.  
- Über **Artikelpreise** regeln Sie Verkauf, Einkauf und Kalkulation.  
- **Artikeleinheiten** sichern korrekte Mengenumrechnungen.  
- **Externe Artikelnummern** stellen eindeutige Kommunikation mit Kunden und Lieferanten sicher.  
- **Loshistorie** liefert Produktionskennzahlen.  
- **Ansprechpartner** schaffen Transparenz in der Verantwortlichkeit.  

Damit erhalten Sie eine konsistente Grundlage für alle Prozesse in Produktion, Einkauf und Vertrieb.