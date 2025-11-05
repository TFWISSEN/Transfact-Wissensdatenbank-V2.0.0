# EK-MRP
[⬅ Zurück zur Übersicht](../index.md)
## Einleitung

Die **EK-MRP-Funktion** (Einkaufsseitige Materialbedarfsplanung) unterstützt Unternehmen dabei, Bedarfe für den Einkauf systematisch zu erkennen und rechtzeitig zu decken.  
Dieses Kapitel zeigt Ihnen, wie Sie mithilfe der MRP-Übersicht den Materialbedarf analysieren, Bedarfsquellen auswerten und daraus Bestellvorschläge oder Anfragen generieren können.

Die Anwendung berücksichtigt dabei Lagerbestände, offene Bestellungen, laufende Produktionslose und Wiederbeschaffungszeiten, um einen aktuellen und verlässlichen Beschaffungsplan zu erzeugen.  
Ziel ist es, Transparenz über das **Was**, **Wann** und **Wie viel** zu schaffen – also, welche Materialien in welcher Menge und zu welchem Zeitpunkt beschafft werden müssen.

---

## Schritt-für-Schritt-Anleitung

### 1. Zugang

Öffnen Sie im Menü **SRM > EK-MRP**.  
Hier sehen Sie eine tabellarische Übersicht aller relevanten Artikel, ihrer Bestände, Reservierungen und Bedarfe.

---

### 2. Bedarfsanalyse

In der Tabelle werden Bedarfe automatisch aus unterschiedlichen Quellen zusammengeführt, zum Beispiel:

- **Auftragsbestätigungen** (direkter Bedarf)
    
- **Mindestbestände** (Sicherheitsreserven)
    
- **Produktionsaufträge** (indirekter Bedarf über Stücklisten)
    
- **Planaufträge oder Prognosen**
    

Das System berücksichtigt außerdem:

- Aktuellen Lagerbestand
    
- Bereits erfasste, aber noch nicht gelieferte Bestellungen
    
- Laufende Produktionslose
    
- Wiederbeschaffungszeiten und optimale Bestellmengen
    

---

### 3. MRP-Tabelle verstehen

Die **EK-MRP-Tabelle** zeigt pro Artikel alle relevanten Planungsinformationen.

|Funktion|Beschreibung|
|---|---|
|Übersicht je Artikel|Lagerbestand, Reservierungen, offene Bestellungen|
|Vorschlagswerte|Empfohlene Bestellmenge und Lieferdatum|
|Lieferantenvorschläge|Standardlieferant und mögliche Alternativen|
|Preisvorgabe|Einheitspreis (automatisch oder manuell)|
|Verbrauchsstatistik|Durchschnittsverbrauch der letzten 6 – 18 Monate|
|Direkte Aktion|Bestellvorschläge können direkt übernommen werden|
Zur Orientierung im Arbeitsalltag helfen Farbcodes, den Status schnell zu erfassen:

|Farbe|Bedeutung|
|---|---|
|🟩 Grün|Alles gedeckt – kein Handlungsbedarf|
|🟨 Gelb|Bestellung unterwegs – Liefertermin noch offen|
|🟥 Rot|Nichts bestellt – akuter Bedarf|

---

### 4. Beispiel

**Material:** 1023

- **Lagerbestand:** 60 kg
    
- **Mindestbestand:** 100 kg
    
- **Offene Bestellungen:** Keine
    
- **Wiederbeschaffungszeit:** 5 Kalendertage (Wochenenden und Feiertage unberücksichtigt)
    
- **Ø Verbrauch (6 Monate):** 1,67 kg / Monat
    

📌 Das System schlägt vor, **heute eine Bestellung über 40 kg** anzulegen, mit geplanter Lieferung in **5 Tagen**.

---

### 5. Bestellung oder Anfrage anlegen

1. **Klicken Sie auf das Häkchen** in der Spalte **„Aktuell“** neben dem gewünschten Material.
    
2. Oben im Bereich erscheint automatisch die **Mengenvorgabe** (z. B. 40 kg).
    
3. Wählen Sie **„Anfrage oder Bestellung aus Auswahl erstellen“**.
    
4. Im Dialogfenster **„Bestellung erstellen“** entscheiden Sie, ob Sie eine **Anfrage** oder **Bestellung** anlegen möchten.
    

Voraussetzung:  
Die Felder **Lieferant** und **Einzelpreis** müssen

- entweder **automatisch aus den Stammdaten** übernommen oder
    
- **manuell** eingetragen werden.
    

Nach dem Speichern wird eine **Belegnummer** erzeugt.  
Ein Klick auf die **Anfrage- oder Bestellnummer** öffnet die Detailansicht des jeweiligen Belegs.

---

### 6. Bedarfsdeckung prüfen

- **Fixierte Bestellungen** gelten als **verbindliche Deckungsmenge** im MRP.
    
- **Anfragen oder nicht fixierte Bestellungen** werden **nicht berücksichtigt**, da sie keine gesicherte Deckung darstellen.
    
- Sobald eine Bestellung fixiert ist, wird der verbleibende Bedarf automatisch neu berechnet und reduziert.
    

Im Bereich **PPS > Nettobedarf** sehen Sie den Lagerbestandsverlauf inklusive geplanter Bestellungen.  
So behalten Sie Engpässe im Blick und können Beschaffung und Lagerführung optimal steuern.

---

## Zusammenfassung

Die Funktion **EK-MRP** unterstützt Sie bei einer klaren, nachvollziehbaren Materialplanung.  
Sie erkennen frühzeitig drohende Engpässe, wandeln Bedarfe mit wenigen Klicks in Bestellungen um und sichern so eine kontinuierliche Versorgung der Produktion.
So bleibt Ihr System konsistent, und Sie behalten jederzeit Überblick über Beschaffung, Termine und Lagerstände.