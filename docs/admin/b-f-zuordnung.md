# Benutzer/Fertigungsbereichs-Zuordnung
[⬅ Zurück zur Übersicht](../index.md)
## Einleitung
Dieses Kapitel zeigt Ihnen, wie Sie **Benutzern Fertigungsbereiche zuordnen** und deren Zugriffsrechte verwalten.  
Damit steuern Sie gezielt, wer in welchen Produktionsabschnitten arbeiten oder Daten einsehen darf.  

Die Funktion dient nicht nur der Berechtigungssteuerung, sondern auch der **Sicherstellung eines klar abgegrenzten Verantwortungsbereichs** innerhalb des Systems.  

**Voraussetzungen:**  
- Benutzerverwaltung aktiv (Kapitel _Admin > Benutzerverwaltung_)  
- Fertigungsbereiche gepflegt (Kapitel _Admin > Properties > Fertigungsbereiche_)

---

## Schritt-für-Schritt-Anleitung

### 1. Zugriff aufrufen
Navigieren Sie zu **Admin > Benutzer Fertigungsbereichs-Zuordnung**.  

---

### 2. Benutzer- und Bereichsauswahl
Im **Parameterbereich** stehen Ihnen folgende Filter zur Verfügung:

- **Benutzer:** Auswahl einzelner Benutzer oder Teams  
  (Standard: *aktive Benutzer* – optional *inaktive* oder *alle* Benutzer).  
- **Team:** Eingrenzung auf Abteilungen oder Teams (Standard: *alle Abteilungen*).  
- **Fertigungsbereich:** Auswahl einer Fertigungsbereichsgruppe (Standard: *aktive Fertigungsbereiche*).  
- **Editieren:** Aktivieren, um Berechtigungen bearbeiten zu können.

---

### 3. Zuordnung bearbeiten
Aktivieren Sie das **Kontrollkästchen „Editieren“** und klicken Sie anschließend auf **„Abfrage starten“**.  
Das System zeigt eine **Matrix**, in der Benutzer den jeweiligen Fertigungsbereichen zugeordnet sind.
In der **Matrix** werden alle Benutzer und deren Berechtigungen pro Fertigungsbereich angezeigt.

- Jede **Zeile** steht für einen Benutzer.  
- Jede **Spalte** steht für einen Fertigungsbereich.  
- Durch Aktivieren oder Deaktivieren der Kontrollkästchen gewähren oder entziehen Sie Zugriffsrechte.

---

### 4. Typische Arbeitsschritte
1. Aktivieren Sie das **Kontrollkästchen „Editieren“**.  
2. Klicken Sie auf **„Abfrage starten“**, um die Matrix anzuzeigen.  
3. Wählen Sie das **Kontrollkästchen** eines Fertigungsbereichs, um Zugriff zu gewähren.  
4. Entfernen Sie das Kontrollkästchen, um die Berechtigung zu entziehen.

---

### 5. Beispiel
- **Transfact, Admin** (admin@dokumentation) → Zugriff auf *alle* Fertigungsbereiche  
- **Mustermann, Max** (Max Mustermann) → Zugriff auf *einige ausgewählte* Fertigungsbereiche  
![[025 Kopie von 020 und weitere Entwicklung/9000 ADMIN/0030 F1/attachments/9.2 Benutzer Fertigungsbereichs-Zuordnung S0030 F1.png]]
So behalten Sie einen klaren Überblick über die Zuständigkeiten jedes Benutzers und sichern die Systemstruktur gegen ungewollte Eingriffe.

---

### 6. Massenbearbeitung von Zuordnungen

#### a) Alle Fertigungsbereiche für einen Benutzer freischalten / entziehen
Klicken Sie im Benutzerbereich das Kontrollkästchen in der Spalte  
**„Alle Berechtigungen für den Fertigungsbereich öffnen“**.  
→ Damit werden alle Fertigungsbereiche für diesen Benutzer freigeschaltet.  
Ein erneutes Anklicken entzieht sämtliche Zuordnungen.

---

#### b) Einen Fertigungsbereich für alle Benutzer freischalten / entziehen
In der Kopfzeile der jeweiligen Spalte können Sie den gesamten Fertigungsbereich aktivieren oder deaktivieren.  
→ Damit erhalten bzw. verlieren alle Benutzer gleichzeitig Zugriff auf diesen Bereich.

---

#### c) Zuordnungen von einem Benutzer auf einen anderen übertragen
1. Klicken Sie beim Quellbenutzer auf das **Symbol mit dem überlappenden Rahmen**.  
2. Aktivieren Sie beim Zielbenutzer das Kontrollkästchen.  
3. Klicken Sie beim Quellbenutzer auf das **grüne Plus-Symbol**, um die Zuordnungen zu übertragen.  
4. Bestätigen Sie die Systemmeldung mit **„Erneut senden“**.  
Das System aktualisiert anschließend die Anzeige.

---

## Zusammenfassung
Mit der Funktion **Benutzer/Fertigungsbereichs-Zuordnung** verwalten Sie übersichtlich,  
welche Benutzer Zugriff auf welche Produktionsbereiche besitzen.  
So bleibt Ihr System konsistent, sicher und transparent in seiner Berechtigungsstruktur.

