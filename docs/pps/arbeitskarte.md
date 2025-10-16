# Arbeitskarte
[⬅ Zurück zur Übersicht](../index.md)
## Einleitung

- **Zweck**  
  Die Funktion **Arbeitskarte** dient zur Abbildung, Pflege und Steuerung der einzelnen Arbeitsschritte eines Artikels. Sie ermöglicht das Hinzufügen, Bearbeiten, Löschen und Freigeben von Arbeitsschritten sowie die Verwaltung zugehöriger Objekte (Checklisten, Prüfpläne).  

- **Einsatzbereich**  
  Diese Funktion wird im Modul **PPS** eingesetzt, insbesondere in der Fertigungsplanung und Produktionssteuerung.  

- **Voraussetzungen**  
  - Zugriff auf das Modul **PPS > Artikel**  
  - Berechtigung zum Anzeigen und Bearbeiten von Arbeitskarten  
  - Definition von Fertigungsbereichen, Arbeitsschritt-Typen und Ressourcen in **ADMIN > Properties**  

---

## Schritt-für-Schritt-Anleitung

### Arbeitsschritt hinzufügen
1. Klicken Sie auf das **grüne Pluszeichen**, um zur Seite **Arbeitsschritte** zu wechseln.  
2. Wählen Sie den **Fertigungsbereich**, legen Sie den **Arbeitsschritt-Typ** fest und – falls erforderlich – eine bestimmte **Ressource**.  
3. Geben Sie die geplanten Zeiten ein:  
   - **Tr** (Rüstzeit)  
   - **Te** (Bearbeitungszeit)  
   - **TMr** (Mitarbeiter-Rüstzeit)  
   - **TMe** (Mitarbeiter-Bearbeitungszeit)  
4. Hinterlegen Sie bei Bedarf zusätzliche Informationen wie Bestellartikel.  
5. Klicken Sie auf **Speichern**, um den Arbeitsschritt anzulegen.  
6. Falls weitere Arbeitsschritte notwendig sind, gibt es zwei Möglichkeiten:  
   - **Wenn Sie bereits wieder auf der Seite Arbeitskarte sind:**  
     Klicken Sie erneut auf das **grüne Pluszeichen** neben einem Arbeitsschritt, um ins Fenster **Arbeitsschritte** zurückzukehren, und wiederholen Sie Schritt 2–5.  
   - **Wenn Sie sich noch im Fenster Arbeitsschritte befinden:**  
     Klicken Sie auf **Weiteren Arbeitsschritt hinzufügen** und wiederholen Sie Schritt 2–5.  
7. Wenn alle Arbeitsschritte erfasst sind, klicken Sie auf **Zurück zur Liste**, um vom Fenster **Arbeitsschritte** zurück zur **Arbeitskarte** zu gelangen.  

---

### Arbeitskarte editieren

#### Reihenfolge ändern
1. Bewegen Sie den Mauszeiger über die **Pos.-Spalte**.  
2. Halten Sie die linke Maustaste gedrückt, um die gewünschte Zeile zu verschieben.  
3. Ziehen Sie die Zeile an die gewünschte Position und lassen Sie die Maustaste los.  

#### Daten bearbeiten
1. Klicken Sie auf **Arbeitskarte editieren**, um die Felder freizuschalten.  
2. Passen Sie die Werte an (z. B. **Tr, Te, Menge**).  
3. Klicken Sie auf **Arbeitskarte aktualisieren**, um die Änderungen zu übernehmen.  

#### Bedingungen setzen
- **Ohne Bedingungen**: Alle Arbeitsschritte werden parallel ausgeführt.  
- **Mit Bedingungen**: Abhängigkeiten zwischen Arbeitsschritten werden definiert.  
- Über **Default-Bedingungen setzen/wiederherstellen** können Standardabhängigkeiten wiederhergestellt werden.  

Beispiel: Arbeitsschritt 20 startet erst, nachdem Arbeitsschritt 10 abgeschlossen ist.  

#### Bedingungen einblenden & anpassen
1. Klicken Sie auf **Arbeitskarte editieren**.  
2. Wählen Sie **Bedingung einblenden**, um Abhängigkeiten sichtbar zu machen.  
3. Aktivieren oder deaktivieren Sie die Haken, um die gewünschte Reihenfolge zu definieren.  
4. Klicken Sie auf **Arbeitskarte aktualisieren**, um die Anpassungen zu speichern.  

---

### Arbeitsschritte löschen
1. Stellen Sie sicher, dass die **Arbeitskarte im Bearbeitungsmodus** ist.  
   - Falls nicht, klicken Sie zunächst auf **Arbeitskarte editieren**.  
2. Setzen Sie in der Spalte **Auswahl** Häkchen bei den zu löschenden Arbeitsschritten.  
3. Klicken Sie auf **Ausgewählte Arbeitsschritte löschen**.  
4. Bestätigen Sie im erscheinenden Fenster mit **OK**.  
   - Die markierten Arbeitsschritte werden entfernt.  
5. Mehrere Arbeitsschritte können gleichzeitig markiert und gelöscht werden.  
6. Um die gesamte Arbeitskarte zu leeren, wählen Sie **Alle Arbeitsschritte löschen**.  

**Hinweis**: Gelöschte Arbeitsschritte können nicht wiederhergestellt werden. Falls erforderlich, müssen sie erneut über **Vorlage einfügen** oder manuell angelegt werden.  

---

### Checkliste
1. Klicken Sie auf das **grüne Pluszeichen**, um eine neue Checkliste hinzuzufügen.  
2. Geben Sie Bezeichnung und Kommentar ein.  
3. Klicken Sie auf **Speichern**.  
4. Die neue Checkliste erscheint in der Spalte **Checkliste** an der gewählten Position.  

---

### Prüfplan
1. Klicken Sie auf das **grüne Pluszeichen**.  
2. Geben Sie Bezeichnung oder Kommentar ein.  
3. Klicken Sie auf **Speichern**.  
4. Der neue Prüfplan erscheint in der Spalte **Prüfplan**.  

---

### Freigabe von Objekten
- **Einzelne Freigabe**: Klicken Sie auf das **grüne Häkchen** in der Spalte **Checkliste** oder **Prüfplan**.  
- **Gesamte Freigabe**: Klicken Sie auf **Alle offenen Objekte freigeben**.  
- **Freigabe zurücknehmen**:  
  - Für einzelne Objekte: Klicken Sie auf das Symbol **Freigabe zurücknehmen** (Pfeilkreis mit rotem X).  
  - Für alle Objekte: Klicken Sie auf **Freigabe aller Objekte zurücknehmen**.  
  - **Achtung**: Wurde ein Objekt bereits in einem Los verwendet, ist die Rücknahme nicht mehr möglich.  

---

## Zusammenfassung
Mit der Funktion **Arbeitskarte** verwalten Sie Arbeitsschritte und deren Abhängigkeiten im Modul PPS.  
- Über **Arbeitsschritt hinzufügen** legen Sie neue Schritte an.  
- Mit **Arbeitskarte editieren** passen Sie Reihenfolge, Werte und Bedingungen an.  
- Durch **Arbeitsschritte löschen** entfernen Sie einzelne oder alle Positionen.  
- Ergänzend können **Checklisten** und **Prüfpläne** gepflegt und freigegeben werden.  

Damit steht ein vollständiges Werkzeug zur Verfügung, um Produktionsabläufe präzise abzubilden und aktuell zu halten.  