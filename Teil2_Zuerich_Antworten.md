# Teil 2: Vom Wunsch zum Prompt (Entwurf zum Abschreiben)

Name: ______________________  Datum: ____________

Ich arbeite allein. Das ist ein Entwurf: Wörter so ändern, dass es nach dir klingt.

---

## E2 · Gedanken zum Einstieg

*Welcher Auftrag hilft der KI eher weiter? Begründe an zwei Stellen.*

Auftrag B hilft mehr. Erstens sagt er, für wen die Seite ist («Jugendliche, die die Stadt noch nicht kennen») und wobei sie helfen soll. Bei Auftrag A weiss die KI nicht, was «cool» heisst. Zweitens sagt B, was die KI zuerst tun soll (eine kurze Übersicht) und dass sie nachfragen darf. Bei A rät die KI einfach.

---

## A1a · Vorhaben und Zielgruppe

**1 · Unser Vorhaben**

Ich entwickle eine Webseite, die Jugendlichen Orte in Zürich zeigt, die gratis oder günstig sind. Die Seite zeigt jeden Ort mit einer kurzen Beschreibung, dem Preis und einer Markierung.

**2 · Zielgruppe und Nutzen**

Die Seite ist für Jugendliche zwischen 13 und 16 Jahren, die zum ersten Mal in Zürich sind und nur Taschengeld dabeihaben. Sie hilft ihnen, einen Tag zu planen, ohne viel Geld auszugeben. Sie sehen schnell, welche Orte gratis sind und ob ein Ort draussen oder drinnen ist.

---

## A1b · Inhalte und Grenzen

**3 · Inhalte und erste Funktionen**

Die Seite zeigt sechs Orte: Lindenhof, Flussbad Oberer Letten, Seepromenade, Uetliberg, Grossmünster und Landesmuseum Zürich. Erste Funktion 1: eine Liste mit Name, kurzer Beschreibung und Preis. Erste Funktion 2: eine Markierung bei jedem Ort («gratis», «draussen» oder «drinnen»).

**4 · Grenzen und Vorgaben**

Die Seite besteht aus einer einzigen HTML-Datei ohne externe Bibliotheken. Sie soll auf dem Handy gut lesbar sein. Vorerst gibt es keine Suche, keinen Filter, keine Karte und keine Anmeldung.

---

## A1c · Unser erster vollständiger Prompt

**5 · Das soll die KI jetzt tun**

Die KI soll eine erste kleine Version der Seite als vollständigen Code in einer einzelnen HTML-Datei ausgeben. Wenn Angaben fehlen, soll sie nachfragen.

**Prompt:**

> Ich entwickle für die Schule einen digitalen Stadtführer für Zürich. Er richtet sich an Jugendliche zwischen 13 und 16 Jahren, die zum ersten Mal in Zürich sind und wenig Geld haben. Die Seite soll ihnen helfen, günstige und gratis Orte zu finden und einen Tag zu planen.
>
> Die erste Version zeigt sechs Orte: Lindenhof, Flussbad Oberer Letten, Seepromenade, Uetliberg, Grossmünster und Landesmuseum Zürich. Jeder Ort hat einen Namen, eine kurze Beschreibung in zwei Sätzen und eine Preisangabe. Dazu bekommt jeder Ort eine Markierung: «gratis», «draussen» oder «drinnen».
>
> Wichtig: Die Seite ist auf Deutsch, besteht aus einer einzigen HTML-Datei ohne externe Bibliotheken und ist auf dem Handy gut lesbar. Es gibt noch keine Suche, keinen Filter, keine Karte und keine Anmeldung.
>
> Gib mir den vollständigen Code der HTML-Datei aus. Wenn dir Angaben fehlen, frag zuerst nach.

---

## A2a · Prompt erproben

Das muss er selbst machen. Prompt in einen KI-Chat kopieren, die Antwort als Text oder Screenshot einfügen und ehrlich ankreuzen, was er benutzt hat. Wenn er keinen KI-Zugang hat, kreuzt er «Mit bereitgestelltem Beispiel gearbeitet» (Material M3) an. **Nicht so tun, als wäre es getestet, wenn es nicht stimmt.**

## A2b · Die erste Antwort prüfen

Das schreibt er, nachdem er die KI-Antwort hat. Er vergleicht sie mit dem Prompt:

- **Das passt:** Zielgruppe stimmt, sechs Orte sind da, jeder hat eine Beschreibung und eine Markierung, es ist eine einzige HTML-Datei.
- **Das fehlt oder weicht ab:** Hat die KI eine Suche, einen Filter oder eine Karte ergänzt, obwohl wir das nicht wollten? Stimmen die Preise? (Preise von Orten immer auf der offiziellen Seite des Ortes prüfen, die KI kann sich irren.)

## A2c · Gezielt nachsteuern

*(Beispiel, an die echte Antwort anpassen.)*

**3 · Unsere begründete Änderung:** Die Preisangaben sollen klarer werden, weil die Zielgruppe wenig Geld hat und genau wissen will, was etwas kostet.

**4 · Rückmeldung an die KI:**

> Überarbeite die Preisangaben bei jedem Ort, weil die Jugendlichen wissen wollen, was genau etwas kostet. Schreib bei jedem Ort in einem Satz, was gratis ist und was Geld kostet. Behalte Zielgruppe, die sechs Orte, die Markierungen und die einzelne HTML-Datei bei. Gib die vollständige überarbeitete Datei aus.

---

## LS2 · Leistungssnack

- **Was sollte die KI tun?** Eine erste Seite mit sechs Orten als HTML-Datei erstellen. (Zeig die Stelle «Gib mir den vollständigen Code» im Prompt.)
- **Welche Stelle hast du geprüft?** Die Markierungen bei jedem Ort. Er sagt, ob sie vorhanden waren und stimmen.
- **Folgeauftrag und Grund:** Klarere Preise, weil das für die Zielgruppe das Wichtigste ist.
- **Ehrlich sagen,** ob er den Folgeauftrag schon ausprobiert hat oder nicht.

---

## A3 · Überarbeitete Prompt-Fassung

> Ich entwickle für die Schule einen digitalen Stadtführer für Zürich. Er richtet sich an Jugendliche zwischen 13 und 16 Jahren, die zum ersten Mal in Zürich sind und wenig Geld haben. Die Seite hilft ihnen, günstige und gratis Orte zu finden und einen Tag zu planen.
>
> Die Seite zeigt sechs Orte: Lindenhof, Flussbad Oberer Letten, Seepromenade, Uetliberg, Grossmünster und Landesmuseum Zürich. Jeder Ort hat einen Namen, eine Beschreibung in zwei Sätzen und einen klaren Preis. Beim Preis steht in einem Satz, was gratis ist und was Geld kostet. Jeder Ort hat eine Markierung: «gratis», «draussen» oder «drinnen».
>
> Die Seite ist auf Deutsch, besteht aus einer einzigen HTML-Datei ohne externe Bibliotheken und ist auf dem Handy gut lesbar. Es gibt noch keine Suche, keinen Filter, keine Karte und keine Anmeldung.
>
> Gib den vollständigen Code der HTML-Datei aus. Wenn dir Angaben fehlen, frag zuerst nach.

☐ Diese Fassung wurde mit einer KI erprobt.  ☑ Diese Fassung ist noch nicht erprobt. *(Nur ändern, wenn er sie wirklich getestet hat.)*

---

## A4 · Abschluss-Check

**2 · Begründe eine Verbesserung:** In A1c stand nur «eine Preisangabe». In A3 steht, dass der Preis in einem Satz sagen soll, was gratis ist und was kostet. Das macht den Auftrag klarer, weil die KI sonst nur «gratis» oder eine Zahl schreibt und das beim Uetliberg oder Grossmünster falsch wäre.

**3 · Offene Punkte:** Die Preise und Öffnungszeiten der Orte sind noch nicht auf den offiziellen Seiten geprüft. Der nächste Schritt ist, das für jeden Ort nachzuschauen.

---

## R2a · Meine Reflexion, Seite 1

**1 · Das habe ich jetzt verstanden:** Die KI kennt meine Arbeitsblätter nicht. Alles Wichtige muss im Prompt stehen: Zielgruppe, Orte, Funktionen und was nicht dazugehört. Eine passende Antwort ist nicht automatisch richtig, deshalb muss ich sie prüfen.

**2 · Das kann ich jetzt:** Ich kann aus meiner Projektidee einen vollständigen Prompt schreiben und die Antwort mit meinen Vorgaben vergleichen. Zum Beispiel prüfe ich, ob die KI eine Suche eingebaut hat, obwohl ich sie ausgeschlossen habe.

## R2b · Meine Reflexion, Seite 2

**3 · Das möchte ich noch verbessern:** Ich muss noch lernen, Preise und Öffnungszeiten auf der offiziellen Seite zu prüfen, statt der KI zu glauben.

**4 · Meine wichtigsten Erkenntnisse:** Überrascht hat mich, wie viel besser die Antwort wird, wenn ich genau sage, was nicht dazugehören soll.

*(Die Reflexion muss persönlich sein. Er ändert sie so, dass sie stimmt.)*
