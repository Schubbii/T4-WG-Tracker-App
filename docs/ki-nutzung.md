# Einsatz von KI

Laut Prüfungs-Briefing ist KI bei der Entwicklung erlaubt und muss dokumentiert werden.

## Werkzeug
Claude (Anthropic), als Chat-Assistent beim Programmieren.

## Wofür
- Planung: Abgleich der Anforderungen aus den Kursfolien mit der Projektidee,
  Vorschläge für Datenmodell, API und Aufbau.
- Code: Backend (Hono-Routen, SQLite-Zugriff, Login) und Frontend (Vue-Komponenten)
  wurden von Claude unterstützt und überarbeitet.
- Tests und Dokumentation: Entwürfe für Tests, API-Doku, Architektur und ADRs.

## Mein Vorgehen
- Ich habe das Projekt in einem neuen Repository Schritt für Schritt selbst aufgebaut:
  Datei für Datei, mit Test und Commit nach jedem Schritt.
- Fehler beim Aufbau (z. B. nicht gespeicherte Dateien, belegter Port, Google-Drive-Ordner)
  habe ich selbst behoben.

## Was ich selbst geprüft habe
- Alle Tests laufen (`deno task test`).
- Die App im Browser durchgespielt, inklusive Fehlerfällen und zweiter WG.
- Die Antworten im Netzwerk-Tab der Entwicklerwerkzeuge angesehen.
