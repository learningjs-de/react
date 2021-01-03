# Einfache Listendarstellung

* Erzeuge eine Komponente mit dem Namen List
* Diese Komponente soll alle Daten über die fetch-API des Browsers vom Backend (http://localhost:8080/books) laden
* Die Datensätze sollen in einer Tabelle dargestellt werden
* Informationen die angezeigt werden sollen:
  * title: Der Titel des Buchs
  * author: Der Autor
  * isbn: Die ISBN
  * rating: Die Bewertung
* Sind keine Informationen im Backend vorhanden, soll der Text "Keine Bücher gefunden." angezeigt werden.

## Hinweise zur Implementierung
* Die Zellen der Tabelle müssen jeweils eine Eigenschaft `data-testid` mit ihrem Typ enthalten. Also für title dann die Eigenschaft `data-testid="title"`
* Vorbereitung:
  * Das Projekt lokal klonen
* Backend starten: 
  * Eine eigenständige Konsole öffnen.
  * Auf der Konsole in das Verzeichnis bookshelf wechseln
  * `npm run backend` eingeben
* Frontend starten:
  * Eine eigenständige Konsole öffnen.
  * Auf der Konsole in das Verzeichnis bookshelf wechseln
  * `npm start` eingeben
* Aufgabenlösung überprüfen:
  * Eine eigenständige Konsole öffnen.
  * Auf der Konsole in das Verzeichnis bookshelf wechseln
  * `npm test aufgabe1` eingeben
