# Operator Screen
[⬅ Zurück zur Übersicht](../index.md)
## Einleitung

- **Zweck**  
  Der **Operatorscreen** dient als zentrale Arbeitsoberfläche für Produktionsmitarbeiter. Hier werden Arbeitsschritte gestartet, durchgeführt und abgeschlossen. Damit bildet er die Brücke zwischen der Produktionsplanung und der tatsächlichen Ausführung auf dem Shopfloor.

- **Einsatzbereich**  
  Diese Funktion wird im Modul **PPS** eingesetzt, insbesondere zur Abarbeitung von Fertigungslosen und zur Rückmeldung von Produktionsfortschritten.

- **Voraussetzungen**  
  - Berechtigung für das Modul **PPS**
  - Zugriff auf die **Abarbeitungsliste** durch **Fertigungsübersicht** 
  - Zuordnung einer gültigen **Ressource** für den jeweiligen Arbeitsschritt  

---

## Schritt-für-Schritt-Anleitung

### Zugang zum Operatorscreen
1. Öffnen Sie **PPS > Fertigungsübersicht > Abarbeitungsliste** und klicken Sie in der Spalte **Aktion** auf das **grüne, nach rechts zeigende Dreieck-Symbol**.  
   Alternativ öffnen Sie **PPS > Losübersicht > Abfrage starten** und klicken dort in der Spalte **Schritt(e)/Verzug** auf dasselbe Symbol.  
2. Der Operatorscreen öffnet sich und zeigt die Detailansicht des gewählten Arbeitsschritts.  

---

### Aufbau des Operatorscreens
Die Seite gliedert sich in **drei Hauptbereiche**:

1. **Oberer Bereich – Fertigungslos und aktueller Arbeitsschritt**  
   Enthält Informationen zu Fertigungsauftrag, Fertigungsartikel, aktuellem Arbeitsschritt und Ressourcendokumenten.  
   Wichtige Funktionen:  
   - **Arbeitsschritt anmelden**  
   - **Arbeitsschritt hinzufügen**（z. B. unvorhergesehenen Schritt, Schritt kopieren, Schritt mit Checkliste/Prüfplan kopieren）

2. **Mittlerer Bereich – Benutzer- und Schichtinformationen**  
   Zeigt die geplanten Werte (Soll-Situation) an, z. B. **1 Stück**, **T Me = 2 Minuten**.  

3. **Unterer Bereich – Checkliste**  
   Enthält die für den Arbeitsschritt hinterlegte **Checkliste** zur Qualitätssicherung.

---

### Arbeitsschritt starten
1. Prüfen Sie im Feld **Ressource**, ob die richtige Maschine oder Arbeitsstation ausgewählt ist.  
2. Klicken Sie auf das **grüne, nach rechts zeigende Dreieck-Symbol** (**Arbeitsschritt anmelden**).  
3. Nach der Anmeldung erscheinen im mittleren Bereich die IST-Daten:  
   - **Benutzername** und **Anmeldezeitpunkt**  
   - Erfasste **Mengen** (Gut, Schlecht, Gesperrt)  
   - **Zeitwerte**:  
     - **Tr** – Rüstzeit  
     - **Te** – Bearbeitungszeit  
     - **Tm** – Mitarbeiterzeit  
   - **Kommentar**: Hier können Sie Anmerkungen oder Hinweise eintragen.  

---

### Arbeitsschritt abschließen
1. Nachdem der Arbeitsschritt abgeschlossen ist, klicken Sie auf das **rote Zahnrad-Symbol** (**Abmeldung**).  
2. Falls keine Zeitwerte eingegeben wurden, öffnet sich ein Dialog zur Zeiteingabe.  
3. Nach der Eingabe und dem Speichern wird der Arbeitsschritt abgeschlossen und der nächste Schritt vorbereitet.  

---

### Arbeiten mit Prüfplan
1. Starten Sie den Arbeitsschritt wie oben beschrieben.  
2. Wenn ein **Prüfplan** vorhanden ist, erscheint ein **Symbol mit schwarzem Rahmen und blauen/schwarzen Kreisen**.  
3. Klicken Sie auf dieses Symbol, um die **Prüfprotokoll-Ansicht** zu öffnen.  
4. Geben Sie dort alle erforderlichen **Messwerte** ein.  
5. Kehren Sie über den **blauen, nach links zeigenden Pfeil** zur Hauptansicht zurück.  
6. Tragen Sie im mittleren Bereich die Daten ein und schließen Sie den Arbeitsschritt mit dem **roten Zahnrad-Symbol** ab.  

---

### Losdetailansicht nach Durchmeldung
Nach der vollständigen Rückmeldung wird in der **Losdetailansicht** der gesamte Fertigungsprozess dokumentiert.  
Sie enthält:
- **Anmeldezeitpunkt** und **Abmeldezeitpunkt**  
- **Verwendete Ressource**  
- **Zeitdaten (Tr, Te, Tm)**  
- **Gut-, Ausschuss- und gesperrte Mengen**

Diese Informationen ermöglichen eine präzise Nachverfolgung und Auswertung der Fertigungsprozesse.  

---

## Zusammenfassung

Der **Operatorscreen** ist das operative Herzstück der Produktion.  
Er ermöglicht es Anwendern, Arbeitsschritte effizient durchzuführen, Zeiten und Mengen zu erfassen und Qualität sicherzustellen.  
Nach der Durchmeldung stehen alle relevanten Daten in der **Losdetailansicht** und auch in der **Rückmeldung** zur Verfügung – als Grundlage für Auswertung, Nachkalkulation und kontinuierliche Verbesserung.  