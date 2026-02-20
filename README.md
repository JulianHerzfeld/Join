<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Join – Projektbeschreibung</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            max-width: 900px;
            margin: 40px auto;
            line-height: 1.6;
            padding: 0 20px;
        }
        h1, h2 {
            color: #222;
        }
        ul {
            margin-bottom: 20px;
        }
        code {
            background-color: #f4f4f4;
            padding: 4px 6px;
            border-radius: 4px;
        }
        pre {
            background-color: #f4f4f4;
            padding: 15px;
            overflow-x: auto;
            border-radius: 6px;
        }
        .section {
            margin-bottom: 40px;
        }
    </style>
</head>
<body>

    <h1>Join</h1>

    <p>
        <strong>Join</strong> ist ein leichtgewichtiges, kollaboratives Planungstool für strukturierte Aufgabenverwaltung.
        Es ermöglicht das Erstellen, Zuweisen und Organisieren von Aufgaben in einem Kanban-ähnlichen Workflow,
        um Transparenz und Effizienz in der Teamarbeit zu erhöhen.
    </p>

    <div class="section">
        <h2>🚀 Features</h2>
        <ul>
            <li>Kanban-ähnlicher Workflow</li>
            <li>Aufgaben erstellen, bearbeiten und löschen</li>
            <li>Aufgaben Personen zuweisen</li>
            <li>Statusverwaltung (z. B. To Do, In Progress, Done)</li>
            <li>Echtzeit-Datenspeicherung mit Firebase</li>
        </ul>
    </div>

    <div class="section">
        <h2>🎯 Zielgruppe</h2>
        <ul>
            <li>Softwareentwicklungsteams</li>
            <li>Projektgruppen</li>
            <li>Studierende</li>
            <li>Einzelpersonen, die ihre Aufgaben strukturiert verwalten möchten</li>
        </ul>
    </div>

    <div class="section">
        <h2>🛠️ Tech Stack</h2>
        <ul>
            <li><strong>Frontend:</strong> HTML, CSS, JavaScript</li>
            <li><strong>Backend / Datenbank:</strong> Firebase</li>
        </ul>
    </div>

    <div class="section">
        <h2>📦 Installation & Setup</h2>

        <h3>1. Repository klonen</h3>
        <pre><code>git clone https://github.com/DEIN-USERNAME/join.git
cd join</code></pre>

        <h3>2. Firebase konfigurieren</h3>
        <ul>
            <li>Firebase-Projekt in der Firebase Console erstellen</li>
            <li>Firebase-Konfigurationsdaten in der entsprechenden JS-Datei eintragen</li>
            <li>Falls Firestore oder Realtime Database genutzt wird: Sicherheitsregeln konfigurieren</li>
        </ul>

        <h3>3. Projekt starten</h3>
        <p>
            Einfach die <code>index.html</code> im Browser öffnen
            oder mit einem Live-Server starten (empfohlen):
        </p>
        <pre><code>npx live-server</code></pre>
    </div>

    <div class="section">
        <h2>📂 Projektstruktur (Beispiel)</h2>
        <pre><code>/join
│── index.html
│── /css
│── /js
│── /assets</code></pre>
    </div>

    <div class="section">
        <h2>🔐 Firebase</h2>
        <p>
            Dieses Projekt verwendet Firebase zur Datenspeicherung.
            Stelle sicher, dass deine API-Keys nicht öffentlich missbraucht werden
            und die Sicherheitsregeln korrekt gesetzt sind.
        </p>
    </div>

    <div class="section">
        <h2>📌 Status</h2>
        <p>Projektstatus: aktiv / in Entwicklung</p>
    </div>

    <div class="section">
        <h2>📄 Lizenz</h2>
        <p>Dieses Projekt steht unter der MIT-Lizenz.</p>
    </div>

</body>
</html>