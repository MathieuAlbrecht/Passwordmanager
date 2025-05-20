# Passwortmanager

Ein einfacher, lokaler Passwortmanager mit grafischer Benutzeroberfläche in Python.

## Übersicht

Dieses Projekt ist ein Passwortmanager, mit dem Benutzer Passwörter sicher speichern, anzeigen, bearbeiten und löschen können. Die Passwörter werden verschlüsselt gespeichert, und jeder Benutzer hat seine eigene Passwortdatei.

Die Anwendung bietet eine GUI mit [tkinter](https://docs.python.org/3/library/tkinter.html) und verwendet [cryptography.fernet](https://cryptography.io/en/latest/fernet/) zur Verschlüsselung.

## Features

- Benutzerregistrierung und -login (lokal, keine Netzwerkverbindung notwendig)
- Passwörter verschlüsselt speichern (mit Fernet Key)
- Passwörter anzeigen, kopieren, bearbeiten und löschen
- Moderne, anpassbare Oberfläche mit [ttkthemes](https://pypi.org/project/ttkthemes/)
- Alles läuft lokal, keine Cloud benötigt


## Voraussetzungen

- Python 3.7 oder neuer
- Abhängigkeiten:  
  `tkinter`, `ttkthemes`, `cryptography`
- Betriebssystem: macOS (für Clipboard-Unterstützung via `pbcopy`), ggf. Anpassung für Windows/Linux nötig


## Hinweise zur Sicherheit

- Der Verschlüsselungs-Key wird in der Datei `key.key` gespeichert. Schütze diese Datei, da sie zur Entschlüsselung benötigt wird.
- Passwörter werden pro Benutzer in separaten Dateien gespeichert.
- Die Anwendung prüft das Login nur anhand des Benutzernamens (keine Passwortprüfung!). Für den produktiven Einsatz sollte dies angepasst werden.


## Anpassung für Windows/Linux

- Das Kopieren in die Zwischenablage (`pbcopy`) funktioniert nur auf macOS. Für Windows ersetze z.B. durch `clip`, für Linux ggf. `xclip` oder `xsel`.


## Autor

Mathieu Albrecht
