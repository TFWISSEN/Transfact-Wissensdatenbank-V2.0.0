# Ereignisse
[⬅ Zurück zur Übersicht](../index.md)
## Einleitung

- **Zweck**  
  Die Funktion **Ereignisse** dient dazu, kundenbezogene Aktivitäten wie Wiedervorlagen, Kommentare oder Dokumente zu erfassen und zu verwalten. Dadurch behalten Anwender den Überblick über fällige Aufgaben und offene Vorgänge.

- **Einsatzbereich**  
  Diese Funktion wird im **CRM-Modul** verwendet, wenn Kundenkontakte, Wiedervorlagen oder Folgeaktivitäten dokumentiert werden sollen.  
  Ereignisse können sowohl in der **Ereignisübersicht** als auch in den **Kundenstammdaten** angelegt werden.

- **Voraussetzungen**  
  - Zugriff auf das Modul **CRM**  
  - Berechtigung zum Anlegen und Bearbeiten von Ereignissen  
  - Vorhandene Kundendaten im System  

---

## Schritt-für-Schritt-Anleitung

### Ereignis anlegen

1. Öffnen Sie **CRM > Ereignisse**.  
2. Bewegen Sie den **Mauszeiger** auf die **grüne Pinnadel** neben der **Ereignisübersicht**.  
3. Wählen Sie im **Vorschlagsfenster** **„Neues Ereignis“**.  
4. Legen Sie im **Pop-up-Fenster** den **Ereignistyp** fest, z. B. **Wiedervorlage**.  
   - Hinweis: In **ADMIN > Properties > Ereignistypen** werden die Ereignisse definiert.  
     - Der Typ mit der Sortierung **1** wird standardmäßig eingesetzt.  
     - Wenn zwei Typen die gleiche Sortierung haben, wird alphabetisch entschieden.  
5. Alternativ können Sie im **Vorschlagsfenster** direkt die Position **Wiedervorlage** und den Zeitraum (1 Tag, 7 Tage usw.) auswählen.  
   - In diesem Fall wird der **Ereignistyp** automatisch auf **Wiedervorlage** gesetzt, und das Datum wird angepasst.  
6. Pflegen Sie **Firmenname, Verantwortlicher, Ansprechpartner, Kommentar** usw., damit das Ereignis alle wichtigen Informationen enthält.  
7. Schließen Sie die Eingabe mit **Speichern** ab.  

**Hinweis:**  
Ereignisse für einen Kunden können auch in den **Kundenstammdaten** angelegt werden.  
Dort befindet sich ebenfalls die **grüne Pinnadel** neben dem Kunden-Namen.  
- Wenn das Ereignis über **CRM > Ereignisse** angelegt wird, wird der **Verantwortliche** auf den **aktuellen Benutzer** gesetzt.  
- Wenn das Ereignis hingegen aus den **Kundenstammdaten** heraus erstellt wird, übernimmt das System als **Verantwortlichen** die in den **Kundenstammdaten** hinterlegte Person aus dem jeweiligen **Vertriebsgebiet**.  

---

### Ereignisübersicht und Bearbeitung

1. Öffnen Sie die **Ereignisübersicht** über **CRM > Ereignisse**.  
2. In der Übersicht werden alle Ereignisse angezeigt, für die Sie als **Verantwortlicher** eingetragen sind und die bis zum aktuellen Datum **fällig** sind.  
3. Bearbeiten Sie ein Ereignis:  
   - Klicken Sie auf das **Bleistift-Symbol** in der Spalte **Kommentar**, um zusätzliche Informationen einzutragen.  
   - Klicken Sie auf die **Büroklammer** in der Spalte **Dokumente**, um Dateien hochzuladen.  
   - Nutzen Sie bei vorhandenen Unterlagen das **Upload-Symbol (grüner Pfeil)**, wählen Sie die Datei und starten Sie den Upload.  

---

### Status und Fälligkeit verwalten

1. Wenn das Ereignis abgeschlossen ist, ändern Sie den **Status** von *offen* auf *erledigt*.  
2. Benötigen Sie mehr Zeit, wählen Sie eine Schnelleingabe (**+1**, **+7**, **+14**, **+28** Tage).  
3. Das **Fälligkeitsdatum** wird entsprechend angepasst.  

---

### Folgeaktionen aus Ereignissen

1. Wählen Sie in der Tabelle der angezeigten Ereignisse ein bestehendes Ereignis.  
2. Klicken Sie auf das **grüne Beleg-Icon (Verkaufsbeleg anlegen)**.  
3. Wählen Sie im Pop-up den gewünschten **Belegtyp** aus.  
4. Sie werden automatisch zur Seite **Verkaufsbeleg anlegen** weitergeleitet.  

---

## Zusammenfassung

Die Funktion **Ereignisse** unterstützt Anwender dabei, alle kundenbezogenen Aufgaben strukturiert zu verwalten.  
Durch klare Eingaben und eine zentrale Übersicht wird sichergestellt, dass Wiedervorlagen, Dokumente und Folgeaktionen effizient bearbeitet werden können.  
Dies erleichtert die Nachverfolgung von Kundenkontakten und erhöht die Transparenz im Vertriebsprozess.  