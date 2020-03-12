<h1> Animationen </h1>
Eine gute Website unterstützt ihre Nutzer – nicht nur durch gutes Design und eine klare Struktur, sondern auch durch eine gute Usability der gesamten Seite. Dabei können Animationen sehr hilfreich sein. Sie erzeugen Aufmerksamkeit und verdeutlichen Zusammenhänge und runden so den gesamten Eindruck ab.

Nicht selten wird Animation als "bewegte Bilder" beschrieben. Sehr allgemein ausgedrückt, wird der Begriff Animation für Darstellungselemente verwendet, deren Eigenschaften oder Merkmale sich über die Zeit verändern. 

<b>Arten von Animationen </b>
<ul> 
<li> Transformation - beschreibt die Formänderung grafischer Merkmale eines Objektes hinsichtlich Grösse, Form, Farbe oder Textur.</li> 

<li> Translation - beschreibt die Veränderung der Position eines Objektes. Diese Bewegung steht entweder in Bezug auf den Rand der Animation oder relativ zu anderen Elementen innerhalb der Animation.<li> 

<li> Transition - beschreibt den Übergang zwischen zwei definierten Zuständen eines HTML-Elements. Dies wird durch eine Userinteraktion ausgelöst. </li> 
</ul>

Die oben genannten Begriffer sind in den entsprechenden CSS3-Befehlen für die CSS3-Animationen wiederzufinden. 

Der Mensch reagiert sehr stark auf Bewegung. Diese Komponente ist Bestandteil einer Animation, weshalb sich diese folglich gut zur Aufmerksamkeitssteuerung einsetzen lässt. Zu beachten ist hierbei jedoch, dass der User im Web weniger intensiv reagiert, als in der Realwelt. Das liegt vermutlich daran, dass sich das Gehirn bei diesem Medium bereits an die oftmals unruhige Bannerwerbung gewöhnt hat. 

<b> Verschiedene Funktionen von Animationen im Web im Überblick </b>
<ul>
  <li> Gestaltung von Übergängen </li>
    <li> Aufmerksamkeitslenkung </li>
    <li> Einsatz als Ornament (Deko, Schmuck) </li>
    <li> Darstellung dynamischer Vorgänge</li>
    <li> Abstraktion dynamischer Vorgänge</li>
    <li> Narrativer Ansatz (Geschichten erzählen, Handlung vermitteln etc.) </li>
  
  </ul>
  
  <h2> Animationen mit CSS3 </h2>
  Mit Hilfe von CSS3-Animationen können animierte Übergänge von einem CSS-Style zum nächsten realisiert werden. Die Animation besteht dabei aus zwei Komponenten: Einem Style, der die Animation beschreibt, sowie einem Set von Keyframes, welches Start, Ende und Schlüsselbilder der Animation definiert. 
  
  Die zu animierenden bildlichen Elemente können dabei auf zwei verschiedene Arten geschaffen werden:
  1. Durch entsprechende CSS-Anweisungen
  2. Vorab in einer Grafiksoftware als Datei erstellen
  
  
 <b> Eigenschaften einer CSS-Animation </b>
 Eine CSS-Animation kann aus den drei folgenden CSS3-Eigenschaften bestehen:
 1. tranform
 2. transition
 3. keyframes
 
 <b> CSS3-Transform </b> 
 Die Transformationseigenschaft ermöglicht Ihnen die visuelle Manipulation eines Elements durch Schrägstellung, Drehung, Verschiebung oder Skalierung:
 .element {
  width: 20px;
  height: 20px;
  transform: scale(20);
}
Selbst mit einer angegebenen Höhe und Breite wird dieses Element nun auf das Zwanzigfache seiner ursprünglichen Größe skaliert.

Viele weitere Beispiele finden Sie unter:
 https://css-tricks.com/almanac/properties/t/transform/
 
 
 <b> CSS3-Transition </b>
 Das Wort transition stammt aus dem Englischen und bedeutet übersetzt so viel Übergang. Genau diese Übergänge können mit dem Befehl transition in CSS gestaltet werden. 
 
 Bislang wurde die Animation über hover ausgelöst und abgespielt. Dabei erfolgt der Ablauf unmittelbar und sehr abrupt. Die Charakteristik ist dabei mit der eines An-/Ausschalters vergleichbar. Mit transition kann die Art des Übergangs nun hinsichtlich der Dauer, Art der Bewegung, Anzahl der beteiligten Elemente sowie der Verzögerung gestaltet werden. 
 
 Beispiel finden Sie unter:
 https://www.mediaevent.de/css/transition.html
 
 <b> CSS3-Keyframe Animation </b>
 
 CSS-Animationen werden durch die @keyframes-Regel erzeugt – einer Liste von CSS-Eigenschaften, die in einzelnen Schritten (Frames) mit weichen Übergängen geändert werden sollen.

@keyframes-Animationen ähneln CSS transition, aber anders als Transitions setzen CSS-Keyframes eine Animationen automatisch und kontinuierlich in Kraft, und nicht als Reaktion auf ein Event wie ein Mausklick, ein Hovern der Maus oder ein Touch.

Jede Animation besteht aus zwei Schritten:

der Definition der Animation in der @keyframes-Regel
dem Aufruf der der keyframe-Regel im CSS-Selektor des HTML-Elements


Weitere Beispiele finden Sie unter:
https://www.mediaevent.de/css/animation.html

<b> Parallax- Effekt </b>
Die Erzählung einer Geschiche erfolgt hierbei durch aktives Scrollen. Aus technischer Sicht basiert der Website-Aufbau auf einem One-Pager und besteht lediglich aus einer einzigen Seite. 

Beim Parallax-Effekt bewegen sich beim Scrollen mindestens zwei oder mehr Elemente unterschiedlcih schnell. Es entsteht ein Eindruck von Dreidimensionalität und Tiefe und lässt den Scrollvorgang dadurch dynamisch erscheinen. Dieser Effekt kann sowohl horizontal als auch vertikal aufgebaut sein. 

Beispiel: 
https://speckyboy.com/10-css-javascript-parallax-scrolling-code-snippets/


Oder über background-attachment: https://www.mediaevent.de/css/background-attachment.html

<h2> Das Scalable-Vector-Graphics-Format (SVG) </h2>
SVG-Dateien sind Textdateien, die auf XML basieren. Dabei beschreibt SVG zweidimensionale Vektorgrafiken. 
SVG beschreibt eine Vektorgrafik. Diese setzt sich im Gegensatz zu einer Pixelgrafik nicht aus Pixeln, sondenr aus mathematisch definierten Objekten zusammen. Entsprechend dieser Definition besteht Vektor-Objekte beispielsweise aus Strecken , welche durch einen bestimmten Startpunkt, Angaben zur Länge und einem Winkel definiert sind, aus Kreisen, Polygonen, Kurven etc. Darüber hinaus können Vektorgrafiken zusätzliche Eigenschaften wie Farbe oder Transparenzen zugewiesen werden können. 

Eine Pixelgrafik besteht aus einem festen und definierten Pixelraster. Wird diese Grafik skaliert, kommt es zur Qualitätsverlusten. 

Einbindung von SVG-Grafiken im HTML: https://www.mediaevent.de/tutorial/svg.html

<h2> HTML5 Canvas </h2>
Neben CSS3 und SVG können Animationen auch mit dem HTML5 Element <canvas> erstellt werden. DAs Wort canvas stammt aus dem Englischen wird wie folgt beschrieben: "a pice of canvas used for painting on"
  
Das canvas-Element ist tatsächlich zunächst nichts anderes als eine reine Leinwand. Auf diese wird über die Canvas API zugefriffen, zum Beispiel mittels JavaScript. Mit dieser Skript-Sprache können dann beispielswiese Grafiken erzeugt, animiert, Videos angezeigt und Audio abgespielt werden. 

Weitere Informationen und Beispiele finden Sie unter: https://www.mediaevent.de/html/canvas.html
https://www.w3schools.com/html/html5_canvas.asp

<h2> Scroll activated animations </h2>
Als scroll-activated animations werden Animationen bezeichnet, die erst dann ablaufen, wenn der Nutzer zu diesen gescrollt hat. Dies bedeutet, dass die Animation nicht automatisch mit dem LAden der Seit ebeginnt, sondern erst startet, wenn sich diese im Sichtbereich des Nutzers befinden. Dadurch können Elemente zum Beispiel nach und nach nit verschiedenen Effekten erscheinen. Für diese Funktionalität wird ein JavaScript benötigt, mit welchem die aktuelle Scroll-Höhe ermittelt werden kann. 

How to #scrollactivatedanimation : https://www.kirupa.com/animations/creating_scroll_activated_animations.htm

<b> Tools für Digital Storytelling Websites </b> 

https://www.pageflow.io/

https://shorthand.com/



https://storyform.co/

Quellen: Buch: Digital Storytelling im Web, Mediaevent, W3Schools
