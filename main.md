<!--

author: Swantje Piotrowski, Gregor Große-Bölting
email:  ggb@informatik.uni-kiel.de
version: 0.1
language: en
narrator: UK English Female

\-->


# Digitale Editionswissenschaft<br/>unterstützt durch KI-Schreibwerkzeuge

**Dozierende:**

* Dr. Swantje Piotrowski, M.A.
* Gregor Große-Bölting, M.A., M.A.

**Zeit und Raum:** Do 10:15 - 11:45, Raum n.V.

**Inhalt:**

In der Veranstaltung zum Thema "Digitale Editionswissenschaft unterstützt durch KI-Schreibwerkzeuge" bieten wir eine Einführung in die Anwendung digitaler Methoden in der Editionswissenschaft. Die Teilnehmer erwerben Kenntnisse in den Bereichen Transkription von historischen Dokumenten, fachwissenschaftliche Einordnung, Auszeichnung von Dokumenten und den Standards dafür sowie den Umgang mit Technologien wie TEI, XSLT und HTML. Weitere Schwerpunkte sind die produktive Verwendung von visuellen Editoren sowie ein kritischer Umgang mit KI-Schreibwerkzeugen. Am Ende werden die Teilnehmer lernen, wie sie die Ergebnisse visualisieren und mit externen Quellen verknüpfen können. Als Prüfungsleistung gilt die Erstellung eines Reflexionsberichts über den Arbeits- und Forschungsprozess sowie die Visualisierung der editorischen Leistung.

Programmierkenntnisse sind nicht erforderlich.

**Lernziele:**

* Transkription von Dokumenten der frühen Neuzeit
* fachwissenschaftliche Einordnung der Leichenpredigten
* Auszeichnung von Dokumenten und Auszeichnungsstandards
* Umgang mit X-Technologien (TEI, XSLT, HTML)
* Verwendung von visuellen Editoren
* produktiver Umgang mit ChatGPT
* kritischer Umgang mit KI-Schreibwerkzeugen
* Visualisierung der Ergebnisse
* wenn möglich: Anbindung externer, programatischer Quellen (Gelehrtenverzeichnis, Wikidata o. ä.)

**Weiterführende Literatur:**

* **Baillot, Anne/Schnöpf, Markus**: Von wissenschaftlichen Editionen als interoperablen Projekten, oder: Was können eigentlich digitale Editionen?, in: Digital Humanities. Praktiken der Digitalisierung, der Dissemination und der Selbstreflexivität, hrsg. von Wolfgang Schmale, Stuttgart 2015, S. 139-156.

**Link zu OLAT:** https://lms.uni-kiel.de/auth/RepositoryEntry/5309268542/CourseNode/107413399882620

## Sitzung am 20.04.

### Semesterplan und Prüfungsleistung

**Termine:**

| Datum | Thema/Inhalt |
|-------|--------------|
| 20.04. | Einführung in das Thema und (Digitale) Editionswissenschaft |
| 27.04. | Inhaltliche Einführung in den Themenbereich "Leichenpredigten" (Gelehrtenverzeichnis) / XML-Grundlagen |
| 04.05. | Inhaltliche Einführung cont'd / Auszeichnung von Dokumenten und TEI |
| 11.05. | Quellenkundliche Einführung und Transkription |
| 18.05. | CHRISTI HIMMELFAHRT |
| 25.05. | TEI, XSLT und HTML und gemeinsame Arbeit: Erstellung eines TEI-Dokuments |
| 01.06. | (visuellen Editoren) und KI-Schreibwerkzeuge |
| 08.06. | Visualisierung der Ergebnisse |
| 15.06. | gemeinsame Arbeit |
| 22.06. | gemeinsame Arbeit |
| 29.06. | Anbindung externer Quellen |
| 06.07. | Präsentation der Ergebnisse, Evaluation |

**Prüfungsleistung:**

* Reflexionsbericht über Arbeits- und Forschungsprozess
* Produkt, sprich Visualisierung der editiorischen Leistung

### "Regierungserklärung"

1. Diese Veranstaltung ist ein Experiment: Wir setzen neue Methoden und Software ein. Seid also nachsichtig mit uns und mit euch selbst, wenn mal etwas nicht funktioniert wie geplant. Lasst uns zeitnah wissen, wenn ihr Probleme habt, dann findet sich für alles eine Lösung!
2. Es dürfen alle KI-Tools verwendet werden, die ihr möchtet, aber es muss transparent gemacht werden, wie und in welchem Umfang. Am Ende muss eure Prüfungsleistung nach wie vor als eigene Leistung erkennbar sein.
3. Der Seminarplan ist "im Fluss".

### ChatGPT verwenden

![Send a message...](img/chatGPT_welcome.png)

Die Nachricht, die man ChatGPT (und ähnlichen Systemen) schickt, wird auch *prompt* genannt. Die Qualität der Ausgabe hängt erheblich davon ab, wie *gut* der eingegebene *prompt* ist. Der Vorgang der Entwicklung möglichst passgenauer *prompts*, wird auch als *prompt design* bezeichnet. *Prompt design* ist mehr Kunst als Wissenschaft und erfordert häufig gezieltes Herumprobieren. Es gibt jedoch einige generelle *best practices*.

Übrigens: *Prompts* können sowohl auf Englisch als auch auf Deutsch eingegeben werden. Von der Eingabesprache hängt häufig auch die Ausgabesprache ab, sofern man nicht definitiv eine Ausgabe in einer bestimmten Sprache anfordert.

#### Rollenspiel

Man kann ChatGPT bitten Rollen einzunehmen und eine Frage oder einen Sachverhalt vor dem Hintergrund dieser Rolle zu kommentieren. Bei Personen, für die ausreichend viele schriftliche Zeugnisse zur Verfügung stehen, kann man sich auch erkundingen, wie eine Stellungnahme der historischen Person aussehen würde.

Angenommen wir möchten verschiedene Einschätzungen eines interessanten Phänomens, dass wir alle in den vergangenen Jahren erfahren haben...

Was würde ein Psychologe sagen?

![Was würde ein Psychologe sagen?](img/chatGPT_corona_psychologe.png)

Was würde ein Physiker sagen?

![Was würde ein Physiker sagen?](img/chatGPT_corona_physiker.png)

Was würde ein Philosoph sagen?

![Was würde ein Philosoph sagen?](img/chatGPT_corona_erkenntnistheorie.png)

Was würde Shakespeare sagen?

![Was würde Shakespeare sagen?](img/chatGPT_corona_shakespeare.png)

#### Fragen stellen lassen

Ein weiteres Verfahren, um gute Ausgaben zu generieren, besteht darin, ChatGPT die "richtigen" Fragen stellen zu lassen. Dazu beschreibt man ein Anliegen oder Problem und bittet ChatGPT darum Fragen zu stellen, die das Problem vertiefen:

> Ich muss eine kurze, geschichtswissenschaftliche Einschätzung darüber schreiben, welchen Effekt dieses Phänomen der veränderten Zeitwahrnehmung während Corona auf die Geschichtsschreibung haben wird. Ich möchte diese Einschätzung gerne mit dir zusammen schreiben. Stell mir dazu zunächst die richtigen Fragen!

ChatGPT antwortet mit einer Reihe von Fragen:

![Fragen an einen Historiker](img/chatGPT_corona_historiker-fragen.png)

Die Beantwortung der Fragen erfolgt nach dem folgenden Schema:

1. Antwort auf Frage 1
2. Antwort auf Frage 2
3. usw.

Da die Antwort "in einem" erfolgen sollte ist es wichtig Umbrüche zu machen: Das funktioniert mit `Shift + Enter`.

Die Ergebnisse sind häufig nicht sehr gut:

> Die Coronapandemie hat zu einer veränderten Wahrnehmung von Zeit geführt, die sich auf verschiedene Aspekte des menschlichen Lebens ausgewirkt hat. Historisch gesehen haben Krisen und Ereignisse in der Vergangenheit oft zu ähnlichen Veränderungen in der Wahrnehmung von Zeit geführt. Die Auswirkungen der Pandemie auf die Geschichtsschreibung sind vielfältig: Einerseits haben die neuen Technologien und die zunehmende Digitalisierung die Entstehung von umfangreichem Datenmaterial begünstigt, welches zukünftige Historiker für ihre Analysen nutzen können. Andererseits hat die Krise auch globale Auswirkungen, wie den Zusammenbruch von Lieferketten und die angespannte Handelssituation, die sich auch auf die Weltpolitik auswirken. Es bleibt abzuwarten, wie zukünftige Historiker die Auswirkungen der Pandemie auf die Wahrnehmung von Zeit und den menschlichen Umgang damit interpretieren werden.

Dadurch, dass man sich aber durch die Beantwortung der Fragen mit der Materie vertieft auseinandergesetzt und auch bereits selbst Textschnipsel produziert hat, fällt einen das Schreiben eines eigenen Textes sehr viel leichter.

#### Daten strukturieren

ChatGPT ist gut darin aus unstrukturierten Daten, strukturierte Daten zu machen. Ein Beispiel:

> Ich habe den folgenden Literatureintrag im APA-Zitierstil:
>
> Sahle, P. 2016. 2. What is a Scholarly Digital Edition? In: Driscoll, M. J., & Pierazzo, E. (Eds.), Digital Scholarly Editing: Theories and Practices. Open Book Publishers. aus dem Werk: http://books.openedition.org/obp/3397
>
> Formatier in bitte als bibtex!

`bibtex` ist ein Literaturformat, dass zur strukturierten Speicherung bibliographischer Daten und in LaTeX für die Generierung und Ausgabe von Literaturangaben und -verzeichnissen verwendet wird.

Antwort von ChatGPT:

> Sure, here's the bibtex entry for the citation you provided in APA style:
>
> @incollection{sahle2016,
> author       = {Sahle, Patrick},
> title        = {What is a Scholarly Digital Edition?},
> booktitle    = {Digital Scholarly Editing: Theories and Practices},
> editor       = {Driscoll, Matthew James and Pierazzo, Elena},
> year         = {2016},
> publisher    = {Open Book Publishers},
> url          = {http://books.openedition.org/obp/3397},
> address      = {Cambridge},
> pages        = {17-34}
> }

Welche Angaben in der Ausgabe von ChatGPT könnten problematisch sein (und warum?) und bedürfen voraussichtlich einer händischen Anpassung? Warum ist die Ausgabe dennoch nützlich?

#### Alternativen

Es gibt auch andere Systeme als ChatGPT und Anbieter für ähnliche Systeme als OpenAI.

Ein Beispiel ist das israelische System ai21, das zwar nicht ganz so, aber auch sehr gute Ergebnisse liefert:

![Erklär mir DH als wäre ich 5](img/ai21_dh.png)

#### Aufgabe

Bildet Kleingruppen aus 3 bis 4 Teilnehmer:innen.

Verwendet eine Textgenerierungssoftware wie ChatGPT (oder GPT3, GPT4, AI21), um einen zwei Minuten-Vortrag über folgendes Thema vorzubereiten:

> Sinn und Unsinn einer digitalen Edition Kieler Leichenpredigten

Speichert die Prompts, die Ihr verwendet habt und diskutiert die folgenden Fragen:

1. Wie sind Prompts formuliert, die für euch gut funktioniert haben?
2. Funktioniert die Textgenerierung problemlos? Wo musstet ihr (in welchem Umfang nacharbeiten)?
3. Kann Textgenerierungs-KI *einfach so* verwendet werden? Wo seht ihr Probleme?
4. Welche Fertigkeiten und Kompetenzen sind erforderlich, um Textgenerierungs-KI zu verwenden.

**Bonus:** Illustriert den Vortrag mit KI-generierten Bildern eines Diensts wie Dall:e2 oder Midjourney.

Ihr habt für die Aufgabe 15 Minuten Zeit.

## Sitzung am 27.04.

### Wiederholung: KI (Schreib-)Werkzeuge

> Wo könnten in diesem Seminar KI Werkzeuge einen sinnvollen und wichtigen Beitrag leisten? Warum?

### Editionswissenschaft

**Was ist eine Edition?**

> Eine Edition ist die erschließende Wiedergabe historischer Dokumente.

1. „erschließend“: Eine Edition reichert die Wiedergabe durch kritisches Wissen an.
2. „Wiedergabe“: Die Edition zielt auf die Repräsentation bereits existierender Texte.
3. "historisch“: Die Edition beschäftigt sich mit Texten bzw. Dokumenten, zu denen eine historische Distanz besteht. Ihre Überwindung ist das Ziel der Edition.
4. „Dokumente“: Das „Dokument“ ist ein verallgemeinernder Begriff für Texte in einem abstrakten Sinne.

Institut für Dokumentologie und Editorik:
https://www.i-d-e.de/themen/editorik/

**Was ist eine Edition?**

Sichtung der Überlieferung +

* Textkritik
* Konstituierter Text
* Publikation

  = Edition

  **Wozu das Ganze?**
* Grundlagenarbeit für die weitere Forschung;
* Kritische Auseinandersetzung mit der Überlieferung;
* Erarbeitung von wissenschaftlichen Informationsressourcen;
* Stabilisierung, Kanonisierung, Referenzierbarkeit

### Digitale Editionen

> A digitised edition is not a digital edition. (Sahle 2016)

Digitale Editionen sind multimedial: Ein Text, der online steht, ist noch keine digitale Edition. Es geht nicht um das Speichermedium.

> A digital edition cannot be given in print without significant loss of content and functionality. (Sahle 2016)

Digitale Editionen haben eine erweiterte Funktionalität gegenüber einer gedruckten Editionen: Eine digitale Edition drucken bedeutet in der Regel Verlust von Funktion(en). Die zusätzlichen Funktionen resultiert aus der Durchsuch- und Filterbarkeit digitaler Medien, mehr noch aber durch die Verwendung von Hypertext und die Verknüpfung verschiedener Ressourcen.

> A scholarly edition is the critical representation of historic documents. (Sahle 2016)

Digitale Editionen sind nicht nur Text/Bild + Metadaten, wie bei einem digitalen Archiv: Digitale Editionen erfordern kritische Auseinandersetzung, wie auch andere Editionen. Die kritische Auseinandersetzung wird durch die umfangreiche Kontextualisierung digitaler Angebot befördert.

> Scholarly digital editions are scholarly editions that are guided by a digital paradigm in their theory, method and practice. (Sahle 2016)

Dig. Editionen sollten gewissen Qualitätsstandards entsprechen, bspw. in der Art und Weise der Präsentation der Daten, wie auch der verwendeten Methodiken (Beachtung von (Meta-)Datenstandards, Transkriptionsregeln, FDM); idealerweise sind die publizierten Daten FAIR (Findable, Accessible, Interoperable, Reusable).

Außerdem wir häufig angestrebt das *Single Source Principle* zu erfüllen, in dem bspw. TEI XML oder ein ähnliches Standarddatenformat verwendet wird.

Um zu beantworten, ob etwas eine digitale Edition ist, können entsprechend die folgenden Fragen herangezogen werden:

> 1. Is there a full representation of the subject in question? This may be an edited text or at least a very accurate transcription. Sometimes, although this is rather an exception than the rule and depends on the specific characteristics of the material, a digital facsimile may suffice. Sometimes even a structured database can be a complete representation.
> 2. Is it *critical*? Have rules for the processing of the material been stated and substantiated? Have these rules been applied in the light of the relevant scholarly knowledge on the material, its genesis, its contexts and its reception? Does the edition add information to the representation making it more accessible, understandable and usable?
> 3. Is the edition of academic quality? Have the rules been applied rigorously and in a transparent manner? Are the responsibilities stated clearly? Does the edition suffice as a substitute for the previous editions or primary documents making it unnecessary to go back to them in most cases? Does it enable further scholarly research on a reliable and trustworthy basis?
> 4. Does the edition follow a digital paradigm? Does it make use of the possibilities of digital technology and media? Is it not printable without a major loss of content and functionality? (Sahle 2016)

---

Sahle, P. 2016. 2. What is a Scholarly Digital Edition? In: Driscoll, M. J., & Pierazzo, E. (Eds.), Digital Scholarly Editing: Theories and Practices. Open Book Publishers. aus dem Werk: http://books.openedition.org/obp/3397

#### Beispiel: RuneS Datenbank

Was macht diese Edition zu einer *digitalen* Edition?

![Screenshot des Fundsteckbriefs](img/runes_steckbrief.png)

#### Beispiel: When The Wall Came Down

Was macht diese Edition zu einer *digitalen* Edition?

![Screenshot eines Dokuments aus 'When The Wall Came Down'](img/when-the-wall-came-down.png)

### Leichenpredigten

Quellenerschließung Leichenpredigt

![Die an Gott stets bleibende Gottes-Kinder“ von Wolfgang Christoph Franck](img/Leichenpredigt.jpg)

> Welche Elemente fallen Ihnen an diesem Titelblatt auf?

> Welche Informationen halten Sie für wichtig?

https://dibiki.ub.uni-kiel.de/viewer/image/PPN875662757/1/

#### Aufbau des Quellentypus Leichenpredigt

Die Leichenpredigten gehören zur Gattung der Personalschriften, also den Schriften, die zu Geburtstagen, Taufen, Verlobungen, Hochzeiten, Amtseinführungen, Jubiläen und zum Tod eines Menschen verfasst und häufig auch gedruckt wurden.

Die Leichenpredigt besteht aus folgenden festen Gliederungspunkten:

1. Widmung
2. Vorrede
3. Leichenpredigt
4. Exordium
5. Abhandlung
6. Personalia/Lebenslauf

Weitere Informationen zur Quellengattung Leichenpredigt finden sich unter:
http://www.personalschriften.de/leichenpredigten.html

##### Widmung

Nennung der Personen, denen der Verfasser die Leichenpredigt widmet.

![Die an Gott stets bleibende Gottes-Kinder“ von Wolfgang Christoph Franck](img/Widmung.jpg)

##### Leichenpredigt

„Im Nahmen Jesu Amen!“ Hier findet man die Predigt, die der Pfarrer am Grab oder in der Kirche auf den Verstorbenen gehalten hatte.

!["Die an Gott stets bleibende Gottes-Kinder" von Wolfgang Christoph Franck](img/Christl_Leichpredigt.jpg)

##### Exordium (Eingang)

Es führt im allgemeinen in den theologischen Teil der Predigt ein.

![Die an Gott stets bleibende Gottes-Kinder“ von Wolfgang Christoph Franck](img/Exordium.jpg)

##### Abhandlung (Hauptteil der Predigt)

Hier wird der Leichtext (eine Textstelle der Bibel) ausgelegt und erläutert, eine Lehre aus ihm gezogen und häufig in der zur Gemeinde und/oder zur verstorbenen Person in Beziehung gesetzt.

![Die an Gott stets bleibende Gottes-Kinder“ von Wolfgang Christoph Franck](img/Abhandlung.jpg)

##### Personalia

In ihm wird der Lebensweg des Verstorbenen mehr oder weniger detailliert geschildert. Sein Ziel ist es, den Verstorbenen als einen beispielhaften Christen zu präsentieren.

![Die an Gott stets bleibende Gottes-Kinder“ von Wolfgang Christoph Franck](img/Personalia.jpg)

#### Quellenwert?

> Für welche verschiedenen wissenschaftlichen Disziplinen könnte die Gattung Leichenpredigt von Interesse sein?

#### Disziplinen

* Sozial- und Wirtschaftsgeschichte
* Theologie
* Genealogie und Biographik
* Literaturgeschichte
* Kunstgeschichte
* Medizingeschichte
* Pharmaziegeschichte
* Historische Demographie
* Universitätsgeschichte
* Bildungsgeschichte
* historische Familiengeschichte

### Gelehrtenverzeichnis

Informationen und Anschlussmöglichkeiten

![Kieler Gelehrtenverzeichnis](img/Gelehrtenverzeichnis.jpg)

https://cau.gelehrtenverzeichnis.de/

## Sitzung am 04.05.

### XML-Grundlagen

> Wo sind euch bereits XML-Formate begegnet?
>
> Welche Beispiele könnt ihr nennen?
>
> Warum könnte das eine sinnvolle Möglichkeit sein Daten abzulegen?

#### Beispiele

Sowohl Word, als auch Excel (und andere Microsoft Office-Tools) speichern ihre Daten im XML-Format ab. Dafür steht das *x* in der Dateiendung *.docx* bzw. *.xlsx* (in dem Fall: das zweite *x*). Man *sieht* die XML-Daten nicht, weil sie komprimiert werden, im sogenannten Zip-Format. Mit ein wenig technischem Verständnis kann man aber die Rohdaten sichtbar machen. In der Regel ist das nicht erforderlich und sollte auch nicht gemacht werden: Word und Excel "wissen", wie sie mit diesen Informationen umgehen müssen, händische (menschliche) Interventionen können die Daten zerstören.

Ein weiteres Beispiel für XML (genau genommen: ein XML-ähnliches Format) ist die Hypertext Markup Language (HTML), die zum Bau von Websiten verwendet wird:

![Die CAU Website ist mit HTML gebaut, einem XML-ähnlichen Standard](img/cau_website.png)

#### Grundlagen

XML — kurz für: eXtensible Markup Language — ist ein textbasiertes Format zur Speicherung von Daten. Von XML leiten sich verschiedene andere Standards ab, die jedoch alle gleichen Prinzipien folgen. Beispiele für solche abgeleiteten Standards sind TEI (*Text Encoding Initiative*), RDF (*Resource Description Framework*) oder XSLT (*Extensible Stylesheet Language Transformation*). XML ist eine Art Metasprache, um verschiedene Wege zu ermöglichen standardisierte Datenbeschreibungen vorzunehmen.

XML-Dokumente bestehen aus sogenannten *tags*:

```xml
<name>Max Mustermann</name>
```

Der *tag* ist in diesem Fall *name*, der aus einem öffnenden und schließenden (mit einem "/" beginnend) Anteil gebildet wird. Dadurch wird ausgezeichnet, *was* beschrieben wird, in diesem Fall ein Name. Der konkrete Name steht zwischen den Tags. Einzelne XML-Tags funktionieren also wie ein Oreo-Keks: Außen herum ist die langweilige, harte Beschreibung, innendrin der weiche, semantische Kern.

![Ein einzelner Tag ist wie ein Oreo-Keks](img/Oreo-Two-Cookies.jpg "Evan-Amos, Public domain, via Wikimedia Commons")

*Tags* können nun ineinander geschachtelt werden oder auch nebeneinander stehen. Stehen zwei *tags* nebeneinander spricht man von Geschwistern, ist ein Tag in einem anderen geschachtelt, so spricht man bei dem inneren von dem Kind- (oder *child*), bei dem äußeren von dem Vater- bzw. Eltern- (oder *parent* bzw. *ancestor*) *tag*.

Es **muss** immer ein Wurzelelement (*root element*) geben, dass alle anderen Elemente beinhaltet. Innerhalb dieses Wurzelelements kann es *siblings* geben, aber das *root element* kann niemals *sibling* zu einem anderen sein.

![XML funktioniert wie eine Matroshka-Puppe](img/1024px-Russian-Matroshka.jpg "No machine-readable author provided. Fanghong assumed (based on copyright claims)., CC BY-SA 3.0 <http://creativecommons.org/licenses/by-sa/3.0/>, via Wikimedia Commons")

In diesem Sinne funktioniert XML wie eine Matroshka-Puppe, da sich *tags* ineinander schachteln und dadurch hierarchische Strukturen bilden lassen:

```xml
<person>
   <name>Max Mustermann</name>
   <alter>30</alter>
      <adresse>
      <straße>Hauptstraße 1</straße>
      <stadt>Berlin</stadt>
      <land>Deutschland</land>
   </adresse>
</person>
```

Ist ein XML-Dokument in diesem Sinne korrekt formatiert, dann sagt man auch es sei **well-formed**: Es wurden keine syntaktischen Fehler gemacht, alle Klammern schließen korrekt und die öffnenden und schließenden *tags* sind korrekt gesetzt.

Es ist zudem möglich ein spezielles Schema mit einem Dokument zu verknüpfen um kenntlich zu machen, welche *tags* es gibt und in welcher Beziehung diese zueinander stehen können. Geschieht dies, so lässt sich automatisch überpüfen, ob ein Dokument **valide** (*valid*) ist.

Noch ein Hinweis zum Schluss: Wenn ein XML-Dokument selbst bestimmte Sonderzeichen innerhalb eines Tags verwenden möchte, so müssen diese Zeichen **escaped** werden:

```xml
<formula>3 < 4 => True</formula>
```

Würde unweigerlich zu einem Fehler führen, während

```xml
<formula>3 < 4 => True</formula>
```

korrekt ist.

---

Als Vorlage dieses Abschnitts diente der hervorragende Blogbeitrag [A shamelessly short intro to XML for DH beginners (includes TEI)](https://latex-ninja.com/2022/02/02/a-shamelessly-short-intro-to-xml-for-dh-beginners-includes-tei/)

#### ChatGPT: Erklär mir XML als wäre ich ein 5-jähriger

Stell dir vor, dass du ein Bild malst und es deiner Freundin oder deinem Freund zeigen möchtest. Wenn du einfach nur das Bild zeigst, kann es schwierig sein, bestimmte Details oder Informationen zu erklären. Wenn du jedoch das Bild in kleinere Abschnitte aufteilst und jeder Abschnitt einen Namen gibst, kann es viel einfacher sein, bestimmte Elemente des Bildes zu identifizieren und darüber zu sprechen.

XML funktioniert auf eine ähnliche Weise. Es teilt Informationen in klar definierte Abschnitte auf, die als "Tags" bezeichnet werden, und jedem Tag wird ein Name gegeben, der beschreibt, was in diesem Abschnitt enthalten ist. Diese Tags können dann in einer bestimmten Reihenfolge angeordnet werden, um eine Struktur oder einen "Baum" von Informationen zu erstellen.

Zum Beispiel könnte XML verwendet werden, um Informationen über eine Person zu organisieren und auszutauschen:

```xml
<person>
   <name>Max Mustermann</name>
   <alter>30</alter>
   <adresse>
      <straße>Hauptstraße 1</straße>
      <stadt>Berlin</stadt>
      <land>Deutschland</land>
   </adresse>
</person>
```

In diesem Beispiel gibt es einen "person"-Tag, der die gesamten Informationen über eine Person enthält. Der "name"-Tag enthält den Namen der Person, der "alter"-Tag enthält das Alter, und der "adresse"-Tag enthält Informationen über die Adresse der Person, einschließlich der Straße, Stadt und Land. Jeder Tag ist klar definiert und in einer bestimmten Reihenfolge angeordnet, um die Informationen übersichtlich darzustellen.

Durch die Verwendung von XML können Computer leichter Informationen austauschen, weil sie wissen, wo sie bestimmte Informationen finden und wie sie auf diese zugreifen können, ohne dass menschliche Intervention erforderlich ist.

#### Übungen

**1.** Gegeben ist das folgende XML-Dokument:

```xml
<person>
   <name>Max Mustermann</name>
   <alter>30</alter>
   <adresse>
      <straße>Hauptstraße 1</straße>
      <stadt>Berlin</stadt>
      <land>Deutschland</land>
   </adresse>
</person>
```

a) Ist das Dokument **well-formed**?

[(X)] Ja
[( )] Nein

b) In welchem Verhältnis stehen die *tags* *name* und *alter* (X ist \_ zu Y) zueinander?

[( )] root element
[( )] child
[( )] parent
[(X)] sibling
[( )] ancestor
[( )] successor

c) In welchem Verhältnis stehen die *tags* *person* und *adresse* (X ist \_ zu Y) zueinander?

[( )] root element
[( )] child
[(X)] parent
[( )] sibling
[( )] ancestor
[( )] successor

d) In welchem Verhältnis stehen die *tags* *land* und *person* (X ist \_ zu Y) zueinander?

[( )] root element
[( )] child
[( )] parent
[( )] sibling
[( )] ancestor
[(X)] successor

---

**2.** Das folgende XML-Dokument ist nicht **well-formed**:

```xml
<book>
   <title>Harry Potter and the Sorcerer's Stone</title>
   <author>J.K. Rowling</autor>
   <year>1997</year>
   <publisher>Scholastic</publisher>
</book>
<genre>Fantasy</genre>
```

Welche Fehler sind darin enthalten?

[[X]] Es gibt kein Wurzelelement
[[ ]] Der Title-tag wird nicht korrekt geschlossen
[[X]] Der Author-tag wird nicht korrekt geschlossen
[[ ]] Es gibt keinen Publisher namens "Scholastic"
[[ ]] Harry Potter gehört in die Kategorie "YA Fantasy"

---

**3.** Das folgende XML-Dokument ist nicht **well-formed**:

```xml
<book>
   <title>The Catcher in the Rye<title>
   <author>J.D. Salinger<author>
   <year>1951</year>
   <publisher>Little, Brown and Company</publisher
</book>
```

Welche Fehler sind darin enthalten?

(Auswahlmöglichkeiten wurden hier bewusst ausgespart.)

### Quellenkundliche Einführung / Metadaten

> Erfassungsrichtlinie für eine Kieler Leichenpredigt von 1696

Die Seite mit dem Dokument der UB Kiel, abrufbar auf

https://dibiki.ub.uni-kiel.de/viewer/image/PPN875662757/1/

#### Angaben zu Titel und Verfasser des vorliegenden Dokumentes

> Titel der Arbeit (Benennung dieses Dokumentes)

* Transkription der Leichenpredigt des Gabriel Wedderkops von 1696

> Untertitel (Benennung des bearbeiteten Abschnitts des Werkes: Seitenzahl der Originalquelle)

* Seite 1:1 – 40:- (32 gezählte Seiten + 8 ungezählte)

> Transkribiert von Originalmanuskript (Namen der Bearbeiter)

* Swantje Piotrowski

#### Kursleitung

> Titel des Kursleiters (z.B. Dr.)

* Dr. phil.

> Vorname des Kursleiters

* Swantje

> Nachname des Kursleiters

* Piotrowski

> Übergeordnete verantwortliche Einrichtung (Institut und Universität)

* Historisches Seminar CAU Kiel

#### Angaben zur Veröffentlichung des Dokumentes

> Kursname (Titel der Lehrveranstaltung)

* Projektseminar zur Geschichte der Neuzeit: Digitale Editionen

> Semester (WS \_\_/ SoSe \_\_ )

* SoSe2023

> Datum (tt.mm.jjjj) (aktuelles Datum)

* 4.April 2023

#### Quellenbeschreibung

> Aufbewahrungsort des Originaldokuments Land (Staat)

* Deutschland

> Region (z.B. Bundesland)

* Schleswig-Holstein

> Stadt (Stadtname)

* Kiel

> Einrichtung, die das Dokument aufbewahrt (Bibliothek, Museum o.a.)

* Universitätsbibliothek der CAU zu Kiel

> Signatur der Handschrift (Kombination aus Buchstaben und Zahlen)

* Arch2 70 82

#### Beschreibung des Dokuments

> Angabe der Seitenzahlen

* Seite 1:1 – 40:- (32 gezählte Seiten + 8 ungezählte)

> Autor (Name des Verfassers des Originaltexts)

* Franck, Wolfgang Christoph

> Titel des Dokuments

* Die an Gott stets bleibende Gottes-Kinder/ Aus denen erwehlten Worten des LXXIII. Psalms/ v. 23. 24

> Untertitel des Dokuments

* Bey ansehnlicher und Volckreicher Beerdigung Des Hn. M. Gabriel Wedderkops/ Wohlverdienten Pastoris Primarii der Gemeidne St. Nicolai in Kiel

> Verlag / Drucker

* Acad. Buchdr. / Gedruckt durch Joachim Reumann

> Auflage

* 1 Auflage

> Genre

* Gebrauchsliteratur; Leichenpredigt

#### Physikalische Beschreibung des Manuskripts

> Beschreibstoff (auf welchem Material wurde geschrieben)

* Nicht herauszufinden

> Anzahl der Seiten (in Bl. =Blatt; Beispiel: 156 Bl.)

* 40 Bl.

> Höhe eines Blattes (in cm)

* Nicht herauszufinden

> Breite eines Blattes (in cm)

* Nicht herauszufinden

> Anzahl der Spalten

* 1

> Name der Schriftart (Name der im Manusskript verwendeten Schriftart; Beispiel: Insulare Rundschrift)

* Fraktur

> Beschreibung des Einbands

* Nicht herauszufinden

#### Angaben zur Entstehungsgeschichte des Dokuments

> Entstehungsort (Stadt, Region, Gebiet, Staat etc.)

* Kiel, Schleswig-Holstein, Deutschland

> Datum / Zeitraum der Entstehung

* 1696

#### Transkriptionsübung

* Aufgabe 1: Übertragung der Handschrift ins moderne Schriftbild (unter Beibehaltung der originalen Zeilenumbrüche, Ausformulierung der Abkürzungszeichen)
* Aufgabe 2: Auflistung von Personen und Orten

![Personalia_Leichenpredigt](img/00000035.jpg)

### Hausaufgabe

Lesen Sie Kapitel 9 "XML" (S. 128 - 146) in:

Jannidis, F.; Kohle, H. & Rehbein, M. (Eds.): *Digital Humanities*. J.B. Metzler, 2017.

## Sitzung am 11.05.

### Wiederholung: XML

Wiederholungsfragen zur letzten Woche bzw. zum Kapitel 9 aus Jannidis:

1. Warum müssen bestimmte Zeichen mit speziellen Zeichen enkodiert werden, bspw. '<' durch '<'?
2. Was ist der Unterschied zwischen *well formed* und *valid* in Bezug auf XML?
3. Was bedeutet es, dass XML eine Metasprache ist?
4. Welche Funktion haben Schemata?
5. Was ist ein Namensraum (*namespace*)?
6. Was ist XSLT und wofür wird es benötigt bzw. eingesetzt?

---

Das folgende XML-Dokument enthält einige Probleme, welche?

```xml
<book>
   <title>The Great Gatsby</title>
   <author>F. Scott Fitzgerald</author>
   <year>1925<year>
   <publishing>
      Publishing House
      <name>Penguin</name>
      <city>New York</city>
   </publishing>
</book>
```

---

Gegeben ist das folgende XML-Snippet:

```xml
<library>
   <book>
      <title>The Hobbit</title>
      <author>J.R.R. Tolkien</author>
      <year>1937</year>
      <publisher>Houghton Mifflin</publisher>
   </book>
   <book>
      <title>To Kill a Mockingbird</title>
      <author>Harper Lee</author>
      <year>1960</year>
      <publisher>J. B. Lippincott & Co.</publisher>
   </book>
</library>
```

In welchen Verhältnissen stehen die Elemente zueinander?

### Fortsetzung "Transkription"

Da er dan von vorbesagter Schule nach der Fürstl. Universität Helmstett gereiset / und ein Jahr unter information des Herrn Doct. Zappen /SS. Theolog. Professor. Ordinar. als auch bey dessen Tisch daselbst verharret / und wie ihm gefällig ferner in Teutschland zureisen und die daselbst herum liegende Universitäten zubesehen / hat er sich von dannen durch Hessen / auf die Universität Marpurg und Giesen eine Monahten verweilend / nacher Heidelberg zu seinen Bruder Herrn Magno von Wedderkop Juris utriusque Doctori, und dahmaligen Juris publici & feudalis Professori Ordinario, nunmehro Ihro zu Schleßwig Hollstein regierenden Hoch Fürstl. Durchl. hochbetrauten Geheimbten Estats-Raht und Ambtmann zu Tremsbüttel begeben / nach verfliessung einiger Jahren aber weiter nach der Universität Tübing verfügt / um mit denen berühmten Leuten als Herr Doct. Osiandro und Wulfino in eine gute Kundschafft zugerahten.
Wie es ihm daselbst nun nicht gefallen wollen / hat er sich nach verfliessung ungefehr vier Monathen nach der berühmten Universität Straßburg erhoben / woselbst er bey nahe 2. Jahr sich aufgehalten und mit großen Nutzen der berühmten Theologorum als Herr Doct. Danhaureri, Doct. Schmidii, Faustii, vornehmlich des Herrn Doct. Bebelii information in Theologicis bedienet / unter welchen er nicht allein unterschiedene Collegia mit guten Vergnügen gehalten / besondern auch unter den letzeren 3. disputationes als 1. De Scepticismo Arminianorum. 2. De Atheismo Socinianoorum. 3. Historico Ecclesiasticam de scriptoribus & Ministerio Ecclesiastico Ecclesiae seculi primi post Christum natum daselbst publice mit Ruhm abgelegt. Ob er nun wohl festiglich entschlossen unter anführung solcher berühmten und gelahrten Männer seine Studia ferner fortzusetzen / so ist ihm doch eine solche Gelegenheit in der Frembde ferner zu reisen an die Hand gekommen / daß er resolviret den Ohrt zu verlassen / und ist im Febr. des 1665sten Jahres darauff nacher Basel gezogen /

### Liste an Personen und Orten

Personen:

* Name: Gabriel von Wedderkop
* https://d-nb.info/gnd/121258564
* Beruf: Magister, Diakon, Hauptpastor an der        Nikolaikirche in Kiel
* Name: Magnus von Wedderkop
* https://d-nb.info/gnd/100879586
* Beruf: Rechtsgelehrter, schleswig-holsteinischer Staatsmann und Politiker
* Name: Johann Adam Osiander
* https://d-nb.info/gnd/104279427
* Beruf: Professor für ev. Theologie, Universität        Tübingen
* Name: Doct. Osiandro + Wulfino (?)

Orte

* Helmstedt: https://d-nb.info/gnd/4024344-8
* Marburg: https://d-nb.info/gnd/4037446-4
* Gießen: https://d-nb.info/gnd/4020989-1
* Heidelberg: https://d-nb.info/gnd/4023996-2
* Tremsbüttel: https://d-nb.info/gnd/4120074-3

Institutionen

* Universität Helmstett: https://d-nb.info/gnd/2051813-4
* Universität Marpurg: https://d-nb.info/gnd/2001630-X
* Universität Giesen: https://d-nb.info/gnd/36154-9
* Universität Heidelberg: https://d-nb.info/gnd/2024349-2
* Universität Straßburg: https://d-nb.info/gnd/1010669-8

### Automatische Transkription mit Transkribus

Transkribus ist ein Transkriptions-Tool, das von der Read COOP entwickelt wurde und Forschern und Wissenschaftlern dabei hilft, handschriftliche Dokumente zu digitalisieren und zu analysieren. Das Tool basiert auf der optischen Zeichenerkennung (OCR) und maschinellem Lernen und kann sowohl gedruckte als auch handgeschriebene Texte automatisch transkribieren. Darüber hinaus ermöglicht Transkribus auch die manuelle Transkription durch menschliche Transkribenten, wobei das Tool sie bei der Organisation und Verwaltung der Transkription unterstützt.

Das Tool ist besonders nützlich für historische Dokumente, Archive, Bibliotheken und Museen, die ihre Dokumente digitalisieren und archivieren möchten. Transkribus bietet auch verschiedene Analysewerkzeuge an, die es Forschern erleichtern, die Inhalte und Strukturen der transkribierten Texte zu untersuchen.

#### Die Benutzeroberfläche

##### Workdesk

![Die Arbeitsoberfläche](img/transkribus_workdesk.png)

##### Collections - View

![Collection View](img/transkribus_collection-view.png)

##### Collections - Organizer

![Collection Organizer](img/transkribus_collections-organizer.png)

##### Document - View

![Document View](img/transkribus_document-view.png)

##### Editor - Elements

![Editor Elements](img/transkribus_editor-elements.png)

##### Editor - Layout and Text 1

![Editor: Layout and Text](img/transkribus_editor.png)

##### Editor - Layout and Text 2

![Editor: Layout and Text](img/transkribus_editor-layout.png)

##### Tools Organizer

![Tools Organizer](img/transkribus_tools-organizer.png)

#### Der Workflow

1. Account anlegen
2. Collection mit einem sinnvollen Namen erstellen
3. PDF Dokument hochladen: Entweder in der Collection oder unter Upload die Datei auswählen; aufpassen, dass der korrekte Dateityp gewählt wird.
4. Automatische Texterkennung starten:
   * *Transkribus Print M1* als Modell auswählen
   * Warten: Die Transkription kann einige Zeit in Anspruch nehmen. Einen Überblick über den Fortschritt kann man sich unter "Jobs" verschaffen.
5. Für jede Seite...
   * Layout überprüfen und anpassen: Stimmen die Regionen oder sollten Regionen zusammengelegt werden? Wurden alle Zeilen erfasst? Wurden die Marginalien erfasst?
   * Transkription überprüfen: Erkennungsfehler beheben.
   * Speichern.
6. Export der Ergebnisse

### Hausaufgabe

> Erstellen Sie mit Transkribus ein Transkript der Ihnen zugewiesenen (Abschnitt einer) Leichenpredigt.
>
> Geben Sie bis zum nächsten Mittwoch (17.05.) einen kurzen Arbeitsstandsbericht ab und beantworten Sie dazu die folgenden Fragen:
>
> * Wo haben Sie Probleme bzw. was bereitet Ihnen Schwierigkeiten?
> * Wo brauchen Sie Unterstützung und weitere Informationen?
> * Was klappt gut?

## Sitzung am 18.05.

**Entfällt wg. Christi Himmelfahrt.**

## Sitzung am 25.05.

Arbeitssitzung, die wir zur gemeinsamen Bearbeitung der Transkription nutzen wollen.

### Vernetzt euch!

![Bildet Olsenbanden!](img/Bildet_olsenbanden.jpg)

### Transkribus FAQ

Den Rückmeldungen nach, die wir erhalten haben, klappt die Transkription mit Transkribus insgesamt gut, auch wenn es hier und da Probleme gibt.

> **HINWEIS:** Transkribus funktioniert *nicht* im Safari-Browser. Sollten Sie ein Apple-Endgerät verwenden, wechseln Sie bitte für die Arbeit mit Transkribus zu Chrome oder Firefox.

Aus den Arbeitsstandsberichten haben wir die folgenden Fragen entnommen...

#### Quellenmaterial

{{1}}
**Q:** Was mache ich, wenn meine Transkription so aussieht?
![Wenn es schief geht...](img/Screenshot_Kortholdt_1.png)

{{2}}
**A:** Bei einer Transkription, bei der die Linien in diesem Ausmaß falsch erkannt werden, liegt das Quellenmaterial vermutlich in zu geringer Auflösung vor. Dies kann insbesondere dann vorkommen, wenn es sich um ein automatisch generiertes PDF-Dokument handelt. Wenden Sie sich in diesem Fall bitte an uns!

{{3}}
**Q:** Was mache ich, wenn überflüssige Informationen (bspw. Anmerkungen von Bibliotheken) mittranskribiert werden?

{{4}}
**A:** Diese Informationen *sollen* restlos gelöscht werden. Die Regionen sollten so angepasst werden, dass sie den entsprechenden Bereich nicht miterfassen.

#### Linien

{{1}}
**Q:** Wie können neue Zeilen (bspw. für Bibelverse) angelegt werden?

{{2}}
**A:** Mit dem Linientool, s. Demo!

{{3}}
**Q:** Wie ist mit getrennten Linien (Zeilen) umzugehen?

{{4}}
**A:** Leider gibt es derzeit keine andere Lösung, als die Inhalte der zweiten Hälfte in die erste zu kopieren und dann das überflüssige Fragment zu entfernen.

{{5}}
**Q:** Wie lassen sich Linien trennen?

{{6}}
**A:** Auch dafür gibt es keine elegante Lösung: Mit dem Linientool sollten für die neuen Elemente Linien gezogen und die Inhalte hinein kopiert werden. Die ursprüngliche Linie kann dann entfernt werden.

#### Regionen

{{1}}
**Q:** Wie können zusätzliche Angaben (wie Bibelstellen) einer Extraregion zugeordnet und trotzdem erkennbar gemacht werden, in welcher Zeile sie ursprünglich standen?

{{2}}
**A:** Das ist möglich, aber für unsere Zwecke nicht notwendig. Implizit wird es bereits miterfasst.

{{3}}
**Q:** Kann ich die Größe/Form von Regionen verlässlich (sprich: nicht mit der Maus) ändern?

{{4}}
**A:** Nein. Leider stellt die Maus derzeit die einzige Möglichkeit der Bearbeitung dar.

{{5}}
**Q:** Wofür müssen neue Regionen angelegt werden bzw. wofür sind einzelne Regionen sinnvoll?

{{6}}
**A:** *So viele wie nötig, so wenig wie möglich.* Für den Fließtext einer Seite sollte eine Region angelegt werden, darüber hinaus für die Marginalia und (falls vorhanden) die Fußnoten. In der Regel sollten Sie mit zwei bis drei Regionen pro Seite auskommen.

#### Transkription

**Q:** Wie mit handschriftlichen Ergänzungen umgegangen werden? Wie verlässlich müssen die transkribiert werden?

{{1}}
**A:** Das kommt ganz darauf an...

{{2}}
**Q:** Wie können große, verzierte Buchstaben transkribiert und zugeordnet werden?

{{3}}
**A:** Transkribus erkennt solche Buchstaben häufig gar nicht; sie sind im Transkript manuell an der korrekten Stelle zu ergänzen.

{{4}}
**Q:** Sind vermutete Leerzeichen in der Transkription zu ergänzen, wenn sie im Original nicht ersichtlich sind?

{{5}}
**A:** Nein.

{{6}}
**Q:** Woran liegt es, dass teils unterschiedlich viele Buchstaben groß/klein geschrieben werden? Muss die Groß- und Kleinschreibung korrigiert werden?

{{7}}
**A:** Die Groß- und Kleinschreibung sollte der Quelle entsprechen.

#### Wie geht es weiter?

**Q:** Gibt es weitere Fragen?

{{1}}
**A:** ...

{{2}}
**Q:** Sollen in Transkribus Annotationen gemacht werden?

{{3}}
**A:** Nein. Das ist zwar möglich, aber wir werden die Annotationen in einem zweiten Schritt (und sehr viel bequemer) angehen.

{{4}}
**Q:** Wenn wir damit fertig sind, wie sollen wir Ihnen das schicken?

{{5}}
**A:** Über den Export sprechen wir in der kommenden Woche.

### Hausaufgabe

> Erstellen Sie mit Transkribus ein Transkript der Ihnen zugewiesenen (Abschnitt einer) Leichenpredigt.
>
> Schließen Sie die Transkription ab.

## Sitzung am 01.06.

Einführung TEI und gemeinsame Arbeitssitzung zur Fortsetzung der Transkription.

### Gemeinsame Sprache TEI

![Logo_TEI!](img/TEI.jpg)

1. Die Text-Encoding-Initiative ist ein Konsortium, das einen *community standard* erstellt und pflegt.
2. Sie stellen v.a. die guidelines zur Verfügung, die ein kontrolliertes Vokabular der Auszeichnung ermöglichen. Aus den (vermutlich) unendlichen Möglichkeiten der XML-Auszeichnungen trifft die TEI eine Auswahl und legt damit ein Vokabular und eine Grammatik fest.

> TEI P5 Guidelines
> http://www.tei-c.org/release/doc/tei-p5-doc/en/html/index.html  
> Version 4.6.0. (letztes Update am 04. April 2023)

#### Wiederholung: Validität

{{1}}
* Erfüllt das Dokument ein Set an Regeln, die in einem spezifischen Schema definiert sind und dem Dokument zugewiesen sind?
* In einem Schema werden die Grammatik und das Vokabular festgelegt, z.B. welche Elementnamen erlaubt sind, ob sie eine nähere Beschreibung mit Attributen erzwingen etc.
* Schemata können sehr allgemein oder sehr spezifisch sein; TEI stellt einige zur Verfügung aber alle können ein eigenes Schema bauen.

#### Vokabular und Grammatik

* Wir weisen unseren Dokumenten ein „Schema“ zu, das die nötigen Einschränkungen enthält. Die Dateiendung eines Schemas ist (in unserem Fall) rng.
* tei_all ist das umfangreichste und größte Schema.

### Grundstruktur

1. Wurzelelemnt ist `<TEI>`
2. Namespace kommt mit in das Wurzelelement: `<TEI xmlns="http://www.tei-c.org/ns/1.0">`
3. Zuweisung des Schemas
4. `<teiHeader>` für die Metadaten
5. `<text>` erst jetzt folgt der Text der Edition

#### Header - Ein Zuhause für Metadaten

* Elektronische Titelei der Edition u.v.m.
* Eines der wenigen verpflichtenden Elemente in TEI.
* Enthält beschreibende und erklärende Metadaten, die der digitalen Ressource vorangestellt sind.
* Repositorien, bspw. Bibliotheken und Archive brauchen Metadaten (Bsp: Kataloge).
* Enthält die Dokumentation der Kodierungspraxis.

#### 4 (oder 5?) Kernelemente

* `<fileDesc>` -> bibliographische Beschreibung der Datei
* `<encodingDesc>` -> Verhältnis zwischen elektronischem Text und seiner Quelle
* `<profileDesc>` -> Beschreibung der nicht-bibliographischen Merkmale des Textes, insbes. Sprache, Entstehung(sbedingungen), Beteiligte, Aussehen des Mediums
* `<xenoData>` -> alle nicht TEI-konformenen Metadaten
* `<revisionDesc>` -> dokumentiert die Änderungen, die an der elektronischen Datei vorgenommen wurden (wer, wann, was)

> Woher können wir diese Informationen in *unserem* Fall bekommen?

#### Must-have I

* `<fileDesc>` ist das einzige verpflichtende Elemente im header.
* Aus der `<fileDesc>` werden wichtige Informationen übernommen, die für Katalogeinträge relevant sind und die Zitation der elektronischen Datei ermöglichen. AutorIn, Titel, HerausgeberIn, Publikation, Distribution, Angaben zur analogen Quelle, Verantwortliche, Finanzierung des Projekts etc. werden dort festgehalten.
* Eine gute `<fileDesc>` weist gute wissenschaftliche Praxis aus und validiert digitale Publikationen als nachvollziehbar und zitierbar.

#### Must-have II

Innerhalb der `<fileDesc>` stehen verpflichtend:

1. `<titleStmt>` Angaben zum Titel der Datei
2. `<publicationStmt>` Angaben zu den Publikationsdaten der Datei
3. `<sourceDesc>` Angaben zur Quelle/Vorlage der Datei

Wie für die meisten Dinge zu Beginn einer Publikation, ist es ratsam, diese Informationen erst am Ende des Prozesses einzutragen und zu Beginn lediglich Platzhalter zu schreiben

#### Unser Annotationsvokabular

* Person (`persName`)
* Organisation (`orgName`)
* Ort (`placeName`)
* Term, Begriff (`term`)
* Datum (`date`)
* Link (`ref`)
* Abkürzung (`abbr`)
* Sic! (`sic`)
* Regulierende Eingriffe (`reg`)
* Highlight (`hi`)

### Vorgaben für die Transkription in Transkribus

Die Transkription der Leichenpredigten in Transkribus sollte pro (regulärer Text-)Seite vier Regionen umfassen:

1. Der Kopfbereich, mit Seitenzahl und -überschrift. Alle inhaltlich distinkten Informationen sollten auf einer eigenen Linie erfasst werden, d. h. im Beispiel besteht diese erste Region aus zwei Zeilen: Die erste enthält die Seitenzahl ("10"), die andere die Überschrift ("Christliche").
2. Die Hauptregion umfasst den gesammten Fließtext der Seite (im Beispiel von "Emahus" bis "möge").
3. Die Marginalinformationen werden in einer eigenen, dritten Region erfasst. Alle Informationen in dieser Region sollten jeweils auf einer eigenen Zeile erfasst werden.
4. Die optionalen Informationen im Fußbereich werden in einer vierten Region erfasst, die Fußnoten und Anmerkungen umfasst.

![Eine Seite, bei der alle vier oben genannten Regionen vorhanden und erfasst sind.](img/transkription1_regions.png)

Die Transkription sieht entsprechend, wie in den folgenden beiden Screenshot gezeigt wird aus:

![Region 1 und 2](img/transkription2_region1und2.png)

usw. Im Beispiel wurde der Text nur strukturell angepasst, aber noch nicht auf seine Richtigkeit hin überprüft.

![Region 3 und 4](img/transkription3_region3und4.png)

#### Weitere Absprachen

* Die Transkription erfolgt quellennah, Eingriffe sollten soweit möglich vermieden werden. 
* Leerzeichen bleiben erhalten, wie sie in der Quelle erkennbar sind.
* Eingriffe in den Text (bspw. weil etwas nicht lesbar, unverständlich oder ergänzt worden ist) werden (zunächst!) durch eckige Klammern "[", "]" kenntlich gemacht. 

### Export der Transkription

Da der Export der Transkription als TEI-Dokument derzeit noch nicht aus dem Online-Tool möglich ist, müssen wir leider einen kleinen Workaround bemühen, der im Folgenden erklärt wird:

(1.) Öffnen Sie die Collection mit Ihrer Leichenpredigt.

![Collections](img/export1_collections.png)

(2.) Lokalisieren Sie auf der linken Seite den Menüpunkt *User-Manager*.

![User Management](img/export2_user-management.png)

(3.) Wechseln Sie auf den Tab *Add* und fügen Sie dort meine E-Mail-Adresse ein.

![E-Mail](img/export3_users.png)

(4.) Ändern Sie die Rolle zu *Editor* und klicken Sie *+ Add*.

![E-Mail und Rolle](img/export4_user-add.png)

(5.) Senden Sie mir eine E-Mail, um mich zu benachrichtigen, sobald Ihre Transkription abgeschlossen ist und Sie einen Export wünschen.

### Hausaufgabe

Lesen Sie Kapitel 18 "Manuelle und automatische Annotationen" (S. 253 - 267) in:

Jannidis, F.; Kohle, H. & Rehbein, M. (Eds.): *Digital Humanities*. J.B. Metzler, 2017.

## Sitzung am 08.06.

### Besprechung von Kapitel 18 (Jannidis)

1. Warum annotieren wir? Welche Funktionen erfüllen Annotationen?
2. Worin unterscheiden sich *prozedurale* und *deklarative* Auszeichnungen?
3. Wie wird durch digitale Annotationen eine schon existierende, analoge Forschungspraxis forgesetzt?
4. Welche Schritte beinhaltet der Prozess der Kategorienbildung? In welchem Schritt befinden wir uns aktuell? Welche Schritte werden wir voraussichtlich nicht oder nur in begrenztem Umfang umsetzen?
5. Wodurch unterscheiden sich manuelle und automatische Annotationsverfahren?
6. Welche Möglichkeiten bietet XML TEI zum Umgang mit Bildern und Bildmaterial?
7. Wie lassen sich Aussagen über die Qualität von Annotationen treffen?

### Unser Annotationsvokabular

* Person (`persName`)
* Organisation (`orgName`)
* Ort (`placeName`)
* Term, Begriff (`term`)
* Datum (`date`)
* Link (`ref`)
* Abkürzung (`abbr`)
* Sic! (`sic`)
* Regulierende Eingriffe (`reg`)
* Highlight (`hi`)

> Genügt das? Brauchen wir mehr (oder weniger)?

### Forschungsfragen entwickeln

> Recherchieren Sie *Ihren* Professor im Kieler Gelehrtenverzeichnis (https://cau.gelehrtenverzeichnis.de).
> 
> Ihre Transkription, das vorgesehene Tagset und die Informationen aus dem Gelehrtenverzeichnis gegeben: Stellen Sie sich vor, Sie *müssen* Ihre Abschlussarbeit mit Hilfe dieser Bausteine/Werkzeuge schreiben:
> 
> 1. Welche Forschungsfrage würden Sie zur Bearbeitung wählen?
> 2. Was fehlt Ihnen? Was würden Sie zusätzlich auszeichnen wollen? Welche Informationen müssten Sie zur Beantwortung Ihrer Fragestellung hinzunehmen/-recherchieren?
> 3. Welche Präsentation der annotierten Leichenpredigt wäre für die Bearbeitung Ihrer Forschungsfrage besonders hilfreich? 

### Hausaufgabe

> Füllen Sie die Erfassungsrichtlinie (OLAT) für Ihr Dokument aus.

## Sitzung am 15.06.

In dieser Woche beschäftigen wir uns mit dem Import der transkribierten Dokumente in den TEI Publisher, der Anpassung des TEI Headers, sowie der Annotation der Dokumente mit den Mitteln des Publishers. 

### Erste Schritte mit dem TEI Publisher

   {{1}}
Der TEI Publisher begrüßt Sie mit dem folgenden Start-Bildschirm:

![Start-Bildschirm des TEI Publishers](img/tei_pub_start.png)

   {{2}}
Loggen Sie sich zunächst mit den Login-Daten ein (oben rechts), die Sie von mir per Mail erhalten haben.

   {{3}}
Klicken Sie anschließend auf "Annotation Samples": Dadurch kommen Sie in eine neue Ansicht, in der Sie eigene Dokumente hochladen können, in dem Sie sie mit *drag and drop* aus einem Verzeichnis in den Upload-Bereich (rechts, unterhalb des Logins) verschieben. 

![Annotations Samples und Upload-Bereich](img/tei_pub_upload.png)

Anschließend sind die Dokumente in der Liste (mitte) sichtbar und können angeglickt werden. Dadurch gelangen Sie in die Annotationsansicht.

   {{4}}
In der Annotationsansicht können Sie ein oder mehrere Worte markieren, wie Sie es aus anderen Textverarbeitungsprogrammen gewohnt sind. Durch einen Klick auf eines der Icon auf der linken Seite, versehen Sie die Markierung mit einer TEI-Annotation (einem *tag*). 

![Annotationsansicht](img/anno_markieren.png)

   {{5}}
Es öffnet sich eine Suchmaske, die die Annotation mit einem eindeutigen *Identifier* in der GND verknüpft. Für die Suche müssen sie u. U. den Suchterm anpassen (und möglicherweise auch verschiedene ausprobieren). 

![Identifier suchen und korrigieren](img/anno_korrigieren.png)

   {{6}}
Gibt es mehrere Auftreten des gleichen Terms im Dokument, dann erhalten Sie auf der linken Seite (unterhalb der Icon) die Möglichkeit durch das Anhaken der Boxen auch alle anderen Auftreten auszuzeichnen. Dies vereinfacht und beschleunigt die Annotation. 


### TEI Header umsetzen

Bevor Sie mit der Annotation des Dokuments loslegen, sollten Sie zunächst den TEI Header anpassen:

   {{1}}
Füllen Sie zunächst die [Erfassungsrichtlinie](https://ruapehu.informatik.uni-kiel.de/erfassungsrichtlinie/) vollständig aus:

![Erfassungsrichtlinie](img/erfassungsrichtlinie.png)

Markieren Sie anschließend das vollständige (!) XML (von und einschließlich `<teiHeader>` bis `</teiHeader>`) und kopieren Sie es.

   {{2}}
Öffnen Sie als nächstes Ihr Dokument im TEI Publisher (s. Erste Schritte). Dort finden Sie den XML-Editor, wenn Sie oben rechts auf das "Burger"-Menü klicken und...

![Burger Menü](img/burger_menu.png)

... in dem Sich anschließend öffnenden Menü "VIEW TEI XML" auswählen.

![View TEI XML](img/view_tei_xml.png)

   {{3}}
Es öffnet sich ein XML-Editor. Innerhalb dieses Editors markieren Sie alles von und einschließlich `<teiHeader>` bis `</teiHeader>`. Diesen Bereich können Sie löschen und durch Ihren neu erstellten Header ersetzen.

![TEI Header ersetzen](img/replace_tei_header.png)

Melden Sie sich bei uns, falls Sie damit Probleme haben sollten! Sie können unabhängig von der Änderung des Headers bereits mit der Annotation beginnen.

### Annotationsrichtlinie

Annotationsrichtlinien sind in der Regel sehr umfangreich und stellen selbst einen bedeutenden Teil der Forschungsarbeit in Projekten dar. Ein Beispiel dafür finden Sie in den [Guidelines for the electronic encoding of Medieval Nordic primary sources](https://www.menota.org/HB3_index.xml). 

Im Rahmen unseres Projektseminars haben wir nicht die Zeit und Ressourcen eine derartig feingliedrige Richtlinie für die Auszeichnung der Inhalte zu erstellen. Wir beschränken uns auf die folgenden Regeln (die im Seminarverlauf durch Ihre Rückmeldungen erweitert und ergänzt werden):

1. Personen, Organisationen, Orte und Datumsangaben sollen vollständig erfasst werden. 
2. Berufsbezeichnungen, Titel und Fachbereiche sollen durch die *Term*-Annotation erfasst und mit einem Eintrag in der GND verknüpft werden. 
3. Auf die Erfassung von Bibelversen und biblischen Personen wird verzichtet.
4. Personen, Organisationen, Orte und Begriffe, die sich nicht im TEI Publisher erfassen lassen, sollen in einem separaten Dokument gesammelt werden. Dieses Dokument sollte neben dem Element auch dessen Position im Dokument, sowie weitere Informationen berücksichtigen, die relevant sind (bei einer Person bspw. das Verwandschaftsverhältnis). 

### Hausaufgabe

> Annotieren Sie bis zur nächsten Woche, soweit Sie kommen.
> 
> Notieren Sie Personen, Orte und Organisationen, für die Sie keinen Eintrag in der GND finden (s. Annotationsrichtlinie). Erstellen Sie sich dafür eine Liste oder ein Excel-Dokument, das den/die Person/Ort/Organisation enthält, die Person im Dokument, sowie weiterführende Informationen (bspw. "ist Onkel von").

## Sitzung am 22.06.

### Neue Annotationstypen: 'trait' und 'event'

Aus den Überlegungen zu eigenen Forschungsfragen in der Sitzung am 08.06. hatten sich zwei Bedarfe für Auszeichnungen ergeben, die über den Standard hinausgehen, den der TEI Publisher bietet:

* Eine Auszeichnung der *Berufsbezeichnungen* bzw. *Titel*, sowie die *Fachbereiche* würden helfen den akademischen Werdegang nachzuvollziehen.
* Es wäre interessant die *Charaktereigenschaften* der verstobenen Personen zu annotieren, wie sie in der Leichenpredigt dargestellt werden.
* Insgesamt wäre es wünschenswert private und berufliche *Ereignisse* im Leben der Person im Text kenntlich zu machen.

Während ersteres sich durch die `term`-Annotation bereits problemlos bewerkstelligen lässt, fehlte für die beiden anderen Punkte eine zufriedenstellende Möglichkeit. Dem haben wir durch eine Erweiterung unseres *tag sets* Abhilfe geschaffen: Durch die `event`-Annotation (Sanduhr-Icon) können Ereignisse, durch die `trait`-Annotation (Herz-Icon) Charaktereigenschaften abgebildet werden.

Für beide ist keine Normdatei oder -datenbank hinterlegt, so dass beim Typ bis auf weiteres selbstgewählte, sinnvolle Werte vergeben werden sollten. Dabei empfiehlt es sich das ausgezeichnete Element auf einen gemeinsamen Wert zu verallgemeinern, bspw. *hochedel*, *edelst*, *des Edelsten Herrn...*, etc. mit dem `type` *edel* zu versehen.

![Neue Annotationen](img/neue_annotationen.png)


### Normdaten und Normdatenbanken

*Normdaten* bieten ein kontrolliertes Vokabular zur Identifikation von Personen, Orten, Institutionen u.v.m. In *Normdatenbanken* werden *Normdaten* anhand eines eindeutigen, persistenten Identifiers zur Verfügung gestellt. Dieser wird auch als *Uniform Resource Identifier* (URI) bezeichnet.

> Warum sind Normdaten und Normdatenbanken eine gute Idee?

      {{1}}
Aus Gründen der **FAIR**ness (Findable, Accessible, Interoperable, Reusable).

#### Wichtige Normdatenbanken (Autoritäten)

* GND (gemeinsame Normdatei): Personen, Körperschaften, Orte
* LCCN (Library of Congress Control Number): amerikanische Variante der GND
* VIAF (Virtual International Authority File): Mapping versch. Normdaten
* Geonames: offenes Projekt für Ortsnamen
* TGN (Getty Thesaurus of Geographic Names): Ortsnamen
* u.v.a.

#### Weitere Informationen

Vertiefende Informationen finden Sie hier (keine Pflichtlektüre, aber empfohlen):

> Kapitel 16 "Aufbau von Datensammlungen" (S. 223 - 233) in:
>
> Jannidis, F.; Kohle, H. & Rehbein, M. (Eds.): *Digital Humanities*. J.B. Metzler, 2017.

### Verlinkung und eigene Normdaten

Innerhalb eines TEI-Dokuments können wir selbst Identifikationen vergeben und *interne Normdaten* zur Verfügung stellen. 

Die Verknüpfung eines Auszeichnung mit internen oder externen Normdaten erfolgt über eine Verlinkung (*linking*).

> In welchen Fällen könnte es sinnvoll sein eigene Normdaten zur Verfügung zu stellen?

#### Linking

*Linking* wird verwendet, um Verbindungen zwischen identifizierten benannten Entitäten (*named entities*, z.B. Personen, Orte, Ereignisse, ...) und einer ausführlicheren Erklärung bzw. einem Normdatum herzustellen.

Eine Verlinkung wird mittels einem Identifier hergestellt, der im `ref`-Attribut des verlinkenden Tags angegeben wird. 

Handelt es sich um einen internen Link, also um einen Link, der auf etwas verlinkt, das im gleichen Dokument definiert wird, muss ein `#` vor dem Identifier stehen. 

#### Beispiel

Das folgende, ausführliche Beispiel aus der [TEI Dokumentation](https://tei-c.org/release/doc/tei-p5-doc/en/html/ref-standOff.html) veranschaulicht sehr gut das Vorgehen: In einem speziellen Bereich, dem `standOff`, werden eigene Normdaten definiert: Die Städte Atlanta und Birmingham. Beide verfügen über einen eindeutigen, einzigartigen Identifier (`LATL` und `LBHM`). Diese IDs können im weiteren Text verwendet werden, um eine interne Verlinkung (bspw. `#LATL`) zwischen einer `placeName`-Auszeichnung und der entsprechenden Stadt herzustellen: `<placeName ref="#LATL">Atlanta</placeName>`. 

```xml
<TEI xmlns="http://www.tei-c.org/ns/1.0">
 <teiHeader>
<!-- ... -->
 </teiHeader>
 <standOff>
  <listPlace>
   <place xml:id="LATL">
    <placeName>Atlanta</placeName>
    <location>
     <region key="US-GA">Georgia</region>
     <country key="USA">United States of America</country>
     <geo>33.755 -84.39</geo>
    </location>
    <population when="1963"
     type="interpolatedCensus" quantity="489359"
     source="https://www.biggestuscities.com/city/atlanta-georgia"/>
   </place>
   <place xml:id="LBHM">
    <placeName>Birmingham</placeName>
    <location>
     <region key="US-AL">Alabama</region>
     <country key="USA">United States of America</country>
     <geo>33.653333 -86.808889</geo>
    </location>
    <population when="1963"
     type="interpolatedCensus" quantity="332891"
     source="https://www.biggestuscities.com/city/birmingham-alabama"/>
   </place>
  </listPlace>
 </standOff>
 <text>
  <body>
<!-- ... -->
   <p>Moreover, I am <choice>
     <sic>congnizant</sic>
     <corr>cognizant</corr>
    </choice> of the interrelatedness of all communities and
   <lb/>states. I cannot sit idly by in <placeName ref="#LATL">Atlanta</placeName> and not be concerned about what happens
   <lb/>in <placeName ref="#LBHM">Birmingham</placeName>. <seg xml:id="FQ17">Injustice anywhere is a threat to justice everywhere.</seg> We
   <lb/>are caught in an inescapable network of mutuality, tied in a single garment
   <lb/>of destiny. Whatever affects one directly affects all indirectly. Never
   <lb/>again can we afford to live with the narrow, provincial <soCalled rendition="#Rqms">outside agitator</soCalled>
    <lb/>idea. Anyone who lives inside the United States can never be considered
   <lb/>an outsider anywhere in this country.</p>
<!-- ... -->
  </body>
 </text>
</TEI>
```

#### Alternativen zum 'standOff'

Neben dem `standOff`-Bereich, der sich unmittelbar unter dem TEI-Wurzelelement befindet, gibt es auch noch zwei Alternativen:

[`back`](https://tei-c.org/release/doc/tei-p5-doc/en/html/ref-back.html) beinhaltet Anhänge und vertiefende Informationen zu einem Text oder Textabschnitt. Entsprechend wird dieser Bereich in der Regel im Anschluss an einen `text` angefügt. 

[`particDesc`](https://tei-c.org/release/doc/tei-p5-doc/en/html/ref-particDesc.html) und [`settingDesc`](https://tei-c.org/release/doc/tei-p5-doc/en/html/ref-settingDesc.html) sind Elemente des TEI Headers und dienen dazu Personen, Organisationen (im Fall von `particDesc`) und Orte (im Fall von `settingDesc`) zu definieren. 

Die verschiedenen Auszeichnungen haben verschiedene Anwendungsbereiche, die sich in der Dokumentation nachlesen lassen. Im Zweifel ist `standOff` in der Regel keine schlechte Wahl und kann verwendet werden, solange sich keine unmittelbaren Gründe ergeben, die dagegen sprechen. 

### Hausaufgabe

> Fahren Sie mit der Annotation der Daten fort! Sofern Sie die Annotation bereits abgeschlossen haben, können Sie gerne die neuen Annotationstypen `trait` und `event` verwenden, um Ihre Auszeichnungen mit weiteren Informationen anzureichern.
>
> Notieren Sie Personen, Organisationen und Orte, die Sie nicht in einer Normdatenbank finden konnten, in der folgenden Cloud-Datei: https://cloud.rz.uni-kiel.de/index.php/s/bDEXxHdtJJN4xFq
> Beachten Sie bitte, dass es für Personen, Organisationen und Orte jeweils ein eigenes Tabellenblatt gibt. 

## Sitzung am 29.06.

## Sitzung am 06.07.

### Aufgabe für die Abschlusspräsentation

> Präsentieren Sie die Person Ihrer Leichenpredigt in einem 3-minütigen Vortrag. Die Vortragslänge wird mit einer Stoppuhr überprüft und nach exakt drei Minuten abgebrochen. Fassen Sie sich also kurz und überlegen Sie sich, welchen Aspekt der Person Sie hervorheben und welche Informationen Ihnen wichtig sind.
> 
> Zur Unterstüztung Ihrer Präsentation können Sie eine (!) PowerPoint-Folie, Website (bspw. das [Kieler Gelehrtenverzeichnis](https://cau.gelehrtenverzeichnis.de/)) oder andere Visualisierung verwenden. 