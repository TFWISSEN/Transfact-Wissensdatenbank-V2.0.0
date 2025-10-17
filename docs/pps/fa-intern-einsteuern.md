# FA intern einsteuern
[⬅ Zurück zur Übersicht](../index.md)
## Einleitung

### Zweck  
Die Funktion **FA intern einsteuern** dient zur Erstellung interner Fertigungsaufträge für Artikel, die in der Produktion gefertigt werden sollen.  
Sie ermöglicht es, Arbeitskarten, Stücklisten und Terminierungen zu berücksichtigen und den gesamten Ablauf der internen Fertigung zu steuern.  

### Einsatzbereich  
Diese Funktion gehört zum Modul **PPS**.  
Sie wird verwendet, wenn für einen Artikel interne Lose erstellt werden, um Fertigungsaufträge mit klarer Terminierung, Losgröße und Komponentensteuerung anzulegen.  

### Voraussetzungen  
- Zugriff auf das Modul **PPS > Artikel**  
- Berechtigung zur internen Steuerung von Fertigungsaufträgen  
- Vorhandene Arbeitskarte und Stückliste im Artikelstamm  

---

## Schritt-für-Schritt-Anleitung

### Zugang zur Funktion  
1. Öffnen Sie **PPS > Artikel > Abfrage starten > Artikel Nr.**  
2. Klicken Sie in der Spalte **Aktion** auf das Symbol mit den **zwei Zahnrädern** – **Los(e)/FA intern einsteuern**.  
3. Alternativ können Sie in den **Artikelstammdaten** auf **Los(e)/FA intern einsteuern** klicken.  

---

### Rückwärts- / Vorwärtsterminierung  
#### Rückwärtsterminierung (Backward Scheduling)  
- Die Planung startet vom **Bereitstellungstermin** und läuft **rückwärts**.  
- Jeder Vorgang beginnt so spät wie möglich, damit der Fertigungsauftrag pünktlich abgeschlossen wird.  

#### Vorwärtsterminierung (Forward Scheduling)  
- Die Planung startet vom **frühestmöglichen Zeitpunkt** und läuft **vorwärts**.  
- Jeder Vorgang beginnt direkt nach dem vorherigen Schritt.  

**Vergleich:**  
- **Rückwärtsterminierung** sorgt für eine pünktliche Fertigstellung am Stichtag.  
- **Vorwärtsterminierung** ermöglicht eine frühere Fertigstellung und bietet Puffer, kann aber höhere Lagerkosten verursachen.  

---

### FA intern einsteuern  

1. **Arbeitskarte auswählen**  
   - Wenn für den Artikel nur **eine Arbeitskarte** vorhanden ist, entfällt dieser Schritt.  

2. **Komponentensteuerung definieren**  
   - Entscheiden Sie, ob die **Komponenten der Stückliste** eingesteuert werden sollen und in welcher Form:  
     - **Vorabreservierungen über Bestellungen durchführen** (Ja/Nein)  
     - **Vorabreservierungen über Fertigungsaufträge durchführen** (Ja/Nein)  
     - **Reservierungen durchführen** (Ja/Nein)  
     - **Nicht verfügbare Fertigungsartikel einsteuern** (Ja/Nein)  

3. **Losgröße und Anzahl festlegen**  
   - Falls in den Artikelstammdaten eine **optimale Losgröße** hinterlegt ist, wird diese automatisch vorgeschlagen.  
   - Beispiel:  
     - **Gesamtmenge**: 50  
     - **Losgröße**: 10  
     - **Anzahl Lose**: 5  

4. **Terminierung festlegen**  
   - Wählen Sie zwischen **Rückwärtsterminierung** oder **Vorwärtsterminierung**.  
   - Geben Sie den gewünschten **Bereitstellungstermin** ein.  

5. **Los einsteuern**  
   - Klicken Sie auf **Intern einsteuern**.  
   - Das System erstellt ein oder mehrere Lose mit einem zugehörigen **Fertigungsauftragsbaum (FA-Baum)**.  

---

## Zusammenfassung  

Mit der Funktion **FA intern einsteuern** können Fertigungsaufträge effizient intern angelegt und gesteuert werden.  
Durch die Auswahl der Terminierungsart, Losgröße und Komponentensteuerung behalten Anwender die Kontrolle über Produktionsplanung und Ressourcenverfügbarkeit.  
So wird eine reibungslose interne Fertigung mit klaren Abläufen und nachvollziehbarer Auftragsstruktur gewährleistet.  