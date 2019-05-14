## User Story 1 ([Vorname Nachname])

[Als WG-Bewohner möchte ich die Temperatur im Raum ablesen können, damit ich dadurch bei erhöhten Temperaturen ein Ventilator /hatte die Idee das wir hier einen 12V PC Lüfter verwenden können, ein Arduino kann diesen ansteuern/ einschaltet und ich die Temperatur durch Heizen bzw Lüften anpassen kann.]

### Zielkriterien

* Z1.1: [Die Temperatur muss mittels eines Thermosensors gemessen werden.]
* Z1.2: [Die Temperatur soll graphisch angezeigt werden (LCD Display oder LED "Ampel"?).]
* Z1.3: [Die gewünschte Temperatur soll mittels Eingabe vorgegeben werden.]
* Z1.4: [Ist die Temperaturabweichung groß, so soll ein Ventilator den Benutzer kühlen.]

## User Story 2 ([Vorname Nachname])

[Als Bewohner einer Wohnung möchte ich eine einfache Alarmalage haben, die, sofern sie eingeschaltet ist, Licht und Ton Signale von sich gibt, damit unbefugte Besucher nicht lautlos das Zimmer betreten können.]

### Zielkriterien

* Z2.1: [An/Ausschalten der Alarmanlage über Infrarot FB.]
* Z2.2: [Bewegungssensor muss Bewegung wahrnehmen und Signal senden.]
* Z2.3: [Ein Ton muss erklingen/Licht muss aufleuchten.]
* Z2.4: [Die Alarmanlage muss über die Fernbedienung abschaltbar sein.]

## User Story 3 ([Vorname Nachname])

[Als armer Student möchte ich, dass das Licht in meinem Zimmer bei Sonnenuntergang automatisch angeht, damit ich vorher nicht unnötig Strom verschwende.]

### Zielkriterien

* Z3.1: [Lichtintensität am Fenster Messen.]
* Z3.2: [Bewegungssignal.]
* Z3.3: [Licht anschalten/ausschalten.]
* Z3.4: [Steuereung über die Infrarot FB.] /* Hier nur die Idee: Arduinos können LED Strips ansteuern und das ganze dann als "Nachtlicht" ansteuern wenn der LED strip z.b. unterm Bett ist da ist nur wieder die Frage ob das dann genug Abweichung vom User Story 2 hat. Sonst wäre es einfacher als mit dem Photosensor zu arbeiten*/ 

## User Story 3 Alternarive ([Vorname Nachname])

[Als armer Student möchte dass das Licht nur an geht, wenn ich den Raum betrete/mich bewege, damit ich Strom spare.]

### Zielkriterien

* Z4.1: [Einstellung der 3 Modi (Dauer an, aus, Bewegung).]
* Z4.2: [Einbindung über Infrarot FB.]
* Z4.3: [Bewegung feststellen.]
* Z4.4: [Licht für 3 Minuten anschalten (habe gegoogelt, timer ist möglich).]

## User Story 4 ([Vorname Nachname])

[ Als Altbau-Bewohner möchte ich die Luftfeuchtigkeit in meinem Zimmer messen und optisch signalisiert bekommen wenn sie zu hoch ist, damit es nicht zu Schimmelbefall kommt.]

### Zielkriterien

* Z2.1: [Lufthfeuchtigkeit messen.]
* Z2.2: [Sollwert über GUI bestimmen.]
* Z2.3: [Ist-Wert der Luftfeuchtigkeit soll geloggt werden.]
* Z2.4: [Lichtsignal (LED Ampel?) wenn der Soll-Wert überschritten ist.]