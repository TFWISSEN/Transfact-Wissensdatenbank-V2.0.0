# Belegübersicht
[⬅ Zurück zur Übersicht](../index.md)
## Einleitung  
Die **Belegübersicht** im Modul **SRM** ist ein flexibles Werkzeug zur Analyse und Steuerung von Einkaufsprozessen.  
Sie erlaubt es, Belege nach individuell definierten Kriterien zusammenzufassen – etwa offene Anfragen, Bestellungen oder Wareneingänge – und so gezielt auf relevante Informationen zuzugreifen.  
Dieses Kapitel zeigt Ihnen, wie Sie eigene Konfigurationen erstellen, anpassen und für wiederkehrende Auswertungen nutzen können.  
So behalten Sie stets den Überblick über offene Vorgänge und Zahlungsstände.

---

## Schritt-für-Schritt-Anleitung  

### 1. Neue Konfiguration anlegen  
1. Öffnen Sie den Pfad **SRM > Belegübersicht**.  
2. Klicken Sie oben links auf das Symbol mit mehreren Quadraten, um die **Konfigurationsseite** zu öffnen.  
3. Wählen Sie **„Eine neue Konfiguration mit Namen erstellen“** und geben Sie einen eindeutigen Namen ein (z. B. *„Offene Anfrage“*).  
4. Optional können Sie folgende Felder anpassen:  
   - **Gruppenname:** Bündelt mehrere Konfigurationen zu einer Gruppe auf der Startseite.  
   - **Konfiguration kopieren:** Nutzt eine bestehende Konfiguration als Vorlage.  
   - **Sichtbar für alle Benutzer:** Gibt die Konfiguration systemweit frei.  
   - **Als Favorit auf der Startseite anzeigen:** Platziert die Konfiguration direkt im Dashboard.  

---

### 2. Filter und Spalten definieren  
1. Öffnen Sie die angelegte Konfiguration erneut über das Symbol mit den Quadraten.  
2. Entfernen Sie alle bestehenden Filter und aktivieren Sie nur die benötigten Kriterien, um die Ansicht klar zu strukturieren.  
3. **Spalten anpassen:**  
   - Klicken Sie mit der rechten Maustaste auf eine Spaltenüberschrift.  
   - Wählen Sie **„Spaltendarstellung editieren“**.  
   - Verschieben Sie relevante Felder in den Bereich **eingeblendete Spalten** und speichern Sie die Auswahl.  

   **Hinweis:** Eine Spaltenanpassung ist nur möglich, wenn mindestens eine Zeile in der **Suchergebnis-Liste** vorhanden ist. Sollte kein Datensatz erscheinen, passen Sie die Filter an und klicken Sie auf **Abfrage starten**.  

4. Klicken Sie abschließend auf **„Konfiguration speichern“**, um Ihre Einstellungen zu sichern.  
   Sie können Spalten später jederzeit nachträglich bearbeiten.

---

### 3. Konfiguration verwenden  
1. Kehren Sie zur **Belegübersicht** zurück.  
2. Wählen Sie in der Liste die erstellte Konfiguration (z. B. „Offene Anfrage“).  
3. Das System zeigt automatisch alle Belege an, die den festgelegten Kriterien entsprechen.  

---

### 4. Bestehende Konfiguration anpassen  
- Wenn sich Anforderungen ändern, bearbeiten Sie bestehende Konfigurationen direkt.  
- Sie können Filter, Spalten oder Sortierungen anpassen, ohne eine neue Konfiguration anzulegen.  

---

## Beispielkonfigurationen  

### Offene Anfrage  
**Filtereinstellungen:**  
- **Modus:** Belege  
- **Belegdatum:** „Heute minus 3 Monate“  
- **Belegtyp:** Anfrage  
- **Lieferant**, **Artikel**, **Zeilenbegrenzung:** 500  
- **Ausgabeformat:** HTML  
- **Gruppierung nach:** Lieferant  
- **Sortierung nach:** Belegdatum (absteigend)  
- **Abfrage sofort starten**

**Wichtige Spalten:**  
**Aktion**, **Auswahl**, **Typ**, **Belegdatum**, **Lieferant**, **Lieferant-Nr.**, **Beleg Nr.**, **Artikel**, **Netto**, **MwSt**, **Brutto (Belegwährung)**  

---

### Offene Bestellungen  
Kopie von *Offene Anfrage* mit geänderten Filtern:  
- **Belegtyp:** Bestellung  
- Zusätzliche Spalte: **LT Bestätigt**

---

### Offene Wareneingänge  
Kopie von *Offene Bestellung* mit geänderten Filtern:  
- **Belegtyp:** Wareneingänge  
- Wichtige Spalten: **Aktion**, **Auswahl**, **Typ**, **Belegdatum**, **Lieferant**, **Lieferant-Nr.**, **Beleg Nr.**, **Artikel**

---

### Offene Positionen je Wareneingang  
Kopie von *Offene Wareneingänge* mit Anpassungen:  
- **Modus:** Belegepositionen  
- **Belegtyp:** Wareneingänge  
- Zusätzliche Spalten: **Pos.-Nr.**, **Bestellt**, **Geliefert**, **Rest**

---

### Zu zahlende Rechnungen  
Kopie von *Offene Bestellungen* mit modifizierten Filtern:  
- **Belegtyp:** EK-Rechnung  
- **Fälligkeitdatum**, **Match Status:** nicht gematcht  
- Zusätzliche Spalten:  
  - **Fälligkeitdatum** (mit bedingter Formatierung: Orange bei Fälligkeit ≤ heute)  
  - **Transaktionen** (Summe €)  
  - **Offener Betrag** (Summe €)  
  - **Zahlstatus**

---

## Zusammenfassung  
Mit der **Belegübersicht** gestalten Sie Ihre eigene Sicht auf Einkaufsprozesse – präzise, übersichtlich und wiederverwendbar.  
Durch die Kombination von Filtern und Spalten definieren Sie, welche Informationen für Ihre tägliche Arbeit relevant sind.  
Die klare Struktur der Konfigurationen hilft, offene Positionen schneller zu erkennen und Entscheidungen auf Basis aktueller Daten zu treffen.  
So bleibt Ihr Beschaffungsprozess transparent, und Ihr System unterstützt Sie im richtigen Moment mit den passenden Informationen.
