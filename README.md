# Background & Background-Images

Ein Background kann genutzt werden um Webseiten besser sichtbar, wie auch angenehmer für das Auge zu machen.
Bei einem farbigen Hintergrund sollte der Inhalt der Seite nicht änlich farbig sein wie der Hintergrund.

## Beispiel:

background: green;
color: black;

## Background-Image

Background-Images können mittels `background-image` oder `img` tag eingefügt werden. Sie können dann lokal gespeichert in img Ordner oder mit Weblink unter `url` oder `src` beigefügt werden.

<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <meta http-equiv="X-UA-Compatible" content="IE=edge" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <title>Background</title>
    </head>
    <body>
        <img
            src="https://images.unsplash.com/photo-1599420186946-7b6fb4e297f0?ixlib=rb-1.2.1&ixid=MnwxMjA3fDF8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=987&q=80"
            alt="Bild von Schreibtisch mit skitzen und eoinem Laptop"
        />
    </body>
</html>

Background kann auch unterschiedliche Farben oder Bilder haben. Will man zwei Bilder nebeneinander kann man das so machen `background-image: url("img_tree.gif"), url("paper.gif");`. Danach gibt man an ob Bilder wiederholt werden sollen, mit `background-repeate` und no-repeate oder repeate.
