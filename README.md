# Think · Pair · Share

Ein schlanker Phasen-Timer für die Think-Pair-Share-Methode im Französisch- und Spanischunterricht. Die Seite zeigt die Aufgabe, die aktuelle Phase, einen ruhigen Countdown, passende Redemittel und Konnektoren in der Zielsprache – optimiert für das iPad 13 Zoll und den Beamer.

## Funktionen

- **Einrichtung beim ersten Start:** Fach (Französisch oder Spanisch) und Dauer jeder Phase wählen; halbe Minuten sind möglich (z. B. 1,5).
- **Aufgabe:** wird von der Lehrkraft direkt in der Zielsprache eingegeben und während aller Phasen groß angezeigt.
- **Phasen Think, Pair, Share:** farbig hervorgehoben, mit festen Arbeitsanweisungen in einfacher Zielsprache (A1–A2).
- **Redemittel pro Phase** in zwei Niveaustufen (★ einfach, ★★ erweitert).
- **Konnektoren** in jeder Phase, nebeneinander mit deutscher Übersetzung:
  - Französisch: d'abord, puis, après, ensuite, enfin
  - Spanisch: primero, después, luego, además, al final
- **Ruhiger Countdown mit Fortschrittsbalken**, ohne Blinken oder Alarmfarben.
- **Klangschalen-Signal** beim Phasenwechsel, direkt im Browser erzeugt (keine Audiodatei); abschaltbar.
- **Automatischer Phasenwechsel:** Nach Ablauf erklingt der Ton, die nächste Phase wird vorbereitet und startet per Klick.
- **Digitale Uhr** mit Wochentag und Datum in der Zielsprache, **analoge Uhr** rechts.
- **Yin-Yang-Logo**, das die Farbe mit der Phase wechselt und zum GitHub-Repository führt.
- **Bildschirm bleibt wach**, solange der Timer läuft (sofern der Browser das unterstützt).
- **Vollbild** für die Präsentation.

## Geräte & Browser

Die Seite passt sich automatisch an jede Bildschirmgröße an:

| Gerät | Darstellung |
|---|---|
| PC/Laptop (Windows, macOS, Linux) | Zweispaltig, passt ohne Scrollen ins Browserfenster (ab ca. 1024 × 600) |
| iPad/Android-Tablet quer | Zweispaltig, passt ohne Scrollen |
| iPad/Tablet hoch | Einspaltig; Aufgabe, Phasen und Timer oben sichtbar |
| Smartphone hoch (iPhone, Android) | Einspaltig, Timer und Start-Button im ersten Bildschirm, Redemittel darunter |
| Smartphone quer | Aufgabe und Phasen links, Timer rechts daneben |

Geeignet für aktuelle Versionen von Safari, Chrome, Edge, Firefox und Samsung Internet. Es werden die Systemschriften des jeweiligen Geräts verwendet (z. B. SF Pro auf Apple-Geräten, Segoe UI unter Windows, Roboto auf Android, Ubuntu/Cantarell/Noto unter Linux). Tastenkürzel gibt es nur mit Tastatur; auf Touchgeräten erfolgt alles über die Buttons. Der Vollbild-Button erscheint nur, wo der Browser Vollbild unterstützt (auf dem iPhone nicht).

## Bedienung

| Aktion | Touch / Maus | Tastatur |
|---|---|---|
| Start / Pause | Start-Button | Leertaste (mit Bestätigung) |
| Nächste Phase | Pfeil-Button rechts oder Phasen-Button | Pfeil rechts (mit Bestätigung) |
| Vorherige Phase | Pfeil-Button links oder Phasen-Button | Pfeil links (mit Bestätigung) |
| Von vorn | Kreispfeil-Button | – |
| Dialog bestätigen / abbrechen | OK / Abbrechen | Enter / Esc |

Tastenkürzel sind deaktiviert, solange ins Aufgabenfeld getippt wird. Mit Esc oder einem Tipp außerhalb des Feldes werden sie wieder aktiv.

Über **„Neu einrichten“** unten links lassen sich Fach und Zeiten jederzeit ändern. Dort können auch alle gespeicherten Daten gelöscht werden.

## Datenschutz

- Die Seite lädt **keine externen Ressourcen** (keine Schriften, Bilder, Skripte oder Tracker von fremden Servern) und sendet **keine Daten**. Eine Content-Security-Policy im Dokument blockiert zusätzlich jede Netzwerkverbindung.
- Fach, Zeiten, Toneinstellung und der Aufgabentext werden ausschließlich **lokal im Browser** (localStorage) gespeichert.
- Hinweis: Wird die Seite über GitHub Pages aufgerufen, protokolliert GitHub als Webhoster technisch bedingt Zugriffe (z. B. IP-Adressen). Wer das vermeiden möchte, kann `index.html` herunterladen und lokal bzw. offline öffnen – alles funktioniert genauso.

## Veröffentlichen mit GitHub Pages

1. Neues Repository anlegen, z. B. `think-pair-share`.
2. `index.html`, `README.md` und `LICENSE` hochladen.
3. Unter **Settings → Pages** als Quelle „Deploy from a branch“, Branch `main`, Ordner `/ (root)` wählen.
4. Nach kurzer Zeit ist die Seite erreichbar unter `https://BENUTZERNAME.github.io/think-pair-share/`.

Der Link des Logos wird automatisch aus dieser Adresse abgeleitet und zeigt auf `https://github.com/BENUTZERNAME/think-pair-share`. Bei lokal geöffneter Datei oder eigener Domain hat das Logo keinen Link.

## Tipps für iPad, iPhone und Android

- **Ton:** Bei aktiviertem Stummschalter oder Fokus-Modus kann der Signalton ausbleiben. Mit „Ton testen“ in der Einrichtung lässt sich die Lautstärke vorab prüfen.
- **Zum Home-Bildschirm hinzufügen** öffnet die Seite wie eine App: auf iPhone/iPad über Teilen → „Zum Home-Bildschirm“, unter Android im Chrome-Menü → „Zum Startbildschirm hinzufügen“.
- Das Wachhalten des Bildschirms benötigt iOS/iPadOS 16.4 oder neuer; unter Android und am PC funktioniert es in Chrome, Edge und Firefox.

## Weitere Sprachen ergänzen

Alle Texte stehen zentral im Objekt `LANG` am Anfang des Skripts. Für eine neue Sprache einen Block (z. B. `fr`) kopieren, übersetzen und in der Einrichtung einen weiteren Sprach-Button ergänzen.
