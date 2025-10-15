## Use Case 1: Preisvorhersage für Mietwohnungen im Kanton Zürich

**Ziel:**  
Ein Modell soll Mietpreise in Zürich anhand von Lage, Fläche und Ausstattung vorhersagen.

**Datenquellen:**  
- **ImmoScout24 (https://www.immoscout24.ch)**  
  - Variablen: Anzahl Zimmer, Wohnfläche (m²), Mietpreis (CHF), Adresse, Beschreibung.  
  - Erhebung: Web Scraping.  
- **BFS Regionalporträts 2021 (https://www.bfs.admin.ch)**  
  - Variablen: Einkommen, Steuerbelastung, Arbeitslosenquote, Einwohnerzahl, Bevölkerungsdichte.

---

## Use Case 2: Angebot und Nachfrage für Supermärkte in Schweizer Gemeinden

**Ziel:**  
Analyse der Supermarktversorgung in Schweizer Gemeinden (Angebot vs. Nachfrage).

**Datenquellen:**  
- **OpenStreetMap (https://wiki.openstreetmap.org/wiki/DE:Key:shop)**  
  - Variablen: Name, Standort (Koordinaten), Adresse, Betreiber.  
  - Erhebung: Web API (Overpass).  
- **BFS Regionalporträts 2021 (https://www.bfs.admin.ch)**  
  - Variablen: Einwohnerzahl, Altersstruktur, Fläche, Einkommen, Urbanisierungsgrad.
