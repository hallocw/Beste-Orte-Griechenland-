# Schöne Orte in Griechenland

Diese Webseite stellt zehn wunderschöne Orte in Griechenland vor, einschließlich ausführlicher Beschreibungen und Empfehlungen für Aktivitäten, Restaurants und Sehenswürdigkeiten.

## Anforderungen

- HTML-Kenntnisse
- Texteditor (z.B. Visual Studio Code, Sublime Text, Notepad)

## Inhalt der Webseite

Die Webseite enthält Informationen zu folgenden Orten in Griechenland:

1. Athen
2. Santorini
3. Mykonos
4. Kreta
5. Delphi
6. Rhodos
7. Thessaloniki
8. Meteora
9. Nauplia
10. Korfu

Jeder Ort hat eine eigene Pastellfarbe und enthält Bilder, längere Beschreibungen und drei Empfehlungen für Aktivitäten und Sehenswürdigkeiten.

## Anleitung zur Einrichtung und Veröffentlichung

### 1. HTML-Datei erstellen

1. **Texteditor öffnen:**
   - Verwende einen Texteditor wie Visual Studio Code, Sublime Text oder Notepad.

2. **HTML-Code einfügen:**
   - Kopiere den HTML-Code von unten und füge ihn in den Texteditor ein.

3. **Datei speichern:**
   - Speichere die Datei als `index.html`.

### 2. Webseite lokal anzeigen

1. **Datei öffnen:**
   - Doppelklicke auf die `index.html` Datei, um sie in deinem Webbrowser zu öffnen und die Webseite lokal anzusehen.

### 3. Webseite mit einem kostenlosen Webhosting-Dienst veröffentlichen

#### Verwende Netlify:

1. **Netlify-Konto erstellen:**
   - Registriere dich bei [Netlify](https://www.netlify.com/).

2. **Neues Projekt erstellen:**
   - Klicke auf `Add new site` und wähle `Import an existing project`.

3. **Git Repository verbinden:**
   - Wähle die Plattform aus, auf der dein Code gehostet ist (GitHub, GitLab, Bitbucket).

4. **Repository auswählen:**
   - Wähle das Repository aus, das deine `index.html` Datei enthält.

5. **Einstellungen konfigurieren:**
   - Konfiguriere die Build-Einstellungen (bei statischen HTML-Seiten sind keine zusätzlichen Einstellungen notwendig).

6. **Deployment starten:**
   - Klicke auf `Deploy site`. Netlify wird deine Webseite automatisch bauen und veröffentlichen.

7. **Webseite ansehen:**
   - Deine Webseite wird unter einer Netlify-Subdomain verfügbar sein (z.B. `https://your-site-name.netlify.app/`). Du kannst auch eine benutzerdefinierte Domain hinzufügen.

### Beispiel HTML-Code

```html
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Schöne Orte in Griechenland</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #FFFFFF; /* Weißer Hintergrund */
            color: #333333; /* Dunkelgrau für Text */
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #00ACC1; /* Türkis */
            color: white;
            padding: 20px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .content {
            padding: 20px;
        }
        .location {
            margin-bottom: 40px;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .location:nth-child(1) { background-color: #B3E5FC; } /* Pastell Blau */
        .location:nth-child(2) { background-color: #D1C4E9; } /* Pastell Lila */
        .location:nth-child(3) { background-color: #F48FB1; } /* Pastell Rosa */
        .location:nth-child(4) { background-color: #FFAB91; } /* Pastell Rot */
        .location:nth-child(5) { background-color: #FFCC80; } /* Pastell Orange */
        .location:nth-child(6) { background-color: #FFF59D; } /* Pastell Gelb */
        .location:nth-child(7) { background-color: #C5E1A5; } /* Pastell Grün */
        .location:nth-child(8) { background-color: #B3E5FC; } /* Pastell Blau */
        .location:nth-child(9) { background-color: #D1C4E9; } /* Pastell Lila */
        .location:nth-child(10) { background-color: #F48FB1; } /* Pastell Rosa */
        .location img {
            width: 100%;
            height: auto;
            border-radius: 10px;
            margin-bottom: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        footer {
            background-color: #00ACC1; /* Türkis */
            color: white;
            text-align: center;
            padding: 10px 0;
            box-shadow: 0 -4px 8px rgba(0, 0, 0, 0.1);
        }
        a {
            color: #FFFFFF; /* Weiß */
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>Schöne Orte in Griechenland</h1>
    </header>
    <div class="content">
        <!-- Ort 1: Athen -->
        <div class="location">
            <h2>Athen</h2>
            <img src="https://www.example.com/athen.jpg" alt="Athen">
            <p>Athen, die Hauptstadt Griechenlands, ist eine Stadt voller Geschichte und Kultur. Mit ihrer reichen antiken Geschichte und einer pulsierenden modernen Atmosphäre ist Athen ein Muss für jeden Besucher Griechenlands. Hier können Sie die majestätische Akropolis besuchen, durch die malerischen Gassen von Plaka schlendern und die vielfältige kulinarische Szene genießen.</p>
            <h3>Empfehlungen:</h3>
            <ul>
                <li>Besuchen Sie die Akropolis und das Akropolismuseum, um in die antike Geschichte Griechenlands einzutauchen.</li>
                <li>Genießen Sie ein Abendessen im Restaurant "Strofi" mit einem atemberaubenden Blick auf die beleuchtete Akropolis.</li>
                <li>Erkunden Sie das Viertel Monastiraki mit seinen lebhaften Märkten und Geschäften.</li>
            </ul>
        </div>
        
        <!-- Ort 2: Santorini -->
        <div class="location">
            <h2>Santorini</h2>
            <img src="https://www.example.com/santorini.jpg" alt="Santorini">
            <p>Santorini ist eine der bekanntesten Inseln Griechenlands und ein beliebtes Ziel für romantische Ausflüge. Berühmt für seine atemberaubenden Sonnenuntergänge, die charakteristischen weiß getünchten Häuser und die blauen Kuppeln, bietet Santorini eine malerische Kulisse für unvergessliche Urlaubserinnerungen.</p>
            <h3>Empfehlungen:</h3>
            <ul>
                <li>Genießen Sie den Sonnenuntergang in Oia, einem der schönsten Dörfer der Insel.</li>
                <li>Besuchen Sie das Weingut Santo Wines und probieren Sie die lokalen Weine mit Blick auf die Caldera.</li>
                <li>Erkunden Sie die archäologische Stätte Akrotiri, eine der am besten erhaltenen minoischen Siedlungen.</li>
            </ul>
        </div>
        
        <!-- Ort 3: Mykonos -->
        <div class="location">
            <h2>Mykonos</h2>
            <img src="https://www.example.com/mykonos.jpg" alt="Mykonos">
            <p>Mykonos ist bekannt für seine lebhafte Partyszene, die schönen Strände und die charmante Altstadt. Die Insel zieht sowohl Ruhesuchende als auch Feiernde an und bietet eine Vielzahl von Aktivitäten und Erlebnissen.</p>
            <h3>Empfehlungen:</h3>
            <ul>
                <li>Feiern Sie in einem der berühmten Strandclubs wie "Paradise Beach Club" oder "Scorpios".</li>
                <li>Spazieren Sie durch die engen Gassen von Mykonos-Stadt und entdecken Sie die malerischen Windmühlen.</li>
                <li>Besuchen Sie das Restaurant "Kastro’s" für ein romantisches Abendessen direkt am Wasser.</li>
            </ul>
        </div>
        
        <!-- Ort 4: Kreta -->
        <div class="location">
            <h2>Kreta</h2>
            <img src="https://www.example.com/kreta.jpg" alt="Kreta">
            <p>Kreta, die größte Insel Griechenlands, bietet eine beeindruckende Vielfalt an Landschaften, von hohen Bergen bis hin zu idyllischen Stränden. Die Insel ist reich an Geschichte und Kultur und bekannt für ihre freundlichen Einheimischen und köstliche Küche.</p>
            <h3>Empfehlungen:</h3>
            <ul>
                <li>Besuchen Sie den Palast von Knossos, um mehr über die minoische Zivilisation zu erfahren.</li>
                <li>Wandern Sie durch die Samaria-Schlucht, eine der längsten Schluchten Europas.</li>
                <li>Genießen Sie ein traditionelles kretisches Essen im Restaurant "Peskesi" in Heraklion.</li>
            </ul>
        </div>
        
        <!-- Ort 5: Delphi -->
        <div class="location">
            <h2>Delphi</h2>
            <img src="https://www.example.com/delphi.jpg" alt="Delphi">
            <p>Delphi war in der Antike als das Zentrum der Welt bekannt und beherbergte das berühmte Orakel von Delphi. Die Ruinen dieser antiken Stadt liegen malerisch an den Hängen des Parnass-Gebirges und bieten einen beeindruckenden Blick auf die umliegende Landschaft.</p>
            <h3>Empfehlungen:</h3>
            <ul>
                <li>Erkunden Sie die archäologischen Stätten von Delphi, einschließlich des Apollon-Tempels und des antiken Theaters.</li>
                <li>Besuchen Sie das Archäologische Museum von Delphi, um Artefakte aus der antiken Stadt zu sehen.</li>
                <li>Genießen Sie ein Mittagessen im Restaurant "To Patriko Mas" mit traditioneller griechischer Küche und Panoramablick.</li>
            </ul>
        </div>
        
        <!-- Ort 6: Rhodos -->
        <div class="location">
            <h2>Rhodos</h2>
            <img src="https://www.example.com/rhodos.jpg" alt="Rhodos">
            <p>Rhodos, die größte Insel des Dodekanes, ist berühmt für ihre gut erhaltene mittelalterliche Altstadt, die zum UNESCO-Weltkulturerbe gehört. Mit ihren herrlichen Stränden und historischen Stätten bietet Rhodos eine perfekte Mischung aus Entspannung und Kultur.</p>
            <h3>Empfehlungen:</h3>
            <ul>
                <li>Erkunden Sie den Großmeisterpalast in der Altstadt von Rhodos.</li>
                <li>Entspannen Sie am Strand von Tsambika, einem der schönsten Strände der Insel.</li>
                <li>Genießen Sie frische Meeresfrüchte im Restaurant "Kerasma" in Rhodos-Stadt.</li>
            </ul>
        </div>
        
        <!-- Ort 7: Thessaloniki -->
        <div class="location">
            <h2>Thessaloniki</h2>
            <img src="https://www.example.com/thessaloniki.jpg" alt="Thessaloniki">
            <p>Thessaloniki, die zweitgrößte Stadt Griechenlands, ist bekannt für ihr lebendiges kulturelles Leben, ihre historische Bedeutung und ihre kulinarischen Köstlichkeiten. Die Stadt ist ein Schmelztiegel der Geschichte und bietet zahlreiche Sehenswürdigkeiten und Aktivitäten.</p>
            <h3>Empfehlungen:</h3>
            <ul>
                <li>Besuchen Sie den Weißen Turm, das Wahrzeichen der Stadt, und genießen Sie die Aussicht von oben.</li>
                <li>Erkunden Sie das Viertel Ladadika, bekannt für seine lebhaften Tavernen und Bars.</li>
                <li>Probieren Sie lokale Spezialitäten im Restaurant "Molyvos" mit einem fantastischen Blick auf das Meer.</li>
            </ul>
        </div>
        
        <!-- Ort 8: Meteora -->
        <div class="location">
            <h2>Meteora</h2>
            <img src="https://www.example.com/meteora.jpg" alt="Meteora">
            <p>Meteora ist bekannt für seine atemberaubenden Klöster, die auf hohen Sandsteinfelsen errichtet wurden. Diese UNESCO-Weltkulturerbestätte bietet eine einzigartige Kombination aus natürlicher Schönheit und spiritueller Erhabenheit.</p>
            <h3>Empfehlungen:</h3>
            <ul>
                <li>Besuchen Sie das Kloster Megalo Meteoro, das größte und bekannteste der Meteora-Klöster.</li>
                <li>Wandern Sie zu den verschiedenen Klöstern und genießen Sie die spektakulären Ausblicke auf die Felsenlandschaft.</li>
                <li>Genießen Sie ein traditionelles griechisches Essen im Restaurant "Meteoron Panorama" mit Blick auf die Felsen von Meteora.</li>
            </ul>
        </div>
        
        <!-- Ort 9: Nauplia -->
        <div class="location">
            <h2>Nauplia</h2>
            <img src="https://www.example.com/nauplia.jpg" alt="Nauplia">
            <p>Nauplia, eine charmante Küstenstadt auf dem Peloponnes, besticht durch ihre venezianische Architektur, malerische Gassen und die beeindruckende Festung Palamidi. Die Stadt ist ein idealer Ausgangspunkt, um die historischen Stätten der Region zu erkunden.</p>
            <h3>Empfehlungen:</h3>
            <ul>
                <li>Erklimmen Sie die Festung Palamidi und genießen Sie die herrliche Aussicht über die Stadt und das Meer.</li>
                <li>Spazieren Sie entlang der malerischen Hafenpromenade und genießen Sie die Atmosphäre.</li>
                <li>Probieren Sie traditionelle griechische Gerichte im Restaurant "Kastro Karima" mit Blick auf die Bucht.</li>
            </ul>
        </div>
        
        <!-- Ort 10: Korfu -->
        <div class="location">
            <h2>Korfu</h2>
            <img src="https://www.example.com/korfu.jpg" alt="Korfu">
            <p>Korfu, die grüne Insel im Ionischen Meer, ist bekannt für ihre üppige Vegetation, kristallklaren Strände und charmanten Dörfer. Die Insel bietet eine perfekte Mischung aus Entspannung, Abenteuer und Kultur.</p>
            <h3>Empfehlungen:</h3>
            <ul>
                <li>Besuchen Sie die Altstadt von Korfu, die zum UNESCO-Weltkulturerbe gehört, und erkunden Sie die engen Gassen und historischen Gebäude.</li>
                <li>Entspannen Sie am Strand von Paleokastritsa, einem der schönsten Strände der Insel.</li>
                <li>Genießen Sie ein Abendessen im Restaurant "Etrusco", das für seine innovative griechische Küche bekannt ist.</li>
            </ul>
        </div>
    </div>
    <footer>
        <p>Folge mir auf <a href="https://www.instagram.com/deinprofil" target="_blank">Instagram</a></p>
    </footer>
</body>
</html>
