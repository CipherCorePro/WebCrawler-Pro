# WebCrawler-Pro: Web Scraper mit API & Quellcode | Funktionsreich, Sicher & Frei Nutzbar

## 📌 Beschreibung der Software

🚀 **WebCrawler-Pro: Ihr Web Scraper mit vollem Funktionsumfang – inklusive Quellcode und allen Rechten!**

Sichern Sie sich jetzt WebCrawler-Pro als einmaligen Kauf und optimieren Sie Ihre Datenprozesse dauerhaft! Diese umfassende Web-Scraping-Lösung, inklusive des kompletten und uneingeschränkten Quellcodes, bietet Organisationen die volle Kontrolle und Flexibilität über die Extraktion, Verarbeitung und Integration von Webdaten. Mit dem Erwerb erhalten Sie alle Rechte zur Nutzung, Anpassung und Weiterentwicklung – ohne versteckte Folgekosten oder Lizenzgebühren.

WebCrawler-Pro ist ein sofort einsatzbereites System für automatisiertes Web-Data-Mining, bereitgestellt mit einer **RESTful API** für die nahtlose Integration in Ihre bestehenden Systeme und Workflows. Sie erwerben nicht nur die Software, sondern die volle Verfügungsgewalt darüber.

🎯 **Ideal für Organisationen, die maximale Kontrolle, Datensicherheit und Anpassbarkeit suchen und eine sofort nutzbare Basis für ihre individuellen Web-Scraping-Projekte benötigen!**

## 🔹 Was WebCrawler-Pro auszeichnet (Kernfunktionen & Vorteile)

- **Web-Scraping mit Selenium:** Automatisieren Sie die präzise Extraktion von Textinhalten, relevanten Metadaten und Keywords – auch von dynamischen und interaktiven Webseiten.
- **RESTful API für umfassende Automatisierung:** Steuern Sie sämtliche Scraping-Prozesse programmatisch über die API und rufen Sie extrahierte Daten in Echtzeit ab.
- **Task-Planung & Monitoring über Datenbank (SQLite):** Definieren und verwalten Sie wiederkehrende Scraping-Aufgaben mit Statusüberwachung.
- **Datenbankbasiertes System mit Caching:** Die lokale SQLite-Datenbank ermöglicht effiziente Datenspeicherung und optimierte Performance durch integriertes Caching.

### 🔹 Sicherheitsorientiertes Design mit Fokus auf Kontrolle

- **Primär textorientierte Extraktion mit optionalen HTML/CSS-Daten**
- **Gezielter Scraping-Ansatz für einzelne URLs** (keine automatische Unterlink-Verfolgung)
- **Integrierte Sicherheitsfunktionen:** API-Key-Authentifizierung, Ratenbegrenzung und Selektor-Validierung
- **Streamlit Admin Dashboard:** Verwaltung von geplanten Tasks und Analyse von Logs über eine Web-Oberfläche
- **Vollständiger Quellcode im Lieferumfang** – uneingeschränkte Kontrolle für eigene Weiterentwicklung

## 🔹 Warum WebCrawler-Pro wählen?

✅ **Sofort nutzbare Architektur:** Web-Scraping, API, Datenbankintegration, Task-Planung und Sicherheitsfeatures in einem System.
✅ **Volle Kontrolle & Unabhängigkeit durch Quellcode-Besitz**
✅ **Kosteneffizientes Modell durch einmaligen Kauf** – keine Lizenzgebühren oder Abonnements.
✅ **Design mit Fokus auf Sicherheit & Kontrolle**
✅ **Detaillierte Dokumentation für maximale Eigenständigkeit**

## 💰 Verkaufsmodell & Rechteübertragung

📌 **Preis:** Verhandelbar (VHB) – Kontaktieren Sie uns für ein individuelles Angebot.

📌 **Einmaliger Kauf – Volle Rechteübertragung:**
- **Uneingeschränkte Nutzung** innerhalb des Unternehmens oder der Organisation
- **Anpassung & Modifikation** durch interne Entwickler
- **Kommerzielle Nutzung & Weiterverkauf**
- **Keine Lizenzgebühren** nach dem Kauf

📌 **Wichtiger Hinweis:** Dies ist ein einmaliger Verkauf des Quellcodes als selbst-gehostete Software-Lösung. **Kein Support oder Wartung nach dem Verkauf inklusive.** Eine umfassende Dokumentation zur internen Wartung, Anpassung und Weiterentwicklung wird bereitgestellt.

📩 **Interesse geweckt?**

Kontaktieren Sie uns direkt für weitere Informationen oder eine persönliche Demo!




# 🚀 **WebCrawler-Pro**

## 📌 **Einführung**
WebCrawler-Pro ist ein leistungsstarkes Werkzeug zur **automatischen Extraktion, Verarbeitung und Bereitstellung von Web-Daten** über eine API. Es kombiniert **Web-Scraping, Datenverarbeitung, API-Integration, Sicherheit und Task-Planung** in einem einzigen System. Die geplante Task-Ausführung und das Monitoring erfolgen direkt über die Datenbank.  Zusätzlich bietet WebCrawler-Pro eine **intuitive Web-Oberfläche mit Streamlit**, um geplante Tasks komfortabel zu verwalten.

### 🔹 **Hauptfunktionen**
✅ **Web-Scraping mit Selenium** (automatisiertes Abrufen von Webseiteninhalten)
✅ **Gezielte Datenextraktion mit CSS-Selektoren** (inkl. Typkonvertierung & Datenbereinigung)
✅ **Datenverarbeitung mit benutzerdefinierten Funktionen** (`processing.py`)
✅ **RESTful API zur Bereitstellung der Daten** (mit detaillierten Fehlermeldungen)
✅ **Automatisierte Task-Planung aus der Datenbank** (mit Monitoring & manueller Ausführung über die API)
✅ **API-Authentifizierung per API-Key** 🔑
✅ **Ratenbegrenzung zum Schutz vor Missbrauch** 🛡️
✅ **Caching zur Leistungssteigerung** ⚡
✅ **Datenbankintegration mit SQLite** 🗄️ (mit Transaktionssicherheit)
✅ **Erweiterbare Sicherheitsmaßnahmen gegen Path Traversal & CSS-Injection**
✅ **Monitoring für geplante Tasks und API-Status über API-Endpunkte** 📊 (inkl. Start-/Endzeiten, Logs, Fehlerberichte, letzter/nächster Ausführungszeit)
✅ **Einfache Konfiguration über YAML-Dateien & Umgebungsvariablen** ⚙️
✅ **Web-Oberfläche mit Streamlit zur Taskverwaltung** 🖥️

📖 Diese Dokumentation beschreibt die **Installation, Konfiguration und Nutzung** des Programms.

---

## 🔧 **1. Installation**
### 📂 **1.1 Voraussetzungen**
📌 **Erforderliche Software:**
- 🐍 **Python 3.7 oder höher** *(empfohlen: 3.9+)*
- 📦 **pip** *(Python-Paketmanager, sollte mit Python installiert sein)*
- 🌐 **Google Chrome + ChromeDriver** *(für Selenium-basiertes Scraping)*
- 🧠 **NLTK Data:** *(Für Keyword-Extraktion: `python -m nltk.downloader stopwords`)*
- 🖥️ **Streamlit:** *(Für die Web-Oberfläche: `pip install streamlit`)*

### 📥 **1.2 Abhängigkeiten installieren**
Führe folgenden Befehl aus, um alle benötigten Pakete zu installieren:
```bash
pip install -r requirements.txt
```


---

## ⚙️ **2. Konfiguration**
Das Programm wird über **YAML-Dateien & Umgebungsvariablen** konfiguriert:
- 📄 **`config.yaml`** → Enthält Einstellungen für Scraping, API, Datenbank & Sicherheit.
- 🔑 **`.env` Datei** → Speichert API-Keys & andere sensible Informationen. *(Umgebungsvariablen haben Vorrang vor `config.yaml`.)*  API-Keys können auch direkt in `config.yaml` unter `api_keys` eingetragen werden.

### 🛠 **2.1 `config.yaml` (Beispiel)**
```yaml
scraping:
  user_agent: "Mozilla/5.0 (Windows NT 10.0; Win64; x64)"
  timeout: 10

database:
  type: sqlite
  path: "data/webcrawler.db"

security:
  api_key_required: true
  rate_limit: 100
```

### 🔑 **2.2 `.env` Datei (Beispiel)**
```ini
API_KEY_1=mein_geheimer_api_key_1
API_KEY_2=mein_geheimer_api_key_2
API_KEY_3=mein_geheimer_api_key_3
```

---

## ▶️ **3. Nutzung**
### 🌍 **3.1 API-Modus** *(Startet den API-Server)*
```bash
python app.py --api
```

### 🕵️ **3.2 Kommandozeilenmodus** *(Einzelnes Scraping ausführen)*
```bash
python app.py https://example.com [Optionen]
```

### ⏳ **3.3 Geplanter Modus** *(Automatische Tasks aus der Datenbank ausführen)*
```bash
python app.py
```
📌 **Hinweis:** Geplante Tasks werden aus der Datenbank (`webdata.db`, konfigurierbar in `config.yaml`) geladen und ausgeführt. 
---


## 🛠 **4. Benutzerdefinierte Datenverarbeitung (`processing.py`)**
📌 **Ermöglicht benutzerdefinierte Verarbeitung gescrapter Daten.**

**Beispiel:**
```python
def process_data(data: dict) -> dict:
    """
    Verarbeitet gescrapte Daten. Muss ein Dictionary zurückgeben.
    Falls `None` zurückgegeben wird, erscheint eine Warnung im Log.
    """
    if not isinstance(data, dict):
        return None

    processed_data = {k: v.strip() if isinstance(v, str) else v for k, v in data.items()}
    return processed_data
```

---

## 🔒 **5. Sicherheitshinweise**
📌 **Schutzmechanismen:**
- 🔑 **API-Key-Authentifizierung** *(API-Endpunkte erfordern einen API-Key im Header)*
- 🛡 **Ratenbegrenzung** *(Maximal 100 Anfragen pro Minute, konfigurierbar in `config.yaml`)*
- 🚨 **Path Traversal-Schutz** *(Verhindert unautorisierten Zugriff auf Dateien)*
- 🔍 **CSS-Selektor-Validierung** *(Unsichere Selektoren werden ignoriert & protokolliert)*

**Beispiel für ein Sicherheitslog:**
```sh
2025-03-09 14:43:19,238 - WARNING - Unsicherer CSS-Selektor erkannt: div[onclick*=alert]
```

---

## 📊 **6. Fehlerbehandlung & Logging**
📌 **Wo werden Fehler protokolliert?**
- 🖥 **Konsolenausgabe** *(Standard, für schnelle Fehleranalyse)*
- 🗂 **Log-Datei `logs/webcrawler.log`** *(falls aktiviert)*

**Log-Level:**
- ✅ **INFO** → Allgemeine Statusmeldungen
- ⚠️ **WARNING** → Sicherheitswarnungen
- ❌ **ERROR** → Kritische Fehler


## 📡 7. API-Endpunkte
📌 **Übersicht der wichtigsten API-Endpunkte (aktualisiert):**
- 🌐 `/api/v1/` → API Root mit Übersicht aller Endpunkte
- 📄 `/api/v1/fetch-html` → HTML-Inhalt abrufen (Parameter: `url`, `stopwords`, `css-selectors`, `save_file`, `processing_function_path`)
- 📄 `/api/v1/fetch-text` → Textinhalt abrufen (Parameter: `url`, `stopwords`, `css-selectors`, `save_file`, `processing_function_path`)
- 🔄 `/api/v1/scheduled-tasks` → Aufgabenverwaltung (GET, POST, PUT, DELETE)
- 🔄 `/api/v1/scheduled-tasks/<task_id>` → Einzelne Task verwalten (GET, PUT, DELETE)
- 📊 `/api/v1/scheduled-tasks/status` → Status aller geplanten Tasks
- 📊 `/api/v1/scheduled-tasks/<task_id>/status` → Status eines spezifischen Tasks  (inkl. letzter/nächster Ausführungszeit und Fehlermeldungen)
- 📊 `/api/v1/scheduled-tasks/<task_id>/run` → Manuelles Ausführen eines Tasks
- ✅ `/api/v1/health` → API Health Check


🔐 **Alle API-Endpunkte erfordern API-Authentifizierung!**

---
## **Weboberfläche**

Mit dem Befehl `streamlit run app.py -- --streamlit` starten Sie die Weboberfläche zur bequemen Verwaltung Ihrer Webcrawling-Tasks.  Sie benötigen hierfür einen gültigen API-Key.

**API-Key Eingabe:**

Nach dem Start der Weboberfläche werden Sie aufgefordert, Ihren API-Key einzugeben.  Dieser dient zur Authentifizierung und Autorisierung des Zugriffs auf die Funktionen der Weboberfläche. Geben Sie Ihren API-Key in das dafür vorgesehene Feld ein und bestätigen Sie mit Enter. Ein ungültiger API Key führt zu einer Fehlermeldung.

**Anzeige geplanter Tasks:**

Die Weboberfläche listet alle geplanten Tasks übersichtlich auf. Für jeden Task werden folgende Informationen angezeigt:

* **Task ID:** Eindeutige Identifikationsnummer des Tasks.
* **URL:** Die zu crawlende Webseite.
* **Zeitplan:**  Definiert, wann der Task ausgeführt wird (z.B. stündlich, täglich um 10:00, alle 30 Minuten).
* **Nur Text:**  Gibt an, ob nur der Textinhalt oder der gesamte HTML-Code extrahiert werden soll.
* **Stopwörter:**  Auflistung der Stopwörter, die bei der Keyword-Extraktion ignoriert werden.
* **CSS-Selektoren:**  Die verwendeten CSS-Selektoren zur gezielten Datenextraktion.
* **Datei speichern:**  Gibt an, ob die extrahierten Daten zusätzlich zur Datenbank in einer Datei gespeichert werden sollen.
* **Verarbeitungsfunktion:**  Pfad zur benutzerdefinierten Verarbeitungsfunktion (optional).
* **Status:**  Aktueller Status des Tasks (z.B. `pending`, `running`, `success`, `failure`).
* **Letzte Ausführung:**  Zeitstempel der letzten Ausführung.
* **Nächste Ausführung:**  Zeitstempel der nächsten geplanten Ausführung.
* **Fehlermeldung:**  Anzeige von etwaigen Fehlermeldungen bei der Ausführung des Tasks.


**Aktionen für jeden Task:**

* **Löschen:**  Über den Button "Task [ID] löschen" kann ein geplanter Task entfernt werden.
* **Sofort ausführen:** Mit dem Button "Task [ID] sofort ausführen" kann ein Task unabhängig vom Zeitplan manuell gestartet werden.  Der Status aktualisiert sich nach der Ausführung.

**Hinzufügen eines neuen Tasks:**

Im Bereich "Neuen Task hinzufügen" können Sie neue Crawling-Tasks erstellen.  Füllen Sie die folgenden Felder aus:

* **URL:**  Die URL der zu crawlenden Webseite.
* **Zeitplan:**  Definieren Sie den Ausführungszeitplan des Tasks. Gültige Formate sind: "stündlich", "täglich um HH:MM" oder "alle X minuten".
* **Nur Text extrahieren:** Aktivieren Sie diese Option, um nur den Textinhalt der Webseite zu extrahieren.
* **Stopwörter:**  Geben Sie optional eine kommagetrennte Liste von Stopwörtern ein.
* **CSS-Selektoren:** Fügen Sie optional CSS-Selektoren im JSON-Format hinzu, um bestimmte Daten von der Webseite zu extrahieren.
* **Datei speichern:**  Aktivieren Sie diese Option, um die extrahierten Daten in einer Datei zu speichern.
* **Verarbeitungsfunktion:** Geben Sie optional den Pfad zu einer benutzerdefinierten Verarbeitungsfunktion an.


Nach dem Ausfüllen der Felder klicken Sie auf "Task hinzufügen", um den neuen Task zu speichern und zu planen.  Die Weboberfläche aktualisiert sich automatisch und zeigt den neu hinzugefügten Task an.  Fehler bei der Eingabe werden direkt angezeigt.

```
```bash
streamlit run app.py -- --streamlit
```

![image](https://github.com/user-attachments/assets/d2b6b9aa-ebaa-4450-8870-0096207fb2e1)

---
---
## **Hier sind einige Beispieleingaben für die Streamlit-Weboberfläche deines WebCrawler-Pro**

**Beispiel 1: Einfacher Webseiten-Crawl**

* **URL:** `https://www.example.com`
* **Zeitplan:** `täglich um 10:00`
* **Nur Text extrahieren:** (deaktiviert)
* **Stopwörter:**
* **CSS-Selektoren:**
* **Datei speichern:** (aktiviert)
* **Verarbeitungsfunktion:**


Dieser Task crawlt täglich um 10:00 Uhr die Webseite `https://www.example.com` und speichert den gesamten HTML-Inhalt in einer Datei.  Es werden keine Stopwörter, CSS-Selektoren oder Verarbeitungsfunktionen verwendet.

**Beispiel 2: Text-Extraktion mit Stopwörtern**

* **URL:** `https://www.wikipedia.org`
* **Zeitplan:** `alle 60 minuten`
* **Nur Text extrahieren:** (aktiviert)
* **Stopwörter:** `und, die, der, das, ist`
* **CSS-Selektoren:**
* **Datei speichern:** (aktiviert)
* **Verarbeitungsfunktion:**


Dieser Task extrahiert stündlich den Textinhalt von `https://www.wikipedia.org`. Die angegebenen Stopwörter werden bei der Keyword-Extraktion ignoriert. Der extrahierte Text wird in einer Datei gespeichert.

**Beispiel 3: Datenextraktion mit CSS-Selektoren**

* **URL:** `https://www.amazon.de/`
* **Zeitplan:** `stündlich`
* **Nur Text extrahieren:** (deaktiviert)
* **Stopwörter:**
* **CSS-Selektoren:**
```json
{
  "product_title": "h2.a-size-mini a.a-link-normal span",
  "product_price": "span.a-price span.a-offscreen"
}
```
* **Datei speichern:** (deaktiviert)
* **Verarbeitungsfunktion:** `./PROCESSING_FUNCTIONS_DIR/#1 custom_processing.py`


Dieser Task crawlt stündlich Amazon und extrahiert Produkttitel und -preise mithilfe der angegebenen CSS-Selektoren. Die extrahierten Daten werden mit der angegebenen Verarbeitungsfunktion weiterverarbeitet und in der Datenbank gespeichert. Beachte, dass der Pfad zur Verarbeitungsfunktion relativ zum Ausführungsverzeichnis des Crawlers sein muss.


**Beispiel 4:  Kombination aller Funktionen**

* **URL:** `https://www.heise.de`
* **Zeitplan:** `täglich um 06:00`
* **Nur Text extrahieren:** (aktiviert)
* **Stopwörter:** `mit, von, am, im`
* **CSS-Selektoren:** `{"article_title": "h2 a"}`
* **Datei speichern:** (aktiviert)
* **Verarbeitungsfunktion:** `./PROCESSING_FUNCTIONS_DIR/#2 custom_processing.py` (oder ein anderer gültiger Pfad)


Dieser Task kombiniert alle verfügbaren Funktionen. Er crawlt täglich um 6:00 Uhr heise.de, extrahiert den Textinhalt, filtert die angegebenen Stopwörter, extrahiert Artikeltitel mithilfe des CSS-Selektors, speichert den Textinhalt in einer Datei und verarbeitet die Daten mit der angegebenen Funktion.

**Wichtig:**

* **Gültige Pfade für Verarbeitungsfunktionen:** Achte darauf, dass die Pfade zu den Verarbeitungsfunktionen korrekt und relativ zum Ausführungsverzeichnis des Crawlers angegeben sind.  Die Beispiele oben gehen davon aus, dass sich die `custom_processing.py` Dateien im Verzeichnis `PROCESSING_FUNCTIONS_DIR` befinden.
* **JSON-Format für CSS-Selektoren:** Die CSS-Selektoren müssen in einem gültigen JSON-Format angegeben werden.
* **Testen:** Teste die Eingaben gründlich, um sicherzustellen, dass sie die gewünschten Ergebnisse liefern.
---
## 🏁 **9. WebCrawler-Pro**
✅ **Automatisierte Task-Planung direkt aus der Datenbank**
✅ **Erweiterbare Datenverarbeitung durch `processing.py`**
✅ **Detaillierte Logging- & Sicherheitsmaßnahmen**
✅ **Einfache Konfiguration über `config.yaml` & `.env`**

🚀 **WebCrawler-Pro ist die ideale Lösung für produktives, sicheres und flexibles Web-Scraping!**





# WOFÜR KANN MAN **WebCrawler-Pro** NUTZEN?

## **Einsatzmöglichkeiten für verschiedene Zielgruppen**

### **1️⃣ Unternehmen & Startups**
**📊 Markt- & Wettbewerbsanalyse**  
- Automatische Überwachung der Konkurrenz-Webseiten (Preise, Produkte, Dienstleistungen).  
- Extraktion von **SEO-Daten** (Meta-Descriptions, Keywords, Überschriften) zur Analyse von Mitbewerbern.
- Identifikation neuer Branchentrends durch **regelmäßiges Crawling von Nachrichtenportalen**.

**📢 Marketing & Lead-Generierung**  
- Sammlung von **potenziellen Kundenkontakten** aus öffentlich zugänglichen Quellen (z.B. Firmenverzeichnisse, Social Media, Events).
- Analyse von **Produktbewertungen und Rezensionen** auf Plattformen wie Amazon oder Trustpilot.
- Überwachung von **Markennennungen** in Blogs oder Foren für gezieltes Online-Reputation-Management.

**⚖️ Compliance & Risikomanagement**  
- Automatische Überprüfung von **gesetzlichen Vorgaben auf regulatorischen Webseiten** (z.B. DSGVO-Updates, Änderungen in AGBs von Partnern).
- **Frühwarnsysteme** für negative Presseberichte oder Fake News über das eigene Unternehmen.
- Erkennung von **Plagiaten oder unerlaubter Nutzung eigener Inhalte** durch Web Scraping.

---

### **2️⃣ Vereine & Organisationen**
**📅 Event- & Mitgliederverwaltung**  
- Automatische Aktualisierung von **Veranstaltungslisten** durch das Scrapen von Ticketseiten oder Event-Plattformen.
- **Monitoring von Förderprogrammen** für gemeinnützige Organisationen und Vereine.
- **Automatisierte Newsletter-Erstellung** basierend auf gesammelten Blogposts und News aus der Branche.

**📣 Öffentlichkeitsarbeit & Fundraising**  
- Beobachtung von **sozialen Medien & Nachrichten**, um Trends für Fundraising-Kampagnen zu identifizieren.
- Sammlung von **Statistiken & Berichten**, die für Förderanträge oder Präsentationen genutzt werden können.
- Erkennung von **Fake News über die Organisation** und schnelle Reaktion durch Überwachung relevanter Webseiten.

---

### **3️⃣ Öffentliche Einrichtungen & NGOs**
**📜 Politische & gesellschaftliche Entwicklungen**  
- Kontinuierliche **Analyse von Gesetzestexten und neuen Vorschriften**, um schnell reagieren zu können.
- **Erkennung von Desinformationen & Fake News**, um gezielte Aufklärungskampagnen zu starten.
- **Wissenschaftliche Studien & Berichte** automatisch sammeln und katalogisieren.

**🌍 Umwelt & Nachhaltigkeit**  
- Überwachung von **Wetter- und Klimadaten** durch Scraping offizieller Wetterseiten.
- **Analyse von Umweltschutzmaßnahmen** anderer Länder zur Vergleichsanalyse.
- Sammlung von **offiziellen Berichten zu CO₂-Emissionen** zur Förderung von Nachhaltigkeitsprojekten.

---

### **4️⃣ Privatpersonen & Blogger**
**📜 Nachrichten & Information**  
- Automatische **Zusammenfassung relevanter Nachrichten** aus verschiedenen Quellen.
- **Persönlicher News-Feed**, der individuell zusammengestellte Themenbereiche crawlt.
- **Verwaltung von Buch- oder Filmkritiken** durch automatisches Extrahieren von Rezensionen.

**💰 Finanzielle Vorteile**  
- **Automatische Preisüberwachung & Schnäppchenalarm** für bestimmte Produkte.
- Vergleich von **Krypto- und Aktienkursen** mit historischen Daten.
- Automatische **Immobilienpreis-Analyse** durch Scraping von Wohnungsbörsen.

**📖 Wissen & Lernen**  
- Sammlung von **Wikipedia-Artikeln und wissenschaftlichen Studien** zu bestimmten Themen.
- Automatische Extraktion von **Online-Kursen & Lernmaterialien**.
- Erstellung eines **automatisierten Blog-Kalenders** mit geplanten Beiträgen aus verschiedenen Quellen.

---

## **Ein vielseitiges Werkzeug für viele Anwendungsfälle!**
**WebCrawler-Pro** ist eine leistungsstarke Lösung für Unternehmen, Vereine, Organisationen und Privatpersonen, die gezielt Informationen aus dem Internet extrahieren möchten. Dank der umfangreichen Konfigurationsmöglichkeiten und der sicheren API-Schnittstelle lassen sich zahlreiche Aufgaben **automatisieren und optimieren**. 🚀



# **Softwarebewertung – WebCrawler-Pro**  
**Autor: CipherCore**  
**Datum: März 2025**  
**Version: 1.1**  

---

## **1. Einführung**  
WebCrawler-Pro ist eine leistungsfähige, vielseitige und sichere Anwendung zur **automatischen Extraktion, Verarbeitung und Bereitstellung von Web-Daten** über eine API. Es kombiniert fortschrittliche **Scraping-Techniken** mit einer **skalierbaren API-Architektur** und bietet eine Reihe von Sicherheitsmechanismen zum Schutz der Daten und Infrastruktur.  

Diese Bewertung analysiert die Software hinsichtlich **Funktionalität, Sicherheit, Performance, Skalierbarkeit, Wartbarkeit, Testabdeckung, Benutzerfreundlichkeit und Dokumentation**.

---

## **2. Funktionalität**  
### **2.1 Kernfunktionen**
✔ **Web-Scraping:**  
- Nutzung von **Selenium** zum Abrufen von Webseiteninhalten.  
- Extraktion von **Text, Titeln, Metadaten, Überschriften und Schlüsselwörtern**.  
- Unterstützung für **CSS-Selektoren** zur gezielten Datenentnahme.  
- Automatisierte **Task-Planung** für regelmäßige Scraping-Prozesse.  

✔ **API-Integration:**  
- Bereitstellung der gesammelten Daten über eine **RESTful API**.  
- **Authentifizierung per API-Key** zum Schutz der Endpunkte.  
- **Ratenbegrenzung**, um Missbrauch zu verhindern.  
- **Monitoring von geplanten Tasks** mit Statusberichten.  

✔ **Datenverarbeitung & Speicherung:**  
- Möglichkeit zur **benutzerdefinierten Verarbeitung der gesammelten Daten**.  
- Speicherung in einer **SQLite-Datenbank** für persistente Datennutzung.  
- **Caching-Mechanismus**, um wiederholte Anfragen effizient zu handhaben.  

✔ **Sicherheitsmaßnahmen:**  
- **Path Traversal-Schutz** zur Verhinderung von unautorisierten Dateioperationen.  
- **CSS-Injection-Prävention** durch Validierung von Selektoren.  
- **Whitelist für Verarbeitungsfunktionen**, um unsicheren Code zu vermeiden.  

---

## **3. Sicherheit**  
**Bewertung: ★★★★★ (5/5)**  

✔ **API-Schutz:**  
- API-Authentifizierung über **API-Keys**.  
- **Ratenbegrenzung**, um DDoS- oder Brute-Force-Angriffe zu verhindern.  

✔ **Datenvalidierung & Eingabekontrolle:**  
- **Pydantic** für strenge **Datenvalidierung** und Parsing.  
- **Filterung & Validierung von CSS-Selektoren**, um XSS oder CSS-Injection-Angriffe zu verhindern.  

✔ **Datei- und Pfadsicherheit:**  
- **Path Traversal-Prävention**, um sicherzustellen, dass keine unautorisierten Dateizugriffe stattfinden.  

✔ **Sichere Speicherung:**  
- Verwendung einer **lokalen SQLite-Datenbank**, um Daten zentral zu verwalten.  
- Möglichkeit zur **Erweiterung auf sicherere Datenbanksysteme**.  

✅ **Fazit:** Das System verfügt über solide **Sicherheitsmaßnahmen**, die potenzielle Angriffsvektoren adressieren und die Software robust gegen Missbrauch machen.  

---

## **4. Performance und Skalierbarkeit**  
**Bewertung: ★★★★☆ (4/5)**  

✔ **Effiziente Architektur:**  
- **Flask als API-Framework**, das leicht skalierbar ist.  
- **Caching** zur Reduktion redundanter Web-Anfragen und Verbesserung der Antwortzeiten.  
- Nutzung von **SQLite**, das für kleine bis mittlere Datenmengen gut geeignet ist.  

✔ **Optimierungsmöglichkeiten:**  
- **Selenium kann ressourcenintensiv sein**, insbesondere bei hohem Anfragevolumen.  
- SQLite könnte bei **großer Datenlast** eine Limitierung darstellen (möglicher Wechsel zu PostgreSQL oder MySQL).  
- **Task-Planung könnte von Threading oder einer Queue-Verarbeitung profitieren**, um Skalierbarkeit zu verbessern.  
- **Flask arbeitet synchron**, eine zukünftige Erweiterung mit `asyncio` und `aiohttp` könnte die Performance weiter steigern.  

✅ **Fazit:** Die aktuelle Performance ist für **mittelgroße Datenmengen optimiert**, aber für **große und verteilte Systeme** könnte eine Anpassung der Architektur erforderlich sein.  

---

## **5. Codequalität & Wartbarkeit**  
**Bewertung: ★★★★★ (5/5)**  

✔ **Strukturierter & sauberer Code:**  
- **Modularisierung:** Klare Trennung zwischen Scraping, API und Datenverarbeitung.  
- **Einsatz von Konfigurationsdateien (.env, YAML)**, um Anpassungen ohne Codeänderungen zu ermöglichen.  
- **Pydantic für Datenvalidierung**, was Fehlerquellen reduziert.  

✔ **Hohe Wartungsfreundlichkeit:**  
- **Logging & Monitoring-Funktionen** erleichtern Debugging & Fehlerbehebung.  
- **Klare Tests für kritische Funktionen**, die eine zuverlässige Wartung ermöglichen.  
- **Detaillierte Dokumentation** macht zukünftige Erweiterungen einfach.  

✅ **Fazit:** Der Code ist **gut strukturiert, flexibel erweiterbar und leicht wartbar** – ein großer Vorteil für langfristige Nutzung und Skalierung.  

---

## **6. Benutzerfreundlichkeit**  
**Bewertung: ★★★★★ (5/5)**  

✔ **Intuitive Bedienung:**  
- **Streamlit-Web-Oberfläche**, die eine einfache Verwaltung von Scraping-Tasks ermöglicht.  
- **API-Dokumentation mit Beispielen**, um schnelle Integration zu gewährleisten.  

✔ **Automatisierung & Konfiguration:**  
- **Task-Planung direkt über UI** möglich.  
- **Konfigurierbare YAML- und `.env`-Dateien**, um die Software an individuelle Bedürfnisse anzupassen.  

✔ **Fehlermeldungen & Logging:**  
- **Detaillierte Logging-Funktionen** helfen bei der Fehlerbehebung.  
- **Fehlermeldungen sind klar und verständlich**, um Probleme schnell zu lösen.  

✅ **Fazit:** Die Software bietet eine **intuitive Nutzerführung** mit einer **benutzerfreundlichen Web-Oberfläche und umfassender Konfigurierbarkeit**.  

---

## **7. Testabdeckung & Qualitätssicherung**  
**Bewertung: ★★★★★ (5/5)**  

✔ **Umfassende Testsuite:**  
- **Unit-Tests für zentrale Funktionen** (z. B. URL-Validierung, HTML-Parsing, API-Endpunkte).  
- **Sicherheitstests für Path Traversal & CSS-Selektor-Validierung**.  
- **Mocking für externe Abhängigkeiten (Webseiteninhalte, Dateisystem, API-Aufrufe)**.  

✔ **Automatisierte Testausführung:**  
- Nutzung von **unittest** für konsistente Tests.  
- Tests können mit folgendem Befehl ausgeführt werden:  
```sh
python -m unittest discover tests
```

✅ **Fazit:** Sehr gute Testabdeckung mit Fokus auf **Sicherheits-, Integrations- und Funktionstests**.  

---

## **8. Fazit & Gesamtbewertung**  
### **Gesamtbewertung: 4,9 / 5 Sterne ⭐⭐⭐⭐⭐**  

✅ **Empfehlung:** Diese Software ist **hochwertig, sicher und flexibel** und eignet sich ideal für **mittelgroße bis große Web-Scraping-Projekte mit API-Integration**. 🚀



