# FA Detailansicht
[⬅ Zurück zur Übersicht](../index.md)
## Einleitung  

### Zweck  
Die Funktion **FA-Detailansicht** ermöglicht es, alle Informationen zu einem Fertigungsauftrag (FA) zentral einzusehen.  
Sie dient der Überwachung des Fertigungsfortschritts, der Materialverfügbarkeit und der Verknüpfung mit zugehörigen Belegen wie Auftragsbestätigungen oder Losen.  

### Einsatzbereich  
Diese Ansicht gehört zum Modul **PPS** und unterstützt Anwender bei der Steuerung und Kontrolle von Fertigungsaufträgen im gesamten Produktionsprozess.  

### Voraussetzungen  
- Zugriff auf das Modul **PPS**  
- Berechtigung zum Anzeigen von Fertigungsaufträgen  
- Bereits angelegte Fertigungsaufträge im System  

---

## Schritt-für-Schritt-Anleitung  

### Zugang zur Funktion  
1. Öffnen Sie die **Belegübersicht**. Wenn ein Beleg eine **FA** beinhaltet, klicken Sie auf die jeweilige **FA-Nummer**, um die **FA-Detailansicht** zu öffnen.  
2. Alternativ können Sie in der **Losübersicht**, wenn ein **Los** zu einer **FA** gehört, ebenfalls auf die **FA-Nummer** klicken.  
3. Die Ansicht öffnet sich in einem neuen Fenster und zeigt die Detailinformationen des gewählten Fertigungsauftrags.  

---

### FA-Übersicht  
In der **FA-Übersicht** sehen Sie die wichtigsten Informationen zum Fertigungsauftrag, z. B. den **Fertigungsartikel**, die **bestellte Menge**, die **gelieferte Menge**, den **Liefertermin**, den **PPS-Bereitstellungstermin (PPS-BST)** sowie den **Fertigungsfortschritt**.  
Zusätzlich stehen **weitere Funktionen** zur Verfügung, etwa **Fertigungskosten anzeigen**.  
Ein Beispiel: Der interne Fertigungsauftrag **FAI250007** ist einer **Auftragsbestätigung (AB)** zugeordnet FAI250007.  

---

### Los- und Materialverfügbarkeit prüfen  
1. Unterhalb der Übersicht finden Sie das erstellte **Los** (z. B. Los-Nr. 460344).  
2. Prüfen Sie die **Verfügbarkeit der Stücklistenartikel**.  
3. Beachten Sie die Spalte **„Stück“** (Status der Artikel):  
   - **Roter Punkt** → Fehlende Artikel für diesen Fertigungsauftrag.  
   - **Gelber Punkt** → Bestand aktuell ausreichend, jedoch mit Unsicherheiten (z. B. Material noch nicht an diesen FA ausgegeben; wenn andere FA denselben Artikel zuerst verbrauchen, kann ein Engpass entstehen).  
   - **Grüner Punkt** → Bestand ausreichend vorhanden.  

---

### Aktionen für Einkaufsartikel (Spalte **„Stand“**)  
Für Einkaufsartikel stehen folgende Buttons zur Verfügung:  
1. **Artikel im Lager suchen und ggf. reservieren oder ausbuchen**  
2. **Reservierung anpassen**  
3. **Neue Vorabreservierung**  
4. **Los(e) einsteuern**  

Zusätzlich gibt es für **Fertigungsartikel der Stücklistenartikel** den Button:  
- **Reservierung durchführen**  

---

### Weiterführende Ansichten  
- Wenn Sie auf **Los-Nr.** klicken, öffnet sich die **Losdetailansicht**. 
- Wenn Sie auf das **grüne, nach links zeigende Dreieck-Symbol** klicken, wechseln Sie zum **Operator Screen**. 

---

## Zusammenfassung  
Die **FA-Detailansicht** bietet einen umfassenden Überblick über jeden Fertigungsauftrag und dessen Materialstatus.  
Sie ermöglicht eine transparente Verfolgung von Fertigungsfortschritt und Verfügbarkeit, unterstützt bei der Steuerung von Losen und bietet direkte Zugänge zu weiterführenden Ansichten wie **Losdetailansicht** und **Operator Screen**.  
Damit ist sie ein zentrales Werkzeug für eine effiziente Produktionssteuerung im PPS-Modul. 