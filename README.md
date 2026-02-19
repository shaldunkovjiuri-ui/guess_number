Description
A console-based game where the computer selects a random integer between 1 and 100, and the user attempts to guess it by receiving "higher" or "lower" hints.

Implemented Logic
The program utilizes an infinite while loop with the following logic:

Number Generation: Employs randint(1, 100) from the random module.

Input Handling: Converts user input into an int type.

Comparison Engine:

If the guess is lower than the target — prompts the user to try a higher number.

If the guess is higher than the target — prompts the user to try a lower number.

Upon a match — terminates the loop and displays a success message.
______________________________________________________________________________
Beschreibung
Ein konsolenbasiertes Spiel, bei dem der Computer eine zufällige Ganzzahl zwischen 1 und 100 generiert.
Der Benutzer muss diese Zahl erraten und erhält dabei Hinweise («größer» oder «kleiner»).

Implementierte Logik
Das Programm basiert auf einer Endlosschleife (while) mit folgender Logik:

Zahlengenerierung: Verwendung der Funktion randint(1, 100) aus dem random-Modul.

Eingabeverarbeitung: Konvertierung der Benutzereingabe in den Datentyp int.

Vergleichslogik:

Wenn die Schätzung niedriger ist — Hinweis, dass die gesuchte Zahl größer ist.

Wenn die Schätzung höher ist — Hinweis, dass die gesuchte Zahl kleiner ist.

Bei Übereinstimmung — Beendigung der Schleife und Ausgabe einer Erfolgsmeldung.
