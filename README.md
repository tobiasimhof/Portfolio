# Portfolio

Portfolio von **Tobias Imhof**: Sportfotografie und Videografie. Die Seite ist der Link
im Lebenslauf für die Bewerbung um eine **Ausbildung zum Mediengestalter Bild und Ton**,
ein Wechsel aus dem jetzigen Beruf heraus. Die Startseite zeigt den Namen, einen Satz
aus Fakten, **ein Standbild** und die zwei Kacheln Fotografie und Videografie. Seit v64
ist es ein **Standbild aus dem Rheinhessen-Clip** (Weintrauben im Gegenlicht,
schwarzweiß), damit der erste Eindruck „Bild und Ton“ sagt. Die Startseite ist damit
ganz schwarz und weiß, die Farbe kommt erst auf der Fotografie-Seite. Weil die
Aufnahmen von Pixabay sind, steht darunter die Quelle.

Live unter **https://tobiasimhof.github.io/Portfolio/** (GitHub Pages aus `main`).

**Herkunft:** Bis zur Version 71 lag das Portfolio zusammen mit der Lern-App
**ColorGrade** im Repo `colorgrade`. Dort ist es entstanden, die Versionen v45 bis v71
stehen unten unter „Vorgeschichte“. Seit der Trennung (Portfolio **v1** hier, ColorGrade
**v72** dort) gehört das Portfolio allein Fotografie und Videografie. Die App ist kein
Teil der Bewerbungsseite mehr, es gibt keine Apps-Kachel und keinen Link dorthin.

**Regel für das Bild auf der Startseite (v59, aus Nutzer-Feedback):** **Kein einzelner
Mensch im Bild.** Er wird für den Bewerber selbst gehalten, das hat der Nutzer beim
Torwartbild aus v58 sofort so gelesen. Von v59 bis v63 stand deshalb ein Zweikampf dort,
seit v64 die Trauben ohne Menschen.
Und es bleibt **klein** (280 px), sonst wirkt die Seite wie ein reines Fotoportfolio,
während die Bewerbung auf Mediengestalter Bild **und Ton** läuft.

**Über mich und Kontakt stehen bewusst nicht auf der Seite.** Wer den Link
anklickt, hat den Lebenslauf offen, dort stehen Werdegang und E-Mail bereits. Ein
zweites Mal wirkt es wie Füllmaterial, und die Startseite soll in zwei Sekunden
sagen, was es zu sehen gibt.

**Jede Seite hat denselben Kopf:** links der Name **Tobias Imhof**, der zur Startseite
führt, rechts die Navigation Fotografie · Videografie. Wer eine Seite ergänzt, baut
diesen Kopf mit ein.

**Was über den Nutzer bekannt ist** (für Texte auf der Seite): Schwerpunkt
Sportfotografie, ehrenamtlich für das Sportportal **FuPa**, liefert dort an
Spieltagen Bilder. Videografie ist neu und wird gerade erarbeitet. Nachname
**Imhof**, seit v56 steht er auf der Startseite. Noch offen und nicht erfinden:
jetziger Beruf und die Ausrüstung über „Nikon D3400, Telezoom" hinaus. Eine
E-Mail-Adresse braucht die Seite nicht.

**Herkunft des Videomaterials:** Den **Match Cut** hat der Nutzer selbst gedreht. Die
Aufnahmen im **Rheinhessen-Clip** („Atmosphäre auf den Beat“) sind **von Pixabay**,
bewusst gutes Material, um Schnitt und Rhythmus zu üben. Auswahl, Schnitt und
Schwarzweiß sind seine Arbeit. Das steht seit v63 offen auf der Karte, und so bleibt es:
**Fremdes Material wird auf der Seite immer benannt.** Deshalb trägt auch das Standbild
auf der Startseite eine Zeile „Aufnahmen: Pixabay“.

> **Für Claude / neue Chats:** Diese README ist der aktuelle Projektstand **und**
> die Arbeitsanleitung. Lies sie zuerst. Vier Regeln sind Pflicht:
> **(1)** `service-worker.js` die Cache-Version um eins hochzählen (`portfolio-vN`),
> **(2)** unten im **Änderungsverlauf** eine Zeile ergänzen, **(3)** keine
> Gedankenstriche im Text, **(4)** **keine privaten Daten auf die Seite**: Vor- und
> Nachname genügen, keine Anschrift, keine Telefonnummer, keine E-Mail. Das Repo ist
> öffentlich, alles darin ist lesbar.

## Stand

> Stand nach **v2** (seit v1 getrennt von ColorGrade): Startseite mit Name, einem Satz, dem
> Standbild und zwei Kacheln. Fotografie-Galerie mit sieben Bildern und Lightbox,
> Videografie mit zwei Clips, 404-Seite, Link-Vorschau, eigene Schrift (Archivo),
> Icon „PF“. Der Feinschliff-Fahrplan aus der Zeit in `colorgrade` ist durch. Offen
> ist nichts, neue Punkte kommen nur noch aus dem Feedback des Nutzers.

> hängen an einem Drehtermin, die Optik nicht. Was am Erscheinungsbild noch offen
> ist, steht unter „Erscheinungsbild".

**Leitlinie des Nutzers für alle Texte:** Ein Personaler klickt sich durch, er liest
nicht. Also kurz halten, keine Absätze, die nach Werbung oder nach KI klingen. Im
Zweifel weglassen statt ausformulieren.

**Und keine Motivation auf der Seite.** Das Warum steht im Anschreiben, doppelt
klingt es nach „ich will das unbedingt". Auf der Seite stehen Fakten: was gemacht
wurde, womit, für wen. Die einzige Ausnahme ist der eine Satz am Kontakt, dass eine
Ausbildung zum Mediengestalter Bild und Ton gesucht wird.


**Schritt 2 · Fotografie** (Galerie steht seit v52, sechs Bilder seit v55)
Sechs Bilder liegen in `assets/img/`. Ganz oben steht seit v53 das **Querformat als
Aufmacher** ohne Überschrift, darunter drei Abschnitte: **Der Moment** (Schuss,
Zweikampf), **Die Menschen** (Torwart, Trainer) und **Das Porträt** (Spielerporträt
allein, `.shots.solo`). Seit v60 folgt darunter **Die Mannschaft** als breites Schlussbild. Lightbox mit
Pfeiltasten und Escape ist gebaut. Die Fotografie-Seite ist damit **fertig**, sieben
Bilder.

**Korrektur am alten Plan:** In der README stand, das Mannschaftsfoto solle als 4:5 in
den Abschnitt „Das Porträt" und dort eine Zweierreihe bilden. Der Nutzer hat es im
**Querformat** aufgenommen und 16:9 geschnitten, und das ist richtig so, eine
Mannschaft in drei Reihen gehört ins Querformat. Ein breites Bild nimmt in der Galerie
die volle Satzbreite, also bekam es einen eigenen Abschnitt am Ende. Das Spielerporträt
bleibt allein stehen.

Regeln, die der Nutzer selbst erarbeitet hat und die für Nachschub gelten:
Hochformate **durchgehend 4:5**, Querformate **16:9**, Schwarzpunkt unter 12,
Weißpunkt über 245, **kein Farbkanal über 2 Prozent am Anschlag** (das sieht man im
Helligkeits-Histogramm nicht, kostet aber unwiederbringlich Zeichnung) und bei
Menschen im Bild **Hautton R minus G zwischen 35 und 40**. Bearbeitet wird in Snapseed, ein Look wird über
Kopieren/Einfügen auf alle Bilder übertragen, damit die Galerie eine Handschrift
hat. Der Firmenlauf ist nach Absprache raus.

Neue Bilder kommen über `scripts/make_photos.py` herein: Quelldatei in die
`BILDER`-Tabelle eintragen, Skript mit dem Quellordner aufrufen, fertig. Es legt je
Bild eine 1600er Fassung für die Lightbox und eine 800er Kachel an. Breite Bilder
(`breit = True`) bekommen nur die 1600er, weil sie die volle Satzbreite von 860 px
füllen und eine 800er Kachel dort hochskaliert würde.

**Das Mannschaftsfoto ist am 22.09.2026 bei Flutlicht entstanden** (Nikon D3400,
25 mm, 1/50 s, f/6,3, ISO 6400). Der Aufnahme-Brief unten hat sich bewährt und bleibt
als Anleitung für den nächsten Flutlicht-Termin stehen. Besonders die Zeit: 1/50 s hat
die 100-Hertz-Pulsation sauber ausgemittelt, kein Streifen im Bild. Auch die
Lichtrichtung stimmte, die Hauthelligkeit lag über alle drei Reihen bei 134, 126 und
134, also praktisch gleich. Genau daran scheitern die meisten Flutlichtbilder:

- **RAW aufnehmen.** Alle bisherigen Dateien sind Kamera-JPEGs. Unter Flutlicht ist
  der Weißabgleich nicht vorhersagbar (Halogenmetalldampf zieht grün, LED je nach
  Hersteller anders). Aus RAW ist der Farbstich verlustfrei zu korrigieren, aus JPEG
  nicht. Snapseed kann RAW entwickeln.
- **Zeit 1/100 oder 1/50 Sekunde.** Netzfrequenz 50 Hertz, Flutlicht pulsiert also
  mit 100 Hertz. Bei 1/125, 1/160 oder 1/200 schwankt die Helligkeit von Bild zu Bild
  und es entstehen Farbstreifen. Eine stehende Mannschaft braucht keine kurze Zeit.
- **Stativ**, **Blende f/5,6** (Schärfentiefe für zwei Reihen), **ISO so niedrig wie
  möglich** (D3400 gut bis 1600, brauchbar bis 3200; sonst lieber auf 1/50 runter).
- **Lichtrichtung beachten:** Flutlicht steht hoch und wirft harte Schatten in die
  Augenhöhlen. Nicht direkt unter den hellsten Mast stellen. Masten und Lampen aus
  dem Bild halten, die brennen aus.
- **15 bis 20 Auslösungen**, einer blinzelt immer.

Danach wie alle anderen: Schwarzpunkt unter 12, Weißpunkt über 245, kein Kanal über
2 Prozent am Anschlag, Hautton R minus G zwischen 35 und 40. Beschnitt 16:9 bei einer
Gruppe, 4:5 bei einem Einzelnen.

**Schritt 3 · Videografie** (Texte seit v48, beide Clips seit v62, **fertig**)
Die zwei Übungen sind beschrieben: „Atmosphäre auf den Beat" (Schnitt auf den Takt,
Zeitlupe) und „Match Cut im Wohnzimmer" (Anschlüsse, allein gedreht). Beide laufen:
`assets/video/beat.mp4` (9,3 MB) und `assets/video/match-cut.mp4` (5,4 MB), Vorschaubilder
daneben in `assets/img/` als `*-poster.webp`. Der Hinweiskasten ist raus, die Klasse
`.note` samt CSS mit.

So kommt ein Clip herein, damit der nächste gleich aussieht:
- **Webfassung mit ffmpeg:** `ffmpeg -i quelle.mp4 -c:v libx264 -preset slow -crf 23
  -profile:v high -pix_fmt yuv420p -movflags +faststart -c:a aac -b:a 96k ziel.mp4`.
  Aus 23 MB Canva-Export (8 Mbit/s) wurden so 5,4 MB bei SSIM 0,987, also sichtbar
  gleich. **Ziel 5 bis 10 MB je Clip**, sonst lädt es am Handy über Mobilfunk zäh.
  Körniges Material braucht mehr: Der Schwarzweiß-Beat-Clip kam mit CRF 23 auf 14,8 MB,
  darum **CRF 26** (9,3 MB, SSIM 0,979). Ab 28 wird es in den hellen Gegenlichtflächen
  flächig.
  `+faststart` ist Pflicht: Es stellt den Index an den Dateianfang, sonst muss der
  Browser erst die ganze Datei laden, bevor das erste Bild kommt.
- **ffmpeg fehlt im Container.** `pip install imageio-ffmpeg` bringt eine fertige
  Programmdatei mit.
- **Vorschaubild** als WebP aus einem ruhigen Bild des Clips, bei `preload="none"` ist
  es das Einzige, was vor dem Klick lädt. Beim Match Cut bewusst ein Bild ohne nackte
  Füße (die Schuhe, wie sie hingestellt werden), damit der erste Eindruck die Übung
  ist und nicht der Mensch.
- **Vorher durchsehen**, bei Drehs zu Hause besonders: nichts mit Anschrift, keine
  Post, keine Familienfotos im Bild. Beim Match Cut geprüft, nichts gefunden.
- **Testen:** Playwrights Chromium hat **keinen H.264-Decoder** (`canPlayType` leer,
  Fehlercode 4). Das ist kein Fehler der Datei, Chrome, Safari und Firefox spielen sie.
  Die Datei darum mit `ffmpeg -v error -i clip.mp4 -f null -` prüfen.
- Der Ton des Match Cuts ist leise (Mittel −37 dB, Spitze −26 dB), das ist Raumton
  aus dem Wohnzimmer und so gelassen.

**Schritt 5 · Feinschliff: der Fahrplan zur seriösen Seite** (festgelegt in v65, sieben Punkte)
Inhalte sind fertig, ab hier geht es nur noch um den Eindruck. Reihenfolge: erst was
ohne Entscheidung des Nutzers geht, dann was eine kleine Entscheidung braucht, zum
Schluss das Aufwendige. Abhaken, wenn erledigt:

1. **404-Seite**, **erledigt in v65.** `404.html` im Wurzelordner, GitHub Pages liefert
   sie für jede falsche Adresse aus. Gleicher Kopf, ein Satz, die Kacheln.
   **Pflicht:** `<base href="/Portfolio/">`, sonst zeigen die Pfade bei einer falschen
   Adresse wie `/Portfolio/a/b/c` ins Leere. Heißt das Repo einmal anders oder kommt
   eine eigene Domain, muss diese Zeile mit.
2. **Link-Vorschau (Open Graph)**, **erledigt in v66.** Wird ein Link per Mail,
   WhatsApp oder Teams geteilt, erscheint eine Karte mit Bild, Titel und Satz. Jede
   Seite hat ihr eigenes Bild in `assets/og/` (1200 × 630, JPEG, weil nicht jeder
   Dienst WebP liest): Startseite die Trauben, Fotografie das Laufduell, Videografie
   die Titeltafel „Rheinhessen“. Alle
   Adressen absolut auf `https://tobiasimhof.github.io/Portfolio/`, **bei einem neuen
   GitHub-Namen oder einer eigenen Domain müssen alle `og:`-Zeilen mit.** WhatsApp
   merkt sich eine Vorschau lange, wer sie neu sehen will, hängt `?1` an den Link.
3. **Eckige Fotos**, **gebaut in v67** (Erscheinungsbild Punkt 3). Die 12 px Rundung an Fotos und Clips
   raus oder auf 2 px. Eine CSS-Zeile, Nutzer sieht vorher und nachher.
4. **Ruhigere Oberfläche**, **gebaut in v68** (Punkte 4 und 5): Karten ohne Rahmen und hellen Grund,
   Zwischenüberschriften normal statt grauer Versalien. Betrifft alle Seiten, mit
   Screenshots abstimmen.
5. **Akzent zurücknehmen**, **gebaut in v67**: Das Orange (`#ff9f45`) steht noch an Rollen-Zeilen und
   aktiven Knöpfen. Auf Weiß oder Grau stellen, dann tragen allein die Bilder Farbe.
6. **Favicon und App-Icons neu**, **gebaut in v68.** Entscheidung des Nutzers:
   **„TI“**, weiß auf Schwarz, in Archivo 700 bei 86 % Breite wie die Überschriften.
   `scripts/make_icons.py` liest die Umrisse direkt aus der Schriftdatei (fontTools,
   `pip install fonttools brotli`) und zeichnet ohne Bildbibliothek, ein Lauf erzeugt
   alle PNGs plus `icons/favicon.svg`. Wer die App schon installiert hat, sieht das
   neue Icon erst nach einmal Entfernen und neu Hinzufügen, das Betriebssystem merkt
   sich das alte.
7. **Archivo auch in der App**, gebaut in v69. Betrifft nur ColorGrade, Einzelheiten
   stehen in dessen README.

**Kein Punkt auf dem Fahrplan: Impressum.** Für eine rein private Bewerbungsseite ohne
geschäftlichen Zweck gilt die Impressumspflicht in der Regel nicht, und eine Anschrift
widerspräche der Regel „keine privaten Daten“. Wird die Seite einmal gewerblich (Aufträge
als Fotograf), neu prüfen.

**Erscheinungsbild** (analysiert in v55, Punkt 1 erledigt in v56)
Der Nutzer findet, dass Schrift, Aufmachung und Bedienelemente „nach KI" aussehen. Die
Analyse hat sechs konkrete Ursachen ergeben, damit der nächste Chat sie nicht neu
herleiten muss:

1. **Der System-Font-Stack**, **erledigt in v56.** Er war der größte Verräter, weil
   jede generierte Seite genau den benutzt. Das Portfolio läuft jetzt auf **Archivo**,
   seit v57 in schmaler Breite.
   **Die App ist seit v69 auch auf Archivo**, mit geprüften SVG-Texten.
2. **Der Regenbogen-Punkt** als Marke (`.dot`, conic-gradient), **erledigt in v59**,
   **das Farbrad der Icons in v68.**
   Die Marke ist jetzt nur noch der Schriftzug **ColorGrade**, auf allen Seiten und in
   der App. **Offen ist der gleiche Punkt an einer zweiten Stelle:** Die App-Icons unter
   `icons/` sind ein HSV-Farbrad (`scripts/make_icons.py`). Wer die App installiert hat,
   sieht es weiter auf dem Startbildschirm. Neues Zeichen erfordert eine Entscheidung
   des Nutzers, das Skript erzeugt die Icons dann in einem Lauf neu.
3. **16 px runde Ecken an allem**, auch an den Fotos. **Fotos erledigt in v67.** Runde Bildecken lesen sich als
   App-Oberfläche, nicht als Fotografie.
4. **Jeder Block ist eine umrandete Karte** (1 px Rahmen, runde Ecken, hellerer
   Hintergrund). Standard-Optik von Dashboard-Templates. **Erledigt in v68.**
5. **Graue Versalien-Überschriften** (`.sec-h`). Gleiche Herkunft. **Erledigt in v68.**
6. **Strich-Icons** auf den Startseiten-Kacheln (Lucide-Look), **erledigt in v58.**
   Die Kacheln tragen jetzt nur noch den Begriff, dafür groß.

**Gemeinsamer Nenner:** Die Oberfläche macht zu viel Lärm um die Fotos herum. Ein
Fotoportfolio wird professionell, wenn die Bedienelemente fast verschwinden und die
Bilder die einzige Farbe im Layout sind.

**Messung:** Die kräftigen Farben in den sechs Bildern sind Blau (220 Grad, 26 %,
das Vereinstrikot), Grün (80 Grad, 7 %, der Rasen) und Rot (10 Grad, 4 %). Der
Akzent der Seite ist Orange `#ff9f45` und kommt in keinem Bild vor. **Trotzdem nicht
gegen Blau tauschen**, sondern den Akzent überhaupt zurücknehmen.

**Die Schrift ist seit v56 gesetzt: Archivo** (Omnibus-Type, SIL Open Font License),
eine Groteske aus der Zeitungsecke, hohe x-Höhe, schmale Formen, keine Verzierungen.
Seit v57 liegt die Fassung mit **zwei Achsen** im Repo, Gewicht 400 bis 700 und Breite
62 bis 125 Prozent, zusammen 90 KB unter `assets/fonts/`, vorgeladen in jeder Seite.
Kein Google Fonts: Die Regel „keine externen Schriften" zielt auf den Datenschutz, eine
Datei auf derselben Domain verletzt sie nicht.

**Die Breite ist die Stellschraube für „edel":** Sie hängt an zwei Variablen oben in
`assets/style.css`, `--w-head` (Überschriften und Bedienelemente, steht auf 86 %) und
`--w-text` (Fließtext, 96 %). Eine Zahl ändern und die ganze Seite wird schmaler oder
breiter, ohne dass ein Layout nachgezogen werden muss. Unter etwa 80 % kippt es vom
Edlen ins Plakathafte, das war die Abwägung. **Pflicht:** Die Spanne
`font-stretch: 62% 125%` muss im `@font-face`-Block stehen, sonst greift `font-stretch`
an den Elementen nicht.

**Keine Unterschrift auf der Seite** (entschieden in v66): Sie steht schon in der
Bewerbung, doppelt braucht es sie nicht.

**Lehrstück aus der Bearbeitung des Mannschaftsfotos (v60):** Das Bild kam mit einem
**Weißpunkt von 232** aus der Kamera, es gab also kein echtes Weiß, und der **Rotkanal
lag in 4,16 Prozent der Pixel auf null** (in der Spielerzone sogar 4,72), wodurch die
tiefen Schatten ins Kühle kippten. Beides sieht man im Helligkeits-Histogramm nicht.
Behoben über zwei Griffe in den Kurven: rechter Endpunkt der RGB-Kurve nach links
(Weißpunkt jetzt **254**) und linker Endpunkt der **Rotkurve** leicht angehoben (Rot
auf null jetzt **0,15 Prozent**). Die Haut wurde dabei um 13 Stufen wärmer, R minus G
von 30 auf 43 gemessen an denselben Pixeln. **Zwei Merksätze:**
**(1)** Bei hohem ISO steigt mit jeder Aufhellung das Korn mit, hier von 5,8 auf 7,1
Standardabweichung in den flachen Flächen. Beim Verkleinern auf die 1600er Fassung
verschwindet es wieder, man darf es also **nicht bei 100 Prozent beurteilen**, sonst
überkorrigiert man.
**(2)** **Korn kostet Dateigröße.** Mit der Normalqualität 82 wog die WebP-Datei
448 KB, mit 74 sind es 325 KB, und der Unterschied liegt im Gesichtsband bei im Mittel
3,9 Helligkeitsstufen, fällt also aufs Rauschen und nicht auf die Gesichter. Dafür hat
`scripts/make_photos.py` seit v60 eine **Qualitätsangabe je Bild**.

**Standbild aus einem Clip auf der Startseite:** erledigt in v64. Der erste Eindruck
sagt damit „Bild und Ton“ statt nur „Bild“.


## Arbeitsweise (wichtig für neue Chats)

- **Aufbau:** mehrere kleine Seiten im Wurzelverzeichnis mit einem gemeinsamen
  `assets/style.css`. Keine Build-Tools, kein Framework.
- **Live gehen:** GitHub Pages veröffentlicht von **`main`** (Repo-Einstellungen →
  *Pages* → Source `Deploy from a branch`, Branch `main`, Ordner `/ (root)`). Jede
  fertige Änderung auf dem zugewiesenen Feature-Branch committen, dann per
  **Fast-Forward in `main`** mergen und `main` pushen; den Feature-Branch nachziehen.
- **Schreibweise (Nutzer-Vorgabe):** **keine Gedankenstriche** im Text. Statt eines
  Strichs mitten im Satz ein Komma, einen Doppelpunkt oder einen neuen Satz setzen.
  Gilt für Seitentexte, Commit-Nachrichten und diese README. Zahlenbereiche
  als „18 bis 55 mm". Werbliche KI-Sätze vermeiden.
- **Privatsphäre:** Keine Anschrift, keine Telefonnummer, keine Tracker, keine externen
  Schriften. Alle Seiten tragen `<meta name="robots" content="noindex" />`. Das ist eine
  bewusste Entscheidung, damit die Seite nur über den Link im Lebenslauf erreicht wird.
- **Zwischenspeicher, zwei Ebenen:** GitHub Pages liefert mit `Cache-Control: max-age=600`
  aus. Deshalb holt der Service-Worker Seiten ausdrücklich frisch (`cache: 'reload'`),
  und eine neue Fassung lädt offene Fenster einmal selbst neu. Wer sofort nach dem Push
  nachsieht, prüft am besten in einem privaten Fenster.
- **Cache-Version:** Nach **jeder** inhaltlichen Änderung die Konstante `CACHE` in
  `service-worker.js` um eins hochzählen (`portfolio-vN`). Neue Dateien zusätzlich in
  die `ASSETS`-Liste eintragen. Videos bleiben draußen, sie laufen am Service-Worker
  vorbei (Range-Anfragen, sonst spielt Safari sie nicht).
- **Adresse:** Ändert sich der Repo-Name oder kommt eine eigene Domain, müssen
  `<base href>` in `404.html` und alle `og:`-Zeilen mit.
- **Testen vor dem Push:** Chromium ist vorinstalliert, Playwright global unter
  `/opt/node22/lib/node_modules`. Lokal `python3 -m http.server 8099` starten, dann jede
  Seite in 1280 und in 390 Pixel Breite laden und prüfen auf: HTTP 200, keine
  Konsolenfehler, kein horizontales Scrollen
  (`document.documentElement.scrollWidth > window.innerWidth`).

## Dateien

| Datei | Zweck |
|-------|-------|
| `index.html` | Startseite: Name, ein Satz, ein Standbild, zwei Kacheln |
| `fotografie.html` · `video.html` | die Unterseiten |
| `404.html` | Fehlerseite für falsche Adressen, mit `<base href="/Portfolio/">` |
| `assets/style.css` | gemeinsames Design aller Seiten |
| `assets/img/` · `assets/video/` | Bilder und Clips (Clips als H.264-MP4, 5 bis 10 MB) |
| `assets/og/` | Vorschaubilder für geteilte Links, eins je Seite (1200 × 630) |
| `assets/fonts/` | Archivo als variable WebFont-Datei (Gewicht und Breite) plus OFL-Lizenz |
| `manifest.webmanifest` | Manifest |
| `service-worker.js` | Offline-Cache (Version hier hochzählen) |
| `icons/` | Icons „PF“ (aus `scripts/make_icons.py` erzeugt, Buchstaben in `TEXT`) |
| `scripts/make_icons.py` | erzeugt die Icons neu (fontTools, liest die Archivo-Datei) |
| `scripts/make_photos.py` | macht aus den Originalfotos die WebP-Dateien der Galerie, mit Qualitätsangabe je Bild |

## Änderungsverlauf

> **Regel:** Jede Änderung zählt die Cache-Version (`service-worker.js`) um eins hoch
> und bekommt hier genau eine Zeile. Neueste oben.

| Version | Was |
|---------|-----|
| **v2** | **Icon „PF“ statt „TI“** (Nutzer-Wunsch): Das Portfolio hatte dasselbe Icon wie ColorGrade, am Tablet scheiterte die Installation vermutlich an der alten, gleich aussehenden Verknüpfung. `TEXT` in `scripts/make_icons.py` auf „PF“, alle PNGs und `favicon.svg` neu erzeugt. ColorGrade behält „TI“. Wer das Portfolio schon installiert hat, sieht das neue Icon erst nach Entfernen und neu Hinzufügen. |
| **v1** | **Eigenes Repo.** Das Portfolio ist aus `colorgrade` (Stand v71) herausgelöst. Übernommen: Startseite, Fotografie, Videografie, 404-Seite, `assets/` ohne das App-Vorschaubild, Icons, beide Skripte. Die Apps-Kachel und der Link „Apps“ im Kopf sind raus, die Startseite hat zwei Kacheln (auch am Rechner nebeneinander, `.tile.wide` entfällt). Die Marke im Kopf heißt jetzt **Tobias Imhof** statt ColorGrade. Satz auf der Startseite ohne die App: „Sportfotografie für das Portal FuPa und erste eigene Videoarbeiten.“ Alle `og:`-Adressen und `<base href>` auf `/Portfolio/`, Cache heißt `portfolio-v1`, Manifest „Tobias Imhof · Portfolio“. |

### Vorgeschichte im Repo `colorgrade` (v45 bis v71)

Die Zeilen sind unverändert übernommen. Was darin die App betrifft, gilt nur noch für
ColorGrade.

| Version | Was |
|---------|-----|
| **v71** | **App-Etiketten ohne Versalien**, wie im Portfolio seit v68. Alle 17 Regeln mit `text-transform: uppercase` in einem Block am Ende des App-CSS überschrieben, Originale unangetastet: Zwischenüberschriften („Das bewegte Bild · die Technik“, „Motiv abheben · 3 Trennungs-Achsen“) 15 px halbfett, Etiketten in Kästen („Merke“, „Probier's aus“, „Empfehlung für dieses Motiv“) 13 px halbfett, Farben wie gehabt. Beim Durchsehen zwei Reste Orange an Bedienelementen gefunden und weiß gestellt: der Knopf „Weiter: …“ am Ende jeder Lektion (`.lk-next`) und alle vollen Knöpfe (`.btn` ohne `ghost`, etwa „+ Eigenes Rezept“). Die Phasen-Überschriften der Video-Lektionen sind weiß statt orange, das Etikett „Lektion 1 · …“ grau. |
| **v70** | **Stichworte unter den Clips entfernt** (Nutzer-Wunsch): Die drei Schlagwörter je Karte („Match Cut · Anschlüsse · allein gedreht“) lasen sich wie Hashtags. Was sie sagten, steht ohnehin in Rollen-Zeile und Text. Die Regeln `.tags` sind aus `assets/style.css` raus, die gleichnamige Klasse in der App ist davon unberührt (eigenes CSS). |
| **v69** | **Die App läuft auf Archivo** (Fahrplan Punkt 7), gleiche Datei wie das Portfolio, vorgeladen, Fließtext bei 96 %, Marke und Kopf-Navigation bei 86 % Breite. Alle 52 Grafiken mit Text vorher einzeln geprüft, siehe Fahrplan. **Bedienelemente ohne Orange:** Der aktive Modus-Knopf ist weiß mit dunkler Schrift, Untertitel „Mein Lerntagebuch …“ grau, die aktuelle Lektion hat einen grauen Rahmen und eine weiße Nummer, die untere Leiste markiert weiß. Farbe in Grafiken, Empfehlungskästen und Rezepten bleibt, dort ist sie Inhalt. „hoch · Reel“ im Seitenverhältnis-Bild zweizeilig, es ragte schon immer aus dem schmalen Kasten. Geprüft in fünf Ansichten (Lektion, Berater, Farben, Rezepte, Video-Berater) bei 390 px, dazu Startseite bei 1280 px: kein Überlauf, keine Fehler. |
| **v68** | **Ruhigere Oberfläche und eigenes Icon** (Fahrplan Punkt 4 und 6). **(1)** Die Kacheln der Startseite sind keine Karten mehr, sondern ein Begriff unter einer feinen Linie mit Pfeil, wie ein Register. Beim Darüberfahren wird die Linie weiß und der Pfeil rückt nach rechts. Die Karten der Videoseite haben keinen Rahmen und keinen hellen Grund mehr, der Clip ist der Kasten. Zwischenüberschriften („Der Moment“, „Worum es ging“) stehen normal gesetzt statt in grauen Versalien, die Stichworte als Zeile mit Mittelpunkt statt als Pillen. **(2)** Favicon und App-Icons zeigen **„TI“** weiß auf Schwarz statt des Farbrads, dazu erstmals ein echtes Favicon (`favicon.svg` plus 32er PNG). Vorher hatte der Browser-Tab gar keins. **(3)** Die Tab-Titel der Unterseiten tragen jetzt den Namen („Fotografie · Tobias Imhof“), passend zur Link-Vorschau. |
| **v67** | **Eckige Fotos und kein Orange im Portfolio** (Fahrplan Punkt 3 und 5). Fotos, Clips, Startbild und Lightbox runden nur noch mit `--r-img: 2px` statt 10 bis 12 px. `--accent` ist hellgrau (`#c8c8ce`, Hover-Rahmen und Fokusring), `--accent-2` weiß (Rollen-Zeilen, Links). Tote Regeln raus: `.ph` samt Seitenverhältnis-Klassen, `.gal` und `.btn`. **Die App behält ihr Orange vorerst**, dort zeigt es an, wo man ist, und wird erst mit dem Schrift-Umbau (Punkt 7) angefasst. |
| **v66** | **Link-Vorschau (Open Graph)** auf Startseite, Fotografie, Videografie und App, je mit eigenem Bild, Titel und Satz. Die Titel in der Vorschau tragen den Namen („Fotografie · Tobias Imhof“), nicht die Marke, weil der Empfänger einen Menschen erwartet und keine App. Die Beschreibung der App ist dabei neu: „Mein Lerntagebuch zu Bild, Video und Farbe, selbst gebaut als Web-App.“ statt des alten Produktsatzes. Punkt 8 (Unterschrift) ist vom Fahrplan gestrichen, Nutzer-Entscheidung. **Nicht geprüft:** die echte Vorschau bei WhatsApp oder Teams, die Umgebung erreicht `github.io` nicht. Lokal geprüft: alle Tags lesbar, alle vier Bilder werden als JPEG ausgeliefert. |
| **v65** | **404-Seite** und der **Fahrplan für den Feinschliff** (Schritt 5, acht Punkte, geordnet von „ohne Entscheidung“ bis „aufwendig“). Die Fehlerseite hat den gleichen Kopf wie alle Seiten, den Satz „Diese Seite gibt es nicht“ und die drei Kacheln. Geprüft mit einer nachgestellten falschen Adresse `/colorgrade/a/b/c`: Schrift, CSS und alle acht Links lösen richtig auf, das geht nur über `<base href>`. Nicht im `ASSETS`-Cache, offline hilft sie niemandem. |
| **v64** | **Zwei Wünsche des Nutzers.** **(1)** Auf der Startseite steht statt des Zweikampfs ein **Standbild aus dem Rheinhessen-Clip**: Weintrauben im Gegenlicht, schwarzweiß, bei 5,4 s aus dem Canva-Export genommen und auf **4:5** geschnitten (576 × 720, mehr gibt ein 720p-Clip nicht her, reicht aber für 280 px auch bei doppelter Pixeldichte), 19 KB. Darunter die Zeile „Standbild aus ‚Rheinhessen‘ · Aufnahmen: Pixabay“, weil fremdes Material auf der Seite immer benannt wird. Die Kacheln enden bei 1024 × 768 bei 617 px, liegen also weiter über der Falz. **(2)** Die App hat oben ihren **einen Satz** wie Fotografie und Videografie: „Ich schreibe eigene kleine Programme für Aufgaben aus meinem digitalen Alltag. ColorGrade ist eins davon …“ Er steht bewusst nicht im festen Kopf, sondern als erstes Element in `main`, sonst würde er auf jedem Bereich Platz kosten. Der alte Kommentar im HTML zum Zweikampf ist mit ersetzt. |
| **v63** | Auf der Karte „Atmosphäre auf den Beat“ steht jetzt, woher die Bilder kommen: „Die Aufnahmen sind von Pixabay, ausgesucht, geschnitten und in Schwarzweiß gesetzt habe ich sie selbst.“ Begründung: Wer aus der Medienbranche kommt, erkennt Stock-Material. Offen benannt wirkt es ehrlich, selbst entdeckt fällt es auf die Arbeit zurück. |
| **v62** | **Der zweite Clip läuft, die Videografie-Seite ist fertig.** „Atmosphäre auf den Beat“ ist ein Film über Rheinhessen in Schwarzweiß: Weinberg aus der Luft, Trauben im Gegenlicht, Lese, Fass, Keller, Abfüllung, Glas, Titel am Anfang und am Ende. Der Nutzer hat ihn in Canva auf 28 MB gebracht (dafür 1 bis 2 Sekunden gekürzt, jetzt 23,7 s), hier ist er auf **9,3 MB** gerechnet, CRF 26 statt 23, weil das Korn im Schwarzweiß sich schlechter packen lässt (CRF 23 hätte 14,8 MB ergeben). Ton vom Nutzer geprüft. Vorschaubild ist die Titeltafel „Rheinhessen“ (7 KB). Der Hinweiskasten „Noch offen“ ist weg und mit ihm die Regel `.note`, die nirgends mehr benutzt wird. |
| **v61** | **Der erste Clip läuft: „Match Cut im Wohnzimmer“.** Der Canva-Export (23 MB, 1280 × 720, 30 fps, 22,9 s) ist auf **5,4 MB** gebracht, H.264 mit CRF 23 und `+faststart`, bei SSIM 0,987 gegen das Original. Vorschaubild `match-cut-poster.webp` (27 KB) zeigt die hingestellten Schuhe, bewusst ohne die nackten Füße. Die kommen im Clip nur kurz und als Teil der Übung vor (vorher barfuß, nachher in Schuhen), das ist für die Bewerbung in Ordnung. Das Wohnzimmer ist durchgesehen, nichts Privates im Bild. **Service-Worker:** Videos laufen jetzt an ihm vorbei. Der Browser holt ein Video in Stücken (Range-Anfrage, Antwort 206), und die alte Regel „erst aus dem Cache“ hätte die ganze Datei geliefert, woran Safari scheitert. Vorgeladen werden Clips auch nicht, 5 MB gehören nicht in den Offline-Speicher; das Vorschaubild schon. Der Hinweiskasten sagt nur noch, dass der Beat-Clip folgt. In der README drei veraltete Stellen nachgezogen (Stand v59, Flutlicht-Brief mit 4:5 für das Mannschaftsfoto, „Länge erfragt“). |
| **v60** | **Das Mannschaftsfoto ist drin, die Fotografie-Seite ist fertig** (sieben Bilder). Es steht als **breites Schlussbild** in einem eigenen Abschnitt „Die Mannschaft" am Ende der Strecke. Der alte Plan (4:5 neben dem Spielerporträt) ist damit hinfällig, der Nutzer hat im Querformat aufgenommen, und das ist für drei Reihen Spieler richtig. **Messung der Bearbeitung, vorher gegen nachher:** Weißpunkt 232 → **254**, Rotkanal auf null 4,16 % → **0,15 %**, Schwarzpunkt 3 → 5, Haut R minus G +13 Stufen an denselben Pixeln gemessen, kein Kanal über 0,74 % am oberen Anschlag. Alle Projektgrenzen eingehalten. **Neu im Skript:** `scripts/make_photos.py` nimmt jetzt je Bild eine eigene WebP-Qualität. Nötig geworden, weil das Korn von ISO 6400 sich schlecht komprimieren lässt: Mit der Normalqualität 82 wog die Datei 448 KB, mit 74 sind es 325 KB bei im Mittel 3,9 Helligkeitsstufen Unterschied im Gesichtsband. Der Hinweiskasten „Noch offen: Ein Mannschaftsfoto" ist von der Seite verschwunden. |
| **v59** | **Drei Punkte aus dem Nutzer-Feedback zur Startseite.** **(1)** Das Torwartbild ist raus, es steht jetzt ein **Zweikampf** dort. Begründung des Nutzers, und sie stimmt: Bei einem einzelnen Menschen im Bild liest der Betrachter, das sei der Bewerber. Bei zwei Spielern im Duell ist klar, dass es die Arbeit ist und nicht das Motiv. **(2)** Das Bild ist deutlich kleiner (280 px statt 360 px Spaltenbreite, feste Deckelung per `max-width`). Grund war ein echter Fehler: Auf dem **Tablet im Querformat** waren die Kacheln unten abgeschnitten, und die Kacheln sind die Navigation der Seite. Der Kopfbereich hat jetzt auch weniger Polsterung. Nachgemessen mit Playwright bei 1024, 1112, 1180 und 1366 px Breite: Die Kacheln enden bei 591 px und damit über 100 px vor der Kante. Am Handy liegt die dritte Kachel weiter unter der Falz, das ist dort in Ordnung und ein Hinweis zum Weiterscrollen. **(3)** Der Regenbogen-Punkt ist weg, die Marke ist nur noch der Schriftzug **ColorGrade**, auf allen Seiten und in der App. **Achtung:** Die App-Icons unter `icons/` sind weiter ein Farbrad, siehe „Erscheinungsbild". Nebenbei: Die zweite Sorge des Nutzers, die Startseite könne nach reinem Fotoportfolio aussehen, löst nicht das Layout, sondern das Material. Sobald die zwei Clips liegen, gehört dort ein Standbild aus einem Clip hin. |
| **v58** | **Erster Eindruck, Nutzer-Wunsch:** Die orangen Strich-Icons raus, die Begriffe groß, und mehr Leben in das schwarz-weiße Bild. **(1)** Die Kacheln tragen nur noch den Begriff (`clamp(21px, 5.6vw, 27px)` statt 15 px) und darunter die Erklärung. Eine Mindesthöhe hatten sie zwischendurch auch, die ist wieder raus: Ohne Symbol reißt sie Begriff und Erklärung nur auseinander. **(2)** Das Leben kommt nicht aus Farbe in der Oberfläche, sondern aus einem Foto. Im Kopfbereich steht ab 900 px links der Name und rechts der **Torwart-Faustgruß**, am Handy untereinander. Bewusst der Faustgruß und nicht das Aufmacherbild der Galerie: ein Gesicht, ein Lächeln, und es wiederholt nicht das erste Bild der Fotografie-Seite. Das Foto behält sein 4:5 und wird **nicht** beschnitten, der Beschnitt ist Sache der Bildbearbeitung und nicht des Layouts. Es lädt mit `fetchpriority="high"`, hat feste Maße gegen das Springen beim Laden und nimmt über `srcset` am Handy die 639er und am Rechner die 1278er Fassung. **Damit ist die Oberfläche der Startseite komplett schwarz und weiß**, der einzige Rest Farbe ist der Regenbogen-Punkt der Marke, siehe „Erscheinungsbild". Die toten Regeln `.tile .ti` und `.tt` sind mit raus. |
| **v57** | **Die Schrift läuft schmaler**, auf Wunsch des Nutzers: schmal wirkt ruhiger und teurer. Dafür liegt jetzt die Archivo-Fassung mit **zwei Achsen** im Repo (Gewicht 400 bis 700 **und** Breite 62 bis 125 Prozent, 90 KB statt 35 KB). Gesteuert wird es über zwei neue Variablen, `--w-head` für Überschriften und Bedienelemente (86 Prozent) und `--w-text` für den Fließtext (96 Prozent). Der Name rendert damit 12 Prozent schmaler. **Zwei Fallstricke, beide geprüft:** **(1)** `font-stretch` an den Elementen bleibt wirkungslos, wenn im `@font-face`-Block die Spanne `font-stretch: 62% 125%` fehlt, der Browser weiß sonst nichts von der Achse. **(2)** Die Datei heißt bewusst neu (`archivo-wdth-latin.woff2` statt `archivo-var-latin.woff2`). Unter dem alten Namen hätte der Browser-Cache bis zu zehn Minuten die alte Datei ohne Breiten-Achse geliefert, und die Seite hätte unverändert ausgesehen, ohne dass ein Fehler sichtbar wird. **Abwägung:** Unter etwa 80 Prozent kippt das Schriftbild vom Edlen ins Plakathafte, deshalb 86. |
| **v56** | **Eigene Schrift und eine leere Startseite.** Zwei Dinge, die zusammen gehören, weil beide dasselbe Ziel haben: Die Seite soll nicht nach Vorlage aussehen. **(1)** Der System-Font-Stack ist raus, das Portfolio läuft auf **Archivo** (Groteske aus der Zeitungsecke, SIL Open Font License). Eine variable Datei für alle Gewichte von 400 bis 700, 35 KB, als Latin-Subset unter `assets/fonts/`, kein Google Fonts. Jede Seite lädt sie per `rel="preload"` vor, sonst findet der Browser sie erst nach dem CSS und der erste Eindruck steht kurz in der Ersatzschrift. Überschriften stehen enger (`-.03em` beim Namen, `-.025em` bei den Seitentiteln), weil Archivo mehr Zug verträgt als der System-Stack. **Merke:** Das Gewicht 650, das an mehreren Stellen steht, gibt es jetzt wirklich; vorher hat der Browser es auf 700 gerundet oder künstlich fett gerechnet. **(2)** Die Startseite zeigt nur noch **Tobias Imhof**, einen Satz aus Fakten und die drei Kacheln. Über mich, Kontakt und der Notizkasten sind raus: Wer den Link anklickt, kommt aus dem Lebenslauf und hat Werdegang und E-Mail schon gelesen. Der Name ist entsprechend größer (38 px, ab 720 px 54 px), der Inhalt sitzt mittig. Die toten Regeln `.hero .kicker`, `.hero-more` und `.ft-in .sp` sind mit raus, ebenso die Kontakt-Links im Fuß der Unterseiten, die ins Leere gezeigt hätten. **Die App unter `app/` behält vorerst den alten Stack**, dort hängen 165 SVG-Texte an den Schriftmaßen. |
| **v55** | **Spielerporträt eingebunden**, die Galerie hat damit sechs Bilder. Es bekommt einen **eigenen Abschnitt „Das Porträt"** statt als drittes Bild zu den Menschen zu wandern: Ein Porträt ist geplante Arbeit und keine Reportage, und drei Bilder hätten in der zweispaltigen Reihe eine Lücke gelassen. `.shots.solo` deckelt die Breite auf 420 px, damit es so groß wirkt wie eine Kachel der anderen Reihen. **Lehrstück aus der Bearbeitung:** Der globale Sättigungsregler trifft Motiv und Hintergrund gleich stark. Ein Minus von 25, das dem lauten Grün galt, nahm der Haut ihre Farbe (R minus G fiel von 39 auf 31, die Haut wirkte milchig). Die Lösung war ein milderes globales Minus plus ein **Kontrollpunkt auf dem Gesicht** in „Selektiv". Ergebnis: Haut wieder bei R minus G = 38, dazu Schwarzpunkt 7, Weißpunkt 251, Kontrast 59,9 und kein Kanal über 1,6 Prozent. Die Gesamtsättigung liegt bei 129 statt der Zielspanne 85 bis 95, das ist hier bewusst: Der Wert kommt fast nur vom großen grünen Hintergrund, und weiter zu senken hätte erneut die Haut gekostet. **Merke: Bei Porträts schlägt ein gesunder Hautton jede Zielzahl für die Gesamtsättigung.** |
| **v54** | **Trainerbild getauscht** gegen die vom Nutzer neu bearbeitete Fassung. Entscheidend war ein Kanal-Clipping, das man im Histogramm der Helligkeit nicht sieht: Der Blaukanal stand in bis zu 5,32 Prozent der Pixel auf 255, dadurch hatte die Regenjacke in den hellen Partien keine Stoffzeichnung mehr, und der Rotkanal lag in 5,28 Prozent auf null, wodurch die Schatten ins Blaue kippten. Beide Werte liegen jetzt bei 0,01 und 0,07 Prozent. Dazu Weißpunkt von 222 auf 242 und Schwarzpunkt von 16 auf 13. **Merke für künftige Bilder:** Ein kräftig blaues Trikot oder sattes Grün ist oft schon ab Werk nah am Anschlag (hier 2,46 Prozent direkt aus der Kamera). Bei solchen Motiven gehört der Sättigungsregler nach unten, nicht nach oben, sonst ist die Zeichnung unwiederbringlich weg. |
| **v53** | Das Querformat („Lauf in den freien Raum") steht jetzt als **Aufmacher ganz oben**, direkt unter dem Einleitungssatz und bewusst ohne Überschrift (Nutzer-Wunsch: es zieht den Blick am besten). Darunter folgen zwei ruhige Zweierreihen im Hochformat. Das Aufmacherbild lädt nicht mehr verzögert, sondern mit `fetchpriority="high"`, weil es über der Falz liegt. Die Reihenfolge in der Lightbox folgt der neuen Anordnung. |
| **v52** | **Fotografie-Galerie gebaut**, der Bereich ist damit inhaltlich gefüllt. Fünf Bilder in zwei Abschnitten: „Der Moment" (Schuss, Zweikampf, Konter) und „Die Menschen" (Torwart, Trainer). Je Bild eine kurze Unterschrift mit Brennweite und Belichtungszeit aus den EXIF-Daten. Neue **Lightbox** (`.lb`) mit Blättern per Pfeiltasten, Schließen per Escape oder Klick auf den Hintergrund, Fokus bleibt im Overlay und kehrt beim Schließen auf die angeklickte Kachel zurück. Bilder als WebP in zwei Größen, 1600 px für die Lightbox und 800 px für die Kachel, erzeugt von `scripts/make_photos.py`; das Raster lädt so nur 280 KB. Zwei Dinge beim Testen gefunden und behoben: **(1)** Die Kachel des Querformats wurde von 800 auf 860 px hochskaliert, breite Bilder nehmen jetzt die 1600er Fassung. **(2)** Der Lightbox-Hintergrund war mit 94 Prozent halbtransparent, dadurch schienen Kopfzeile und Bildunterschriften durch und hellten die Tiefen des Fotos auf; jetzt deckend. Dazu sitzt die Unterschrift nicht mehr am unteren Bildschirmrand, sondern direkt unter dem Foto (`max-height` statt `flex: 1`). |
| **v51** | Texte auf der Startseite gekürzt (Nutzer-Wunsch): Die Kopfzeile ist ein Satz aus Fakten statt einer Absichtserklärung („Sportfotografie für das Portal FuPa, erste eigene Videoarbeiten, eine selbst gebaute App"). Über mich von vier Karten auf drei, je höchstens zwei kurze Sätze; die Karte „Mein Ziel" ist aufgelöst, ihr Kern steht jetzt als **ein** Satz beim Kontakt. Hintergrund: Das Warum steht im Anschreiben, auf der Seite klang es doppelt und zu sehr nach Wollen. Das Quellenverzeichnis aus v43 bleibt entfernt, das ist entschieden. |
| **v50** | App entschlackt (Nutzer-Wunsch): Der Block **„Über ColorGrade"** am Ende der Wissen-Startseite ist komplett raus, er war zu lang und klang zu sehr nach KI. **Achtung:** Das ausklappbare Quellen- und Literaturverzeichnis lag in diesem Block und ist damit ebenfalls weg (v43, sieben Publikationen). Wer es zurückholen will, findet es in der Historie. Dafür sagt die Kopfzeile jetzt sofort, worum es geht: „Mein Lerntagebuch zur Bildbearbeitung" steht in Akzentgelb und halbfett statt klein und grau. Das tote `.about`- und `.about-src`-CSS ist mit raus. |
| **v49** | Navigation vereinheitlicht (Nutzer-Wunsch): **Jede** Seite hat jetzt denselben Kopf, die App eingeschlossen, mit Marke links (führt zur Startseite) und Fotografie · Videografie · Apps rechts. Die eigene Über-mich-Seite ist aufgelöst, ihr Inhalt und der Kontakt stehen auf der Startseite. Dabei zwei echte Fehler gefunden und behoben. **(1)** Die App stylte `nav` als Element, also erbte der neue Kopf-`nav` die feste Positionierung der unteren Leiste und lag auf dem Untertitel; Regeln auf `body > nav` eingegrenzt. **(2)** Der Selbstheiler im Service-Worker (offene Fenster nach einer neuen Fassung neu laden) verklemmte sich: `activate` wartete per `await` auf `client.navigate()`, und ein Service-Worker liefert keine `fetch`-Ereignisse aus, solange `activate` läuft. Jetzt wird nicht mehr abgewartet, und die Fenster werden **vor** `claim()` eingesammelt, damit ein erster Besuch nicht mitten im Laden neu geladen wird. Mit einem Testaufbau geprüft, der GitHub Pages samt `max-age=600` nachstellt. |
| **v48** | Zwei Dinge. **(1)** Videografie-Seite mit den zwei echten Übungen gefüllt: „Atmosphäre auf den Beat" (Schnitt auf den Takt, leichte Zeitlupe) und „Match Cut im Wohnzimmer" (Anschlüsse, allein gedreht), je mit „Worum es ging" und „Was ich geübt habe". Kein Showreel, zwei Clips sind dafür zu wenig. **(2)** Fehler behoben, den der Nutzer gemeldet hat: Nach dem Live-Gehen stand in der App weiter der alte Text mit Umfrage. Ursache war nicht der Service-Worker-Cache, sondern der **Browser-Cache**: Pages liefert mit `max-age=600`, also bediente der Browser das `fetch` des Service-Workers bis zu zehn Minuten lang selbst. Seiten werden jetzt mit `cache: 'reload'` geholt, im Betrieb und beim Vorladen. |
| **v47** | Apps-Bereich auf ColorGrade zugespitzt (Nutzer-Wunsch): Die Kachel führt jetzt **direkt** in die App unter `app/`, die Zwischenseite `apps.html` ist gelöscht, das Winzer-Warenwirtschaftssystem wieder raus. In der App selbst alles entfernt, was für eine Bewerbung nichts beiträgt: Tally-Umfrage, Forschungsabsatz zur Bachelorarbeit und der Plattform-Text. Der Über-Text beschreibt die App jetzt als Lerntagebuch, die Untertitel im Kopf ebenso, und der frühere Feedback-Link oben rechts ist der Rückweg ins Portfolio. Quellenverzeichnis bleibt. Toter Code raus: `openAbout` und die `.about-fb`-Regeln. |
| **v46** | Startseite nach Nutzer-Wunsch umgebaut: oben ein kurzes Über mich, darunter **drei** Kacheln (Fotografie, Videografie, PWA und Apps) statt vier. Die dritte Kachel nimmt am Handy die volle Breite und stellt Symbol und Text nebeneinander, damit keine Lücke entsteht. Die Über-mich-Seite ist mit echten Angaben gefüllt: Schwerpunkt Sportfotografie, ehrenamtlich für FuPa, Einstieg in die Videografie, Ziel Ausbildung Mediengestalter Bild und Ton. Offen bleiben E-Mail, jetziger Beruf und Ausrüstung, die sind bewusst als Platzhalter markiert. |
| **v45** | **Umbau zum Portfolio.** Die Startseite ist jetzt ein Portfolio mit vier Kacheln (Fotografie, Videografie, PWA und Apps, Über mich), dazu je eine Unterseite und ein gemeinsames `assets/style.css`. Die bisherige Lern-App ist unverändert nach `app/` gezogen und hat ein eigenes Manifest, die Pfade für Icon und Service-Worker sind nachgezogen. Der Service-Worker bleibt im Wurzelverzeichnis, cacht jetzt Portfolio und App und legt jede Seite unter ihrer eigenen Adresse ab statt alles unter `index.html`. Alle Seiten stehen auf `noindex`, Inhalte sind noch Platzhalter. Gefunden und behoben beim Testen: `aspect-ratio` in einem Grid ohne `align-items: start` streckte die Galerie-Kacheln und sprengte die Seitenbreite. |
