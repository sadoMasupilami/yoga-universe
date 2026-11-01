# Yoga-Universe

Homepage von Yoga-Universe – Yoga und Entspannung mit Karin Stieglitz-Klug.

Die Seite ist reines HTML/CSS (Ordner `site/`), ohne Build-Schritt, ohne Cookies und ohne externe Inhalte.
Jeder Push auf `main` wird per GitHub Actions (`.github/workflows/pages.yml`) auf GitHub Pages veröffentlicht.

## Noch zu ergänzen

In `site/index.html` sind folgende Stellen mit `[... ergänzen]` markiert:

- **Kontakt**: E-Mail, Telefon, Adresse des Yogaraums
- **Impressum**: Anschrift und E-Mail (in Österreich Pflicht)
- **Kurse**: Die Zeiten im Wochenplan sind Beispiele
- **Foto**: Bild als `site/karin.jpg` ablegen und den Platzhalter im Abschnitt „Über mich“ ersetzen

## Lokal ansehen

```sh
python3 -m http.server -d site 8000
```
