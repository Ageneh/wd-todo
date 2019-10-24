<small>TechAcademy Wintersemester 19/20</small>

# Web-Development Semesteraufgabe

### Ziel der Aufgabe

Erstellen einer einfachen ToDo-Liste. Die ToDo-Liste wird es erlauben, über ein einfaches Eingabefeld einen Titel für eine neue ToDo anzugeben und mit einem Button die Eingabe zu bestätigen.<br/>
Zusätzlich kann man jeden Eintrag abschließen oder löschen. Eine abgeschlossene ToDo wird für 3 Sekunden noch gezeigt und verschwindet danach.
Bevor es losgeht, solltest du dir folgende Links einprägen und *niemals vergessen*,
vor allem dann nicht, wenn du mal nicht weiter weißt. Diese Seiten bieten dir
alle Informationen, die du zu HTML, CSS und JavaScript benötigst - und noch vieles
mehr.

  - [Google - dein Freund und Helfer](https://www.google.de/search?sxsrf=ACYBGNTdFl0T8CM5nhPF4Jc4mjm983wpsA%3A1571959632745&source=hp&ei=UDOyXcOSK-elmwWq55XYBg&q=sqrt%28cos%28x%29%29*cos%28300x%29%2Bsqrt%28abs%28x%29%29-0.7%29*%284-x*x%29%5E0.01%2C+sqrt%286-x%5E2%29%2C+-sqrt%286-x%5E2%29+from+-4.5+to+4.5&oq=sqrt%28cos%28x%29%29*cos%28300x%29%2Bsqrt%28abs%28x%29%29-0.7%29*%284-x*x%29%5E0.01%2C+sqrt%286-x%5E2%29%2C+-sqrt%286-x%5E2%29+from+-4.5+to+4.5&gs_l=psy-ab.3...564.564..798...0.0..0.106.106.0j1......0....2j1..gws-wiz.PdyN8nNa0_g&ved=0ahUKEwjD-oj8hbblAhXn0qYKHapzBWsQ4dUDCAc&uact=5)
  - [Stackoverflow](https://stackoverflow.com/questions/8318911/why-does-html-think-chucknorris-is-a-color) (ist meistens der erste Link bei einer Google-Suche)
  - [W3Schools](https://www.w3schools.com)
  - [SELFHTML](https://wiki.selfhtml.org)

Gerne kannst du dir auch eine simple Version anschauen und testen. Unter [TechAcademy-Todo](https://TA-Todo-List--ageneh.repl.co) findet ihr eine Beispiel-ToDo-App, welche den Mindestanforderungen entspricht.

#### Was kann man erwarten?
1. Selbständiges Designen, Lernen und Implementieren einer einfachen ToDo-Web-App.
2. Das Erlernen, der wesentlichen Operationen im Umgang mit HTML/CSS.
    - Manipulation der DOM-Elemente, mittels Vanilla/plain JS oder jQuery
    - Verwendung von eigenen, responsiven Stylesheets
    - Umgang mit (Interaktions-)Events, als Reaktion auf ein vom User gewünschtes Verhalten
3. Die Möglichkeit, Kreativitat mit einfließen zu lassen. 



---



### Gruppen und Abgabe

Ihr werdet in kleine Gruppen eingeteilt und jeder von euch sollte etwas zu dem Projekt beitragen. Ihr trefft euch dafür bitte so oft wie möglich, um euch über eure Ideen und Ansätze austauschen und zusammen daran arbeiten. Bestenfalls habt ihr als Gruppe eine gesamte Lösung.

Für die Abgabe gibt es nicht allzu viel zu beachten.
Ihr müsst:  

- die Projekt-Dateien (HTML, CSS, JS),
- Wireframes
- und, wenn nötig, auch sonstige obercoole Dateien, die ihr unbedingt abgeben wollt

in eine gemeinsame Zip-Datei umwandeln und diese vor der Deadline an unsere [Projektabgabe-Email-Adresse]() schicken.

Die Zip-Dateien sollen nach folgenden Mustern benannt werden: **``[Gruppenname].zip``**.
Die Gruppenlösung soll die Lösung sein, welche ihr als Gruppe abgeben möchtet und zusammen erarbeitet habt. 

Die **Deadline** für die Abgabe ist der **02.02.2020**.



### Vorbereitungen

1. Installiere einen der folgenden Browser - falls du diese noch nicht
nutzen solltest. 
  
  - [Google Chrome](https://www.google.com/intl/de_de/chrome/)
  - [Mozilla Firefox](https://www.mozilla.org/de/firefox/new/)
2. Setze dich als nächstes mit den ``Entwicklerwerkzeugen`` der jeweiligen Browser auseinander. Versuche dir einen Überblick über die einzelnen Funktionen und Informationen zu verschaffen.
  Konzentriere dich dabei hauptsächlich auf die Tabs **Elemente**, **Konsole** und
  **Netzwerk** und gewinne einen groben Überblick.
  **Elemente** zeigt dir die Struktur des HTMLs und die Styling-Eigenschaften an. Du kannst hier live coden und **live** Elemente hinzufügen oder auch löschen.
  
  > Starte außerdem Google/Firefox und dort die `Entwicklerwerkzeuge`. Spiele dann einfach mal mit den CSS- und HTML-Eigenschaften der einzelnen Elemente. Du kannst zum Beispiel eigene Styles und Elemente einfügen oder auch andere löschen und deaktivieren. Das ist eine tolle Möglichkeit, live zu coden und man sieht sofort, was passiert.
  >
  > Auch in repl kannst du die Entwicklerwerkzeuge nutzen. Dazu musst du nur mit der rechten Maustaste auf das Fenster klicken, in welchem du deine Website sehen kannst, und dann die Entwicklerwerkzeuge auswählen.
3. Bevor es nun an das Coden geht, erstelle noch ein **Wireframe**, welches zum Einen deine Vorstellungen grob visualisieren soll und dir zum Anderen helfen wird, ein besseres Verständnis für den Aufbau der ToDo-App zu erlangen.
   Zum Erstellen der Wireframes kannst du z.B. [Wireframe.cc](https://wireframe.cc/) oder [Draw.io](https://draw.io/) nutzen. Bitte gib auch diese Wireframes ab. Dazu exportierst du die Wireframes einfach als Bilder oder PDFs und schließt sie in deiner Zip-Datei mit ein.



---



### HTML
In dem ersten Aufgabenblock geht es zuerst nur um das HTML-Gerüst! Das Styling und die Funktionen werden später behandelt. Es geht nun erst einmal darum, dass das Grundgerüst der Webseite aufzubauen (welches zu Beginn noch nicht perfekt aussehen muss) und dich mit den Entwicklerwerkzeugen im Browser vertraut zu machen.

1. Erstelle ein Grundgerüst, welches noch keine Funktionen besitzt. Es soll aus einem Container-Element, einem Listen-Element, welche die ToDo-Einträge beinhalten wird, und einem Input-Container bestehen, damit auch Eingaben getätigt werden können. 
2. In dem Input-Container sollen mindestens ein Eingabefeld für den Titel und ein Button zum Erstellen der neuen ToDo vorhanden sein.
3. Erstelle eine Komponente für ToDo-Einträge. Ein ToDo-Eintrag soll mindestens aus dem **Titel** des Eintrags und je einem Button für das **Abschließen** und **Löschen** der ToDo bestehen.
4. Damit du deine Komponenten richtig gestalten kannst, solltest du den jeweiligen Komponenten, je nach Aufgabe und Rolle eine passende Klasse und/oder ID zuweisen. Versuche deshalb, die einzelnen Elemente deiner ToDo-Liste in eine sinnvolle Anordnung zu bringen. Orientiere dich dafür an deinem Wireframe. Es muss anfangs nicht perfekt sein und kann sich auch im Laufe des Semesters gerne ändern.



---



 ### CSS/Styling

Jetzt darfst du dich ein wenig mit dem Styling auseinandersetzen. Aber halte dich hier nicht zu lange auf. Das Styling ist nicht das Wichtigste an der ToDo-Liste.

Für das Styling hat repl dir die ``style.css``-Datei schon bereitgestellt. Du bist jedoch nicht auf diese einzige CSS begrenzt. Du kannst auch gerne mehrere Styling-Dateien verwenden. Und wenn du möchtest, kannst du dir gern andere Dialekte wie [LESS](http://lesscss.org/usage/) oder [SASS](https://sass-lang.com/guide) anschauen und verwenden - es gibt keine Extrapunkte, ist aber eine coole Sache. 

1. Versuche die einzelnen Elemente deiner ToDo-Liste in eine sinnvolle Anordnung zu bringen. Es muss anfangs nicht perfekt aussehen.
2. Erstelle dir eine Klasse. Diese wird zum Animieren der Elemente benötigt. Hierzu kannst du auch verschiedene Animations- bzw. Transition-Klassen erstellen und dir auch ausdenken, welche Element-Attribute und -Klassen wie animiert werden sollen.
> Du kannst dich hierbei zwischen zwei Arten entscheiden:
> 1. Animationen mit Hilfe von Keyframes. - [Keyframe-Animationen](https://www.w3schools.com/css/css3_animations.asp)
> 2. Übergänge, die mithilfe von `transition` erstellt werden. Das ist um einiges leichter und reicht auch vollkommen aus. - [Transitions](https://www.w3schools.com/css/css3_transitions.asp)

> Falls du ein Style-Framework verwenden möchtest, kannst du auch Bootstrap nutzen. Wie du das am besten machst, kannst [hier](https://getbootstrap.com/docs/) nachlesen.  

> *Bootstrap erleichtert es dir, deine Elemente zu gestalten, da sehr viele Elemente, wie einfache [Buttons](https://getbootstrap.com/docs/4.3/components/buttons/), [Eingabefelder](https://getbootstrap.com/docs/4.3/components/input-group/) oder [Container](https://getbootstrap.com/docs/4.3/layout/overview/)
>  bereits fertig gestaltet verwendbar sind. Um die jeweiligen Elemente zu verwenden, musst du nur in deren [Dokumentation](https://getbootstrap.com/docs/4.3/getting-started/introduction/) nachschauen.*

Die nächsten Schritte setzt du bestenfalls erst um, **nachdem** du die JavaScript-Funktionen umgesetzt hast.

1. Füge eine Animation hinzu - mithilfe der schon vorhandenen Animations-/Transition-Klasse - welche zu sehen sein wird, wenn man eine ToDo abgeschlossen hat. Dabei soll die Todo noch für 3 Sekunden sichtbar sein und danach langsam verschwinden. Ob es ein Verblassen, Wegbewegen oder sonstiges ist, ist dir überlassen.
   Diesen Schritt solltet ihr aber möglichst erst einbauen, **nachdem** ihr die Löschfunktion per JavaScript umgesetzt habt.
2. Gib den ToDo-Einträgen einen Schatten, wenn man mit der Maus über einem Eintrag schwebt.
3. Die Buttons zum Abschließen und Löschen einer ToDo sollen, nach einem Klick, nicht ein weiteres Mal angeklickt werden können. 



---



*Jetzt kommen wir zum Herzstück der gesamten Aufgabe:*

### JavaScript
Als nächstes wirst du dich um die tatsächliche Funktionalität der ToDo-Liste kümmern. Dazu verwendest du die **script.js**-Datei in [repl.it](https://repl.it/repls). Du kannst auch mehrere JavaScript-Dateien verwenden, wenn du diese z.B. nach Funktionen separierst. 

1. Erstelle für die jeweiligen Buttons passende Funktionen, welche aufgerufen werden, sobald einer der Buttons geklickt wird. Binde eine Funktion allerdings nicht mit dem onclick-Attribut an einen Button, sondern mithilfe von EventHandlern.
  Beispiel: wenn der Button `<button class="done" />` angeklickt wird, soll die Funktion **done(event) {...}** aufgerufen werden.   

  > Du kannst dir testweise immer eine Meldung auf der **Konsole** in deinem Browser ausgeben lassen, um zu sehen, ob alles funktioniert. Dazu kannst du `console.log(„Deine Meldung als String“);` innerhalb der Funktionen einsetzen. Das Gleiche geht auch offensichtlicher, wenn du die Konsole nicht verwenden möchtest. Mit `alert(„Nachricht“);` kannst du eine Popup-Meldung erzeugen, welche in deinem Browserfenster zu sehen sein wird.
  > Damit du dir keine ToDos ausdenken musst, kannst du auch eine REST-Schnittstelle nutzen, unter folgendem Link: [JSON-Placeholder](https://jsonplaceholder.typicode.com). Du kannst unter [/todos](https://jsonplaceholder.typicode.com/todos) vorgefertigte ToDos mit z.B. einem asynchronen fetch-Call abrufen und deren Daten nutzen, um deine ToDo-Liste zu befüllen. Es ist euch überlassen ob ihr diese Api oder eine andere verwendet, solange das Abrufen und Verarbeiten der Daten funktioniert.  
  > Hilfreiche Links: 
  >
  > - https://www.w3schools.com/js/js_htmldom_events.asp 
  > - https://www.w3schools.com/js/js_htmldom_css.asp 
  > - https://www.w3schools.com/js/js_htmldom_html.asp 
  > - https://www.w3schools.com/js/js_htmldom_elements.asp 



2. Setze als nächstes das Erstellen der Listen-Einträge über JavaScript um. Erstelle dazu für jede verfügbare ToDo einen Eintrag mit den benötigten Daten.

   > Schaue dir hierzu gern [Folgendes](https://www.w3schools.com/js/js_htmldom_nodes.asp) an.



3. Schließlich soll natürlich etwas mit den Einträgen passieren, wenn ein Button angeklickt wird. Wird beispielsweise der Button zum Abschließen einer ToDo mit der `id=„todo-17“` geklickt, soll diese ToDo mithilfe einer Animation verschwinden und aus dem DOM gelöscht werden. Dazu musst du dann die CSS-Eigenschaften der ToDo  `todo-17` passend ergänzen und zum richtigen Zeitpunkt löschen.

   Damit etwas passiert, füge beim Klick auf den Abschluss-Button der ToDo eine Klasse `done`  hinzu. Beim Löschen soll die ToDo gänzlich gelöscht werden.
   Welche Eigenschaften die Klasse `done` haben soll, kannst du selbst festlegen.
   ***Mach dir an diesem Punkt auch genau Gedanken darüber, wann welche Aktion eintreten soll.***
   _Wichtiges Keyword: [setTimeout()](https://www.w3schools.com/js/js_timing.asp)_



4. Damit du nicht nach jedem Neuladen die selben Todo erneut erstellen musst, müssen die Daten noch irgendwie persitiert werden. Dir stehen dazu verschiedene Wege zur Verfügung:
   - [Cookies](https://www.w3schools.com/js/js_cookies.asp)
   - [Web Storage](https://www.w3schools.com/html/html5_webstorage.asp)
   - [IndexedDB](https://wiki.selfhtml.org/wiki/JavaScript/IndexedDB)

   > Entscheide dich für einen der Persistenz-Konzepte und nutze diesen, zur Erhaltung der Todo-Zustände. Implementiere zusätzlich dazu noch einen einfachen Button, welcher die persistierten Daten reinitialisiert.



---



### Extras

Diese gesamte Aufgabe soll dich bestenfalls über das gesamte Semester begleiten und dir einen Einblick in das Web Development geben. 

Dir ist freigestellt, **wie** du diese ToDo-App implementierst. Du kannst natürlich noch eigene Funktionen einbauen. Das wird von unserer Seite wirklich gerne gesehen wird. Du kannst z.B. 

- einen Zähler einbauen, welcher zählt, wie viele ToDos schon erledigt sind und wie viele noch offen sind,
- einen Papierkorb erstellen, aus welchem gelöschte ToDos wiederhergestellt werden können,
- verschiedene Kategorien für die ToDos definieren, diese danach zuweisen und farblich, je nach Kategorie, markieren,
- etc.

Auch Spaßfunktionen kannst du gern einbauen und scheue dich auch nicht vor JavaScript-Bibliotheken - nutze nur bitte keine Library, welche dir eine fertige Todo ausspuckt ;). Es existieren zahlreiche Bibliotheken mit echt coolen Funktionen, die dir sogar einige Funktionen, die gefordert sind, von der Hand nehmen können. 


---


_Solltest du Interesse an mehr haben (z.B. an der Verwendung eines Frameworks wie z.B. ReactJS oder Next.js) bzw. bereits Kenntnisse haben, kannst du auch gerne auf die Mentoren zukommen._



---


# Mindestanforderungen

### Allgemein
1. Alle Kurse bis einschließlich Kurs 17 abgeschlossen
2. Mindestens ein Wireframe/Sketch/... von der Todo-Liste erstellt



---



### HTML
1. Grundgerüst implementiert [ ]
2. Hauptelemente sind vorhanden [ ]
   - Mindestens ein Eingabefeld, für den Titel einer neuen Todo [ ]
   - Mindestens ein Button, zum Bestätigen der Eingabe [ ]
   - Mindestens ein Listen-Element, mit den Todo-Einträgen [ ]
      - Sollte bestenfalls eine passende ID oder zumindest eine Klasse besitzen [ ]
3. Speziell angefertigtes "Todo-Element" [ ]
   - Besitzt einen Titel [ ]
   - Besitzt einen Button zum Abschließen der Todo [ ]
   - Besitzt einen Button zum Löschen der Todo [ ]
   - Besitzt eine eigene, todo-spezifische Klasse [ ]
   - Hat entweder jeweils eine ID oder nutzt ein Data-Attribut, zur korrekten Zuweisung der Todo-Inhalte [ ]



---



 ### CSS/Styling
1. Es existiert mindestens eine Klasse zum animieren von Elementen [ ]
2. Es existiert ein Style für das Hovern über einem Eintrag [ ]
3. Die Buttons einer gelöschten oder abgeschlossenen Todo sollen nicht mehr klickbar sein [ ]
4. Eine gelöschte oder abgeschlossene Todo ist für einige Sekunden sichtbar, bevor diese dann weganimiert wird [ ]



---



### JavaScript
1. Click-Handler für die jeweiligen Buttons sind verfügbar und angebunden
   - Button zum Bestätigen der Eingabe ruft Funktion ```create(value)``` o.ä. auf [ ]
     - erstellt entsprechenden Todo-Eintrag
   - Button zum 'Abschließen' ruft Funktion ```done()``` o.ä. auf [ ]
     - entfernt den Todo-Eintrag aus der Todo-Liste [ ]
   - Button zum 'Löschen' ruft Funktion ```remove()``` o.ä. auf [ ]
     - entfernt den Todo-Eintrag aus der Todo-Liste, bewegt diesen in eine andere Tabelle oder wird anderwertig verarbeitet [ ]
2. Fetching von einer JSON-Api funktioniert [ ]
   - Todo-Einträge können aus den erhaltenen Daten erstellt werden [ ]



---



### Extras

Diese gesamte Aufgabe soll dich bestenfalls über das gesamte Semester begleiten und dir einen Einblick in das Web Development geben. 

Dir ist freigestellt, **wie** du diese ToDo-App implementierst. Du kannst natürlich noch eigene Funktionen einbauen. Das wird von unserer Seite wirklich gerne gesehen wird. Du kannst z.B. 

- einen Zähler einbauen, welcher zählt, wie viele ToDos schon erledigt sind und wie viele noch offen sind,
- einen Papierkorb erstellen, aus welchem gelöschte ToDos wiederhergestellt werden können,
- verschiedene Kategorien für die ToDos definieren, diese danach zuweisen und farblich, je nach Kategorie, markieren,
- etc.

Auch Spaßfunktionen kannst du gern einbauen und scheue dich auch nicht vor JavaScript-Bibliotheken - nutze nur bitte keine Library, welche dir eine fertige Todo ausspuckt ;). Es existieren zahlreiche Bibliotheken mit echt coolen Funktionen, die dir sogar einige Funktionen, die gefordert sind, von der Hand nehmen können. 
