# Lerne selber Informatik

Als autodidaktische/r Ingenieur/in oder Bootcamp Absolvent/in schuldest du es dir selber, Informatik zu lernen. Zum Glück kannst du dir eine erstklassige Informatikausbildung verschaffen, ohne Jahre und ein kleines Vermögen in ein Studium zu investieren 💸.

Es gibt da draußen zahlreiche Ressourcen, manche davon besser als andere. Du brauchst jedoch nicht nochmal eine Liste von "200+ kostenlosen Online-Kursen". Du brauchst die Antwort auf folgende Fragen:

* **Welche Themen** soll ich lernen, und warum?
* Was ist die **beste Lektüre oder Vorlesungsreihe** für jedes Thema?

Dieser Leitfaden versucht, diese Fragen endgültig zu beantworten.

## TL;DR (Zusammenfassung)

Lerne alle neun unten aufgeführten Themen etwa in der gegebenen Reihenfolge mithilfe des Lehrbuchs oder Videovorlesungen, idealerweise jedoch mit beiden. Rechne etwa 100-200 Lernstunden pro Thema ein, und besuche nochmal deine Favoriten im Laufe deiner Karriere 🚀.

| Thema                                                                   | Weshalb lernen?                                                                                                                                                              | Buch                                                          | Videovorlesung                      |
| --------------                                                          | ---------------                                                                                                                                                              | ----                                                          | --------------                      |
| **[Programmierung](#programmierung)**                                   | Sei nicht die Person, die etwas wie Rekursion "nie ganz verstanden" hat.                                                                                                     | *Structure and Interpretation of Computer Programs*           | Berkeley CS 61A von Brian Harvey    |
| **[Computerarchitektur](#computerarchitektur)**                         | Ohne solides mentales Modell dafür, wie Computer tatsächlich funktionieren, werden all deine höhere Abstraktionen brüchig sein.                                              | *Computer Systems: A Programmer's Perspective*                | Berkeley CS 61C                     |
| **[Algorithmen und Datenstrukturen](#algorithmne-und-datenstrukturen)** | Wenn du nicht weißt, wie du allgegenwärtige Datenstrukturen wie Stapel, Warteschlangen, Bäume und Graphen verwenden sollst, wirst du schwierige Probleme nicht lösen können. | *The Algorithm Design Manual*                                 | Vorlesungen von Steven Skiena       |
| **[Mathematik für Informatik](#mathematik-fuer-informatik)**            | Informatik ist im Grunde ein Zweig der angewandten Mathematik, also wir dir das Mathe lernen einen Wettbewerbsvorteil verschaffen.                                           | *Mathematics for Computer Science*                            | MIT 6.042J von Tom Leighton         |
| **[Betriebssysteme](#betriebssysteme)**                                 | Der Großteil von Code, den du schreibst, wird vom einem Betriebssystem ausgeführt. Du solltest also wissen, wie diese Systeme zusammenwirken.                                | *Operating Systems: Three Easy Pieces*                        | Berkeley CS 162                     |
| **[Computernetzwerke](#computernetzwerke)**                             | Das Internet stellte sich als große Sache heraus. Lerne, wie es funktioniert, um sein volles Potenzial zu erschließen.                                                       | *Computer Networking: A Top-Down Approach*                    | Stanford CS 144                     |
| **[Datenbanken](#datenbanken)**                                         | Daten sind das Herzstück vieler wichtigen Anwendungen, aber nur wenige verstehen, wie Datenbanksysteme wirklich funktionieren.                                               | *Readings in Database Systems*                                | Berkeley CS 186 von Joe Hellerstein |
| **[Verteilte Systeme](#verteilte-systeme)**                             | Heutzutage bestehen die *meisten* Systeme aus verteilten Systemen.                                                                                                           | *Designing Data-Intensive Applications* von Martin Kleppmann  | MIT 6.824                           |

## Immer noch zu viel?

Ist die Vorstellung zu überwältigend, 9 Themen über mehrere Jahre selber durcharbeiten zu müssen, empfehlen wir, du fokussierst dich nur auf zwei Bücher: *Computer Systems: A Programmer's Perspective* und *Designing Data Intensive Applications*. Erfahrungsgemäß bieten diese zwei Bücher eine unglaublich hohe Rendite auf die investierte Zeit, insbesondere für autodidaktische Ingenieur/innen und Bootcamp Absolvent/innen, die an vernetzten Anwendungen arbeiten. Sie können auch eine "Einstiegsdroge" für die weiteren oben aufgelisteten Themen dienen.

## Warum Informatik lernen?

Es gibt zwei Arten von Softwareingenieur/innen: Die einen, die Informatik ausreichend gut verstehen, um anspruchsvolle, innovative Arbeit zu leisten, und die anderen, die nur über die Runden kommen, weil sie mit einigen high-level Tools vertraut sind.

Beide nennen sich Softwareingenieur/in, und beide verdienen ähnlich viel in den frühes Berufsjahren. Aber Ingenieur/innen der 1. Art entwickeln sich mit der Zeit zu erfüllenderen und besser vergüteten Arbeit, sei es wertvolle kommerzielle Arbeit, bahnbrechende Open-Source Projekte, technische Führung oder hochwertige individuelle Beiträge.

Ingenieur/innen der 1. Art finden Wege, um Informatik tiefer zu erlernen, sei es mit konventionellen Mitteln oder durch unermüdliches Lernen im Laufe der Karriere. Ingenieur/innen der 2. Art bleiben typischerweise an der Oberfläche, lernen bestimmte Tools und Technologien anstatt deren Grundlagen, und eignen sich nur dann neue Fähigkeiten an, wenn die Winde technologischer Trends sich drehen.

Zur Zeit steigt die Anzahl der Berufseinsteiger in der Branche rasch an, während die Anzahl an Informatikabsolvent/innen relativ stabil bleibt. Dieses Überangebot an Ingenieur/innen der 2. Art reduziert inzwischen ihre Berufschancen und hält sie von der erfüllenderen Arbeit in der Branche fern. Egal ob du anstrebst, ein/e Ingenieur/in der 1. Art zu werden, oder mehr Jobsicherheit suchst: Informatik zu lernen ist der einzige zuverlässige Weg.

## Leitfäden der Themen

### Programmierung

Die meisten Grundstudiengänge in der Informatik beginnen mit einer "Einführung" in die Computerprogrammierung. Die besten Versionen dieser Kurse richten sich nicht nur an Anfänger, sondern auch an diejenigen, die nützliche Konzepte und Programmiermodelle beim ersten Erlernen des Programmierens verpasst haben.

Unsere Standardempfehlung für diesen Inhalt ist der Klassiker *Structure and Interpretation of Computer Programs*, der online kostenlos als [Buch](https://sarabander.github.io/sicp/html/index.xhtml) und als Reihe von [Videovorlesungen am MIT](https://sarabander.github.io/sicp/html/index.xhtml) verfügbar ist. Obwohl diese Vorlesungen hervorragend sind, empfehlen wir als Videovorlesung stattdessen die [SICP Vorlesungen von Brian Harvey](https://archive.org/details/ucberkeley-webcast-PL3E89002AA9B9879E?sort=titleSorter) (vom Kurs 61A in Berkeley). Diese sind ausgefeilter und besser für neue Studierende geeignet als die MIT-Vorlesungen.

Wir empfehlen, wenigstens die ersten drei Kapitel von SICP und die Übungsaufgaben durchzuarbeiten. Als zusätzliche Übung, bearbeite eine Reihe von kleinen Programmieraufgaben, z.B. die Aufgaben auf [exercism](https://exercism.org/).

Seit dieser Leitfaden in 2016 zuerst veröffentlicht wurde, war eine der meist gestellten Fragen ob wir inzwischen eine aktuellere Aufzeichnung von Kurs 61A von John DeNero, oder das entsprechende Lehrbuch [Composing Programs](https://composingprograms.com/) empfehlen würden, das in der "Tradition von SICP" steht, aber Python verwendet. Wir sind der Meinung, diese Ressourcen von DeNero sind auch großartig, und manche Studierende werden diese bevorzugen, aber wir schlagen trotzdem vor, SICP, Scheme und Brian Harveys Vorlesungen als erste Ressourcen auszuprobieren.

Weshalb? Weil SICP einzigartig in seiner Fähigkeit ist, zumindest potenziell deine grundlegenden Überzeugungen über Computern und Programmierung zu verändern. Nicht alle werden diese Erfahrung machen. Manche werden das Buch hassen, andere schaffen es nicht weiter als die ersten paar Seiten. Aber der potentielle Gewinn macht es einen Versuch wert.

Wenn du an SICP keinen Spaß findest, versuche es mit *Composing Programs*. Wenn dir das immer noch nicht zusagt, probiere [How to Design Programs](http://htdp.org/) aus. Wenn sich deine Bemühungen trotzdem nicht lohnen, ist es vielleicht ein Zeichen dafür, dass du dich zunächst auf andere Themen konzentrieren und in 1-2 Jahren wieder auf das Disziplin der Programmierung zurückkommen solltest.

Abschließend eine Klarstellung: Dieser Leitfaden ist NICHT für absolute Programmieranfänger ausgelegt. Wir nehmen an, du bist bereits kompetent im Programmieren ohne Informatikhintergrund, und möchtest Wissenslücken schließen. Die Tatsache, dass wir einen Abschnitt über Programmierung eingefügt haben, ist lediglich eine Erinnerung daran, dass es noch mehr zu lernen geben kann. Für diejenigen, die noch nie programmiert haben, es aber gern tun würden, wäre vielleicht [dieser Leitfaden](https://www.reddit.com/r/learnprogramming/wiki/faq/#wiki_getting_started) der richtige.

###Computerarchitektur

(In Bearbeitung)
