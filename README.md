# 🚀 Agentic AI Portfolio

Willkommen in meinem KI-Automatisierungs-Portfolio! In diesem Repository sammle ich produktiv einsatzbereite Workflows, die mithilfe von **n8n**, hochentwickelten KI-Modellen (**Google Gemini**) und smarten API-Integrationen alltägliche Geschäfts-, Vertriebs- und Analyseprozesse komplett automatisieren.

Jedes Projekt ist in seinem eigenen Ordner sauber dokumentiert, enthält die dazugehörige `.json`-Workflow-Datei zum direkten Importieren sowie visuelle Previews der Ergebnisse.

---

## 🛠️ Übersicht der enthaltenen Projekte

Hier findest du eine Übersicht aller 5 Automatisierungen, die ich entwickelt habe:

### 1. 📊 [Finance Tracker](./finance-tracker)
* **Ziel:** Wöchentliches Finanz- & Abo-Controlling.
* **Funktion:** Liest Transaktionsdaten aus Google Sheets aus. Ein KI-Agent analysiert das Ausgabenverhalten, deckt ungenutzte Abos auf und liefert konkrete Spartipps.
* **Ergebnis:** Generiert ein dynamisches HTML-Dashboard mit Chart.js-Diagrammen und schickt es direkt als krisensichere Datei in dein E-Mail-Postfach.

### 2. 🧮 [Kundenabrechnungen](./kundenabrechnungen)
* **Ziel:** Automatisiertes Monats-Controlling für Dienstleister und Agenturen.
* **Funktion:** Aggregiert offene Zeiteinträge aus Google Sheets und berechnet die Umsätze. Ein Switch-Node prüft den Status gegen das Projektbudget.
* **Ergebnis:** Bei Budgetüberschreitung geht sofort ein interner Alarm ans Team. Läuft alles nach Plan, textet Gemini ein professionelles HTML-Anschreiben für den Kunden.

### 3. 🌐 [Marktanalyst](./marktanalyst)
* **Ziel:** Kontinuierliches strategisches Monitoring der Wettbewerber.
* **Funktion:** Scannt die RSS-Feeds und Webseiten von Tech-Giganten. Gemini bewertet die Dringlichkeit der Marktveränderungen auf einer Skala von 1 bis 3.
* **Ergebnis:** Kritische Bedrohungen (Stufe 3) triggern sofort eine Eilmeldung auf Discord. Harmlose Updates werden gesammelt und im wöchentlichen Report archiviert.

### 4. 📰 [Newsletter-Agent](./newsletter-agent)
* **Ziel:** Personalisierte und kuratierte Tech-News ohne Informations-Overload.
* **Funktion:** Sammelt aktuelle Artikel führender Tech-Magazine, zieht den Volltext via Firecrawl-Scraper und lässt Gemini prägnante Zusammenfassungen schreiben.
* **Ergebnis:** Erstellt ein elegantes HTML-Layout inklusive eines visuellen "Hype-Barometers" zur Bewertung der allgemeinen Marktstimmung.

### 5. 📥 [Webanfragen-Filter](./webanfragen-filter)
* **Ziel:** Intelligente B2B-Lead-Qualifizierung in Echtzeit.
* **Funktion:** Ein HTML-Formular übergibt Anfragen per Webhook an n8n. Gemini extrahiert vollautomatisch Firmennamen und Budgets aus dem Freitext, loggt sie im Google-Sheets-CRM und leitet sie per Switch-Node weiter.
* **Ergebnis:** Verteilt Leads vollautomatisch: Schickt Budget-Rückfragen bei fehlenden Angaben, normale Bestätigungen oder exklusive VIP-Benachrichtigungen für Großkunden direkt an das Team.

---

## 🚀 Wie man die Workflows nutzt

1. Navigiere in den Ordner des gewünschten Projekts.
2. Lade dir die dort hinterlegte `.json`-Datei herunter.
3. Importiere die Datei ganz einfach per Drag-and-Drop in deine n8n-Instanz.
4. Trage deine eigenen API-Schlüssel (Credentials) für Google, Discord oder Firecrawl ein.
5. Workflow auf **Publish** stellen und die Automatisierung genießen!
