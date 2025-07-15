# MitokyAssist

**MitokyAssist** ist ein innovatives Projekt, das einen Telegram-Bot mit Künstlicher Intelligenz und eine To-Do-List-Funktion kombiniert. Der Bot ermöglicht das Verarbeiten von Textanfragen, Sprachnachrichten und Bildanalysen sowie das Verwalten von Aufgaben direkt im Telegram-Chat. In Zukunft wird eine eigenständige To-Do-List-App mit Synchronisation über die Telegram-ID entwickelt.

Besuchen Sie die Website: [yoursitename.netlify.app](https://yoursitename.netlify.app)

## Funktionalität

- **Textbefehle und Nachrichten**: Der Bot antwortet auf Befehle wie `/start` und Textnachrichten.
- **Bildanalyse**: Analyse hochgeladener Fotos mit KI.
- **Sprachnachrichten**: Verarbeitung von Sprachnachrichten.
- **To-Do-List**: Verwalten von Aufgaben mit den Befehlen:
  - **`/add`**: Aufgaben hinzufügen
  - **`/list`**: Aufgaben anzeigen
  - **`/delete`**: Aufgaben löschen
  - **`/done`**: Aufgaben als erledigt markieren
- **Datenbank**: Sichere Speicherung von Aufgaben in einer SQLite-Datenbank.

## Verwendete Technologien

- **Telegram Bot API**: Für die Interaktion mit Nutzern.
- **Python**: Für die Bot-Entwicklung.
- **SQLite**: Für die Speicherung von Aufgaben.
- **HTML, CSS, Bootstrap, JavaScript**: Für die Website mit dynamischer Karussell-Demo.

## Installation und Start

### Voraussetzungen
- Node.js (für lokale Entwicklung mit Bootstrap, falls erforderlich).
- Python 3.x (für den Telegram-Bot, falls der Code verfügbar ist).
- SQLite (für die Datenbank).

### Website lokal starten
1. Klone das Repository:
   ```bash
   git clone https://github.com/Mitokyff/MitokyAssist.git
   ```
2. Öffne `index.html` in einem Browser oder starte einen lokalen Server:
   ```bash
   python -m http.server 8000
   ```
3. Öffne `http://localhost:8000` im Browser.

### Telegram-Bot starten
> **Hinweis**: Der Bot-Code ist nicht öffentlich. Kontaktieren Sie den Entwickler für Details.

1. Stelle sicher, dass Python und die erforderlichen Bibliotheken installiert sind (z. B. `python-telegram-bot`).
2. Konfiguriere den Bot-Token von Telegram.
3. Starte das Bot-Skript (z. B. `main.py`).

## Screenshots

Die Website enthält eine Karussell-Demo mit Screenshots, die die To-Do-List-Funktionen zeigen:
- **/add und /list**: Aufgaben hinzufügen und anzeigen.
- **/delete**: Aufgaben löschen.
- **/done**: Aufgaben als erledigt markieren.

## Kontakt

- **GitHub**: [github.com/Mitokyff](https://github.com/Mitokyff)
- **E-Mail**: [mykyta.kyrychenko.de@gmail.com](mailto:mykyta.kyrychenko.de@gmail.com)
- **Telegram**: [t.me/MitokyBot](https://t.me/MitokyBot)

## Lizenz

Dieses Projekt ist unter der MIT-Lizenz lizenziert. Siehe [LICENSE](LICENSE) für Details.