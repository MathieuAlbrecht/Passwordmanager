# Passwordmanager

Ein einfacher Passwordmanager geschrieben in Python.

## Überblick

Dieses Projekt ist ein Passwordmanager, der es ermöglicht, Passwörter sicher zu speichern, zu verwalten und abzurufen. Der Fokus liegt auf Benutzerfreundlichkeit und Sicherheit.

## Features

- Speicherung und Verwaltung von Passwörtern
- Sichere Speicherung (z.B. verschlüsselt in einer Textdatei)
- Einfache Benutzeroberfläche (über `main.py` als Einstiegspunkt)


## Sicherheitshinweise

- Die gespeicherten Passwörter werden verschlüsselt abgelegt (Details siehe Quellcode).
- Das Master-Passwort sollte stark gewählt werden und nicht verloren gehen, da ohne dieses kein Zugriff auf die gespeicherten Passwörter möglich ist.
- Für maximale Sicherheit empfiehlt es sich, das Repository und die Passwort-Datenbank nicht in der Cloud zu speichern.

## Technische Details

- Programmiersprache: Python
- Einstiegspunkt: `main.py`
- Mögliche Bibliotheken: `cryptography`, `tkinter` (für GUI), `sqlite3`
