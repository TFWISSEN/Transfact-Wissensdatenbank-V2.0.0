# Lieferantenstammdaten
[⬅ Zurück zur Übersicht](../index.md)
## Einleitung  
Dieses Handbuch unterstützt Sie bei der Pflege und Verwaltung der **Lieferantenstammdaten** im Modul **SRM**.  
Es richtet sich an Benutzerinnen und Benutzer, die Lieferanteninformationen erfassen, ändern oder prüfen möchten.  

Die Lieferantenstammdaten bilden die Grundlage vieler Einkaufsprozesse. Hier werden alle relevanten Informationen zu Lieferanten gespeichert – von Adress- und Kontaktdaten bis hin zu Bankverbindungen, Projekten und Preisvereinbarungen.  
Durch eine sorgfältige Pflege der Stammdaten wird sichergestellt, dass Einkaufsbelege, Rechnungen und Auswertungen korrekt verarbeitet werden.  

**Voraussetzungen:**  
- Zugriff auf das Modul **SRM**  
- Berechtigung zum Bearbeiten von Lieferantenstammdaten  

---

## Schritt-für-Schritt-Anleitung  

### 1. Zugangswege zu Lieferantenstammdaten  
Überall dort, wo der **Lieferantenname** blau und verlinkt dargestellt ist, können Sie durch Anklicken direkt zu den **Lieferantenstammdaten** wechseln.  

**Beispiele:**  
1. **SRM > Lieferanten** → **Abfrage starten** → in der Tabelle auf **Lieferantenname** klicken.  
2. **SRM > Ereignisse** → in der Spalte **Kunde/Lieferant** oder **Ereignisobjekt** auf **Lieferantenname** klicken.  
3. **SRM > Belegübersicht** → auf **Lieferantenname** klicken.  

---

### 2. Reiter „Firmenname“  
Im ersten Reiter (benannt nach dem Lieferantennamen) werden die wichtigsten, zusammengefassten Informationen angezeigt, die in den weiteren Reitern gepflegt werden.  
Dies ermöglicht Ihnen einen schnellen Überblick über den Lieferanten.  

Für neu angelegte Lieferanten sollten die Reiter **Allgemein**, **Ansprechpartner**, **Adresse**, **Bankverbindung** und **Finanzen** vollständig ausgefüllt werden.  

---

### 3. Reiter „Allgemein“  
Im Reiter **Allgemein** können Sie grundlegende Informationen, Kontaktdaten, Branchenzuordnungen und Hinweistexte pflegen.  

#### Aktiv- und Gesperrt-Status  
Diese Felder steuern, ob ein Lieferant im System verwendet werden kann:  
- **Aktiv = ja:** Lieferant ist aktiv und kann in Belegen verwendet werden.  
- **Aktiv = nein:** Lieferant bleibt sichtbar, kann jedoch nicht mehr für neue Vorgänge genutzt werden.  
- **Gesperrt = ja:** Lieferant ist vollständig gesperrt; keine Einkaufsbelege (z. B. Anfragen, Bestellungen, Rechnungen) können erstellt werden.  
- **Gesperrt = nein:** Lieferant ist freigegeben und kann in Einkaufsprozessen genutzt werden.  

#### Kontaktdaten hinzufügen  
1. Klicken Sie auf das **grüne Pluszeichen** – es öffnet sich ein Pop-up-Fenster.  
2. Tragen Sie **E-Mail-Adresse**, **Telefonnummer**, **Website** usw. ein.  
3. Beispiel:  
   - Wählen Sie im Dropdown-Pfeil rechts neben der E-Mail den Typ **WWW** aus.  
   - Geben Sie den Firmenlink ein.  
   - Klicken Sie auf **Speichern**.  

Ein zusätzlicher **Hinweistext** kann hinterlegt werden, der beim Erstellen eines Belegs angezeigt wird.  

---

### 4. Reiter „Ansprechpartner“  
In diesem Reiter erfassen Sie die Kontaktpersonen des Lieferanten.  

1. Klicken Sie auf **Neuen Ansprechpartner anlegen**.  
2. Geben Sie die Kontaktdaten der Person im Pop-up-Fenster ein.  
3. Klicken Sie auf **Speichern**.  
4. Wiederholen Sie den Vorgang bei Bedarf für weitere Ansprechpartner.  

---

### 5. Reiter „Adressen“  
Hier pflegen Sie die Adressinformationen des Lieferanten.  

- **Hauptadresse bearbeiten:** Klicken Sie auf das **Stiftsymbol**, ändern Sie die Daten und speichern Sie.  
- **Weitere Adressen hinzufügen:** Klicken Sie auf **Neue Adresse anlegen** (grünes Pluszeichen) und geben Sie die zusätzlichen Informationen ein – z. B. eine separate Lieferadresse.  

---

### 6. Reiter „Bankverbindungen“  
Im Reiter **Bankverbindungen** hinterlegen Sie die Bankdaten des Lieferanten.  

1. Klicken Sie auf **Neue Bankverbindung anlegen**.  
2. Geben Sie die **IBAN** und den **Kontotyp** ein.  
3. Klicken Sie auf **Weiter** – das System ergänzt automatisch die Bankdaten.  
4. Prüfen Sie die Angaben und klicken Sie auf **Speichern**.  

Das angelegte Konto erscheint anschließend in der Übersicht.  

---

### 7. Reiter „Finanzen“  
Hier werden alle buchungsrelevanten Daten gepflegt, die für die spätere Rechnungsverbuchung notwendig sind:  
- **Kreditorenkonto**  
- **Zahlungsart**  
- **Zahlungsziel**  
- **Handelsregisternummer (HR-Nr.)**  
- **Steuernummer**  

**Hinweis:**  
Die Felder **Zahlungsart** und **Zahlungsziel** können über **Admin Properties** definiert werden.  
Ebenso lassen sich Sicherheitsstufen und Zugriffsrechte in den Properties festlegen.  

---

### 8. Reiter „Objektzuordnungen“  
In diesem Reiter ordnen Sie Lieferanten bestimmten Objekten zu – beispielsweise Standorten, Anlagen oder Lagern.  

1. Klicken Sie auf **Neue Zuordnung zuordnen**.  
2. Geben Sie den Objektnamen im Suchfeld ein und wählen Sie das gewünschte Objekt aus.  
3. Legen Sie den Zeitraum (**von/bis**) fest.  
4. Klicken Sie auf **Speichern**.  

---

### 9. Reiter „Verträge“  
Dieser Reiter dient der Verwaltung von Lieferantenverträgen.  

1. Klicken Sie auf **Neuen Vertrag anlegen**.  
2. Geben Sie **Abrechnungszeitraum von/bis**, **Referenz-Nr.** und ggf. ein **Referenzzeichen** ein.  
3. Speichern Sie den Vertrag.  

---

### 10. Reiter „Artikelzuordnungen“  
Hier können Sie Ansprechpartner auf Artikelebene hinterlegen.  

1. Klicken Sie auf **Neue Zuordnung anlegen**.  
2. Wählen Sie den betreffenden **Artikel**, den zuständigen **Ansprechpartner** und die gewünschte **Art der Zuordnung** (z. B. QS, Einkauf, Logistik).  
3. Geben Sie das **Gültig-von-Datum** ein und speichern Sie.  

---

### 11. Reiter „Projekte“  
Im Reiter **Projekte** ordnen Sie Lieferanten bestimmten Projekten zu.  

1. Klicken Sie auf **Neues Projekt anlegen**.  
2. Erfassen Sie **Projektnummer**, **Bezeichnung**, **Zeitraum**, ggf. **externe Projektnummer** und **Kommentar**.  
3. Klicken Sie auf **Speichern**.  

---

### 12. Reiter „Preiskonditionen“  
In diesem Reiter pflegen Sie Lieferantenpreise auf Artikelebene.  

1. Klicken Sie auf **Neuen Preis festlegen**.  
2. Geben Sie die Artikel- und Preisinformationen ein.  
3. Klicken Sie auf **Speichern**.  
4. Verwenden Sie die Kopierfunktionen, um Preise auf weitere Mengenstaffeln zu übertragen.  

---

### 13. Reiter „Externe Artikelnummern“  
1. Klicken Sie auf **Neue Externe Nummer hinzufügen**.  
2. Geben Sie **Artikelnummer**, **externe Artikelnummer** und ggf. eine **Beschreibung** ein.  
3. Klicken Sie auf **Speichern**.  

**Hinweis:**  
Pro Artikel kann nur eine externe Nummer gepflegt werden. Wird eine zweite eingegeben, erscheint eine Fehlermeldung.  

---

### 14. Reiter „Statistik (Einkauf)“  
Dieser Reiter zeigt eine eingeschränkte SRM-Statistik für den ausgewählten Lieferanten.  
Die Belege können nach verschiedenen Dimensionen analysiert werden:  
- Branche  
- Artikelgruppe  
- Kostenstelle  
- Vertriebsgebiet  
- Auftragsart  
- Produktgruppe  

Ein Klick auf eine Dimension öffnet die zugehörigen Belegdaten.  

---

### 15. Reiter „Zusatzinformationen“  
Im Reiter **Zusatzinformationen** können individuelle Parameter gepflegt werden.  

1. Wählen Sie in der linken Parameterliste die gewünschten Felder aus.  
2. Klicken Sie auf **Ausgewählte Parameter zuordnen**.  
3. Tragen Sie die benötigten Informationen ein – diese werden automatisch gespeichert.  

---

### 16. Reiter „Lieferantenbewertung“  
Klicken Sie auf **Abfrage starten**, um die Bewertung des Lieferanten anzuzeigen.  
In der Onlinehilfe finden Sie detaillierte Erläuterungen zur Berechnungsgrundlage der Bewertung (z. B. Liefertermine, Kennzahlen).  

---

### 17. Reiter „Creditreform“  
Falls Ihr Unternehmen Mitglied bei **Creditreform** ist, können Sie die Zugangsdaten in **ADMIN → FiBu** hinterlegen.  
Im Reiter **Creditreform** können Sie anschließend über **Auskunft abrufen** die Bonitätsdaten einsehen.  

---

### 18. Reiter „Historie“  
Im Reiter **Historie** werden Änderungen – z. B. Anpassungen des Zahlungsziels – automatisch dokumentiert.  
Hier sehen Sie jederzeit, wann und von wem eine Änderung vorgenommen wurde.  

---

## Zusammenfassung  
Die Lieferantenstammdaten sind ein zentraler Bestandteil des Einkaufsmoduls.  
Durch eine konsequente Pflege dieser Daten sichern Sie die Qualität Ihrer Einkaufsprozesse und schaffen Transparenz über alle relevanten Lieferanteninformationen.  

Denken Sie daran: Eine saubere Stammdatenpflege spart Zeit, reduziert Rückfragen und ermöglicht eine präzise Auswertung.  
Dieses Handbuch begleitet Sie dabei als zuverlässige Unterstützung im Arbeitsalltag.  
