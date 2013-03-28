---
layout: doc
title: Erste Schritte beim Editieren
permalink: /de/beginner/start-josm/
lang: de
category: beginner
---

Erste Schritte beim Editieren mit JOSM
======================================

In diesem Kapitel werden wir Schritt für Schritt lernen, wie man JOSM, 
den Java OpenStreetmap Editor, herunterlädt und installiert. Damit die 
Benutzung einfacher wird, werden wir ein paar Enstellungen verändern. 
Anschließend werden wir eine Beispielkarte öffnen, und einige der 
grundlegenden Arbeitsschritte der Software lernen. Erinnerst du dich 
an das erste Kapitel, in dem du eine Karte deines Wohnortes zeichnen 
solltest? Wir werden dieses Kapitel abschließen indem wir die Karte 
noch einmal zeichnen, dieses Mal allerdings digital. Hiernach solltest 
du ein gutes Verständnis davon haben, wie man in JOSM Karten erstellt.

JOSM Herunterladen
------------------

- Wenn du bereits eine Version von JOSM auf CD oder einem USB-Stick 
  hast, kannst du direkt zu Schritt 2, "JOSM Installieren" springen.
- Wenn du JOSM noch nicht hast, oder die aktuellste Version haben 
  möchtest, öffne deinen Browser - dies könnte Firefox, Chrome, Opera 
  oder Internet Explorer sein.
- Gebe am oberen Rand des Fensters in der Adresszeile folgenden Link 
  ein und drücke Enter:[josm.openstreetmap.de](http://josm.openstreetmap.de)
- Du kannst die Seite auch finden, indem du einfach nach "JOSM" suchst.
- Die Webseite sollte dann in etwa so aussehen:

  ![]({{site.baseurl}}/images/start_josm_image05_en.png)

- Falls du Windows auf deinem Computer installiert hast, klicke auf 
  "Windows Installer", um JOSM herunterzuladen. Wenn du ein anderes 
  Betriebssystem benutzt, klicke auf den entsprechenden Link für dein 
  System. Die Datei sollte dann automatisch heruntergeladen werden. In 
  diesem Kapitel werden wir davon ausgehen, dass du Windows benutzt, 
  aber die Vorgehensweise ist für andere Betriebssysteme ähnlich.

JOSM Installieren
-----------------

- Es kann sein, dass du bei der Installation von JOSM Probleme hast, 
  falls Java noch nicht auf deinem Computer installiert ist. Sollte das 
  der Fall sein, versuche Java herunterzuladen und zu installieren:
  [http://www.java.com/de/download/](http://www.java.com/de/download/)
- Suche die JOSM-Installationsdatei und doppelklicke sie, um die 
  Installation zu starten.
- Klicke "OK", "Weiter", "Annehmen", "Weiter" und "Installieren". Wenn 
  die Installation abgeschlossen ist, klicke "Weiter" und "Fertig 
  stellen", um JOSM das erste Mal zu starten. Wenn du später JOSM 
  starten willst, klicke auf das Startmenu in der unteren linken 
  Ecke deines Desktops, und anschließend auf das Programm JOSM.
- Möglicherweise siehst du ein Fenster, welches fragt, ob du JOSM 
  aktualisieren willst. Da die Software neu ist, ist dieses nicht 
  notwendig. Klicke daher auf 'Aktualisierung überspringen'. Falls du 
  diese Nachricht nicht mehr sehen willst, aktiviere das Auswahlfeld 
  im unteren Teil des Fensters.
- Wenn JOSM gestartet ist, wird es in etwa so aussehen:

  ![]({{site.baseurl}}/images/start_josm_image08_en.png)

JOSM Einstellungen ändern
-------------------------

Bevor wir Anfangen, JOSM zu benutzen, ist es sinnvoll ein paar 
Einstellungen zu ändern, damit es einfacher zu benutzen wird. Klicke 
dafür im oberen Menu auf "Bearbeiten" und anschließend auf "Einstellungen".

![]({{site.baseurl}}/images/start_josm_image13_en.png)

### Bing Sat hinzufügen

- Wir möchten die Möglichkeit haben, Satellitenbilder zu nutzen, um 
  unsere Karten zu erstellen. Auf der linken Seite des 
  Einstellungen-Fensters sind verschiedene Symbole für diverse 
  Einstellungen. Klicke nun auf das Symbol, welches mit "WMS TMS" 
  beschriftet ist. Möglicherweise musst du auf den Pfeil nach unten 
  klicken, um das Symbol zu finden:
  
  ![]({{site.baseurl}}/images/start_josm_image07_en.png)
  
  ![]({{site.baseurl}}/images/start_josm_image02_en.png)

- Klicke nun auf on “Bing Sat”. Dann klicke auf “Aktivieren”.

  ![]({{site.baseurl}}/images/start_josm_image11_en.png)

- Nun sollte “Bing Sat” in der Liste unter der Aktivieren-Schaltfläche 
  erschienen sein.

### Vorlagen hinzufügen

- Solltest du eine Datei haben welche zum Vorlagen-Menu hinzugefügt 
  werden soll, kannst du diese nun hinzufügen. Eine solche Datei könnte 
  zum Beispiel buildings.xml heißen.
- Solltest du das Einstellungen-Fenster nicht mehr geöffnet haben, 
  klicke erneut auf "Bearbeiten" und anschließend auf "Einstellungen" 
  um das Fenster erneut zu öffnen.
- Klicke nun auf der linken Seite auf das Symbol, welches wie ein Raster 
  aussieht:

  ![]({{site.baseurl}}/images/start_josm_image09_en.png)

- Klicke in der oberen Leiste nun auf den Reiter "Objektvorlagen".
- Klicke die "+" Schaltfläche oben rechts.
- Klicke nun auf das Ordnersymbol rechts neben dem zweiten Eingabefeld. 
  Navigiere zur Vorlagendatei, welche du hinzufügen willst, zum 
  Beispiel buildings.xml.
- Klicke OK.

### Walking Papers Erweiterung hinzufügen

- Später werden wir in dieser Anleitung etwas über das Walking Papers 
  Werkzeug erfahren, welches uns erlaubt, einen Kartenausschnitt 
  auszudrucken, darauf zu zeichnen und Notizen zu machen und es 
  anschließend in JOSM als Hintergrund zu laden. Dann können wir unsere 
  Zeichnungen und Notizen in OpenStreetMap hinzufügen. Nun werden wir 
  zunächst die Walking Papers Erweiterung zu JOSM hinzufügen.
- Solltest du das Einstellungen-Fenster nicht mehr geöffnet haben, 
  klicke erneut auf "Bearbeiten" und anschließend auf "Einstellungen" 
  um das Fenster erneut zu öffnen.
- Klicke nun auf der linken Seite auf das Symbol, welches wie ein 
  Stecker aussieht:

  ![]({{site.baseurl}}/images/start_josm_image04_en.png)

- Klicke nun auf die Schaltfläche "Liste herunterladen". Nun wird eine 
  Liste mit optionalen Erweiterungen aus dem Internet geladen, welche 
  nach kurzer Zeit erscheint.
- Gebe nun in der Suchleiste im oberen Teil des Fensters "walking" ein. 
  Daraufhin werden nur noch die Elemente der Liste angezeigt, welche 
  das Wort "walking" im Titel haben.
- Klicke nun in das Auswahlkästchen neben der walkingpapers Erweiterung 
  und klicke OK im unteren Teil des Fensters.
- Die Erweiterung wird nun heruntergeladen und installiert. Klicke 
  nicht auf "Abbrechen".

### Sprache einstellen

- JOSM wurde bereits in eine Vielzahl von Sprachen übersetzt. Wenn JOSM
  schon in deine Sprache übersetzt wurde, kannst du diese in den 
  Einstellungen aktivieren.
- Öffne das Einstellungen-Fenster über Bearbeiten -\> Einstellungen,
  wenn du es noch nicht geöffnet hast.
- Klicke auf der linken Seite auf das oberste Symbol, es sieht aus wie
  ein Pinsel mit einem Topf Farbe.
- At the top of the window, click the tab that says “Look and Feel”.
- Klicke jetzt im rechten Teil des Fensters auf den Reiter “Verhalten
  und Aussehen”.
- Wähle deine Sprache im Auswahlfeld neben dem Wort “Sprache”.
- Klicke OK.
  
  ![]({{site.baseurl}}/images/start_josm_image01_en.png)

- Du musst den JOSM Editor neu starten, damit diese Einstellung 
  gespeichert wird. Klicke dazu auf das Menü “Datei” in der linken 
  oberen Ecke, dann wähle “Beenden” am unteren Ende des Menüs.
- Starte den JOSM Editor erneut indem du das Windows Start Menü in 
  der linken unteren Ecke des Bildschirm öffnest. Gib “JOSM” in die 
  Suche ein oder wähle es über “Alle Programme” aus.

Learn Basic Drawing with JOSM
-----------------------------

- Now let’s open up a sample OSM file which we will use to learn the
  basic ways to draw maps with JOSM. Note that this map is not real,
  in that it is not a real map of a real place, so we will not save it
  on OpenStreetMap.
- If you were given a set of files by your instructor, you should
  already have the file we will open, named sample.osm.
- If you don’t have the file sample.osm on your computer, you can
  download it from the internet. Open your internet browser. In the
  address bar at the top of the window, enter the following text:
  [http://www.learnosm.org/files/](http://www.learnosm.org/files/)
- With your mouse, right click on the file called sample.osm, and click
“Save Link As...” Choose a location on your computer to save the file.
- Now let’s open the sample map file in JOSM. Open JOSM. Click the
  “Open” button in the upper left.

  ![]({{site.baseurl}}/images/start_josm_image12_en.png)

- Find the file sample.osm. Click on it, and then click “Open”.
- You should now see a sample map, similar to this:

  ![]({{site.baseurl}}/images/start_josm_image03_en.png)

### Basic Operations

- To move the map left or right, up or down, hold your right mouse
  button down, and move your mouse.
- There are several ways to zoom in and out of the map. If you have a
  mouse, you can use your scroll wheel to zoom in and out. If you are
  using a laptop and don’t have a mouse, you can zoom in and out using
  the scale bar in the upper left of the map window. Drag the bar left
  and right by holding your left mouse down and moving the bar left or
  right with your mouse.

  ![]({{site.baseurl}}/images/start_josm_image14_en.png)

-  Look at the sample map. There a few different types of objects here.
   There is a river, a forest, some buildings, several roads, and a
   couple of shops. To select an object, click on it with your left
   mouse button.

### Points, Lines, and Shapes

- As you click different objects on the sample map, notice that there
  are three different types of objects on the map. There are points,
  lines, and shapes.
- Points are a single location, represented by symbols. On this sample
  map, there are two points, a clothing shop and a market. The
  clothing shop is represented by a shirt symbol, and the market is
  represented by a shopping cart.
- There are several lines on the map as well, which represent roads.
  If you look closely you will see that within the lines, there are
  points as well. These points don’t have any symbols or other
  information associated with them, but they help to define where the
  line is located.
- Lastly, there are numerous shapes on the sample map, representing
  different places - a forest, a river, and buildings. A shape
  generally represents an area, like a field or a building. A shape is
  exactly like a line - the only difference is that the line begins at
  the same point where it ends.
- You may notice that when you select an object, a list appears to the
  right of the map in a window called “Properties”. These are known as
  tags. Tags are information that is tied to a point, line or shape
  that describes what it is. We’ll learn more about tags in Chapter 7,
  Advanced Editing. For now all you need to know is that this
  information helps describe whether our object is a forest, a river,
  a building, or something else.
- Think about drawing a map by hand, and how you are also drawing
  points, lines, and shapes. What other places are best represented by
  points? Lines? Shapes?

### Changing Objects

- Select the forest on the left side of the map. Be sure to click on
  the line around the forest, not one of the points on the line. Now
  hold your left mouse button down and drag your mouse. You should be
  able to move the forest to a new location on the map.
- Click on one of the points on the line around the forest. Hold your
  left mouse button down and drag your mouse. You should be able to
  move the point. This is how you can change the shape of an object,
  or move a point.

### Drawing

- On the left side of a JOSM is a column of buttons. Many of these
  buttons open new windows on the right side that provide more
  information about the map. The most important buttons, however, are
  at the top of these column. These buttons change what you can do
  with your mouse.
- The top four buttons in this column are the most important. They
  allow you to:

  1.  Select
  2.  Draw
  3.  Zoom in
  4.  Delete

- Until now, you have been using the Select tool, which looks like
  this:

  ![]({{site.baseurl}}/images/start_josm_image00_en.png)

- Before you draw, you need to make sure that nothing is selected.
  Click in the black space on the map, where it is empty, to make sure
  nothing is selected.
- Click on the second button, the Draw tool.

  ![]({{site.baseurl}}/images/start_josm_image10_en.png)

- Find an empty area on the map, and double-click with your mouse.
  This will draw a single point.
- To draw a line, single-click with your mouse. Move your mouse and
  click again. Continue until you are happy with your line. To end the
  line, double-click your mouse.
- Draw a shape the same way that you draw a line, but finish the shape
  by double-clicking on the point where you started the line.

### Add Presets

- Now we know how to draw points, lines and shapes, but we still
  haven’t defined what they represent. We want to be able to say that
  our points are shops, schools, or something else, and whether our
  shapes are fields, buildings, or something else.
- Click on the Select tool, in the column of buttons on the left.

  ![]({{site.baseurl}}/images/start_josm_image00_en.png)

- Select one of the objects that you drew with the Draw tool. On the
  top menu, click “Presets”. Move your mouse through the sub-menu to
  the type of location you would like to define.
- When you click on a preset, a form will pop up asking you for more
  information. You do not have to fill in every field, but you may
  wish to add some of the important fields, such as the name of the
  object.
- When you are finished entering the information, click “Apply
  Preset”. If everything went well, your point, line, or shape should
  change colors or show a symbol. This is because you have defined
  what it is.

Draw Your Own Map
-----------------

- Now let’s draw a map in order to practice the techniques you have
  learned. You may wish to redraw the map that you drew on paper in
  Chapter 1.
- Drag the map away from the sample map. Hold the right mouse button
  and drag your mouse, until you have a nice empty area to draw on.
- Use the Draw tool to create points, lines, and shapes. Describe what
  your objects are by selecting from the Presets menu.
- When you are finished, you should have your own map, similar to the
  sample map that we opened in sample.osm.

Summary
-------

Excellent! If all went well you have learned how to setup JOSM on your
computer, and the basic tools for drawing maps. In the next two
chapters, you will learn how to use GPS and Walking Papers to map your
town or village. In Chapter 6, we will return to JOSM and using the
information we collected, we will add objects to OpenStreetMap.