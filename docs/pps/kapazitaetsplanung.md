# Kapazitätsplanung
[⬅ Zurück zur Übersicht](../index.md)
## Einleitung

- **Zweck**  
  Die Funktion **Kapazitätsplanung** dient zur Analyse und Steuerung der Auslastung von Abteilungen, Ressourcen und Arbeitsplätzen.  
  Sie kombiniert eine grafische Übersicht (Kapazitätsdiagramme) mit einer detaillierten Liste von Fertigungsdaten.  

- **Einsatzbereich**  
  Diese Funktion wird im Modul **PPS** genutzt. Sie unterstützt Produktionsplaner:innen und Ressourcenverantwortliche bei der frühzeitigen Erkennung von Engpässen sowie bei der Optimierung von Ressourcenzuweisungen.  

- **Voraussetzungen**  
  - Zugriff auf das Modul **PPS > Kapazitätsplanung**  
  - Berechtigung zum Anzeigen und Bearbeiten von Losen und Arbeitsschritten  
  - Vorhandene Rückmeldungen und Fertigungsdaten im System  

---

## Schritt-für-Schritt-Anleitung

### Einstellungen & Visualisierung (oberer Bereich)
1. Öffnen Sie **PPS > Kapazitätsplanung**.  
2. Wählen Sie die **Filter & Auswahlparameter**:  
   - **Modus** (Wochenbasis oder Tagesbasis)  
   - **Berechnung** (z. B. Abmeldung [Soll], Abmeldung [Prog])  
   - **Zeitraum** (z. B. KW28 bis KW39)  
   - **Fertigungseinheit & Ressourcen** (z. B. Abteilung Montage)  
3. Prüfen Sie die Diagramme:  
   - **Kapazitätsplanung gesamt**: zeigt Rückstand, geplante Auslastung, angelaufene Auslastung und Verfügbarkeit  
   - **Mitarbeiterkapazitätsplanung**: zeigt Verfügbarkeiten und tatsächliche Buchungen auf Mitarbeiterebene  

---

### Detailanalyse & Arbeitsaufträge (unterer Bereich)

#### Ressourcenauswertung pro Woche
1. Prüfen Sie die **Auslastung in Stunden** nach Arbeitsplätzen (z. B. 1WP1, 1WP2).  
2. Achten Sie auf farblich hervorgehobene Engpässe.  
3. Prüfen Sie die **kapazitive Auslastung [%]** zur Erkennung von Über- oder Unterplanung.  
4. Beachten Sie den Wert **Nulldurchgang Rückstand (h)**, der auf nicht abgedeckte Lasten hinweist.  

#### Arbeitsschritte (Losbearbeitung)
1. In der Tabelle sehen Sie die Fertigungslose mit Angaben zu Kunde, Artikel, Losnummer und Beschreibung.  
2. Vergleichen Sie **Soll-Schritt** und **Ist-Schritt**, um Abweichungen zu erkennen.  
3. Prüfen Sie Ressourcenzuweisungen und geplante sowie tatsächliche Abmeldedaten.  

---

### Aufgabenanpassung (Mehrfachbearbeitung von Losen)
1. Markieren Sie mehrere Lose in der Tabelle.  
2. Klicken Sie auf **Ausgewählte Lose bearbeiten**.  
3. Im Bearbeitungsfenster können Sie folgende Felder ändern:  
   - **Priorität** des Loses  
   - **Soll-Ressource** (Arbeitsplatz/Ressource)  
   - **Anmeldedatum** (Startzeitpunkt)  
   - **Neuberechnungsregel** (ab aktuellem Schritt, ab Beginn, ab bestimmtem Datum)  
4. Klicken Sie auf **Neuberechnung starten**, um die Kapazitätsplanung neu zu berechnen.  
5. Prüfen Sie die aktualisierten Auswirkungen im oberen Kapazitätsdiagramm.  

---

## Zusammenfassung

Die Funktion **Kapazitätsplanung** bietet eine umfassende Übersicht über die Auslastung von Ressourcen und Arbeitsplätzen.  
Sie ermöglicht die Analyse von Engpässen, die Anpassung von Losparametern und die direkte Auswirkungskontrolle im Kapazitätsdiagramm.  
Dadurch wird eine effiziente Ressourcenplanung und -steuerung unterstützt.  