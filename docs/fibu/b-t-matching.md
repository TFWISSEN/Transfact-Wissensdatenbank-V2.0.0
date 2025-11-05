# B-T Matching
[⬅ Zurück zur Übersicht](../index.md)
## Einleitung

**Zweck:**  
Die Funktion **B-T Matching** in der Finanzbuchhaltung (FIBU) dient dazu, Buchungsbelege mit Banktransaktionen zu verknüpfen. Dadurch wird die Zahlungsabwicklung nachvollziehbar und eindeutig dokumentiert.

**Einsatzbereich:**  
Das B-T Matching wird verwendet, um einzelne oder mehrere Belege mit Transaktionen abzugleichen. Ebenso können mehrere Transaktionen einem Beleg zugeordnet werden.  

**Voraussetzungen:**  
- Berechtigung für den Zugriff auf **FIBU → B-T Matching**  
- Vorhandene Belege und Banktransaktionen im System  

---

## Schritt-für-Schritt-Anleitung

### Allgemeine Schritte

1. Wählen Sie einen **Beleg** aus.  
   - Beispiel: Der Beleg **ER240002** soll mit der Transaktion vom **20.02.2024** gematcht werden.  
   - Klicken Sie auf den entsprechenden Beleg in der Spalte **Zug. Transaktion**.  
   - Der Hintergrund des Belegs wird grün.  

2. Wählen Sie eine **Transaktion** aus.  
   - Klicken Sie auf die entsprechende Transaktion in der Spalte **Zug. Belege** (nicht auf **Sammelzahlung**, da Sammelzahlungen mehrere Belege zu einer Transaktion matchen können).  
   - Durch Klicken auf das **rote X** auf beiden Seiten kann das Matching abgebrochen werden.  

---

### Mehrere Belege und Transaktionen

- Mehrere Belege können zu einer Transaktion gematcht werden.  
- Mehrere Transaktionen können zu einem Beleg gematcht werden.  

---

#### Beispiel A: Zwei Belege zu einer Transaktion

**Situation:**  
Die Belege **VR2410024** und **VR2410025** sollen mit der Transaktion vom **26.06.2024** über **12.665** gematcht werden.  

**Vorgehensweise:**  
1. Klicken Sie auf **VR2410024** (oder **VR2410025**) in der Spalte **Zug. Transaktion**.  
2. Nachdem der Hintergrund des Belegs grün wird, klicken Sie auf **Sammelzahlung** bei der Transaktion über **12.665**.  
3. Überprüfen Sie die Inhalte im Dialog.  
4. Wenn alles korrekt ist, klicken Sie auf **Match durchführen**.  

---

#### Beispiel B: Zwei Transaktionen zu einem Beleg

**Situation:**  
Eine Transaktion über **4.000** soll zusammen mit **3.085** zu Beleg **VR2410026** gematcht werden.  

**Vorgehensweise:**  
1. Klicken Sie auf **VR2410026** in der Spalte **Zug. Transaktion**.  
2. Klicken Sie in der Spalte **Zug. Belege** auf die Transaktion über **4.000**.  
3. Klicken Sie erneut auf **VR2410026** in der Spalte **Zug. Transaktion**.  
4. Klicken Sie in der Spalte **Zug. Belege** auf die Transaktion über **3.085**.  

---

### Teilzahlung vs. Skontozahlung

Bei der Zuordnung von Zahlungen ist es entscheidend, zwischen **Teilzahlungen** und **Skontozahlungen** zu unterscheiden.  

- **Teilzahlung** bedeutet: Der Kunde zahlt nur einen Teil des Rechnungsbetrags. Der Rest bleibt als offene Forderung bestehen.  
- **Skontozahlung** bedeutet: Der Kunde hat den gesamten Rechnungsbetrag beglichen, jedoch unter Abzug eines vereinbarten Skontos.  

**Beispiel:**  
Eine Rechnung über **1.000 €** liegt vor.  

1. **Fall A – Teilzahlung korrekt gebucht**  
   - Der Kunde überweist **200 €**.  
   - Im Matching wird **Teilzahlung** gewählt.  
   - Ergebnis: Offene Restforderung = **800 €**.  

2. **Fall B – Fehler: Teilzahlung als Skonto gebucht**  
   - Der Kunde überweist ebenfalls **200 €**.  
   - Im Matching wird fälschlicherweise **„Manuell mit Skonto“** gewählt.  
   - Das System interpretiert: Kunde hat **1.000 €** gezahlt, minus **800 € Skonto**.  
   - Automatisch wird eine zusätzliche Buchung über **800 €** erzeugt.  
   - Ergebnis: Restforderung = **0 €**, obwohl tatsächlich noch **800 €** offen sind.  

---

### Richtiger Einsatz von „Manuell mit Skonto“

Die Option **„Manuell mit Skonto“** ist nur dann korrekt, wenn folgende Bedingungen erfüllt sind:  

1. Der Kunde zahlt den Rechnungsbetrag abzüglich eines Skontos.  
   - Beispiel: Rechnung 1.000 €, Zahlung 980 € (2 % Skonto).  
2. Es gibt eine vereinbarte Skontoregel (z. B. 2 % bei Zahlung innerhalb von 10 Tagen).  
3. Die Zahlung weicht exakt um den vereinbarten Skontobetrag ab.  

**Vorgehen im Matching:**  
- Betrag **980 €** auswählen.  
- Option **„Manuell mit Skonto“** aktivieren.  

**Ergebnis:**  
- Rechnung wird als vollständig bezahlt markiert.  
- Differenz von **20 €** wird automatisch als Skonto verbucht.  
- Offene Restforderung = **0 €**.  

---

### Wann NICHT „Manuell mit Skonto“

- Wenn der Kunde nur einen Teilbetrag ohne Bezug auf Skonto zahlt (z. B. 200 € von 1.000 €).  
- Wenn die Zahlung nicht exakt dem Skontobetrag entspricht.  
- Wenn keine Skontovereinbarung vorliegt.  

---

## Zusammenfassung

Mit der Funktion **B-T Matching** können Sie Belege und Banktransaktionen effizient miteinander abgleichen.  
Dabei gilt:  

- Teilzahlungen immer als **Teilzahlung** verbuchen.  
- Skonto nur dann verwenden, wenn eine gültige Vereinbarung vorliegt.  
- Falsches Matching kann zu **Doppelbuchungen** und falschen Restforderungen führen.  

So bleibt Ihre Finanzbuchhaltung transparent und korrekt.
