# Losdetailansicht
[⬅ Zurück zur Übersicht](../index.md)
## Einleitung

**Zweck**  
    Die Funktion **Losdetailansicht** bietet eine vollständige Übersicht über den Status und die Entwicklung eines Fertigungsloses.  
    Anwender können hier Soll- und Ist-Daten vergleichen, Bearbeitungen durchführen und sämtliche zugehörigen Informationen – von Dokumenten bis zu Mitarbeiterzeiten – nachvollziehen.
**Einsatzbereich**  
    Diese Funktion gehört zum Modul **PPS** und wird überall dort genutzt, wo Fertigungslose geplant, überwacht und analysiert werden, z. B. in der **Losübersicht**, **Fertigungsübersicht**, **Artikelstammdaten** oder im **WIP**.
**Voraussetzungen**
    - Zugriff auf das Modul **PPS**
    - Berechtigung zum Anzeigen und Bearbeiten von Losen
    - Ein bestehendes Fertigungslos (z. B. über einen Fertigungsauftrag oder eine Auftragsbestätigung erzeugt)

---

## Schritt-für-Schritt-Anleitung

### Zugang zur Losdetailansicht

1. Öffnen Sie **PPS > Losübersicht** oder **PPS > Fertigungsübersicht**.
2. Klicken Sie auf die gewünschte **Losnummer** (z. B. im Beleg oder in der Fertigungsübersicht).
3. Die **Losdetailansicht** öffnet sich in einem neuen Fenster und zeigt die Detailinformationen des ausgewählten Fertigungsloses.

---

### Aufbau der Losdetailansicht

Die Seite ist in zwei Hauptbereiche gegliedert:

#### 1. Übersicht des Fertigungsloses (oberer Teil)

Hier finden Sie alle zentralen Informationen zum Fertigungsstatus:

- Zugeordnete **Auftragsbestätigung (AB)** und **Fertigungsauftrag (FA)**
- **Fertigungsartikel**
- **Menge** und **Fortschritt**
- **Bereitstellungstermin (BT)** und **Endtermin**
- Schaltflächen für:
    - **Lagerbewegungen anzeigen**
    - **Fertigungskosten anzeigen**

#### 2. Arbeitsschritte (unterer Teil)

- Die **Soll-Situation** wird aus der **Arbeitskarte** und dem **Bereitstellungstermin** übernommen.
- Die **Ist-Situation** ergibt sich aus den laufenden **Anmeldungen** und **Abmeldungen** der Mitarbeitenden.
- Sobald das Los **durchgemeldet** wurde, können Soll- und Ist-Daten direkt verglichen werden.

Dieser Vergleich ist eine wichtige Grundlage für zukünftige **Planung und Optimierung** der Fertigung.

---

### Navigation zum Operator Screen

- Klicken Sie auf das **grüne, nach links zeigende Dreieck-Symbol**, um in den **Operator Screen** zu wechseln.

---

### Nach der Durchmeldung

Sobald ein Los **durchgemeldet** wurde, erscheinen in der Losdetailansicht alle erfassten **IST-Daten**:

- **Anmeldezeitpunkt** und **Abmeldezeitpunkt**
- **Genutzte Ressource**
- Zeitdaten (**Tr**, **Te**, **Tm**)
- **Gutmenge**, **Ausschussmenge**, **gesperrte Menge**

Diese Angaben dienen der exakten Rückverfolgung der Fertigungsprozesse und Qualitätskontrolle.

---

### Los bearbeiten

#### Header (oberer Bereich – Mitte)

1. Klicken Sie auf das **Stiftsymbol**, um den Bearbeitungsmodus zu aktivieren.
2. Im Editiermodus können Sie:
    - den **Losstatus** ändern,
    - die **Priorisierung** anpassen,
    - den **Endtermin** neu festlegen,
    - **Menge**, **Schrottmenge**, **Prüfart**, **Verantwortliche(r)** oder **Kommentar** bearbeiten.
#### Header (oberer Bereich – rechts)

1. Laden Sie **Dokumente** hoch, die für das Los relevant sind.
2. Ergänzen oder bearbeiten Sie **Vorgängerlose**, **Nachfolgelose** oder **Referenzlose**.
    - Auch das **Löschen** nicht mehr benötigter Referenzen ist hier möglich.
#### Details nach Arbeitsschritt (unterer Bereich)

1. Passen Sie vorhandene **Arbeitsschritte** an (z. B. **Bedingung**, **Anweisung**, **Soll-Ressource**).
    
2. Fügen Sie neue Arbeitsschritte hinzu:
    
    - **A:** Einzelner Arbeitsschritt ohne **Checkliste/Prüfplan**
    - **B:** Einzelner Arbeitsschritt mit **Checkliste/Prüfplan**
    - **C:** Mehrere Arbeitsschritte aus **Vorlage** laden und Position festlegen
3. Ergänzen Sie **Nacharbeitsschritte**, indem Sie festlegen, zwischen welchen Positionen diese eingefügt werden sollen.

---

### An- und Abmeldungen verwalten

1. Wenn ein Los eine **aktive Anmeldung** enthält, können Sie folgende Aktionen ausführen:
    - **An-/Abmeldung komplett zurücknehmen** → Alle Zeiten werden gelöscht.
    - **Anmeldung abbrechen/zurücknehmen** → Die Anmeldung wird beendet,  
        **Zeiten und Daten bleiben erhalten**, die Ressource wird freigegeben.
2. Über das **Stiftsymbol** in der jeweiligen Anmeldung können Sie die Details einsehen oder bearbeiten.
    

---

### Erweiterte Funktionen

1. Klicken Sie im oberen Bereich (Header – Mitte) auf das Symbol mit **zwei Quadraten** (_weitere Aktionen_).
2. Es erscheinen zusätzliche Funktionen:
    
    - **Ausführliche Anzeige der Mitarbeiterzeiten** → Zeigt alle Zeiteinträge im unteren Bereich an.  
        Wenn mehrere Einträge existieren, können Sie über den **Pfeil nach unten** alle Positionen einblenden.
    - **Ausführliche Anzeige der Checklisten** → Listet alle zum Los gehörenden Checklisten auf.
    - **Fertigungskosten anzeigen** → Zeigt **Planwert**, **Istwert** und **Abweichung** im Vergleich.

---

## Zusammenfassung

Die **Losdetailansicht** ist das zentrale Werkzeug für Transparenz im Fertigungsprozess.  
Sie verbindet Plan- und Ist-Daten, ermöglicht gezielte Nachverfolgung und bietet Bearbeitungsfunktionen für alle Losinformationen.  
Durch diese integrierte Sicht behalten Anwender stets die Kontrolle über **Ressourcen**, **Termine** und **Kosten**.