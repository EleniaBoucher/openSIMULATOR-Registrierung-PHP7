# Grid-Avatar-Registrierung-PHP7
Eine Grid Avatar Registrierung für den OpenSimulator um einen neuen Benutzer in einer Virtuellen Welt anzulegen.

Dies ist eine vorab Version die gerade im Testbetrieb läuft.

Diese Registriert jetzt den Avatar und installiert die Verzeichnisse.

Der unterschied zu anderen arten einen neuen Avatar anzulegen, 
ist hier das direkte hineinschreiben in die Datenbank.

Es brauchen deswegen keine Einstellungen im OpenSimulator oder im Robust vorgenommen werden.

Der Nachteil ist der Avatar ist leer also eine Wolke.

Im Inventar befindet sich aber das Standard Inventar, 
so das man seinen Avatar mit wenigen Klicks erstellen kann.

Zum Upgraden oder zum erweitern von openSIMULATOR-SPLASH-PHP7, 

wird nur die Datei createavatar.php benötigt alles andere könnt ihr so belassen.

.

### ACHTUNG Es wird in eure Datenbank geschrieben, Benutzung ausdrücklich auf eigene Gefahr!!!

.

    Verzeichnis /includes beschreibbar machen.

    install.php starten und angaben ausfüllen, anschließend Install anklicken.

    createavatar.php aufrufen und testen.

    Das beschreibbar machen des Verzeichnis /includes rückgängig machen.

    install.php löschen.

Fertig!

.

V079 Einfache Captcha eingefügt

V075 Einige Prüfungen habe ich jetzt eingefügt.

Alles muss ausgefüllt werden,
eine Anmeldung mit fehlenden angaben führt zu Beendigung des Programms.

Max Mustermann und Bettina Mustermann können sich anmelden aber nicht zweimal mit dem gleichen Namen.

Beispiel: Wenn es bereits einen Max Mustermann gibt muss der Vorname und/oder der Nachname geändert werden.

E-Mail wird auf Gültigkeit geprüft, Fehler führen zur Beendigung des Programms.

Passwort wird mit der Passwortwiederholung geprüft, Fehler führen zur Beendigung des Programms.



TODO:

Benutzer der Registrierung (IP, Datum, Uhrzeit, usw.) Speichern

Captcha einfügen
