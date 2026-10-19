# oneSCM Manual (v2.96.0 Snapshot)

Dies ist die zum Zeitpunkt der Übertragung **aktuellste, vollständige Version**
des "ONESCM Ticket-Cockpit" mit allen Features — als eigenständige,
selbst-enthaltene Single-Page-Webapp (`webapp/ticket_cockpit.html`,
`APP_VERSION = "2.96.0"`).

## Herkunft dieser Datei

Diese Datei stammt aus der **veröffentlichten Claude-Artifact-Seite**
(Stand 2026-10-17), **nicht** aus dem Git-Verlauf von
`andreas76761/jira_reelaseletter`. Der dortige Branch
`claude/blissful-einstein-4ngntr` liegt bei v2.82.0 und enthält nicht
dieselben Features — insbesondere fehlt dort:

- **Jira Input** (Nav-Punkt `jirainput`): HTML-Massenupload von
  Jira-Exporten mit KI-gestützter Label-Anreicherung.
- **Editor – neues Benutzerhandbuch** (Nav-Punkt `editor`, inhaltlich
  **nicht** identisch mit dem gleichnamigen Nav-Punkt im
  `jira_reelaseletter`-Repo, der dort Word/PowerPoint-Screens einliest):
  3-Spalten-Arbeitsbereich zum Erstellen eines neuen Benutzerhandbuchs
  (aktueller Stand / Verbesserungen aus Review & Stilprüfung / neues
  Handbuch mit internen Kommentaren), inkl. Review-Skills, Stil-Diff,
  KI-Antwort-Cache, Layout-Druck/-Download, Lauf-Fortsetzung und
  Begriffs-Sperre.

**Wichtige Einschränkung:** Es handelt sich hier nur um die **kompilierte
HTML-Ausgabe** dieser Artifact-Version. Der zugehörige unkompilierte
Quellcode, die Testsuite und das CLI-Tool, mit denen diese Version
gebaut wurde, lagen in keinem der für diese Session verfügbaren
Repositories vor und konnten daher nicht mit übertragen werden. Diese
Datei lässt sich direkt im Browser öffnen (Ansicht/Suche/Filter
funktionieren lokal; Downloads benötigen die Claude-Artifact-Laufzeit),
ist aber ohne das ursprüngliche Build-Setup nicht weiterentwickelbar
(keine Tests, kein Versions-Build-Skript).

## Datei

- `webapp/ticket_cockpit.html` — die vollständige Webapp (1 Datei, kein
  Server, kein Build-Schritt nötig zum Öffnen).
