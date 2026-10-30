# Entwicklungsumgebung Setup

Ein Schritt-für-Schritt-Guide für die perfekte Einrichtung deiner Entwicklungsumgebung.

---

## Voraussetzungen

Bevor du mit dem Kurs startest, benötigst du:

1. Einen Computer (Mac, Windows oder Linux)
2. Internetverbindung
3. Etwa 30 Minuten Zeit für das Setup

---

Webex-Konferenzaufzeichnung: Setup, Tooling - Aufzeichnung
Link zur Aufzeichnung: https://fhgr.webex.com/fhgr/ldr.php?RCID=b13717cee5b30f1e6385597588e2313a
Kennwort: Tooling1-5

## 1. Browser installieren

Du benötigst einen **modernen Browser** mit guten Developer Tools.

### Empfohlene Browser (wähle einen):

**Option 1: Google Chrome** (empfohlen für Anfänger)
- Download: https://www.google.com/chrome/
- Vorteile: Beste DevTools, viele Tutorials basieren darauf
- Tastenkombination DevTools: `Cmd + Option + I` (Mac) oder `F12` (Windows)

**Option 2: Mozilla Firefox**
- Download: https://www.mozilla.org/firefox/
- Vorteile: Gute Privatsphäre, ausgezeichnete CSS-Grid-Tools

**Option 3: Microsoft Edge**
- Download: https://www.microsoft.com/edge
- Vorteile: Basiert auf Chromium, bereits auf Windows vorinstalliert

**Nicht empfohlen:** Safari (begrenzte DevTools), Internet Explorer (veraltet)

---

## 2. Code-Editor installieren

### PHPStorm

PhpStorm installieren : [Anleitung für mmp-Studierende der FHGR](https://github.com/Interaktive-Medien/101-MMP/blob/main/resources/phpstorm.md)

### Installation:

**Mac:**
1. DMG-Datei herunterladen
2. PHPStorm in den Programme-Ordner ziehen

**Windows:**
1. EXE-Datei herunterladen
2. Installer ausführen
---



## 3. Arbeitsumgebung einrichten
Anleitung: [Web-Development-Workflow mit Hostpoint & PhpStorm](https://github.com/Interaktive-Medien/101-MMP/blob/main/resources/Hostpoint_PhpStorm_Tutorials/README.md)

[Videotutorial Hostpoint und PHPStorm](https://www.youtube.com/playlist?list=PLLZlqg08CVic) (ohne Datenbanken)

**Tipp:** Öffne immer den **gesamten Projekt-Ordner**, nicht einzelne Dateien!

---

## 4. Browser DevTools kennenlernen

### DevTools öffnen:

- **Mac:** `Cmd + Option + I`
- **Windows/Linux:** `F12` oder `Ctrl + Shift + I`
- **Rechtsklick auf Element:** "Element untersuchen"

### Wichtige Tabs:

#### 1. **Elements / Elemente**
- HTML-Struktur live ansehen und bearbeiten
- CSS-Styles inspizieren und testen
- Box Model visualisieren

**Übung:** Rechtsklick auf ein Element → "Untersuchen"

#### 2. **Console / Konsole**
- JavaScript-Fehler sehen (SEHR WICHTIG!)
- `console.log()` Ausgaben
- JavaScript direkt testen

**Übung:** Tippe in der Konsole: `console.log("Hallo!")`

#### 3. **Network / Netzwerk**
- Zeigt alle geladenen Dateien
- Prüft, ob CSS/JS geladen wurde
- Hilfreich bei 404-Fehlern (Datei nicht gefunden)

#### 4. **Sources / Quellen**
- JavaScript debuggen
- Breakpoints setzen
- Code Schritt für Schritt durchgehen

---

## 5. Installation testen

### Test-Projekt erstellen:

1. **Ordner erstellen:**
   ```
   test-projekt/
   ├── index.html
   ├── css/
   │   └── style.css
   └── js/
       └── script.js
   ```

2. **index.html erstellen:**
   ```html
   <!DOCTYPE html>
   <html lang="de">
   <head>
       <meta charset="UTF-8">
       <meta name="viewport" content="width=device-width, initial-scale=1.0">
       <title>Setup Test</title>
       <link rel="stylesheet" href="css/style.css">
   </head>
   <body>
       <h1>Setup erfolgreich!</h1>
       <p>Wenn du diese Seite siehst und die DevTools öffnen kannst, ist alles korrekt eingerichtet.</p>
       <button id="testButton">Klick mich!</button>

       <script src="js/script.js"></script>
   </body>
   </html>
   ```

3. **css/style.css erstellen:**
   ```css
   body {
       font-family: Arial, sans-serif;
       max-width: 800px;
       margin: 50px auto;
       padding: 20px;
       background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
       color: white;
   }

   h1 {
       color: #fff;
   }

   button {
       background: white;
       color: #667eea;
       border: none;
       padding: 10px 20px;
       font-size: 16px;
       border-radius: 5px;
       cursor: pointer;
   }

   button:hover {
       background: #f0f0f0;
   }
   ```

4. **js/script.js erstellen:**
   ```javascript
   console.log("JavaScript erfolgreich geladen!");

   const button = document.getElementById('testButton');

   button.addEventListener('click', () => {
       alert("Alles funktioniert perfekt!");
       console.log("Button wurde geklickt!");
   });
   ```

5. **Testen:**
   - Rechtsklick auf `index.html` → Open in → Browser 
   - Seite sollte im Browser öffnen
   - DevTools öffnen (F12)
   - In der Konsole sollte "JavaScript erfolgreich geladen!" stehen
   - Button klicken → Alert sollte erscheinen

### Wenn alles funktioniert:
- Browser zeigt die Seite mit Styling
- Console zeigt die Nachricht
- Button löst Alert aus
- Änderungen werden automatisch neu geladen

**Herzlichen Glückwunsch! Du bist bereit für den Kurs!**


---

## Nächste Schritte

1. Installation abgeschlossen
2. Test-Projekt funktioniert
3. Beginne mit dem Kurs: [01-html-basics](../01-html-basics/)

---

## Tipps für den Alltag


### Best Practices:

1. **Speichere regelmäßig!** (`Cmd/Ctrl + S`)
2. **Nutze Auto Save** (siehe Einstellungen)
3. **Öffne die DevTools** bei jedem Test
4. **Lies Fehlermeldungen** in der Konsole
5. **Nutze Prettier** für sauberen Code

---

**Du bist jetzt bereit! Viel Erfolg im Kurs!**
