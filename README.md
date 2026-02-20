# Join

**Join** ist ein leichtgewichtiges, kollaboratives Planungstool für strukturierte Aufgabenverwaltung.  
Es ermöglicht das Erstellen, Zuweisen und Organisieren von Aufgaben in einem Kanban-ähnlichen Workflow, um Transparenz und Effizienz in der Teamarbeit zu erhöhen.

---

## 🚀 Features

- Kanban-ähnlicher Workflow  
- Aufgaben erstellen, bearbeiten und löschen  
- Aufgaben Personen zuweisen  
- Statusverwaltung (z. B. To Do, In Progress, Done)  
- Echtzeit-Datenspeicherung mit Firebase  

---

## 🎯 Zielgruppe

**Join** richtet sich an:  

- Softwareentwicklungsteams  
- Projektgruppen  
- Studierende  
- Einzelpersonen, die ihre Aufgaben strukturiert verwalten möchten  

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript  
- **Backend / Datenbank:** Firebase  

---

## 📦 Installation & Setup

Da es sich um ein Frontend-Projekt mit Firebase-Anbindung handelt, kann es lokal wie folgt gestartet werden:

1. **Repository klonen**
```bash
git clone https://github.com/DEIN-USERNAME/join.git
cd join

2. Firebase konfigurieren

Firebase-Projekt in der Firebase Console
 erstellen

Firebase-Konfigurationsdaten in der entsprechenden JS-Datei eintragen

Falls Firestore oder Realtime Database genutzt wird: Sicherheitsregeln entsprechend konfigurieren

3. Projekt starten

Einfach die index.html im Browser öffnen

Oder mit einem Live-Server starten (empfohlen):

npx live-server
📂 Projektstruktur (Beispiel)
/join
│── index.html
│── /css
│── /js
│── /assets
🔐 Firebase

Dieses Projekt verwendet Firebase zur Datenspeicherung.
Stelle sicher, dass deine API-Keys nicht öffentlich missbraucht werden und die Sicherheitsregeln korrekt gesetzt sind.

📌 Status

Projektstatus: aktiv / in Entwicklung

📄 Lizenz

Dieses Projekt steht unter der MIT-Lizenz.