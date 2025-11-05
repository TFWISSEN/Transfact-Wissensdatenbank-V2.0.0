# CRM Artikelpreise
[⬅ Zurück zur Übersicht](../index.md)
## Einleitung

- **Zweck**  
  Die Funktion **Artikelpreise** dient der Verwaltung und Auswertung von artikelbezogenen Preisvereinbarungen mit Kunden oder Lieferanten.  
  Sie ermöglicht eine gezielte Suche, den Überblick über alle Preisstrukturen und unterstützt Sie bei der Pflege und Analyse von Preisänderungen.

- **Einsatzbereich**  
  Diese Funktion wird im Modul **CRM** eingesetzt. Sie kommt immer dann zum Einsatz, wenn Preislisten gepflegt, Preisdaten geprüft oder Preisentwicklungen nachvollzogen werden sollen.

- **Voraussetzungen**  
  - Zugriff auf das Modul **CRM > Artikelpreise**  
  - Berechtigung zur Anzeige und Pflege von Preisvereinbarungen  
  - Vorhandene Artikel- und Kunden- bzw. Lieferantendaten  

---

## Schritt-für-Schritt-Anleitung

### Preisdatensätze suchen
1. Öffnen Sie **CRM > Artikelpreise**.  
2. Geben Sie im oberen Bereich die gewünschten Suchkriterien ein:  
   - **Preistyp(en)**: z. B. Verkaufspreis oder Preiskondition pro Artikel im Verkauf  
   - **Artikel / Artikel-Freitext**: Artikelnummer oder Suchtext  
   - **Kunde / Lieferant**: Auswahl des Geschäftspartners  
   - **Preis gültig ab / bis**: Zeitraum der Preisgültigkeit  
   - **Status**: Aktiv / Inaktiv / Alle  
   - **Auftragsart / Preisgruppe / Projekt / Kostenstelle**: Weitere Eingrenzungsmöglichkeiten  
3. Klicken Sie auf den grünen Button **„Abfrage starten“**, um die Suche zu starten.  
4. Das System zeigt die gefundenen Preisdatensätze im unteren Tabellenbereich an.

---

### Suchergebnisse verstehen
Die Ergebnisliste enthält sämtliche relevanten Informationen zu Preisvereinbarungen und ist wie folgt strukturiert:

#### 🔹 Stammdaten
- **Artikelnummer**  
- **Artikelbeschreibung** (Beschreibung 1 und 2)  
- **Kunde / Lieferant**  
- **Matchcode** (Schnellsuche)  
- **Artikelart** (z. B. Fertigungsartikel, Rohmaterial)  
- **Produktgruppe**

#### 🔹 Gültigkeitsdaten
- **Gültig von / bis**  
- **Aktivitätsstatus** des Preises

#### 🔹 Preis- und Margeninformationen
- **Preis / Einzelpreis**  
- **Herstellungskosten**  
- **Marge** (absolut und in Prozent)  
- **Rabattierter Preis** (falls vorhanden)  
- **Preisherkunft** (z. B. Verkaufspreis, Preiskondition pro Artikel im Verkauf)

#### 🔹 Einkaufs- und Verkaufsbedingungen
- **Mindestmenge**  
- **Preiseinheit / Basiseinheit** (z. B. Stück)  
- **Auftragsart / Preisgruppe**  
- **Nur Vielfaches erlaubt** (z. B. Verpackungseinheit)

#### 🔹 Zusätzliche Informationen
- **Kommentar**  
- **Projekt / Kostenstelle**  
- **Zeichnungsnummer**  
- **Externe Beschreibung / externe Nummer** (falls gepflegt)

---

### Preisdaten exportieren
1. Klicken Sie im unteren Bereich auf **Exportieren**.  
2. Wählen Sie das gewünschte Format (**HTML** oder **Excel**).  
3. Verwenden Sie die exportierten Daten z. B. zur Kalkulation oder Preisanpassung.  
4. Nach der Bearbeitung können Sie die aktualisierten Preise über den **ERP-Import** wieder ins System einspielen.

**Beispiel:**  
Bei Preiserhöhungen für viele Kunden mit unterschiedlichen Erhöhungssätzen kann die Liste in Excel exportiert, dort angepasst und anschließend gesammelt importiert werden.

---

## Zusammenfassung
Die Funktion **Artikelpreise** im Modul **CRM** bietet eine übersichtliche und effiziente Möglichkeit, Preisvereinbarungen mit Kunden oder Lieferanten zu verwalten.  
Sie erleichtert das Prüfen, Vergleichen und Anpassen von Preisen und sorgt für Transparenz in der Preisgestaltung über alle Artikel hinweg.
