# MCUtourguide

Static single-page checklist for an MCU watch order.

Kurzanleitung zum Deployment

- Lokales Testen: Einfach `index.html` im Browser öffnen.
- GitHub Pages (empfohlen): Die mitgelieferte GitHub Actions-Workflowdatei deployt automatisch den Inhalt des Repositories bei Push auf `main`.

Wenn du manuell pushen möchtest:

```bash
git add .
git commit -m "Prepare site for deployment"
git push origin main
```

Die Action verwendet die offiziellen GitHub Actions für Pages; nach dem Push aktiviere (falls nötig) GitHub Pages unter den Repository-Einstellungen.
