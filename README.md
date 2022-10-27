# DIS01 Programmieren und Webentwicklung

## Generelle Informationen
Diese Webseite ist im Rahmen des Moduls DIS01.1 Programmieren und Webendwicklung endstanden.
Hierfür gab es besondere Prüfungsregularien, an welche wir uns halten sollten.

## Prüfungsregularien
### Ihre Website soll folgende formale bzw. technische Vorgaben erfüllen:
- Ihre Website soll enthalten:
a.	mindestens 9 HTML-Dateien, im zwei- oder dreispaltigen Layout mit einem horizontalen Menü zur Navigation durch diese Seiten
b.	jedes Dokument soll jeweils mindestens folgende HTML-Elemente enthalten: nav, main, footer, aside, figure, article, p,
c.	in jedem html-Dokument sollten ausserhalb des Menüs (nav-Element) mindestens je zwei interne und ein externer Hyperlink  vorhanden sein.
d.	eine Tabelle (mit mindestens 3 Spalten und 3 Zeilen)
e.	eine Aufzählung
f.	weitere sinnvolle HTML-Tags zur Binnen-Strukturierung der Texte (zur Auszeichnung von Überschrift, Zitat, Wichtigkeit, Abkürzung etc.)
g.	mindestens zwei Überschriftebenen pro Dokument
h.	zwei interaktive Elemente implementiert mit JavaScript nach folgenden Mustern
i.	
1.	Funktion 1 : Galeriefunktion oder Darstellungsänderung
Entweder:
Durch Klick auf ein Interaktionselement verschwindet ein Teil der Seite, und durch erneutes Klicken erscheint es wieder. 
Das Interaktionselement könnte bspw. ein Button oder ein Icon sein und der verschwindende Teil ein Text, ein Menü oder ein Bild.
Oder/ alternativ:
durch Javascript wird das Nachladen und Anzeigen einer Reihe von Bildern auf einer Seite interaktiv gesteuert.
vgl. z.B. https://css-tricks.com/snippets/javascript/showhide-element/ oder https://www.on-design.de/tutor/javascript/beispiele/gallery/index.html
2.	Funktion 2:  Zeichenzähler
Auf der Startseite Ihrer Miniwebsite wird nach einem Klick auf einen Button die Menge der dargestellten Zeichen (inkl. Leerzeichen) in allen Absätzen dieses Dokuments als Zahl ausgegeben.
Die Ausgabe dieser Zahl wird am Ende der Seite - strukturell im footer des DOMS-  mit dem einleitenden Text:
"Diese Seite enthält in den Absätzen "n" Zeichen."


- Alle anderen Layoutaspekte müssen ausschließlich mit CSS umgesetzt werden - Die Darstellungsregeln befinden sich in nur einer externen CSS-Datei.
- Verwenden Sie für die allgemeine Raumaufteilung Ihrer Seiten das Gridmodul.
Die zwei- bzw. dreispaltige Darstellung der Inhalte soll also über "display: grid" und weitere davon abhängige Deklaration umgesetzt werden.
- Verwenden Sie in Ihren Styles in jedem Falle auch folgende Eigenschaften:
width, padding, margin, border, color, background, font-family, font-size, font-weight, line-height, float, display, grid-template-areas
- Stellen Sie Schriftgrößen mit den Einheiten em, rem oder % ein.
- Verzichten Sie soweit wie möglich auf pixelbasierte Bemaßungen von Elementboxen, verwenden Sie stattdessen relative Einheiten wie em, %, vw etc.
- Das horizontale Menü soll (im Desktop Layout) aus nebeneinander angeordneten farbig hervorgehobenen Schaltflächen bestehen, die über CSS-Pseukoklassen einen Farbwechsel bei Mausberührung erhalten. (vgl. https://wiki.selfhtml.org/wiki/HTML/Tutorials/Links/Gestaltung_mit_CSS)
- Gewährleisten Sie, dass auf sehr schmalen Displays eine einspaltige Darstellung mit sinnvoller Reihung der Inhalte und angemessenen Bildgrößen ermöglicht wird. D.h. für den "Desktop" eine mehrspaltige Darstellung und für "mobile" kleinformatige Nutzungszenarien einspaltig
(verwenden Sie dazu das Gridmodul von CSS3; wenn nötig, implementieren Sie das flexible Layout nach Bedarf mit einer Medienabfrage).
- Integrieren Sie für die Darstellung der Überschriften einen innerhalb des Projekts gehosteten Webfont.
(siehe: https://t3n.de/news/google-fonts-selber-hosten-751438/) - berüchsichtigen Sie für die @font-face Regel nur moderne Browser und laden Sie nur die minimal nötigen Font-Ressourcen, die Sie für Ihr Layout brauchen.
- Bitte geben Sie in jeder HTML-Datei im Head als Kommentar Ihre vollständigen Namen und Matrikelnummern an.
- Auf der Stammebene Ihres Projektes befindet sich nur eine "index.html" als Startseite ("Homepage" als einleitende Begrüssungsseite). Weitere Dateien befinden sich in eigenen Unterordnern. Verwenden Sie für die Speicherung der Bilder und Fonts zwei separate Unterordner (d.h. Verzeichnisse) innerhalb ihres Projektordners und referenzieren Sie projektintern alle Ressourcen Dokument-relativ (d.h. mit relativen Pfaden)
- Bitte stellen Sie sicher, dass Sie nur dokument-relative Pfade verwendet haben, damit die Pfade auch nach dem Übertragen der Dateien auf einen anderen Rechner (auch offline, ohne Webserver) noch gültig sind


Erzeugen Sie ein ZIP-Archiv, das alle benötigten Dateien und Ordner enthält, also auch CSS-Dateien und Bild-Dateien. Bitte geben Sie ein ZIP-Archiv (ZIP-Datei) pro Gruppe ab, d.h. es soll nur ein Gruppenmitglied das ZIP-Archiv einreichen. Der Dateiname soll Ihre durch unterstriche getrennte Nachnamen enthalten ("niehaus_schulze_mueller.zip"), aber keine Umlaute, ß oder Leerzeichen enthalten, also bspw. mueller_schmidt_krue.zip. Der Dateityp, die Sie abgeben, muss unbedingt ein ZIP-Archiv sein und die Endung .zip haben. Andernfalls gilt die Aufgabe als nicht bestanden.
Laden Sie die ZIP-Datei bitte bis einschließlich 15. März 2021 (23.59h) hier auf Moodle hoch.
Geben Sie Ihre Dateien nicht an andere Gruppen weiter. Die Weitergabe von Dateien an Studierende außerhalb Ihrer Gruppe stellt einen Täuschungsversuch dar und führt zum Nicht-Bestehen.
Sie sollten im Stande sein, Ihren Code auf Nachfrage zu erklären. Einige Gruppen müssen ein Gespräch über Ihre Website absolvieren, das im April stattfindet. Hier soll überprüft werden, ob die Gruppe die Website selbst erstellt hat und ob alle Gruppenmitgleider aktiv mitgearbeitet haben.
- Kriterien zur Bewertung der Qualität des Quellcodes
Allgemein
- Sinnvolle Dateiorganisation (Verzeichnis- und Dateinamen kurz, sinnvoll, kleingeschrieben, ohne Leer- und Sonderzeichen)
- Standardkonformität: sachgerechte und valide Umsetzung gemäß aktueller W3C Spezifikation ("Recommendations" für CSS3, HTML5)
- konsequente Trennung von Inhaltsstruktur, Darstellung und Verhalten (kein Inline-Styling, keine "presentational" Elemente in HTML, Vermeidung unnötiger HTML-Strukturen ohne inhaltliche Funktion)
- Dokumentation:
Verwenden Sie Kommentare, die die Pflege des Codes ("maintainability") erleichtern und ihre Vorgehensweise verständlich machen.
- Code einheitlich aufräumen: gut lesbarer, logisch aufgebauter Code (einheitliche Einrückungen und Umgang mit Leerzeilen und Zeilenschaltungen) 
- Konsistenz: "Gleiches gleich behandeln": gehen Sie einheitlich vor z.B. in der Strukturierung der Inhalte, bei der Vergabe von Attributen, im Selektorbau und bei der Anwendung von CSS-Eigenschaften.
- Insb. in CSS: Redundanz bzw. Wiederholungen sind zu vermeiden. Die Nutzung von Kaskade und Vererbung sowie sinnvoller Selektoren ermöglichen gezielten und sparsamen Code.
### HTML
•	xml-kompatible Syntax (d.h. "ausführliche" xHTML-Schreibweise von Elementen und Attributen) verwenden:
https://en.wikipedia.org/wiki/Polyglot_markup sowie
https://wiki.selfhtml.org/wiki/HTML/Unterschiede_von_HTML_zu_XHTML
(Wichtig: Kleinschreibung von Elementen und Attributen, selbstschliessende "leere Elemente", alle Elemente explizit schließen, Attributwerte in Anführungszeichen)
•	Sparsamkeit: Weglassen unsemantischer Elemente und überflüssiger Strukturen ("div-Suppe"); (ebenso auch: gezielter, sparsamer Umgang mit class- und id-Attributen.)
•	Verwenden Sie semantisch sinnvolle und ausdrucksstarke Strukturelemente.
•	Wählen Sie ausdrucksstarke Werte für IDs und Classes.
•	Schaffen Sie eine inhaltlich angemessene Strukturtiefe, um die Inhalte klar und sinnvoll zu kennzeichnen.
### CSS
•	Sparsamkeit
- Wiederholungen vermeiden
- Unnötige Widersprüche und unnötiges Überschreiben vermeiden
- Jede Deklaration sollte eine zielgerichtete Funktion haben.
- Gute Lesbarkeit des Codes (konsistente Einrückungen, neue Zeilen etc.,)
- Regeln nach Themen gruppieren und kommentieren
(in den Themenblöcken können Sie dann die Regeln "von Außen nach Innen", bzw. vom "Allgemeinen zum Speziellen" sortieren)
- Spezifität von Selektoren gering halten:
Verwenden Sie Selektoren mit möglichst niedriger Spezifität. Kombinatoren helfen dabei. Gehen Sie mit Class- und ID-Selektoren sparsam um.
https://css-tricks.com/strategies-keeping-css-specificity-low/
- Selektoren zusammenfassen:
Deklarationen, die für mehrere Elemente gelten, sollen nur einmal angegeben werden oder durch Vererbung wirksam werden.
- Nutzung von Vererbung und Kaskade
(auch hier ist das Ziel: Sparsamkeit und die Vermeidung unnötiger Deklarationen)
- Im Zweifelsfalle:
Richten Sie sich (wo für Ihr Projekt anwendbar) nach den Empfehlungen von MDN zur Erstellung guter CSS-Codebeispiele
https://developer.mozilla.org/en-US/docs/MDN/Contribute/Guidelines/Code_guidelines/CSS
- vgl. zum Thema Codequalität allgemein auch 
https://code.tutsplus.com/tutorials/top-15-best-practices-for-writing-super-readable-code--net-8118
### JS

-	Bevorzugen Sie "modernes JavaScript". Aus historischen Gründen enthält die Sprache diverse alte Objekte und Methoden, die heute nicht mehr (oder wenigier ) zeitgemäß sind. Im zweifel Orientieren Sie sich an den Möglichkeiten und Empfehlungen die mit ECMAScript 6 (seit 2015) gegeben sind.
-	Konsistenz, Transparenz, Logik in Aufbau und Syntax
-	Effizienz, leichte Anpassbarkeit und Erweiterbarkeit.
-	Dokumentation: Kommentieren Sie Ihren Code.
Erklären Sie in js-Kommentaren die Funktion aller Variablen, jedes Statements und jeder Funktion Ihres Scripts.
Eine detaillierter Kommentar für "best Practices ", d.h. für guten HTML, CSS- und JS-Code findet sich unter:
https://learn.shayhowe.com/html-css/writing-your-best-code/
Dies kann als allgemeine Richtlinie für ihre Hausarbeit gelten.
