# Website – Praxis für Psychotherapie, Mag.a Silke Pfeifer-Mayer

Statische Website (reines HTML/CSS, keine Abhängigkeiten, keine externen Dienste).

## Struktur

| Datei | Inhalt |
|---|---|
| `index.html` | Startseite |
| `qualifikation.html` | Qualifikationen |
| `berufserfahrung.html` | Berufserfahrung & Fortbildungen |
| `kontakt.html` | Organisatorisches/Kontakt |
| `impressum.html` | Impressum |
| `assets/profilbild.jpg` | Profilbild (Startseite) |
| `404.html` | Fehlerseite |
| `assets/style.css` | Gestaltung (Farben oben unter `:root` anpassbar) |
| `.nojekyll` | GitHub Pages liefert die Dateien unverändert aus |

## Veröffentlichen mit GitHub Pages

1. Neues Repository anlegen und alle Dateien dieses Ordners (inkl. `.nojekyll`) in den Hauptordner hochladen.
2. Im Repository: **Settings → Pages → Build and deployment → Source: „Deploy from a branch“**, Branch `main`, Ordner `/ (root)` → **Save**.
3. Nach ca. 1 Minute ist die Seite unter `https://<benutzername>.github.io/<repository>/` erreichbar.
4. Optional eigene Domain: unter **Settings → Pages → Custom domain** eintragen und beim Domain-Anbieter einen CNAME-Eintrag auf `<benutzername>.github.io` setzen.

## Texte ändern

Texte direkt in der jeweiligen `.html`-Datei bearbeiten. Kopfzeile und Fußzeile sind in jeder Datei enthalten – Änderungen dort (z. B. Telefonnummer) bitte in allen Dateien vornehmen. Die Krankenkassen-Zuschüsse („Stand September 2026“) stehen in `kontakt.html`.

## Hinweis

Eine **Datenschutzerklärung** ist noch nicht enthalten (GitHub Pages speichert technisch IP-Adressen in Server-Logs) und sollte ergänzt werden.
