# Artikel
[⬅ Zurück zur Übersicht](../index.md)
## Einleitung

### Zweck  
Die Funktion **Artikel** ist das Herzstück des Moduls **PPS**.  
Sie dient nicht nur der Anlage, Pflege, Suche von Artikeln, sondern stellt sicher, dass alle nachgelagerten Prozesse – vom Einkauf über die Fertigung bis zur Buchhaltung – auf konsistenten Stammdaten basieren.  
Mit ihr verwalten Sie sowohl Materialien als auch Dienstleistungen und steuern interne Fertigungsaufträge.  

### Einsatzbereich  
Diese Funktion wird im Modul **PPS** eingesetzt. Sie unterstützt Anwender bei der Arbeit mit Artikelstammdaten, Stücklisten, Arbeitskarten sowie bei der internen Steuerung von Fertigungsaufträgen.  

### Voraussetzungen  
- Zugriff auf das Modul **PPS**  
- Berechtigung zum Anlegen, Bearbeiten von Artikeln   

---

## Schritt-für-Schritt-Anleitung

### Artikel suchen
1. Öffnen Sie im Menü **PPS > Artikel**.  
2. Geben Sie passende **Filterkriterien** ein, um die Suche einzugrenzen.  
3. Wählen Sie das **Ausgabeformat** (HTML oder Excel).  
4. Klicken Sie auf **Abfrage starten**.  

---

### Artikel anlegen
1. Klicken Sie auf das **grüne Pluszeichen**.  
2. Erfassen Sie die wichtigsten Parameter:  
   - **Beschreibung 1** (Pflichtfeld)  
   - **Artikelart** (Pflichtfeld)  
   - **Artikelnummer** (optional: Eingabe möglich, ansonsten wird eine Systemnummer vergeben)  
   - **Zeichnungsnummer** (optional)  
   - Weitere relevante Informationen können je nach Bedarf ergänzt werden.  
3. **Speichern** Sie die Eingaben.  
   - Nach dem Speichern öffnet sich automatisch die **Artikelstammdaten** des neu angelegten Artikels.  
   - Angezeigt wird zunächst die **Übersicht**; weitere Reiter wie **Allgemein** oder **Freigabeobjekte** stehen zur Verfügung.  
   - Wenn Sie eine Artikelnummer eingegeben haben, wird diese angezeigt. Haben Sie keine eingegeben, vergibt das System automatisch eine Nummer.  
4. Achten Sie auf die Felder **Erlöskonto** und **Aufwandskonto** für die Buchhaltung.  

---

### Artikel kopieren
Das Kopieren eines Artikels ermöglicht es, einen bestehenden Artikel inklusive seiner Stammdaten als Vorlage für einen neuen Artikel zu verwenden.  
Der neue Artikel enthält dabei automatisch einen **Referenzartikel**, der auf den Ursprung verweist.  

**Variante 1 – Kopieren aus der Artikelliste**  
1. Klicken Sie in der Artikelliste auf das Symbol **Artikel kopieren** (zwei übereinanderliegende Blätter).  
2. Eine neue Maske öffnet sich. Der kopierte Artikel wird mit einer neuen Artikelnummer angezeigt.  
3. Im Feld **Referenzartikel** ist der ursprüngliche Artikel automatisch eingetragen.  

**Variante 2 – Kopieren aus den Artikelstammdaten**  
1. Öffnen Sie die Stammdaten des gewünschten Artikels.  
2. Klicken Sie oben rechts auf **Artikel kopieren**.  
3. Auch hier wird ein neuer Artikel erzeugt. Im Feld **Referenzartikel** erscheint der ursprüngliche Artikel.  

**Hinweis:**  
- Die neue Artikelnummer wird automatisch vergeben.  
- Der neue Artikel übernimmt grundlegende Stammdaten vom Referenzartikel, kann aber individuell angepasst werden.  

---

### Stückliste hinzufügen
1. Klicken Sie auf das **grüne Pluszeichen**, abhängig vom Kontext:  
   - Im **PPS Artikel**-Hauptfenster (nach **Abfrage starten**) klicken Sie in der Spalte **Stückliste** auf das **grüne Pluszeichen**.  
   - In den **Artikelstammdaten** klicken Sie neben **Aktuelle Stückliste** auf das **grüne Pluszeichen**.  
2. Geben Sie eine **Beschreibung** und weitere Informationen ein.  
3. **Speichern** Sie die Eingaben.  
4. Die neue Stückliste erscheint anschließend in der Artikelseite.  

---

### Arbeitskarte hinzufügen
1. Klicken Sie auf das **grüne Pluszeichen**, abhängig vom Kontext:  
   - Im **PPS Artikel**-Hauptfenster (nach **Abfrage starten**) klicken Sie in der Spalte **Arbeitskarte** auf das **grüne Pluszeichen**.  
   - In den **Artikelstammdaten** klicken Sie neben **Aktuelle Arbeitskarte** auf das **grüne Pluszeichen**.  
2. Geben Sie eine **Beschreibung** und weitere Informationen ein.  
3. **Speichern** Sie die Eingaben.  
4. Die neue Arbeitskarte erscheint anschließend in der Artikelseite.  

---

### Freigabe von Stückliste und Arbeitskarte
1. Suchen Sie den gewünschten Artikel (z. B. **TF-HK-1203**).  
2. Klicken Sie auf den **grünen Haken**, abhängig vom Kontext:  
   - Im **PPS Artikel**-Hauptfenster (nach **Abfrage starten**) klicken Sie in der Spalte **Stückliste** oder **Arbeitskarte** auf den **grünen Haken**.  
   - In den **Artikelstammdaten** wechseln Sie in den Reiter **Freigabeobjekte** und klicken in der entsprechenden Zeile (Stückliste oder Arbeitskarte) auf den **grünen Haken**.  
3. Bestätigen Sie die Freigabe mit **OK**.  
4. Hinweis: Wenn die Arbeitskarte Objekte wie **Checkliste** oder **Prüfplan** enthält, müssen diese zuerst freigegeben werden.  

---

### FA intern einsteuern
1. Öffnen Sie die Funktion **FA intern einsteuern**, abhängig vom Kontext:  
   - Im **PPS Artikel**-Hauptfenster (nach **Abfrage starten**) klicken Sie in der Spalte **Aktion** auf das Symbol mit den **zwei Zahnrädern**.  
   - In den **Artikelstammdaten** klicken Sie im Reiter **Übersicht** auf **Los(e)/FA intern einsteuern** (Symbol mit den **zwei Zahnrädern**).  
2. Erfassen oder prüfen Sie die Angaben.  
3. **Speichern** Sie die Eingaben.  
4. Der Fertigungsauftrag wird intern gesteuert.  

---

## Zusammenfassung
Die Funktion **Artikel** bildet die Basis für verlässliche Stammdaten im gesamten Unternehmen.  
Mit ihr können Artikel neu angelegt oder bestehende kopiert werden.  
Zusätzlich lassen sich Stücklisten und Arbeitskarten hinzufügen, freigeben und Fertigungsaufträge intern steuern.  
So behalten Sie jederzeit den Überblick und vermeiden Fehler in nachgelagerten Prozessen.  