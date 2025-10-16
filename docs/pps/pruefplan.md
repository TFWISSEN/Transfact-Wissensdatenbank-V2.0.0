# Prüfplan
[⬅ Zurück zur Übersicht](../index.md)
## Einleitung

- **Zweck**  
  Die Funktion **Prüfplan** dient dazu, qualitätsrelevante Prüfkriterien für Artikel zu erfassen, zu pflegen und zu steuern. Sie stellt sicher, dass in der Fertigung standardisierte Prüfwerte und Toleranzen angewendet werden.  

- **Einsatzbereich**  
  Der Prüfplan wird im Modul **PPS > Artikel** verwendet, insbesondere in Verbindung mit Arbeitskarten und Stücklisten. Er bildet die Grundlage für Qualitätsprüfungen in der Fertigung.  

- **Voraussetzungen**  
  - Zugriff auf das Modul **PPS > Artikel**  
  - Berechtigung zum Anlegen und Bearbeiten von Prüfplänen  
  - Gegebene Definitionen für Prüfkriterien, Messeinheiten und Prüfmittel (über **ADMIN > Properties**)  

---

## Schritt-für-Schritt-Anleitung

### Prüfplan öffnen

1. Öffnen Sie den Prüfplan, z. B. über **PPS > Artikel > Abfrage starten > Arbeitskarte Nr. > Prüfplan Nr.**  
   oder über **PPS > Artikel > Abfrage starten > Artikel Nr. > Arbeitskarte Nr. > Prüfplan Nr.**.  
2. Hinweis: Häufig genügt ein Klick auf eine mit Hyperlink versehene **Prüfplan Nr.**, um direkt in den Prüfplan zu springen.  

---

### Prüfkriterien anlegen

1. Klicken Sie auf **Prüfkriterium hinzufügen**.  
2. Wählen Sie den **Prüfkriterium-Typ** (z. B. **Prüfmittel**).  
3. Geben Sie die folgenden Werte ein:  
   - **Sollwert**  
   - **UEG (Untere Eingriffsgrenze)**  
   - **UWG (Untere Warngrenze)**  
   - **OWG (Obere Warngrenze)**  
   - **OEG (Obere Eingriffsgrenze)**  
4. Wählen Sie die **Einheit** aus.  
5. Ergänzen Sie die **Prüfschärfe** sowie eine **Anweisung**.  
6. Klicken Sie auf **Speichern**.  
7. Für weitere Prüfkriterien wiederholen Sie diesen Vorgang.  

---

### Prüfkriterien bearbeiten

1. Klicken Sie auf **Prüfprotokoll editieren** (Symbol: **Bleistift**).  
   - Die Prüfkriterien wechseln in den Bearbeitungsmodus.  
   - In den Spalten **Prüfkriterium**, **Sollwert**, **UEG/UWG/OWG/OEG**, **Einheit**, **Anweisung** usw. können die Werte angepasst werden.  
   - Nach Abschluss klicken Sie auf **Prüfprotokoll aktualisieren**.  

2. Alternativ: Klicken Sie auf das **Bleistift-Symbol** in einer Zeile.  
   - Ein Pop-up-Fenster öffnet sich mit den Details des Prüfkriteriums.  
   - Nach Abschluss klicken Sie auf **Speichern**.  

3. Reihenfolge ändern:  
   - Jedes Prüfkriterium ist in der Spalte **Position** nummeriert.  
   - Passen Sie die **Positionsnummer** an (z. B. von „1“ auf „3“).  
   - Nach dem Aktualisieren übernimmt das System die neue Reihenfolge automatisch.  

---

### Prüfkriterien löschen

1. Wählen Sie die gewünschten Prüfkriterien über die Spalte **Auswahl** (Checkbox) aus.  
2. Klicken Sie im Menü auf **Ausgewählte Prüfkriterien löschen**.  
   - Einzelne Prüfkriterien können auch über das **rote X-Symbol** entfernt werden.  
3. Bestätigen Sie die Abfrage mit **Ja**.  
4. Die ausgewählten Prüfkriterien werden gelöscht.  
5. Um alle Prüfkriterien zu entfernen, klicken Sie auf **Prüfprotokoll löschen** und bestätigen Sie mit **OK**.  

**Hinweis:** Gelöschte Prüfkriterien können nicht wiederhergestellt werden. Falls erforderlich, müssen sie erneut angelegt werden.  

---

### Freigabe und Bearbeitung

- Wenn ein **Prüfplan freigegeben** ist, können keine Prüfkriterien mehr angelegt, bearbeitet oder gelöscht werden.  
- Um Änderungen vorzunehmen, muss die Freigabe über das Symbol **Freigabe zurücknehmen** (grüner Pfeilkreis mit rotem X) aufgehoben werden.  
- Erst nach der Rücknahme sind Bearbeitungen wieder möglich.  

---

## Zusammenfassung

Der Prüfplan unterstützt die strukturierte Pflege und Anwendung von Prüfkriterien im Fertigungsprozess.  
- Sie können Sollwerte, Toleranzen und Einheiten hinterlegen.  
- Prüfkriterien lassen sich anlegen, bearbeiten, neu sortieren oder löschen.  
- Durch die Freigabefunktion wird sichergestellt, dass nur geprüfte und abgestimmte Prüfpläne im Produktionsprozess verwendet werden.  
Damit trägt der Prüfplan entscheidend zur Qualitätssicherung bei.  