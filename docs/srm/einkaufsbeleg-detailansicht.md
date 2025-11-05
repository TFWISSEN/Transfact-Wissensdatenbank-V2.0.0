# Einkaufsbeleg Detailansicht
[⬅ Zurück zur Übersicht](../index.md)
## Einleitung
Dieses Benutzerhandbuch beschreibt die Nutzung der **Einkaufsbeleg-Detailansicht** im Modul **SRM**.  
Die Ansicht dient der Anzeige, Pflege und Weiterverarbeitung von Einkaufsbelegen wie **Anfragen**, **Bestellungen**, **Wareneingangsbelegen** und **EK-Rechnungen**.  

Sie lernen hier, wie Sie Belege öffnen, bearbeiten, fixieren, archivieren sowie in Folgebelege überführen.  
Voraussetzung ist, dass Sie über entsprechende Berechtigungen im SRM-Modul verfügen.  

---

## Schritt-für-Schritt-Anleitung

### 1. Zugang zur Beleg-Detailansicht
1. Für **neu angelegte Belege** öffnen Sie die Seite über **SRM > Einkaufsbelege anlegen**.  
   Nach dem **Speichern** wird der Beleg angezeigt und kann weiterbearbeitet werden.  
2. Für **vorhandene Belege** klicken Sie auf die **Belegnummer** in der **Belegübersicht**.  
   Der ausgewählte Beleg öffnet sich in der Detailansicht.  

---

### 2. Überblick zur Beleg-Detailansicht
In der **Kopfzeile** sehen Sie die **Belegnummer** sowie Symbole für **Druckvorschau** und **Ereignisverknüpfungen**.  

Die Ansicht gliedert sich in drei Hauptbereiche:

- **Linker Bereich:** zeigt den zugehörigen **Kreditor (Lieferanten)**, die **Sprache** aus den Lieferantenstammdaten, das **Belegdatum** und vorhandene **Dokumente**.  
- **Mittlerer Bereich:** enthält Aktionen wie **Beleg überführen in**, **Kopieren**, sowie Verknüpfungen zu anderen Belegen.  
- **Rechter Bereich:** bietet die Funktionen **Beleg fixieren** und **Beleg archivieren** sowie eine Statusanzeige.  

Im unteren Teil befinden sich mehrere **Reiter**, über die Sie Inhalte des Belegs bearbeiten oder anzeigen können, z. B. **Positionen**, **Adressen**, **Textbausteine**, **Ereignisse/Dok.** und **Beleg Historie**.  
Je nach Belegtyp erscheinen zusätzliche Register wie **Paketversand** oder **Fibu**.

---

### 3. Reiter in der Beleg-Detailansicht

#### 3.1 Reiter Positionen
1. Klicken Sie auf **Neue Positionen erstellen**, um das Fenster **Position editieren** zu öffnen.  
2. Wählen Sie einen **Artikel** und geben Sie die gewünschte **Menge** ein.  
3. Ergänzen Sie bei Bedarf weitere Angaben und klicken Sie auf **Speichern**.  
   Die Position wird dem Beleg hinzugefügt.  
4. In der Spalte **Liefertermin** können Sie das gewünschte **Lieferdatum** eintragen.  

#### 3.2 Reiter Adressen
1. Öffnen Sie den Reiter **Adresse**.  
2. Standardmäßig werden übernommen:  
   - **Rechnungsanschrift** aus den Lieferantenstammdaten  
   - **Lieferanschrift** aus den Stammdaten des TF-Systems  
3. Wenn mehrere Adressen verfügbar sind, können Sie eine andere auswählen:  
   - Markieren Sie die gewünschte Adresse.  
   - Ziehen Sie sie per **Drag & Drop** auf das Ziel-Adressfeld.  
4. Dasselbe Verfahren gilt für **Ansprechpartnerdaten**: Ziehen Sie den gewünschten Kontakt nach oben, um ihn zu übernehmen.  

#### 3.3 Reiter Textbausteine
Die Textbausteine werden automatisch geladen, sofern in **ADMIN > Textbausteinvorlagen** eine Standardvorlage definiert ist.  
Wenn keine Vorlage vorhanden ist, wählen Sie manuell eine aus dem Dropdown **Aus Vorlage laden** und übernehmen diese.  

Ist die Vorlage als bearbeitbar definiert, können Sie sie direkt im Beleg anpassen.  
Mit **Leeren Textbaustein hinzufügen** lässt sich ein neuer Abschnitt ergänzen.  

- **Vorangehende Textbausteine** erscheinen oberhalb der Positionsliste.  
- **Nachfolgende Textbausteine** erscheinen unterhalb der Positionsliste.  
- **E-Mail-Textbausteine** werden beim Versand des Belegs per E-Mail verwendet.  

#### 3.4 Reiter Zusatzinformationen
Hier pflegen Sie ergänzende Informationen zur Bestellung, die nicht in den Positionen, Adressen oder Textbausteinen enthalten sind.  
Diese Daten sind hilfreich für Dokumentation, Nachverfolgung und spätere Auswertungen.  

#### 3.5 Reiter Ereignisse/Dok.
Unter **Ereignisse/Dok.** werden alle Aktivitäten, Mitteilungen und Dokumente angezeigt, die mit dem Beleg verknüpft sind.  
Sie sehen hier sowohl externe Lieferantenkommunikation als auch interne Notizen oder Prüfunterlagen.  

#### 3.6 Reiter Beleg Historie
Die **Beleg Historie** zeigt sämtliche Änderungen und Systemaktionen an, die im Zusammenhang mit dem Beleg stehen.  
Sie können jederzeit nachvollziehen, **wann**, **von wem** und **welche Aktion** ausgeführt wurde.  

---

### 4. Funktionen im Header

#### 4.1 Beleg fixieren
Wenn alle Inhalte vollständig sind, können Sie den Beleg durch Aktivieren des Kontrollkästchens **Beleg fixieren** sperren.  
So wird der Bearbeitungsstand geschützt.  

Um die Fixierung aufzuheben:
1. Deaktivieren Sie das Kontrollkästchen **Beleg fixiert**.  
2. Geben Sie im angezeigten Fenster einen Kommentar ein.  
3. Klicken Sie auf **Fixierung aufheben**.  

**Hinweis:** Wenn der Beleg bereits **original gedruckt** oder **archiviert** wurde, müssen diese Zustände zuerst aufgehoben werden.

#### 4.2 Original drucken
Mit dieser Funktion erzeugen Sie das offizielle PDF-Dokument des Belegs.  
Verwenden Sie sie nur, wenn ein offizielles Dokument benötigt wird, z. B. auf Kundenanforderung.  

1. Öffnen Sie den Beleg in der **Druckvorschau** und prüfen Sie die Eingaben.  
2. Aktivieren Sie das Kontrollkästchen **Original drucken**.  
3. Wählen Sie die gewünschte **Druckversion** (z. B. DE, EN oder Geschäftspapier).  
4. Wählen Sie anschließend:  
   - **Drucken:** wählen Sie einen Drucker und klicken Sie auf **Drucken**.  
   - **Per E-Mail senden:** klicken Sie auf **Per E-Mail**, füllen Sie die Felder **Absender** und **Empfänger** aus und klicken Sie auf **Senden**.  

Gesendete E-Mails und angehängte Dokumente werden automatisch im Bereich **Dokumente** gespeichert.  

#### 4.3 Beleg archivieren
1. Aktivieren Sie das Kontrollkästchen **Beleg archivieren**, um den Beleg manuell zu archivieren.  
2. In vielen Fällen erfolgt die Archivierung automatisch, wenn der Beleg in einen Folgebeleg überführt wird.  
3. Zum Aufheben der Archivierung deaktivieren Sie das Kontrollkästchen **Beleg archiviert**, geben Sie einen Kommentar ein und klicken Sie auf **Archivierung aufheben**.  

#### 4.4 Belegkopie erstellen
Über diese Funktion können Sie eine Kopie eines bestehenden Belegs erzeugen.  
Alle Daten werden übernommen.  
Wenn Sie den Beleg für einen anderen Lieferanten verwenden, prüfen und aktualisieren Sie bitte Adress- und Preisdaten.  

---

### 5. Überführen in nachfolgende Belege
Mit **Beleg überführen in** können Sie bestehende Belege in Folgebelege umwandeln.  

#### 5.1 Anfrage → Bestellung
1. Öffnen Sie den Beleg vom Typ **Anfrage**.  
2. Klicken Sie auf **Bestellung**, um das entsprechende Fenster zu öffnen.  
3. Geben Sie die **Menge** ein.  
4. Klicken Sie auf **Positionen in neuen Beleg vom Typ Bestellung überführen**.  
5. Der neue Beleg vom Typ **Bestellung** wird geöffnet.  
6. In der Spalte **Positionsreferenzen** sehen Sie die ursprüngliche **Anfragenummer**.  

#### 5.2 Bestellung → Wareneingangsbeleg
1. Klicken Sie auf **Wareneingangsbeleg**, um das Eingabefenster zu öffnen.  
2. Geben Sie die **Lieferscheinnummer** (vom Lieferanten) ein.  
3. Tragen Sie die **Menge** ein oder klicken Sie auf **Alles übernehmen**, um die gesamte Menge zu übernehmen.  
4. Ergänzen Sie bei Bedarf zusätzliche Informationen wie **Chargennummer** oder **Verfallsdatum**.  
5. Klicken Sie auf **Positionen in neuen Beleg vom Typ Wareneingangsbeleg überführen**.  
6. Der neue Wareneingangsbeleg öffnet sich automatisch.  

#### 5.3 Wareneingangsbeleg → EK-Rechnung
1. Öffnen Sie den fixierten Wareneingangsbeleg.  
2. Klicken Sie auf **EK-Rechnung**, um das Fenster zu öffnen.  
3. Geben Sie die **Rechnungsnummer** und die **Menge** ein.  
4. Klicken Sie auf **Positionen in neuen Beleg vom Typ EK-Rechnung überführen**.  
5. Laden Sie die Lieferantenrechnung über die **Büroklammer Dokumente** hoch.  
6. **Fixieren** Sie den Beleg abschließend.  

**Voraussetzungen für eine erfolgreiche Buchung:**  
- Ein **Aufwandskonto** für die Artikel ist definiert.  
- Ein **Kreditorenkonto** für den Lieferanten ist angelegt.  

---

## Zusammenfassung
Die Einkaufsbeleg-Detailansicht ermöglicht es Ihnen, sämtliche Belegarten zentral zu bearbeiten, nachzuverfolgen und weiterzuverarbeiten.  
Sie unterstützt Sie dabei, Bestellungen effizient zu erstellen, Wareneingänge und Rechnungen präzise zu verbuchen und alle relevanten Dokumente im Überblick zu behalten.  

Mit den Funktionen **Fixieren**, **Archivieren** und **Überführen in Folgebelege** sichern Sie die Datenqualität und schaffen eine nachvollziehbare Dokumentationskette innerhalb Ihres SRM-Prozesses.
