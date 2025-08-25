# Kunden
[⬅ Zurück zur Übersicht](app://obsidian.md/index.md)
# Funktion: CRM >> Kunden

## 1. Einleitung

Die Funktion **Kunden** dient der Anlage, Suche und Verwaltung von Kundenstammdaten. Diese Stammdaten bilden die Basis für nahezu alle weiteren CRM-Prozesse wie Angebote, Aufträge, Rechnungen sowie für die Integration mit ADMIN (z. B. E-Mail Client) und PPS (z. B. Artikel).  
Voraussetzung: Zugriffsrechte im Modul CRM.  

## 2. Schritt-für-Schritt-Anleitung

1. **Kunden suchen nach Firmennamen**
    Menü: **CRM → Kunden**
    - Stichwort in das Feld _Firmenname_ eingeben.
        
    - System zeigt alle passenden Kunden an.
        
    - Je mehr Zeichen, desto präziser die Treffer.
        
    - Gewünschten Kunden auswählen.
          
2. **Kunden suchen mit anderen Filterkriterien**
    
    - Filter definieren (z. B. Belegdatum).
        
    - Auf „Abfrage starten“ klicken.
        Wenn nur ein Kunde gefunden wird → Kundenstammdaten-Firmenname-Seite öffnet sich direkt.
    - Wenn mehrere Kunden gefunden werden → Ergebnisliste zeigt alle passenden Kunden 
        → gewünschten Kundennamen in der Liste anklicken → Kundenstammdaten-Firmenname-Seite öffnet sich. 
1. **Neuen Kunden anlegen**
    
    - „Kunde anlegen“ klicken → Pop-up öffnet sich.
        
    - Pflichtfelder:
        
        - Kundentyp (Firma oder Person)
            
        - Firmenname (bei Person Vor- und Nachname)
            
    - Optionale Zusatzdaten eingeben.
        
    - „Speichern“ klicken → System erzeugt automatisch eine Kundennummer (z. B. 168888).
        
    - Weiterleitung auf die Kundenstammdaten-Firmenname-Seite mit allen Basisinformationen.
        

## 3. Best Practices

- Suchanfragen möglichst durch Filter eingrenzen, um Ladezeiten zu reduzieren.
    
- Einheitliche Namenskonventionen (z. B. Schreibweise von Firmen) festlegen.
    

## 4. Vorteile

- Schnelle und gezielte Suche nach Kundeninformationen.
    
- Konsistente Datenbasis für alle CRM- und PPS-Funktionen.
    
- Automatische Kundennummer verhindert Dubletten.
    
- Effiziente Weiterverarbeitung in Angeboten, Verträgen und Rechnungen.
    

## 5. Verknüpfte Module

- **CRM:** Ereignisse, Anrufliste, Verkaufsbeleg anlegen
    
- **ADMIN:** E-Mail Client
    
- **PPS:** Artikel
    

## 6. Zusammenfassung

Die Funktion **Kunden** ist die zentrale Basis für das gesamte CRM-Modul. Sie gewährleistet, dass Geschäftspartnerdaten vollständig, konsistent und systemweit verfügbar sind. Besonders nützlich ist diese Funktion beim Aufbau einer sauberen Stammdatenbasis für Vertrieb und Kundenservice.

---

# Funktion: CRM >> Kundenstammdaten

## 1. Einleitung

Die Funktion **Kundenstammdaten** dient der strukturierten Erfassung und Pflege aller relevanten Kundeninformationen. Sie ist Grundlage für Angebote, Verträge, Rechnungen und wird in vielen weiteren Modulen wie PPS (z. B. Artikel), SRM (Lieferantenverknüpfung) oder ADMIN (z. B. E-Mail Client) verwendet.  

## 2. Schritt-für-Schritt-Anleitung
#### Kunden aufrufen

Kunden suchen mit Filtern
   - Menü: **CRM → Kunden → Abfrage starten**
 Alternative Wege:
- Direkt aus einem verknüpften Beleg, Ereignis oder der Anrufliste.
- Über die Globale Suche (Kundennummer oder Name eingeben, Beleg auswählen).

- **Reiter Firmenname**
    
    - Zusammenfassung der wichtigsten Inhalte aus allen Reitern.
        
    - Ermöglicht schnellen Überblick über den Kunden.
        
- **Pflicht-Reiter bei neuem Kunden**
    
    - Allgemein
        
    - Ansprechpartner
        
    - Adressen
        
    - Bankverbindungen
        
    - Finanzen
        
- **Reiter Allgemein**
    
    1. Allgemeine Informationen, Kontaktdaten, Branchen, Hinweistexte erfassen.
        
    2. Status setzen/prüfen:
       Aktiv-Status:  
          **Aktiv** → Kunde für Belege nutzbar
          **Nicht aktiv** → Keine Belege möglich
      Gesperrt-Status setzen:  
         **Gesperrt** (bei aktivem Kunden) → Nur Angebote möglich, keine Aufträge
         **Nicht gesperrt** → Angebote und Aufträge möglich   
        
    3. Kontaktdaten über „+“ hinzufügen (E-Mail, Telefon, Website).
        
    4. Hinweistext pflegen (z. B. „Nur Vorkasse“).
        
- **Reiter Ansprechpartner**
    
    - „Neuen Ansprechpartner anlegen“ → Pop-up → Daten eingeben und speichern.
        
- **Reiter Adressen**
    
    - Hauptadresse mit Stiftsymbol bearbeiten.
        
    - Zusätzliche Adressen durch „+ Neue Adresse anlegen“ hinzufügen (z. B. separate Lieferadresse).
        
- **Reiter Bankverbindungen**
    
    - Bankkonto hinzufügen → System zeigt gespeicherte Daten im Reiter.
        
- **Reiter Finanzen**
    
    - Felder wie Debitorenkonto, Zahlungsart, Zahlungsziel, USt-IdNr., HR-Nr. pflegen.
        
    - Sicherheitsstufen zuordnen.
        (Abhängig von Systemfunktion und Benutzerrechten)
- **Weitere Reiter**
    
    - **Objektzuordnungen**: Kunden Objekten (z. B. Gebäuden) zuordnen.
        
    - **Verträge**: Neuen Vertrag anlegen (Abrechnungszeitraum, Referenz).
        
    - **Artikelzuordnungen**: Ansprechpartner bestimmten Artikeln zuordnen.
        
    - **Projekte**: Projektdaten erfassen.
        
    - **Preiskonditionen**: Artikelpreise hinterlegen.
        
    - **Externe Artikelnummern**: Kundenspezifische Nummern pflegen.
        
    - **Statistik**: Umsatz, Auftragsvolumen, Zahlungen.
        
    - **Zusatzinformationen**: Parameter aus ADMIN → Properties pflegen.
        
    - **Creditreform**: Auskünfte abrufen (falls Zugangsdaten in ADMIN > Einstellungen > FiBu hinterlegt).
        
    - **Historie**: Änderungen am Zahlungsziel oder Status (aktiv/gesperrt) automatisch dokumentiert.
        

## 3. Best Practices

- Bei Neuanlage sofort alle Pflicht-Reiter vollständig ausfüllen.
    
- Hinweistexte nutzen, um Vertriebsprozesse abzusichern (z. B. „Vorkasse erforderlich“).
    
- Verträge und Preiskonditionen regelmäßig prüfen und aktualisieren.
    

## 4. Vorteile

- Vollständige 360°-Sicht auf den Kunden.
    
- Integration mit PPS, SRM und ADMIN sichert durchgängige Prozesse.
    
- Automatische Dublettenprüfung über Kundennummer.
    
- Unterstützung für Preispolitik, Projektmanagement und Vertragsverwaltung.
    

## 5. Verknüpfte Module

- **CRM:** Ereignisse, Verkaufsbelege, Anrufliste
    
- **PPS:** Artikel>Artikelzuordnungen
    
- **FIBU:** Geschäftspartner
    
- **ADMIN:** Properties (Parameter, E-Mail, FiBu)
    

## 6. Zusammenfassung

Die **Kundenstammdaten** sind die Schaltzentrale für alle Kundeninformationen im System. Sie sichern eine konsistente Datenbasis für Vertrieb, Service, Projektmanagement und Finanzprozesse. Besonders wertvoll sind sie für Unternehmen, die Wert auf transparente Kundenhistorie und saubere Vertrags- und Preisdaten legen.


