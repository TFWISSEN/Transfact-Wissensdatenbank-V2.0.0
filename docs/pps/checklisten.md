# Checklisten
[⬅ Zurück zur Übersicht](../index.md)
## Einleitung

**Zweck:**  
Die Funktion **Checkliste** dient der strukturierten Verwaltung von Arbeitsschritten in einer Arbeitskarte.  
Sie ermöglicht das Hinzufügen, Bearbeiten, Löschen sowie die Reihung von Checklistenpositionen.  

**Einsatzbereich:**  
Die Funktion wird im Modul **PPS** genutzt, wenn Arbeitsschritte mit zusätzlichen Prüfungen oder Anweisungen versehen werden sollen.  
Typische Einsatzbereiche sind Fertigungsplanung, Qualitätssicherung und Produktionssteuerung.  

**Voraussetzungen:**  
- Zugriff auf das Modul **PPS > Artikel**  
- Berechtigung zum Anzeigen und Bearbeiten von Arbeitskarten und Checklisten  
- Definition relevanter **Checklisten-Typen** in **ADMIN > Properties > AS-Checklisten-Typen**  

---

## Schritt-für-Schritt-Anleitung

### Checkliste öffnen
1. Öffnen Sie die gewünschte Checkliste über **PPS > Artikel > Abfrage starten > Arbeitskarte Nr. > Checkliste Nr.**  
   oder über **PPS > Artikel > Abfrage starten > Artikel Nr. > Arbeitskarte Nr. > Checkliste Nr.**.  
2. Hinweis: Häufig genügt ein Klick auf eine mit Hyperlink versehene **Checkliste Nr.**, um direkt in die Checkliste zu springen.  

---

### Checklistenpositionen hinzufügen
1. Klicken Sie auf **Checklistenposition hinzufügen** – ein Pop-up-Fenster öffnet sich.  
2. Wählen Sie den **Typ** aus.  
3. Optional:  
   - Wählen Sie Eingaben aus.  
   - Geben Sie eine Anweisung ein.  
4. Klicken Sie auf **Speichern**.  
5. Nach dem Speichern gelangen Sie zurück zur Checkliste-Seite – die neu hinzugefügten Positionen sind jetzt sichtbar.  

---

### Checklistenpositionen bearbeiten
1. Klicken Sie auf **Checklistenpositionen bearbeiten** (Symbol: **Bleistift**).  
   - Die Positionen wechseln in den Bearbeitungsmodus.  
   - In den Spalten **Eingabe**, **Anweisung** usw. können Sie die Werte direkt anpassen.  
   - Nach Abschluss klicken Sie auf **Checklistenpositionen aktualisieren**.  
2. Alternativ: Klicken Sie direkt auf das **Bleistift-Symbol** in einer Zeile.  
   - Ein Pop-up-Fenster öffnet sich, in dem Sie die Details der gewählten Position bearbeiten können.  
   - Nach Abschluss klicken Sie auf **Speichern**.  
3. Reihenfolge ändern:  
   - Bewegen Sie den Mauszeiger in der Spalte **Pos.** über die gewünschte Zeile (der Cursor wird zu einer Hand).  
   - Ziehen Sie die Zeile an die gewünschte Position und lassen Sie die Maustaste los.  
   - Die Reihenfolge der Positionen wird sofort angepasst.  

---

### Checklistenpositionen löschen
1. Wählen Sie die zu löschenden Positionen über die Spalte **Auswahl** (Checkbox) aus.  
2. Klicken Sie im Menü auf **Ausgewählte Checklistenpositionen löschen**.  
   - Einzelne Positionen können auch über das **rote X-Symbol** gelöscht werden.  
3. Bestätigen Sie die Abfrage mit **OK**.  
4. Die markierten Positionen werden entfernt.  
5. Wenn Sie alle Positionen in einem Schritt löschen möchten, klicken Sie auf **Checkliste löschen** und bestätigen Sie mit **OK**.  

**Hinweis:** Gelöschte Positionen können nicht wiederhergestellt werden. Falls erforderlich, müssen sie erneut hinzugefügt werden.  

---

### Hinweis zu Freigabe und Bearbeitung
Wenn eine **Checkliste bereits freigegeben** ist, können keine neuen Positionen hinzugefügt, bestehende bearbeitet oder gelöscht werden.  
Um Änderungen vorzunehmen, muss die Freigabe zuerst zurückgenommen werden.  

- Dies erfolgt über das Symbol **Freigabe zurücknehmen** (grüner Pfeilkreis mit rotem X).  
- Erst nach der Rücknahme können wieder Positionen hinzugefügt, bearbeitet oder gelöscht werden.  

---

## Zusammenfassung

Mit der Funktion **Checkliste** im Modul PPS können Sie Arbeitsschritte strukturiert ergänzen und verwalten:  
- Über **Checklistenposition hinzufügen** erweitern Sie Arbeitskarten.  
- Mit **Checklistenpositionen bearbeiten** passen Sie Inhalte oder Reihenfolgen an.  
- Durch **Checklistenpositionen löschen** entfernen Sie gezielt oder vollständig Positionen.  
- Beachten Sie den Zusammenhang mit der **Freigabe**: Nur nicht-freigegebene Checklisten können geändert werden.  

Dies unterstützt die Qualitätssicherung und sorgt für eine klare Struktur in der Fertigungsplanung.
