Softwaretechnologie: Java 2

# Übung 1

## a) Fehler finden

In der Datei `a/A.java` findet sich Code, der das folgende tun soll: Ein Array soll mit zufälligen Zahlen gefüllt werden. Ist die Summe der Zahlen im Array größer als 750, soll "Hello World" ausgegeben werden. Leider ist der Code voller Fehler. Finden und beheben Sie sie!

## b) Geldautomat

In der Datei `b/ATM.java` finden Sie den Quellcode für einen Teil einer Geldautomaten-Steuerungslogik. Damit kann die folgende Interaktion durchgeführt werden:

```
exercise-01$ java b/ATM
Enter the amount to withdraw: 21
Enter the amount to withdraw: 452
Enter the amount to withdraw: 5.6
```

Wie Sie sehen, kann der Geldautomat nur mit ganzen Zahlen operieren und stürzt ab, wenn etwas anderes eingegeben wird. Es gibt verschiedene Verbesserungen, die wir in den nächsten Wochen am Geldautomat vornehmen wollen. Heute wollen wir die `ATM`-Klasse erstmal so verändern, dass sie überprüft, ob der Benutzer genug Geld zur Verfügung hat, und eine passende Fehlermeldung ausgibt, wenn das nicht der Fall ist. Der Kontostand sollte sich dann auch im Laufe einer Sitzung verändern, also mitgespeichert werden, wie viel die Benutzerin noch übrig hat. Wir gehen hier der Einfachheit halber davon aus, dass der Geldautomat immer genügend Bargeld zur Verfügung hat, und schreiben den initialen Kontostand "hart" in den Code.


Eine Interaktion sollte also ungefähr so aussehen:
```
exercise-01$ java b/ATM
Enter the amount to withdraw: 25
Ok, here is your money, enjoy!
Enter the amount to withdraw: 200
Sorry, not enough money in the bank.
Enter the amount to withdraw: exit
```


## c) GitHub-Account schicken

Falls noch nicht geschehen, schicken Sie Ihren GitHub-Account an [nils.reiter@uni-koeln.de](mailto:nils.reiter@uni-koeln.de).