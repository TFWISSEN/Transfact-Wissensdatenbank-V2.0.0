# Textbausteinvorlagen
[⬅ Zurück zur Übersicht](../index.md)
## Einleitung  

Dieses Kapitel beschreibt, wie Sie im Modul **Textbausteinvorlagen** standardisierte Textbausteine zentral verwalten und gezielt in Belege einfügen können.  
Die Funktion unterstützt Sie dabei, wiederkehrende Texte – etwa für **Rechnungen**, **Angebote** oder **Auftragsbestätigungen** – systematisch zu pflegen.  
So bleiben Ihre Belege einheitlich formuliert und die Pflegeaufwände reduzieren sich deutlich.  

Ein häufiger Anwendungsfall ist das automatische Einfügen von Zahlungsbedingungen oder kundenbezogenen Hinweisen.  
Dadurch gewinnen Sie Konsistenz und vermeiden Tippfehler oder Abweichungen zwischen verschiedenen Belegen.  

---

## Schritt-für-Schritt-Anleitung  

### 1. Aufrufen des Moduls  

Navigieren Sie zu **Admin > Textbausteinvorlagen**.  
Das Fenster gliedert sich in zwei Hauptbereiche: **Filter** (oben) und **Vorlagenübersicht** (unten).  

---

### 2. Filterbereich verwenden  

Im oberen Bereich können Sie bestehende Textbausteine gezielt filtern.  
Verfügbare Filteroptionen sind:  

- **Textbausteintyp** (z. B. *Beleg nachfolgend*)  
- **Belegtyp** (z. B. *VK-Rechnung*, *EK-Rechnung*)  
- **Zahlungsziel**, **Sprache**, **Auftragstyp**, **Kunde/Lieferant**  

Klicken Sie auf **„Abfrage starten“**, um die passenden Vorlagen anzuzeigen.  
Diese Filter erleichtern es, für jedes Dokument den korrekten Textbaustein zu finden.  

---

### 3. Vorlagenübersicht lesen  

In der unteren Tabellenansicht werden alle vorhandenen Vorlagen angezeigt.  
Jede Zeile steht für eine Textbausteinvorlage mit den folgenden Feldern:

| Feld | Beschreibung |
|------|---------------|
| **Modul / Belegtyp** | Gibt an, in welchem Bereich der Textbaustein gilt (z. B. „VK“ für CRM, „EK“ für SRM). |
| **Name** | Interner Name der Vorlage. |
| **Zahlungsziel** | Beispiel: „30 Tage – Skonto 7 Tage 3 %“. |
| **Inhalt** | Der eigentliche Text, der Platzhalter enthalten kann. |
| **Textbausteintyp** | Position des Textes im Beleg (z. B. *Beleg nachfolgend*). |

Beim Erstellen eines Belegs prüft das System automatisch, welche Vorlage zutrifft, und fügt sie direkt ein.  

---

### 4. Neue Textbausteinvorlage anlegen  

1. Klicken Sie auf das **grüne Plus-Symbol**, um eine neue Vorlage zu erstellen.  
2. Wählen Sie den passenden **Textbausteintyp**, z. B. *Beleg nachfolgend*, wenn der Text am Ende des Dokuments erscheinen soll.  
3. Geben Sie im Feld **Name** eine interne Bezeichnung ein, z. B. *Angebot Standard*.  
4. Wählen Sie mindestens einen **Belegtyp** (z. B. *Angebot*). Optional können Sie zusätzliche Filter wie **Sprache**, **Kunde** oder **MwSt.-Gruppe** setzen.  
5. Tragen Sie im Feld **Inhalt** den gewünschten Text ein. Sie können Platzhalter wie folgende verwenden:  
```
Dieses Angebot ist gültig bis zum {FAELLIGKEITSDATUM}.  
Mit freundlichen Grüßen  
{BELEGERSTELLER}
```

6. Zusätzliche Optionen:  
- **Textbaustein im Beleg editierbar** → erlaubt spätere Änderungen direkt im Dokument.  
- **Standardvorlage / automatisch in den Beleg laden** → sorgt für automatisches Einfügen beim Belegerstellen.  
7. Klicken Sie auf **„Speichern“**, um die Vorlage dauerhaft zu sichern.  

---

### 5. Best Practice: Angebot-Vorlagen nach Kundengruppe steuern  

Diese Funktion erlaubt, dass das System automatisch unterschiedliche Textbausteine je nach Kundengruppe auswählt.  

**Anwendungsfall:**  
Für Angebote sollen verschiedene Vorlagen abhängig von der Kundengruppe geladen werden.  

| Vorlage | Gilt für | Einstellung |
|----------|-----------|-------------|
| **1** | alle Kunden außer A, B, C | Feld *Kunde/Lieferant*: A, B, C → **Filter invertieren aktivieren** |
| **2** | Kunden A und B | Feld *Kunde/Lieferant*: A, B → **Filter invertieren deaktivieren** |
| **3** | Kunde C | Feld *Kunde/Lieferant*: C → **Filter invertieren deaktivieren** |

**Ergebnis:**  
- Vorlage 1 gilt für alle Kunden außer A, B, C.  
- Vorlage 2 gilt nur für A und B.  
- Vorlage 3 gilt nur für C.  

**Hinweis:**  
Die Option **Filter invertieren** kehrt die Bedingung um:  
- **Nicht aktiviert** → gilt nur für die angegebenen Kunden.  
- **Aktiviert** → gilt für alle Kunden außer den genannten.  

---

## Zusammenfassung  

Mit dem Modul **Textbausteinvorlagen** gestalten Sie Ihre Belege effizient und einheitlich.  
Durch Filter und Platzhalter lassen sich kundenspezifische Textvarianten automatisch einfügen, wodurch Kommunikationsfehler vermieden und Prozesse beschleunigt werden.  

So schaffen Sie klare, konsistente Dokumente – und behalten dennoch die volle Flexibilität, individuelle Inhalte gezielt zu steuern.  
