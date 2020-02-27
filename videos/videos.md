<h1> Grundlagen zu Videos </h1>
Videos bestehen grundsätzlich aus vielen einzelnen Bildern und dem dazugehörigen Ton. Für die Aufzeichnung des Bildes sind vier unterschiedliche Werte relevant: Die Bildwiederholungsrate bzw. Bildwiederholfrequenz, die entweder in Hertz (Hz) oder in Bildern pro Sekunde (fps = frames per second) wiedergegeben wird. Je höher dieser Wert, desto mehr Bilder werden verwendet, um das Video zu erstellen, und desto größer wird die Datei. Der zweite Wert ist Farbtiefe, welche Informationen zu den Farb- und Helligkeitswerten enthält. Das Filmformat gibt drittens die Auflösung des Bildes in Pixel bzw. das Seitenverhältnis des Videos an (ZB 16:9 oder 4:3). Und viertens noch die Tonspur, welche den aufgezeichneten Klang enthält. Je höher Bildauflösung, Qualität und Länge des Videos, desto größer wird die Datei auf der Festplatte. Zur Verringerung wird Komprimierung verwendet.


Jedes Video im Web muss generell für das Abspielen auf einer Webseite vorbereitet werden: Speicherformat, Codecs, Auflösung und Bitrate sind die vier Parameter für Video im Internet.

Die Frage nach dem besten Video-Format, dem besten Codec oder der optimalen Bitrate erübrigt sich im Internet: Hier wird das genommen, was die Browser und die Internetverbindung hergeben. Video mit Plugin – das ist out.


<h2>MP4-Video </h2>
Nachdem Flash-Video über Jahre hinweg das sicherste Format für Video im Internet war, ist heute der Computer ist nicht mehr das Internet. Smartphones und Tabletts stellen auf allen Webseiten einen großen Anteil der Zugriffe und haben zum Umdenken geführt.

Auf dem iPhone und dem iPad gab es von Anfang an kein Flash-Video. Ende 2011 hat Adobe das Ende der Entwicklung des Flash-Players für mobile Geräte angekündigt. Zur Standard-Kombination für Video in HTML-Seiten gehörte lange Zeit MP4 für Safari und Internet Explorer, OGV oder WebM für Firefox und Chrome (aber Chrome zog dennoch MP4 vor). Heute spielt auch Firefox MP4-Video ab.

Auf jeden Fall müssen vier Einstellungen für jedes Video im Internet getroffen werden:

<h2> Speicherformat </h2>
Ähnlich wie bei Bildern, wo man sich zwischen JPEG, GIF und BMP entscheiden muss, muss auch für das Video ein Speicherformat festgelegt werden.

Container-Formate für Video, Bilder und PDF Schema für Video-Formate, Bild-Formate und PDF
<img src="https://www.mediaevent.de/tutorial/img/container-fuer-video-bilder-pdf-schema.png"> <br>
Videos bestehen i.d.R. aus einem Video-Track, einem oder mehreren Audio-Tracks, Untertiteln und evt. aus Metadaten wie dem Titel des Videos. Diese Tracks sind miteinander verbunden, damit Audio-Track und Untertitel immer synchron zu den gezeigten Bildern bleiben.

MP4, M4V, MOV, AVI, FLV, OGV … sind Containerformate für Videos – ähnlich wie TIF ein Container für Pixeldaten und PDF ein Container für Text und Bilder sind.

<h2> Auflösung des Videos </h2>
Zusätzlich müssen hochauflösende Videos - z.B. ein Full HD-Format mit 1920 x 1020 Pixeln – verkleinert werden. Auf der einen Seite wäre Full HD für die meisten Monitore zu groß und natürlich spart die Verkleinerung jede Menge Bandbreite.

Immerhin strebt das Video Web der HD-Auflösung (1280 x 720 Pixel) entgegen, aber zusätzlich sollte für mobile Geräte eine kleiner Version des Videos angeboten werden.

<video controls> 
   <source type="video/mp4" media="all and (min-width:680px)" src="video-large.mp4" > 
   <source type="video/mp4" media="all and (min-width:320px)" src="video-small.mp4" >  
</video>

<h2> Datenrate des Videos </h2>
Bei der Vorbereitung des Videos für das Internet wird eine Datenrate eingestellt – die erzielbare Datenrate richtet sich nach der Übertragungsleitung vom Server zum Betrachter des Videos. Für eine normale DSL-Leitung können wir z.B. eine effektive Datenrate von 1 bis 5 MBit/s annehmen, für HD-Video sollte die Datenrate 2 bis 5 MBit/s betragen.

<h2> Browserunterstützung für Videoformate </h2>
Mit der Dateiendung der Videodatei können wir Videos am einfachsten identifizieren – .avi, .mov, .mp4 oder .flv. Es gibt .mp4 (MPEG 4) und .m4v (von Apple entwickeltes Videoformat, wie mp4, aber mit optionalem DRM-Kopierschutz), .flv (Flash Video), .ogv (OGG) und Google kommt mit webM.

Browser spielen nur eine begrenzte Zahl von Videoformaten von Haus aus ab. Ältere Browser wie Internet Explorer 8 brauchten ein Plugin, z.B. das Flash-Plugin oder ein Quicktime-Plugin. Mit HTML5 bringen alle Browser ein Videoformat von Haus aus mit.

Nach anfänglichen Differenzen können heute alle modernen Browser MP4 abspielen – auch Firefox. Firefox war lange auf OGV bzw. WebM beschränkt, aber da Google Chrome weiterhin MP4 abspielt und Cisco eine Open Source-Version von H.264 auf Github zur Verfügung stellt, hat sich Firefox der Mehrheit angeschlossen und spielt nun ebenfalls MP4 ohne Erweiterung oder Plugin ab.


Eines Tages sind die Server sicher schnell genug, um Videos on the fly von einem Format in ein anderen zu konvertieren, aber bis dahin müssen Videos »auf Vorrat« in die gängigen Formate konvertiert werden. Ein einfaches Programm zum Konvertieren von MP4- oder MOV-Videos in OGV oder WebM ist z.B. ffmpeg2theora, zum Konvertieren von Videos in MP4 bzw. M4V ist Handbrake.


<img src="https://www.mediaevent.de/tutorial/svg/handbrake.svg">
Video zu MP4 konvertieren und Web-Optionen in Handbrake <br>
<ul>
<li> MP4 (MPEG-4-Dateiformat) | Standard-Containerformat für MPEG-4-ASP-/-AVC-Videostreams; basiert auf dem Quicktime-Containerformat. </li>
<li> OGG | ein Format für Firefox, das sowohl Audio als auch Video enthalten kann.</li>
<li>OGV | heute setzt Firefox auf OGV für Video und ogg oder oga für Audio.</li>
<li>webM | Google wollte urprünglich webM als Standard für Video im Internet etablieren.</li>
<li>FLV Flash Video von Adobe Systems | Flash Video (.flv) ist ein für Webstreaming optimiertes Format. Allerdings muss im Webverzeichnis des Servers ein Shockwave-Player liegen, denn flv kann nicht direkt abgespielt werden, sondern braucht einen Shockwave-Player.</li>
</ul>
<li>AVI (Audio Video Interleave) | das wahrscheinlich überflüssigste Containerformat, das wir jetzt endgültig begraben können.

<em> Quelle: https://www.mediaevent.de/tutorial/html-video.html </em>

<h2> Free-Tools zur Videobearbeitung </h2>

<a href="https://www.blender.org/">Blender </a> <br>
<a href="https://www.lwks.com/"> Lightworks </a> <br>
<a href="https://shotcut.org/"> Shotcut</a>

<h2> Einbindung von Video mit HTML 5 </h2>

Durch stetige Weiterentwicklung des Webs können Videos immer problemloser eingebunden und verbreitet werden. Geschah dies früher umständlich über ein Plug-In, wie zum Beispiel Flash, werden Videos heute von den modernen Browsern, wie Chrome, Firefox, Edge, Safari und Opera, nativ unterstützt. 
<br>
<b> Codebeispiel:  </b> <br>
<video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4">
  <source src="movie.ogg" type="video/ogg">
  Your browser does not support the video tag.
</video>

<br>
<b> Beispiel: </b>
Wie auf der Website ge.com/digitalvolcano ersichtlich, ist in dem Hintergrundvideo eine Bewegung in Form von einer Kamerafahrt erkennbar. 
