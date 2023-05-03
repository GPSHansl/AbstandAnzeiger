# AbstandAnzeiger

Kleines Werkzeug zur visuellen Darstellung von Fahrbahnen, Fahrzeugen und dem Seitenabstand zu einem Fahrradfahrer.

## Basis

Die Kommandozeilenversion, welche als Basis für diese JavaScript-Seite dient, findet sich unter (https://gitlab.com/joschtl/ueberholabstand/).

## Docker

Docker-Image bauen und starten:
```
    docker build -t apache-abstandanzeiger .
    docker run -dit --name my-abstandanzeiger-app -p 8080:80 apache-abstandanzeiger
```

Aufruf:
```
    http://localhost:8080
```

## Todo
- Speichern des Canvas 
  - Dateiformate: SVG, PNG oder JPG
  - Berechnung/Export mit optimaler Höhe
- weitere Fahrzeuge wählbar
- Verschieben/Ändern der Maße direkt mittels der fabric.js-Funktionen 
