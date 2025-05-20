# Passwordmanager

Ein einfacher Passwordmanager geschrieben in Python.

## Überblick

Dieses Projekt ist ein Passwordmanager, der es ermöglicht, Passwörter sicher zu speichern, zu verwalten und abzurufen. Der Fokus liegt auf Benutzerfreundlichkeit und Sicherheit.

## Features

- Speicherung und Verwaltung von Passwörtern
- Passwort-Generierung
- Sichere Speicherung (z.B. verschlüsselte Datenbank oder Datei)
- Einfache Benutzeroberfläche (über `main.py` als Einstiegspunkt)
- Suche und Filterung gespeicherter Passwörter

## Installation

1. Klone das Repository:
   ```bash
   git clone https://github.com/MathieuAlbrecht/Passwordmanager.git
   cd Passwordmanager
   ```

2. Installiere die benötigten Abhängigkeiten:
   ```bash
   pip install -r requirements.txt
   ```

## Nutzung

Starte das Programm mit:

```bash
python main.py
```

Folge den Anweisungen in der Konsole, um Passwörter zu speichern, anzeigen zu lassen oder zu generieren.

> **Hinweis:** Die Datei `main.py` ist der Einstiegspunkt zum Programm.

## Sicherheitshinweise

- Die gespeicherten Passwörter werden verschlüsselt abgelegt (Details siehe Quellcode).
- Das Master-Passwort sollte stark gewählt werden und nicht verloren gehen, da ohne dieses kein Zugriff auf die gespeicherten Passwörter möglich ist.
- Für maximale Sicherheit empfiehlt es sich, das Repository und die Passwort-Datenbank nicht in der Cloud zu speichern.

## Technische Details

- Programmiersprache: Python
- Einstiegspunkt: `main.py`
- Mögliche Bibliotheken: `cryptography`, `tkinter` (für GUI), `sqlite3`
