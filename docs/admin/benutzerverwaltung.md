# Benutzerverwaltung
[⬅ Zurück zur Übersicht](../index.md)
## Einleitung
Die **Benutzerverwaltung** ist die zentrale Stelle, an der alle Zugriffsrechte und Mitarbeiterdaten des Transfact-Systems zusammenlaufen.  
Hier bestimmen Sie, **wer** das System nutzen darf, **welche Aufgabenbereiche** sichtbar sind und **unter welchen Rahmenbedingungen** gearbeitet wird.  
Dieses Kapitel vermittelt das Grundverständnis für Aufbau und Zweck dieser Funktion – von der Benutzeranlage bis zur Einbindung in das Zeit- und Projektmanagement.  

Voraussetzung:  
Sie verfügen über Administratorrechte im Modul **ADMIN** und haben Zugriff auf **Benutzerverwaltung** im Hauptmenü.

---

## Schritt-für-Schritt-Anleitung

### 1. Neuen Benutzer anlegen
1. Öffnen Sie **Admin → Benutzerverwaltung**.  
2. Klicken Sie auf das **grüne Plus-Symbol**, um einen neuen Benutzer anzulegen.  
3. Geben Sie die Pflichtfelder ein:  
   - **Name**  
   - **Vorname**  
   - **Benutzername**  
   - **Kürzel**  
   - **Passwort**  
   > *(Weitere Felder wie Ausweis-Nr. oder Kreditoren-Nr. können später ergänzt werden.)*  
4. Klicken Sie auf **Speichern**.  
   → Nach erfolgreicher Speicherung erscheint die Meldung **„Aktion erfolgreich“**, und die Detailansicht öffnet sich automatisch.

---

### 2. Berechtigungen zuweisen
Ein neu angelegter Benutzer besitzt zunächst keine Rechte.  
Wenn Sie Rechte eines bestehenden Benutzers übernehmen möchten:

1. Klicken Sie beim betreffenden Benutzer auf das Symbol mit den **zwei überlappenden Rechtecken**.  
2. Aktivieren Sie das **Kontrollkästchen** in der Spalte **Auswahl** beim neuen Benutzer.  
3. Wählen Sie:  
   - **„Rechte der ausgewählten Benutzer werden ersetzt“** → Vorhandene Rechte werden überschrieben.  
   - **„Rechte der ausgewählten Benutzer werden ergänzt“** → Bestehende Rechte bleiben bestehen und werden erweitert.

---

### 3. Projektberechtigungen prüfen und pflegen
Mit Projektberechtigungen steuern Sie, an welchen Projekten ein Benutzer im **PZE-Modul** teilnehmen darf.

1. Klicken Sie in der Spalte **Aktion** auf das Symbol **grüner Benutzer mit Haken**.  
   → Die Übersicht **Projektberechtigungen [Benutzername]** öffnet sich.  
2. Dort können Sie:  
   - Projektberechtigungen bearbeiten oder löschen,  
   - über **+ Projektberechtigung anlegen** neue hinzufügen,  
   - oder mit **+ Projektberechtigungen für alle allgemeinen Projekte setzen** Standardprojekte (z. B. *Urlaub*, *Krankheit*, *Reisezeit*) aktivieren.  

> 💡 **Hinweis:**  
> Änderungen in ADMIN und **PZE → Projekte → Detailansicht** sind systemweit synchronisiert.

---

### 4. Arbeitsverträge hinterlegen
Arbeitsverträge bilden die Grundlage für Zeiterfassung und Auswertungen.

1. Klicken Sie in der Spalte **Aktion** auf das Symbol **blauer Stift auf weißem Dokument**.  
   → Die Seite **Arbeitsverträge [Benutzername]** öffnet sich.  
2. Wählen Sie **+ Arbeitsvertrag anlegen** und geben Sie ein:  
   - **Gültigkeit von / bis** *(Pflichtfeld)*  
   - **Standort**  
   - **Arbeitstage pro Woche / Wochenstunden / Jahresurlaub**  
   - **Pausenzeiten** (z. B. 30 Minuten nach 6 h gemäß § 4 ArbZG)  
   - Optional: **Stempelzeit bei Nachtschicht**, **Einschränkungen der Stempelzeiten**, **Automatisches Ausstempeln nach**  
3. Speichern Sie den Vertrag.  

> ⚠️ **Fehlerhinweis:**  
> Überschneidende Zeiträume erzeugen die Meldung  
> **„Mindestens ein Arbeitsvertrag überschneidet sich mit einem vorhandenen Arbeitsvertrag.“**  
> Bitte passen Sie die Gültigkeiten an.  

> 💡 **Tipp:**  
> Die Vertragsdaten fließen automatisch in **PZE → Stundenübersicht / Stempelzeiten** ein.

---

### 5. Ressource-Qualifikationen verwalten
Hier bestimmen Sie, für welche Ressourcen ein Benutzer berechtigt ist.

1. Klicken Sie in der Benutzerliste auf das Symbol **mit dem grünen Lupenzeichen (Ressource)**.  
2. In der Übersicht **Ressource-Qualifikationen** wählen Sie die freizuschaltenden Ressourcen.  
3. Diese Zuweisung ist erforderlich, wenn in **Admin → Properties → Ressourcen** eine der folgenden Optionen aktiviert ist:  
   - **Beim Anmelden von Arbeitsschritten**  
   - **Beim Anmelden von Arbeitsschritten und beim Aufrufen der Abarbeitungsliste**  
4. Nur Benutzer mit entsprechender Qualifikation sehen diese Ressourcen in der **Fertigungsübersicht** und können sich an Arbeitsschritten anmelden.

---

## Zusammenfassung
Die **Benutzerverwaltung** verbindet Stammdaten, Rechte und Zeitmodelle zu einer konsistenten Struktur.  
Durch die korrekte Pflege dieser Daten bleibt Ihr System klar gegliedert, die Zuständigkeiten transparent und alle Module arbeiten synchron.  
So entsteht ein verlässlicher Rahmen, in dem Benutzer, Projekte und Ressourcen harmonisch zusammenspielen.

