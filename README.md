# Bazaro 2027 – einfache Fassung

## Ziel
So wenig Technik wie möglich.

Im Repository liegen nur:
- `index.html`
- `README.md`
- genau **ein** Hintergrundbild

Das Hintergrundbild darf beliebig heißen, zum Beispiel:
- `Bazaro Frühherbst.PNG`
- `Winter am See.jpg`
- `IMG_4711.jpeg`

Die Seite findet dieses eine Bild automatisch.

## Bild wechseln
1. Altes Hintergrundbild auf GitHub löschen.
2. Neues Bild mit seinem normalen Dateinamen hochladen.
3. Committen.
4. GitHub Pages veröffentlicht den neuen Stand.

Keine `admin.html`, kein Token, kein `active-image.txt`, kein Häkchen und keine Automatik.

## Countdown
Zieldatum: **17.09.2027**

Die Anzeige lautet:
- `noch`
- automatisch berechnete Tageszahl
- `Tage`

Die Zahl wird aus dem aktuellen Kalendertag und dem Zieldatum berechnet.
Nach jedem Tageswechsel sinkt sie automatisch um 1; am Zieldatum steht sie auf 0.

## Wichtig
Es darf absichtlich nur **eine** JPG/JPEG/PNG/WEBP-Datei im Hauptverzeichnis liegen.
Sind mehrere vorhanden, zeigt die Seite eine klare Fehlermeldung statt zufällig das falsche Bild zu verwenden.
