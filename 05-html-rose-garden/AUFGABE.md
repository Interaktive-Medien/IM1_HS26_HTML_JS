# Vom Screenshot zum HTML

## 1. Analysieren

Betrachte den bereitgestellten Screenshot, ohne den HTML-Quelltext der Vorlage zu öffnen.

- Welche grossen Bereiche erkennst du?
- Welche Inhalte gehören zusammen?
- Welche Muster wiederholen sich?
- Welche Texte sind Überschriften, Absätze oder Links? Welche Elemente sind Bilder?

## 2. DOM zeichnen

Zeichne einen möglichen DOM-Baum ab dem `body` auf Papier oder digital. Beschrifte die Knoten mit passenden HTML-Elementen und kurzen Inhaltsangaben. Zeige Eltern-Kind-Beziehungen und Geschwisterelemente.

Ein Screenshot legt den DOM-Baum nicht eindeutig fest. Begründe deine Wahl der semantischen Elemente. Ergänze Container dort, wo du Inhalte für das Layout zusammenfassen möchtest.

## 3. HTML nachbauen

Öffne `starter/index.html` und setze deine Skizze als HTML um. Das CSS ist bereits eingebunden. Verwende die vorgegebenen Klassen; die CSS-Datei musst du nicht ändern.

Die Bilddateien erreichst du aus der Startdatei über `../logo.svg` und `../hero.svg`. Gib Bildern passende Alternativtexte. Ein Logo neben einem gleichlautenden Markennamen darf einen leeren Alternativtext erhalten.

### Verfügbare CSS-Klassen

Nutze diese Übersicht erst nach deiner ersten DOM-Skizze. Mehrere Klassen lassen sich mit Leerzeichen kombinieren.

| Klasse | Verwendung |
| --- | --- |
| `container` | Zentrierte Inhaltsbreite |
| `site-header` | Hintergrund des Kopfbereichs |
| `header-content` | Logo und Navigation nebeneinander |
| `logo` | Logo-Bild und Markenname nebeneinander |
| `logo-dot` | Farbiger Punkt im Markennamen |
| `hero` | Text und Bild nebeneinander |
| `hero-copy` | Textbereich der Hero-Section |
| `eyebrow` | Kleine Einleitungszeile |
| `hero-description` | Einleitungstext |
| `button` | Link mit Schaltflächenoptik |
| `hero-image` | Responsive Hero-Grafik |
| `dashboard` | Abstand des Dashboard-Bereichs |
| `section-heading` | Überschriftengruppe und Demo-Hinweis nebeneinander |
| `demo-label` | Kleiner Hinweistext |
| `card-grid` | Raster für die drei Karten |
| `card` | Einzelne Karte |
| `metric` | Grosse Kennzahl |
| `trend` | Grüner Veränderungswert |
| `card-description` | Erläuterung der Kennzahl |
| `site-footer` | Trennlinie des Fussbereichs |
| `footer-content` | Logo links, Copyright rechts |

Das CSS gestaltet auch HTML-Elemente direkt, etwa `h1`, `h2`, `h3` und Links innerhalb von `nav`. Ein `span` innerhalb von `h1` hebt einen Teil der Überschrift farbig hervor.

Verwende für das Linkziel des Logos die ID `start` und für das Linkziel der Dashboard-Links die ID `dashboard`.

## Prüfen und abgeben

- Vergleiche deine Seite bei derselben Fensterbreite mit dem Screenshot.
- Prüfe die Reihenfolge der Überschriften und die Funktion der Sprunglinks.
- Verkleinere das Browserfenster: Die Karten sollen untereinander erscheinen.
- Prüfe, ob Links mit der Tabulatortaste erreichbar sind.
- Gib deine DOM-Skizze und deine HTML-Datei ab. Erläutere eine Entscheidung zu deiner Struktur.


Schau mal hier. Schau mal da.

Grosse Ideen.
Alles im Blick.
Ein klarer Kopf beginnt mit einem guten Überblick. Hier findest du deine wichtigsten Zahlen — einfach, kompakt und an einem Ort.

Ein grüner Planet mit zwei Umlaufbahnen
DEIN DASHBOARD

Die blanken Zahlen
Demo · Alle Werte frei erfunden
Besucher:innen
12’840

Aktive Projekte
24

Kaffee & Kreativität
98 %


orbit.
© 2026 orbit. Alle Rechte vorbehalten.