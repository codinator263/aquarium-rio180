# Aquarium Rio 180 – Wissensportal

Mobile-freundliche, statische Wissensdatenbank für ein geplantes Juwel Rio 180.

## Aufbau

- `site/` – fertige Website (HTML, CSS und JavaScript)
- `wissen/` – separat pflegbare Markdown-Quelldokumente
- `site/index.html` – Startseite

Die Website ist aktuell eine aus den Markdown-Inhalten redaktionell erstellte Fassung; **eine automatische Markdown-zu-HTML-Synchronisierung existiert noch nicht**. Änderungen müssen an beiden Stellen erfolgen, bis ein Generator ergänzt wurde.

## GitHub Pages aktivieren

1. Neues GitHub-Repository `aquarium-rio180` erstellen. Für GitHub Free + Pages möglichst **öffentlich**, da GitHub Pages keine private Zugriffssteuerung bietet.
2. Inhalt dieses Ordners ins Repository hochladen. Die Website liegt in `site/`, nicht im Repo-Stamm.
3. Im Repository **Settings → Pages → Build and deployment → Source: GitHub Actions** auswählen.
4. Die enthaltene Datei `.github/workflows/pages.yml` veröffentlicht automatisch den Ordner `site/` bei Änderungen auf `main`.
5. Die Adresse erscheint in **Settings → Pages**, typischerweise `https://BENUTZERNAME.github.io/aquarium-rio180/`.

## Lokal testen

`site/index.html` im Browser öffnen. Es ist kein Server erforderlich.

## Datenschutz

Alle veröffentlichten Website-Inhalte sind öffentlich. Keine privaten Dokumente, Zugangsdaten oder vertraulichen persönlichen Daten einfügen.

## Aktualisieren

Markdown-Dateien unter `wissen/` bearbeiten und die dazugehörigen Texte in `site/index.html` nachführen. Anschließend Änderungen an GitHub übertragen.
