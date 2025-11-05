# Belegübersicht
[⬅ Zurück zur Übersicht](../index.md)
## Einleitung

- **Zweck**  
  Die Funktion **Belegübersicht** dient zur Erstellung individueller Berichte, mit denen Belegarten wie Angebote, Aufträge, Lieferscheine oder Rechnungen gezielt analysiert werden können.  
  Anwender können durch eigene Konfigurationen schnell auf relevante Belege zugreifen und Arbeitsprozesse im Vertrieb, Einkauf oder Controlling effizient steuern.

- **Einsatzbereich**  
  Diese Funktion wird im Modul **CRM** verwendet. Sie unterstützt die tägliche Arbeit mit Kundenbelegen, erleichtert die Nachverfolgung offener Vorgänge und ermöglicht eine strukturierte Übersicht aller Belege.

- **Voraussetzungen**  
  - Zugriff auf das Modul **CRM > Belegübersicht**  
  - Benutzerrechte zum Erstellen, Bearbeiten und Speichern von Konfigurationen  
  - Ggf. Berechtigungen zum Anzeigen bestimmter Belegarten  

---

## Schritt-für-Schritt-Anleitung

### 1. Neue Konfiguration erstellen
1. Öffnen Sie **CRM > Belegübersicht**.  
2. Klicken Sie oben links auf das Symbol mit den kleinen Quadraten, um die **Konfigurationsseite** zu öffnen.  
3. Wählen Sie **„Eine neue Konfiguration mit Namen erstellen“** und geben Sie einen aussagekräftigen Namen ein (z. B. *offene Angebote*).  
4. Optional können Sie folgende Einstellungen anpassen:  
   - **Gruppenname:** Mehrere Konfigurationen mit demselben Gruppennamen werden auf der Startseite zusammengefasst.  
   - **Konfiguration kopieren:** Nutzen Sie eine bestehende Konfiguration als Vorlage.  
   - **Sichtbar für alle Benutzer:** Aktivieren Sie diese Option, um die Konfiguration für alle freizugeben.  
   - **Als Favorit auf der Home-Seite anzeigen:** Legen Sie fest, dass die Konfiguration auf der Startseite erscheint.  
5. Speichern Sie Ihre Eingaben.

---
### 2. Filter und Spalten festlegen
1. Öffnen Sie die neu angelegte Konfiguration erneut über das Symbol mit den kleinen Quadraten.  
2. Deaktivieren Sie zunächst alle Filter und aktivieren Sie anschließend nur die benötigten Filter, um eine übersichtliche Darstellung zu gewährleisten.  
3. **Spalten anpassen:**  
   - Klicken Sie mit der rechten Maustaste auf eine Spaltenüberschrift im unteren Bereich.  
   - Wählen Sie **„Spaltendarstellung editieren“**.  
   - Fügen Sie die gewünschten Spalten zu den **eingeblendeten Spalten** hinzu und speichern Sie die Auswahl.  

   **Hinweis:**  
   Die Spaltenanpassung ist nur möglich, wenn im unteren Bereich der **Suchergebnisliste** mindestens eine Zeile angezeigt wird.  
   Falls keine Zeilen vorhanden sind, passen Sie die **Filter** an und klicken Sie auf **Abfrage starten**, bis Datensätze erscheinen. Erst dann können Sie die Spaltenanpassung durchführen.  

4. Klicken Sie auf **„Konfiguration speichern“**, um Ihre Einstellungen zu sichern.  
   **Tipp:** Sollten Sie vor dem Speichern keine Spaltenanpassung vorgenommen haben, können Sie diese auch nachträglich durchführen, indem Sie die gewünschte Konfiguration erneut öffnen.

---

### 3. Konfiguration verwenden
1. Kehren Sie zur **Belegübersicht** zurück.  
2. Wählen Sie die gewünschte Konfiguration (z. B. *offene Angebote*) aus der Liste.  
3. Das System zeigt automatisch alle Belege, die den gesetzten Kriterien entsprechen.

---

### 4. Aktualisierung und Verwaltung
- Bereits gespeicherte Konfigurationen können jederzeit angepasst werden, wenn sich Ihre Anforderungen ändern.  
- So bleiben Filter, Spalten und Gruppierungen immer aktuell.  
- Im Folgenden finden Sie Beispiele für häufig verwendete Konfigurationen.

---

## Beispielkonfigurationen

### Offene Angebote
- **Zweck:** Übersicht über alle Angebote, die noch nicht vollständig in Auftragsbestätigungen überführt wurden.  
- **Wichtige Filter:**  
  - **Modus:** Belege  
  - **Belegdatum:** z. B. „Heute minus 3 Monate“  
  - **Belegtyp:** Angebot  
  - **Kunde, Artikel:** sichtbar  
  - **Zeilenbegrenzung:** 500  
  - **Ausgabeformat:** HTML  
  - **Abfrage sofort starten:** aktiv  
  - **Gruppierung:** Kunde  
  - **Sortierung:** Belegdatum (absteigend)  
- **Empfohlene Spalten:**  
  **Aktion, Auswahl, Typ, Belegdatum, Kunde, Kunden-Nr., Beleg Nr., Artikel, Netto/MwSt/Brutto (Belegwährung)** sowie **Realisierung** (grün ab 70 %) und **Ablehnungsgrund**.  
  → Diese Konfiguration erleichtert die Nachverfolgung offener Angebote.

---

### Offene Auftragsbestätigungen
- **Zweck:** Übersicht über bestätigte Aufträge, die noch nicht vollständig abgeschlossen sind.  
- **Wichtige Filter:**  
  - **Belegtyp:** Auftragsbestätigung  
- **Empfohlene Spalten:**  
  **Aktion, Auswahl, Typ, Belegdatum, Kunde, Kunden-Nr., Beleg Nr., Artikel, LT Bestätigt (gelb), Netto, MwSt, Brutto.**

---

### Offene Auftragspositionen
- **Zweck:** Analyse von Auftragspositionen, die noch nicht vollständig geliefert oder fakturiert wurden.  
- **Wichtige Filter:**  
  - **Modus:** Belegepositionen  
- **Empfohlene Spalten:**  
  **Bestellt, Geliefert, Rest, Lagerbestand, Verfügbarkeit, Reservierungen, Produktionsstatus.**

---

### Offene Lieferscheine
- **Zweck:** Kontrolle von Lieferscheinen, die noch nicht vollständig ausgeliefert oder abgerechnet wurden.  
- **Wichtige Filter:**  
  - **Modus:** Belegepositionen  
  - **Belegtyp:** Lieferschein  
  - **Lieferstatus:** Offen  
  - **Zeilenbegrenzung:** 500  
  - **Ausgabeformat:** HTML  
  - **Gruppierung:** Kunde  
  - **Sortierung:** Lieferdatum (absteigend)  
- **Empfohlene Spalten:**  
  **Aktion, Typ, Belegdatum, Kunde, Kunden-Nr., Beleg Nr., Artikel, Geliefert, Rest, Lagerbestand, Netto, MwSt, Brutto.**

---

### Noch nicht bezahlte Rechnungen
- **Zweck:** Unterstützung des Zahlungsmanagements durch Anzeige offener Rechnungen.  
- **Wichtige Filter:**  
  - **Modus:** Belege  
  - **Belegtyp:** Rechnung  
  - **Zahlstatus:** Offen  
  - **Belegdatum:** z. B. „Heute minus 6 Monate“  
  - **Gruppierung:** Kunde  
  - **Sortierung:** Fälligkeitsdatum (aufsteigend)  
- **Empfohlene Spalten:**  
  **Aktion, Typ, Belegdatum, Fälligkeitsdatum, Kunde, Kunden-Nr., Beleg Nr., Betrag offen, Letzte Zahlung, Mahnstufe, Saldo gesamt.**  
  → Diese Konfiguration ermöglicht eine gezielte Überwachung überfälliger Zahlungen.

---

## Zusammenfassung
Die Funktion **Belegübersicht** bietet flexible Möglichkeiten zur Erstellung und Verwaltung individueller Auswertungen.  
Mit gezielten Filtern, konfigurierbaren Spalten und benutzerdefinierten Gruppierungen behalten Anwender jederzeit den Überblick über offene Angebote, Aufträge, Lieferungen und Rechnungen.  
Dadurch wird eine strukturierte, transparente und effiziente Steuerung der Kundenprozesse im CRM ermöglicht.
