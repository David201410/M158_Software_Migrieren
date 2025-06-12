# Unterschied zwischen absoluten und relativen Pfaden

## Lokal
Folgende Datenstruktur ist schlaggebend:

```
C:\Daten\Bilder
C:\Daten\CSS
C:\Daten\index.html
C:\Daten\Bilder\Blume.jpg
C:\Daten\Bilder\test.html
C:\Daten\CSS\main.css
```

- **Wie ist der absolute Pfad von der Datei "main.css"?**
    - C:\Daten\CSS\main.css

- **Angenommen, Sie wollen in der "index.html" Datei das Bild "Blume.jpg" einfügen, wie ist der relative Pfad zum Bild?**
    - \Bilder\Blume.jpg

- **Sie wollen von der Datei "main.css" auf das Bild "Blume.jpg" zugreifen, wie ist der absolute Pfad?**
    - C:\Daten\Bilder\Blume.jpg

- **Sie wollen von der Datei "main.css" auf das Bild "Blume.jpg" zugreifen, wie ist der relative Pfad?**
    - ..\Bilder\Blume.jpg

- **Sie wollen von der Datei "test.html" auf das Bild "Blume.jpg" zugreifen, wie ist der relative Pfad?**
    - \Blume.jpg

## Im Netz
Domain: ihreadresse.ch
Lokaler Root-Pfad: /srv/var/www/htdocs
Document Root: /htdocs
Dateien:


Ordner 1 (innerhalb htdocs): wp-content/uploads/2022/5/Dokument.pdf


Ordner 2 (innerhalb htdocs): wp-content/plugins/neon/files/download.php


- **Wie ist der lokale & absolute Pfad auf Dokument.pdf?**
    - **Lokal**: wp-content/uploads/2022/5/Dokument.pdf
    - **Absolut**: /srv/var/www/htdocs/wp-content/uploads/2022/5/Dokument.pdf

- **Wie ist der lokale & absolute Pfad auf download.php?**
    - **Lokal**: wp-content/plugins/neon/files/download.php
    - **Absolut**: /srv/var/www/htdocs/wp-content/plugins/neon/files/download.php

- **Wie lautet die URL von Dokument.pdf?**
    - https://ihreadresse.ch/wp-content/uploads/2022/5/Dokument.pdf

- **Wie ist die URL von download.php?**
    - https://ihreadresse.ch/wp-content/plugins/neon/files/download.php

- **Sie möchten in der Datei download.php einen Link auf das Dokument.pdf herstellen. Wie lautet der relative Pfad?**
    - ../../../uploads/2022/5/Dokument.pdf