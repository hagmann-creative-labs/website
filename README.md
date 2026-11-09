# hagmannlabs.de

Statische Website der Hagmann Creative Labs UG: Startseite, Impressum, Datenschutzerklärung (Website + Apps).
Keine Cookies, kein Tracking, keine externen Schriften.

## Veröffentlichen über GitHub Pages

1. Öffentliches Repo `hagmann-creative-labs/website` anlegen und diese Dateien hochladen.
2. Repo → Settings → Pages: Source „Deploy from a branch“, Branch `main`, Ordner `/ (root)`.
   Custom domain: `hagmannlabs.de` (steht schon in `CNAME`). Nach erfolgreicher DNS-Prüfung „Enforce HTTPS“ aktivieren.
3. DNS bei Strato (Domainverwaltung → hagmannlabs.de → DNS):
   - A-Record der Domain: `185.199.108.153` (GitHub Pages; weitere gültige: .109, .110, .111.153)
   - CNAME für `www`: `hagmann-creative-labs.github.io`
   - MX-Einträge (E-Mail) NICHT ändern.

## Pflege

- E-Mail-Adresse steht in allen drei Seiten (`alex@hagmannlabs.de`).
- Datenschutzerklärung anpassen, sobald neue Dienste in die App kommen (z. B. In-App-Käufe, Analyse).
- Wechsel des Hostings → Abschnitt 3 „Hosting“ in `datenschutz.html` anpassen.
