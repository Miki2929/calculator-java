# calculator-java
simple calculator written in Java; supports addition, subtraction, multiplication and division
Koristio sam se alatom IntelliJ IDEA.
Metrike:
LOC (zbirno za sve fajlove): 222
Metode evaluateExpression i Calculate imaju sljedeće metrike:

evaluateExpression:
Ciklomatska složenost: 4
Kognitivna složenost: 12
Calculate:
Ciklomatska složenost: 3
Kognitivna složenost: 6

Izvještaj sa zapažanjima:

Calculator.java
1 - Nedostaje Javadoc komentar za paket.
3 - Nedostaje Javadoc komentar za klasu.
5 - Nedostaje Javadoc komentar za konstruktor.
8 - Nedostaje Javadoc komentar za metodu.
8 - Metoda je dugačka i kompleksna, sa visokom kognitivnom složenošću i nekoliko loše strukturisanih blokova koda.
19 - Nedostaje Javadoc komentar za metodu.
19 - Loš naziv metode, trebalo bi nazvati evaluateExpression.
19 - Metoda je dugačka i kompleksna, sa visokom kognitivnom složenošću i nekoliko loše strukturisanih blokova koda.
56 - Nedostaje Javadoc komentar za metodu.
56 - Loš naziv metode, trebalo bi nazvati isNumeric.
63 - Loša praksa korišćenja System.out.println() umesto korišćenja loggera.

Napomena: Izvještaj je rađen na osnovu statičke analize koda bez pokretanja istog.
