# Myproject

My first Website
Beschreibung der Beispielwebseite:

Zuerst habe ich den Befehl !DOCTYPE html angegeben. Damit wird der Dokumententyp angegeben, sodass der Browser weiß, um welche Version von HTML
es sich handelt.
head ist der Kopfbereich des Dokuments. Hier stehen Informationen über das Dokument, wie z. B. ein Zeichensatz oder Titel.
html lang="de" steht dafür, dass das Dokument auf Deutsch verfasst ist.
meta charset="UTF-8" stellt sicher, dass Sonderzeichen wie ä,ü und ö oder ß richtig dargestellt werden.
Die nächste meta-Angabe ist dafür da, dass die Seite sich auch auf kleinen Bildschirmen anpassen kann.
<meta name="description" liefert eine Beschreibung der Webseite.
Der eigentliche Inhalt der Seite steht innerhalb von <body>. Dort habe ich die Überschrift h1 definiert und ihr mit dem Befehl
<link rel= "stylesheet" href="stil css"> einen Stil mit Verweis auf die CSS-Datei zugewiesen.
Mit dem Befehl <style> habe ich der Überschrift 1 direkt einen grauen Hintergrund hinzugefügt.
Die Befehle header, article, nav und main sind für die Struktur der Webseite hilfreich. Der Befehl header ist der Kopfbereich. Im Unterschied zu head
kann header Inhalte auf der Seite darstellen. 
Der Befehl <nav> ist für die Seitennavigation vorgesehen. Innerhalb des Befehls <nav> kommen die Besucher über die Links zu anderen Webseiten.
<main> stellt den Hauptteil der Webseite dar. Article Elemente sind Inhalte, die auch eigenständig existieren können. Man kann sie beispielsweise
mit einem Blogeintrag vergleichen. <footer> kennzeichnet den Fußbereich. Über den Befehl "ul" = unordered list, habe ich eine ungeordnete Liste erstellt.
Mit "li" stelle ich die Aufzählungspunkte dar. Der Befehl "a href" macht aus den Aufzählungspunkten Links. href verweist auf andere Webseiten. Mit Klick auf den
Link wird man direkt auf eine andere Webseite verwiesen. Im Projekt selbst habe ich noch zwei Bilder eingebaut. Mit dem Befehl "img src" können 
die Bilder eingefügt werden. Sie müssen sich jedoch im gleichen Ordner wie die html Datei selbst befinden. <figcaption> hat die Funktion einen Text
beim Bild einzufügen. Mittels <p> habe ich die Zeilenumbrüche gemacht. Das letzte Tool, das ich eingebaut habe, ist das Tool <script>
Mittels <script>alert("Hallo Welt") scheint ein Kästchen auf, bevor man auf die Seite kommt. Dieses zeigt den Text Hallo Welt an.
  
Beschreibung CSS-Dokument:
CSS-Dokument Beschreibung:
Um mein HTML-Dokument mit CSS zu verknüpfen,  habe ich einen Befehl <link rel="stylesheet" href"stil css"> eingebunden, um das Html Dokument mit CSS
zu verbinden. 
"color" eingeleitet. Wenn man Abstände zwischen den Elementen haben möchte, so gibt man den Befehl "margin" an.

Der Übeschrift "h1" habe ich mittels font-size auch die entsprechende Schriftgröße zugewiesen.
font-weight soll die Schrift fett oder normal darstellen, font-weight normal (nicht fett), font-weight bold (fett)
Mit dem Befehl text-align: center habe ich die Schrift zentriert. Den Abstand zwischen Text und Rand habe ich bei der Überschrift h1 auf 2rem gesetzt.
Der Abstand zwischen den Elementen liegt bei 0.

Danach habe ich Navigationen eingebaut. nav a{ und nav ul{ sind eigene Klassen. Für die eigentliche Navigation habe ich die Hintergrundfarbe grau gewählt.
Die nav a{ hat keine eingeleitete Textfarbe. Dort habe ich den Innenabstand 0.8 festgelegt. 

Bei nav ul{ habe ich den Abstand zwischen den Elementen auf 0 gesetzt. Mit list style none werden normalerweise Aufzählungszeichen ausgeblendet.

Den Hauptbereich main habe ich mit einer maximalen Breite von 62rem definiert. Der Abstand zwischen den Zeilen ist auf auto gesetzt (margin auto).

Beim article Bereich habe ich für die Inhalte eine Maxialbreite von 50% definiert und der Abstand zwischen den Zeilen ist auf 2rem.

Beim footer (Fußbereich der Webseite) habe ich mittels background-color die Hintergrundfarbe festgelegt und mittels color die Schriftfarbe. Mittels padding
ist der Abstand zwischen Text und Rand bei 2rem. Der Abstand oberhalb der Zeilen (margin-top) ist auf 1rem gesetzt.

Mit der Klasse .bildlinks habe ich versucht habe ich auch mit dem Befehl float left versucht den Text um das Bild herum umfließen zu lassen.
Der Abstand ist auf 0,5rem rechts gesetzt.
