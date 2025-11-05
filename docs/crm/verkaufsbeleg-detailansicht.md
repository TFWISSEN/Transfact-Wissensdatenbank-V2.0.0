# Verkaufsbeleg Detailansicht
[⬅ Zurück zur Übersicht](../index.md)
## Einleitung

### Zweck  
Die Funktion **Verkaufsbeleg Detailansicht** ermöglicht Anwendern, Verkaufsbelege im System einzusehen, zu bearbeiten und deren Prozessstatus zu steuern.  
Sie bildet den zentralen Einstiegspunkt für die Verwaltung von Angeboten, Aufträgen, Lieferscheinen und Rechnungen innerhalb des CRM-Moduls.

### Einsatzbereich  
Diese Funktion wird im Modul **CRM** verwendet und unterstützt alle Schritte des Verkaufsprozesses – von der Angebotserstellung über die Auftragsbearbeitung bis hin zur Rechnungsstellung.  
Sie bietet Zugriff auf Belegdaten, Positionen, Adressen, Textbausteine, Zusatzinformationen und Dokumentationen.

### Voraussetzungen  
- Zugriff auf das Modul **CRM
- Berechtigung zum Anzeigen und Bearbeiten von Belegen  
- Berechtigung für spezifische Funktionen (z. B. Fixierung, Archivierung, Lieferterminanpassung)  

---

## Schritt-für-Schritt-Anleitung

### Beleg ansehen
1. Öffnen Sie einen vorhandenen Beleg durch Klick auf eine **Belegnummer** (z. B. im Suchergebnis in **CRM Belegübersicht** oder aus einem verknüpften Modul, wie **PPS**).  
2. Der Beleg öffnet sich in der **Detailansicht**, bestehend aus:
   - **Kopfzeile:** Belegnummer, Funktionssymbole, z. B. Druckvorschau oder Ereignisverknüpfung  
   - **Header-Bereiche:**  
     - **Links:** Geschäftspartner, Sprache, Belegdatum, Dokumente  
     - **Mitte:** Aktionen wie **Beleg überführen in**, Kopieren oder Verknüpfungen  
     - **Rechts:** Fixierung, Archivierung, Statusanzeige  
   - **Unterer Bereich:** Reiter für Positionen, Adressen, Textbausteine, Zusatzinformationen, Ereignisse/Dokumente und Historie  

---

### 2. Reiter im Verkaufsbeleg

#### Reiter Positionen
1. Klicken Sie auf **Neue Positionen erstellen** (grünes Plus-Symbol).  
2. Geben Sie im Pop-up-Fenster Artikel, Menge, Preis und Rabatt ein.  
3. **Speichern** Sie die Eingaben.  
4. Nach dem Speichern können Sie Positionen **bearbeiten**, **kopieren**, **löschen** oder **Stücklisten anzeigen**.

#### Reiter Adressen
1. Klicken Sie auf den Reiter **Adressen**.  
2. Rechnungs- und Lieferanschriften werden standardmäßig aus den Kundenstammdaten übernommen.  
3. Wenn mehrere Adressen existieren, können Sie per **Drag & Drop** eine andere auswählen.  
4. Gleiches gilt für Ansprechpartner: Ziehen Sie den gewünschten Kontakt nach oben, um ihn zu übernehmen.

#### Reiter Textbausteine
1. Klicken Sie auf den Reiter **Textbausteine**.  
2. Beim Anlegen eines Belegs werden Textbausteine automatisch geladen, wenn in **ADMIN > Textbausteinvorlagen** eine Standardvorlage definiert ist.  
3. Fehlt eine Standardvorlage, können Sie mit **Leeren Textbaustein hinzufügen** neue Textabschnitte erstellen oder wählen Sie über **Aus Vorlage laden** eine Vorlage aus, falls eine Vorlage vorhanden ist. Wenn eine Vorlage bearbeitbar ist, können Sie sie im Beleg anpassen.  
   - **Vorangehende Textbausteine** erscheinen oberhalb der Positionsliste.  
   - **Nachfolgende Textbausteine** erscheinen unterhalb der Positionsliste.  
   - **E-Mail-Textbausteine** werden beim Versand per E-Mail verwendet.

#### Reiter Zusatzinformationen
1. Klicken Sie auf den Reiter **Zusatzinformationen**.  
2. Hier verwalten Sie ergänzende Belegdaten, z. B. Objekt, Auftragsart, Kostenstelle, Projekt, Liefertermine, Versandart oder Zahlungsziel.  
3. Je nach Berechtigung können Felder manuell geändert oder automatisch aus Kunden- und Projektstammdaten übernommen werden.  
4. Die angezeigten Felder variieren je nach Belegtyp: z.B.:
   - Bei **Angeboten** erscheint das Feld **Ablehnungsgrund**.  
   - Bei **Auftragsbestätigungen** wird dieses Feld ausgeblendet.

#### Reiter Ereignisse/Dok.
1. Klicken Sie auf den Reiter **Ereignisse/Dok.**  
2. Hier werden alle zum Beleg gehörenden Ereignisse und Dokumente angezeigt.  
3. Spalten: Ereignisobjekt, Ereignistyp, Fälligkeitsdatum, Verantwortlich, Status, Kommentar, Dokumente, Aktion.  
4. Ereignisse können gelöscht oder deren Historie angezeigt werden.  
5. Über **Zeige Ereignisse vom Debitor** können auch Ereignisse desselben Kunden eingeblendet werden.  
6. Dokumente (z. B. PDF, Word, Bilder) können hochgeladen oder geöffnet werden; sie werden automatisch mit dem Beleg verknüpft.

#### Reiter Beleg-Historie
1. Klicken Sie auf den Reiter **Beleg-Historie**.  
2. Hier werden Änderungen an Positionen (z. B. Mengenänderungen) automatisch dokumentiert.  
3. Die Historie zeigt alle Bearbeitungen von Angebot bis Rechnung an.

---

### 3. Funktionen im Header

#### Beleg fixieren
1. Klicken Sie auf das Kontrollkästchen neben **Beleg fixieren** (rechts oben), um den Beleg gegen Änderungen zu sperren.  
2. Zum Aufheben der Fixierung klicken Sie erneut, geben einen Kommentar ein und bestätigen mit **Fixierung aufheben**.  
3. Hinweis: Wenn der Beleg bereits **Original gedruckt** oder **archiviert** wurde, müssen diese Zustände zuerst aufgehoben werden.

#### Original drucken
1. Klicken Sie auf das Kontrollkästchen neben **Original drucken**, um das offizielle PDF-Dokument des Belegs zu erstellen. Diese Funktion soll nur verwendet werden, wenn ein offizielles PDF erforderlich ist.  
2. Der Beleg kann in der **Druckvorschau** geprüft, gedruckt oder per E-Mail versendet werden. Wenn er per E-Mail versendet wird, sollen zwei Felder beachtet werden:  
   **Absender:** muss als Ansprechpartner hinterlegt sein.  
   **Empfänger:** kann automatisch aus Adressen übernommen oder manuell eingegeben werden.  
3. Dokumente und E-Mails werden automatisch im Bereich **Dokumente** gespeichert.

#### Beleg archivieren
1. Klicken Sie auf das Kontrollkästchen **Beleg archivieren**, um den Beleg manuell zu archivieren.  
2. In vielen Fällen erfolgt eine automatische Archivierung, sobald der Beleg in einen Folgebeleg überführt wird.  
3. Zum Aufheben der Archivierung entfernen Sie das Häkchen, geben einen Kommentar ein und bestätigen mit **Archivierung aufheben**.

#### Überführen in nachfolgende Belege
1. Je nach Belegtyp stehen folgende Optionen zur Verfügung:  
   - Angebot → Auftragsbestätigung (oder Abrufauftrag)  
   - Auftragsbestätigung → Lieferschein, Rechnung, Abschlagsrechnung, Schlussrechnung  
   - Lieferschein → Rechnung  
2. Im Dialog können Positionen hinzugefügt oder entfernt werden.  
3. Eine optische Beleghistorie zeigt alle Kundenprozesse übersichtlich an.

#### Belegkopie
1. Klicken Sie auf **Beleg kopieren**, um eine identische Kopie zu erstellen.  
2. Alle Daten werden übernommen.  
3. Bei Übernahme für andere Kunden oder Lieferanten prüfen Sie Adressen und Preise.

---

### 4. Zusatzinfo für Liefertermin nach Fixierung anpassen

1. Diese Funktion erlaubt die Änderung bestätigter Liefertermine, auch wenn der Beleg bereits fixiert ist.  
2. Anpassungen können nötig werden durch Produktionsänderungen, Materialverfügbarkeit oder Kundenwünsche.  
3. Änderungen wirken sich auf abhängige Prozesse (Produktion, Versand) aus und können betreffen:
   - **Ist-Termin**  
   - **Soll-Termin**  
   - **Zahlungsrelevanter Soll-Termin**  
   - **Wunschliefertermin**  
4. Alle Änderungen werden im Belegverlauf protokolliert.

#### Liefertermin Wunsch anpassen
1. Ermöglicht das Nachtragen oder Ändern des Wunschliefertermins nach Fixierung.  
2. Diese Änderung wird nicht protokolliert.  
3. Das Datum gilt für den gesamten Beleg und kann auf alle Positionen übertragen werden.  
4. Anschließend kann der Liefertermin auf Positionsebene überprüft oder geändert werden.

#### Liefertermin Soll anpassen
1. Berechtigt zum Ändern des Soll-Termins bei nicht zahlungsrelevanten Belegen (z. B. Auftragsbestätigung, Lieferschein).  
2. Änderungen auf Positionsebene werden im Reiter **Beleg-Historie** dokumentiert.

#### Liefertermin Soll anpassen (zahlungsrelevant)
1. Ohne Berechtigung können Soll-Termine in zahlungsrelevanten Belegen (z. B. VK-Rechnungen) nicht geändert werden.  
2. Mit Freigabe ist die Anpassung möglich.

---

## Zusammenfassung

Die Funktion **Verkaufsbeleg Detailansicht** bietet eine umfassende Übersicht über Verkaufsbelege und ermöglicht deren gezielte Bearbeitung, Fixierung, Archivierung und Terminsteuerung.  
Durch strukturierte Reiter, nachvollziehbare Historien und integrierte Rechteverwaltung wird sichergestellt, dass der gesamte Verkaufsprozess transparent, sicher und effizient abgebildet wird.
