# Fertigungsübersicht              [⬅ Zurück zur Übersicht](../index.md)
### 📊 Modulübersicht

Die **Fertigungsübersicht** im Transfact PPS-Modul bietet eine zentrale Echtzeitansicht aller Fertigungsbereiche (Produktionsbereiche) und deren Ressourcen (Arbeitsplätze). Sie dient der Visualisierung des Fertigungsfortschritts, der Aufgabenverteilung sowie der Ressourcenverfügbarkeit und Priorisierung.

Zugriffspfad: **PPS > Fertigungsübersicht**

## 🔍 Feldbeschreibung

Jeder Fertigungsbereich (FB) enthält mehrere Ressourcen (Arbeitsplätze). Jede Ressource zeigt folgendes Format: L: x / P: y / z h

| Feld | Bedeutung                                                                          |
| ---- | ---------------------------------------------------------------------------------- |
| `L`  | Anzahl der aktuell auf dieser Ressource **zu bearbeitenden Fertigungslosen (Los)** |
| `P`  | Anzahl der **priorisierten Lose** unter den offenen Losen                          |
| `h`  | Geplante Gesamtbearbeitungszeit dieser Lose auf der Ressource (in Stunden)         |

**Beispiel:** L: 4 / P: 2 / 1h → 4 offene Lose auf dieser Ressource, davon 2 mit hoher Priorität, geplante Bearbeitungszeit 1 Stunde.

---

## 🚪 Navigationspfade


### ▶ 1. Anzeige der Abarbeitungsliste eines Fertigungsbereichs

Durch Klicken auf den **Namen eines Fertigungsbereichs** (z. B. `TF15-01 Montage`) 
![](pps_fb_001.png.png)
gelangt man zur **Abarbeitungsliste** dieses Bereichs:
![](pps_fb_002.png)
- Anzeige aller Los-Aufträge in diesem Bereich;
    
- Filtermöglichkeiten nach Losnummer, FA-Nummer, Artikel, Projekt usw.;
    
- Tabellarische Darstellung aller Auftragsdaten wie Schritt, Status, Anweisung etc.
    

### ▶ 2. Anzeige der Abarbeitungsliste einer Ressource

Durch Klicken auf eine bestimmte **Ressourcennummer** (z. B. `1WP1`) 
![](pps_fb_003.png)gelangt man zur **Abarbeitungsliste dieser Ressourcen (Arbeitsplatz)**;
![](pps_fb_004.png)
- Anzeige aller Lose, die dieser Ressource zugeordnet sind.

### ▶ 3. Detailansicht eines einzelnen Loses

Ist ein Los aktuell auf einer Ressource angemeldet (Bearbeitung aktiv), wird es in der Liste **fett markiert**.
![](pps_fb_005.png)Durch Klicken auf die **Losnummer** (z. B. 460341) öffnet sich die:
![](pps_fb_006.png)
- **Detailansicht des Fertigungsloses** mit:
    
    - Grunddaten (Artikel, Auftrag, Kunde, Projekt);
        
    - Bearbeitungsstatus, Verzugstage;
        
    - Arbeitsschritte, Ressourcenzuweisung, Qualitätsstatus usw.
        

---

## 🛠 Verwaltung des Ressourcenstatus

Durch Klicken auf das **Zahnrad-Symbol** neben einer Ressource öffnet sich die:
![](pps_fb_007.png)
 **Ressourcen-Status-Seite**;
![](pps_fb_008.png)
- Möglichkeit, den Status zu ändern (z. B. `Reparatur`);
    
- Eingabe von voraussichtlicher Dauer und Bemerkung;
    
- Nach Klick auf **Speichern** wird der neue Status (z. B. rot markiert) in der Fertigungsübersicht angezeigt.

![](pps_fb_009.png)
## 🛠️ Layoutanpassung der Fertigungsübersicht

### Zugang: Button **Fertigungsübersicht verändern** (oben rechts)
![](pps_fb_010.png)
Im Bearbeitungsmodus:
![](pps_fb_011.png)
- Auswahl der Spaltenanzahl: `1-spaltig` bis `8-spaltig`
    Spaltenanzahl: Bildschirmabhängige Empfehlung
    **3–4 Spalten** für schmale Bildschirme (z. B. Laptops)
    **6–8 Spalten** für breite Bildschirme (z. B. große Monitore)
    
- Jeder FB zeigt 3 Symbole:
    
    - ⬆️ nach oben verschieben
        
    - ⬇️ nach unten verschieben
        
    - ☑️ sichtbar / unsichtbar schalten
        

### Sichtbarkeit

- Wird der Sichtbarkeits-Haken deaktiviert, verschwindet der FB aus der Ansicht
    
- Reaktivierung durch erneutes Anhaken

### Sortierung

- Per ⬆️ / ⬇️ Symbole die Reihenfolge der Bereiche anpassen

![](pps_fb_012.png)
- **Wichtig**: Anschließend **Fertigungsübersicht anzeigen** klicken, um neue Anordnung zu übernehmen
## 🔄 Zusammenfassung der Schritte

```
Fertigungsübersicht
│
├─▶ Fertigungsbereich klicken → Abarbeitungsliste des FBs
│
├─▶ Ressource klicken → Abarbeitungsliste der Ressource
│
├─▶ Los klicken → Losdetailansicht
│
├─▶ Zahnrad klicken → Ressourcenstatus setzen (z. B. Reparatur)
│
└─▶ "Fertigungsübersicht verändern" klicken
    ├─▶ Spaltenanzahl, Reihenfolge und Sichtbarkeit anpassen
    └─▶ "Fertigungsübersicht anzeigen" klicken zur Übernahme
```

---

Diese Anleitung unterstützt Sie bei der effektiven Nutzung der Fertigungsübersicht zur Produktionsplanung, Ressourcensteuerung und Auftragsverfolgung im Transfact PPS-System.