# Abarbeitungsliste
[⬅ Zurück zur Übersicht](../index.md)
## Einleitung

- **Zweck**  
  Die Funktion **Abarbeitungsliste** dient als zentrales Steuerungsinstrument für Produktionsplaner und Werker.  
  Sie ermöglicht die Überwachung, Bearbeitung und Dokumentation aller offenen oder laufenden Fertigungsschritte eines bestimmten Bereichs.  

- **Einsatzbereich**  
  Diese Funktion wird im Modul **PPS > Fertigungsübersicht > Fertigungsbereich oder Ressource** genutzt. Sie unterstützt insbesondere die operative Fertigungssteuerung im Shopfloor.  

- **Voraussetzungen**  
  - Zugriff auf das Modul **PPS > Fertigungsübersicht**  
  - Berechtigung zum Anzeigen und Bearbeiten von Fertigungsaufträgen  
  - Vorhandene Lose mit Fertigungsschritten im System  

---

## Schritt-für-Schritt-Anleitung

### Filter setzen
1. Öffnen Sie **PPS > Fertigungsübersicht > Fertigungsbereich oder Ressource Name**.  
2. Wählen Sie die gewünschten Filter aus, z. B.:  
   - **Losnummer, Kunde, Artikelnummer, Fertigungsbereich**  
   - Anzeige nur für **offene Lose**, nur **in Bearbeitung befindliche Lose** oder **geplante Lose**  
3. Wählen Sie das **Ausgabeformat** (**HTML** oder **XLSX**).  
4. Klicken Sie auf **Abfrage starten**.  

---

### Ergebnisliste (Abarbeitungsliste)

#### Grundlegende Auftragsinformationen
- **Aktion** (Starten/Abmelden eines Schritts)  
- **Los-Nr., Kostenstelle, Auftragsart**  
- **Artikel & Bezeichnung** (z. B. TF-HK-1203 Mini Hubschrauber)  

#### Komponenten- und Kundeninformationen
- **Lagerbestand (Komponenten)** mit Bestand, Bedarf und Reservierungen  
- **Erste Komponente der Stückliste**  
- **Kunde, Objekt, Zeichnung, Lieferadresse**  

#### Status und Prozessfortschritt
- **Losstatus** (z. B. „Angelaufen“)  
- **Aktuelle Schritte** mit ggf. Verzug in Tagen (z. B. 77,9d)  
- **Nachfolgende Schritte** mit geplanter Ressource  

#### Zeit- und Ressourcenplanung
- **Anmeldung / Abmeldung (Soll)** (geplanter Start- und Endzeitpunkt)  
- **Abmeldung Prognose** (prognostizierter Abschlusszeitpunkt)  
- **Verzug in Tagen** (Verspätungstage)  
- **Arbeitsplatz / Geplante Ressource** (Maschine oder Arbeitsplatz)  

#### Technische & operative Informationen
- **Startdatum des Loses, Bereitstellungstermin**  
- **Beschreibung, Zeichnungen, Dateien**  
- **Alternative Ressourcen**  
- **Zeichnungsnummer, Dokumente pro Arbeitsschritt oder Los**  

---

### Übergang zur Operatorscreen
1. In der Spalte **Aktion** finden Sie ein **grünes Dreiecksymbol (nach rechts zeigend)**.  
2. Klicken Sie auf das Symbol, um den **Operatorscreen** zu öffnen.  
3. Dort erfolgt die Bedienung einzelner Fertigungsschritte direkt im Shopfloor.  
4. Weitere Details siehe Kapitel **Operatorscreen**.  

---

## Zusammenfassung

Die Funktion **Abarbeitungsliste** bietet eine zentrale Übersicht über alle laufenden und offenen Fertigungsschritte.  
Sie unterstützt bei der Steuerung von Produktionsprozessen, zeigt Engpässe und Verzögerungen an und ermöglicht den direkten Wechsel in den **Operatorscreen** zur Bearbeitung einzelner Schritte.  
