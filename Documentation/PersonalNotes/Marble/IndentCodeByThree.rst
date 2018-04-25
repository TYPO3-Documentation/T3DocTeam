.. include:: ../../Includes.txt

====================
Indent Code By Three
====================

Reasoning - to be translated and worked through:

Es sollten drei sein. Warum?
Nach folgenden Überlegungen (in unsortierter Reihenfolge):

* Readability counts: 

  - Code-Beispiele sind Beispiele, und man soll die Doku vor allem lesen können.
  - An small devices with Tablets, Smartphones, schmal eingestellten Browser denken.
  - Experimente haben gezeigt hinsichtlich Lesbarkeit: zwei ist "zu eng", drei funktioniert optimal, vier schränkt das Fenster dessen, was man sehen kann, je nach Code und Gerät schon gehörig ein.

* Wer Beispielcode aus der Doku kopiert kann in seinem Editor per Tastendruck, wie Ctr+Alt+L die richtige Formatierung und Einrückung erzielen. Umgekehrt geht das nicht.

* In der Doku empfiehlt es sich, die Zeilen nicht zu lang zu machen:

  - Um die reST-Sourcen selbst als Doku lesen zu können
  - Um die Sourcen zu sehen, wenn man auf "Show page source" klickt (sonst wandern die rechts raus)
  - Wenn man Texte links und rechts hat und vergleichen will

* Für reST-Files haben wir "drei Spaces" für einen Indentation-Level eingestellt. Code-Beispiele sind halt Teil der Seite und funktionieren dann genau so.

* Es gibt nicht nur PHP-Styleguides. Wir haben auch jede Menge anderer Code-Lanuages. Es scheint mir nicht sinnvoll zu fordern, dass wir uns da jeweils an die jeweiligen Styleguides halten.

* Die Komplexität, innerhalb der Gemeinde der Documentation-Contributor auch noch die verschiedenen Styleguides erklären und diskutieren zu müssen würde ich uns gerne ersparen.

* Während ich dieses schreibe, wird mir noch ein gewichtiger Aspekt klar: Wenn man in der Doku arbeitet, bekommt man natürlich "auch einen Blick" dafür, was richtig aussieht, richtig eingerückt ist und was nicht. Da kommen einem verschiedene Indentations ganz schön in die Quere.

* Ein perfektes Einhalten eines Languagestyleguides wäre für die Code-BEISPIELE ja auch nicht unbedingt sinnvoll. Vielleicht will man ja gerade Leerzeilen einfügen oder Teile unüblich einrücken, um etwas zu demonstrieren?!

Das wären für mich erstmal die GRUNDSÄTZLICHEN Überlegungen. Wenn jemand fragt: Wie rückt man Code-Beispiele ein, ist meine grundsätzliche Antwort: nimm drei Blanks.
