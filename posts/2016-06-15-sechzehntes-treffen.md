---
title: Programm für das sechzehnte Treffen am 14. Juli 2016
subtitle: Zipper, Cobra, kategorielle Patch-Theorie, Typtheorie
meetup-announcement: 2016-07-14
meetup-counter: "16"
meetup-time: 19:00
author: Matthias Hutzler
---

Makarius stellt [Cobra](http://www.flatmap.net/cobra) vor, ein modernes
Framework, um Code und Beweise zu präsentieren. Cobra unterstützt
Isabelle-Beweise sowie Scala- und Haskell-Code.

Profpatsch teilt seine Beobachtung, dass
[Zipper](https://www.st.cs.uni-saarland.de/edu/seminare/2005/advanced-fp/docs/huet-zipper.pdf)
zu den coolsten Datenstrukturen gehören, und wird damit die Reihe
über funktionale Datenstrukturen fortsetzen.

Bei diesem oder dem nächsten Treffen wird Tim einen Vortrag zu
Versionskontrollsystemen und Patch-Theorie halten. Er wird darin die
unterschiedlichen Modelle von git, darcs und insbesondere dem neuen
Versionskontrollsystem [Pijul](http://pijul.org/) vorstellen. Letzteres VCS
basiert auf (oder ist laut Webseite "inspiriert von") einer
kategorientheoretischen [Theorie von](http://www.lix.polytechnique.fr/Labo/Samuel.Mimram/docs/mimram_ctp.pdf)
[Patches](http://www.lix.polytechnique.fr/Labo/Samuel.Mimram/docs/mimram_ctp_slides.pdf)
von Samuel Mimram und Cinzia Di Giusto.

[Kurze Werbepause: Das Paper ist richtig cool! Die Autoren gehen von der
Kategorie der "normalen", linearen Dokumente aus und wollen dann
"mergen" als Pushout modellieren. Damit Patches immer gemergt werden
können, sollte die Kategorie endlich kovollständig sein, damit alle
Pushouts existieren. Deshalb gehen die Autoren zur freien konservativen
(schon existierende Kolimiten bleiben erhalten) Kovervollständigung der
Kategorie der linearen Dokumente über. Diese Kovervollständigung man
nach einem Folklore-Theorem explizit als volle Unterkategorie der
Kategorie der Prägarben auf der Kategorie der linearen Dokumente
beschreiben. Im Hauptteil des Papers leiten die Autoren eine viel
konkretere, graphentheoretische Beschreibung dieser Kategorie her.]

Ingo beginnt unter dem Titel *Was sind und was sollen die Typen?* eine
Einführung in Typtheorie unter besonderer Beachtung von
Homotopietyptheorie. Die grundlegende Motivation aus der Informatik und der
Programmierpraxis sind natürlich bekannt: Man möchte zur Compilezeit
Informationen über das Programmverhalten gewinnen, um fehlerhafte Programme
noch vor ihrer Ausführung erkennen und ablehnen zu können.

Aber es ist vielleicht weniger bekannt, wie Typtheorie entstanden ist
(das war nämlich lange vor den Programmiersprachen), welches Problem sie
ursprünglich lösen sollte (und auch tatsächlich löst), und wie ein
Typsystem aufgebaut ist.

Ziel des ersten Teils wird auch sein, ein Grundverständnis im Lesen von
Typsystemspezifikationen zu vermitteln. Wir werden extensionale und
intensionale Martin-Löf-Typtheorie behandeln.

Homotopietyptheorie ist ein neuer Zweig der Mathematik,
der Aspekte von verschiedenen anderen Teilgebieten der Mathematik auf
verblüffende Art und Weise kombiniert. Es ist Teil von Voevoedskys Programm zu
einer *univalenten Grundlegung* der Mathematik und basiert auf einer kürzlich
entdeckten Verbindung zwischen Homotopietheorie aus der Mathematik und
Typtheorie aus der Logik und theoretischen Informatik.

In gewöhnlichen Zugängen zu einer Grundlegung der Mathematik unterscheidet man
zwischen Objekten (wie zum Beispiel natürlichen Zahlen und Mengen) und Aussagen
über diese Objekte. In Homotopietyptheorie gibt es diese Unterscheidung nicht.
Objekte und Aussagen über Objekte werden auf eine gemeinsame Stufe gestellt.
Beweisen und Konstruieren werden miteinander identifiziert.

Der Vortrag setzt keine Vorkenntnisse aus Logik und Typtheorie und
selbstverständlich auch keine aus Homotopietheorie voraus. Der Vortrag ist für
Leute konzipiert, die sich für diese neue Bewegung in der Logik interessieren,
aber nicht praktizierende Mathematikerinnen sind.

Er wird folgende Fragen klären: Was hat es mit Homotopietyptheorie auf sich?
Wie werden in Homotopietyptheorie Objekte und Aussagen miteinander vereint, auf
eine Stufe gestellt? Wozu ist Homotopietyptheorie gut? Wieso und für wen ist
sie interessant?

Ein Teil der Antwort auf die letzte Frage lautet: Homotopietyptheorie ist für
Leute interessant, die computergestützt Beweise führen möchten.