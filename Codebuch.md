# Codebuch Testat Teil 2 MTV Stuttgart von Kübra Kilic (hk061)

## Edgelist
**from** 
(Sender) id, eindeutige Bezeichnung der Spielerinnen jeweils mit Nachnamen

**to**
(Empfänger) id, eindeutige Bezeichnung des Vereins/der Organisation und des Heimatlandes

Verein/Organisation: Abkürzung mit Anfangsbuchstaben;
Heimatland: Identifizierbare, passende Abkürzung

**relationship**
(Art der Beziehung)
**1=** Heimatland,
**2=** Ehemaliger Verein

## Nodelist

**id**
Eindeutige Bezeichnung der Kanten mit jeweils
Spielerinnen: Nachnamen;
Vereine/ Organisationen: Abkürzung mit Anfangsbuchstaben;
Heimatländer: identifizierbaren, passenden Abkürzungen

**name**
vollständiger Name der Spielerinnen, der Vereine/ Organisationen und der Heimatländer

**type**
**0=** Person (Spielerin),
**1=** Verein/ Organisation oder Land

**birth**
(Zusammengefasste Geburtsjahrgruppen)
**1=** 1991-1993,
**2=** 1994-1996,
**3=** 1997-1999,
**4=** 2002-2002,
**5=** 2003-2005

**age**
(Zusammengefasste Altersgruppen)
**1=** über 30,
**2=** 27-30,
**3=** 24-26,
**4=** 21-23,
**5=** unter 20

**country**
(Heimatländer der Spielerinnen)
**1=** Niederlande,
**2=** Bulgarien,
**3=** Deutschland,
**4=** Belgien,
**5=** Polen,
**6=** USA,
**7=** Spanien,
**8=** Finnland

**position**
(Postionen der Spielerinnen auf dem Spielfeld)
**1=** Mittelblock,
**2=** Zuspiel,
**3=** Außenangriff,
**4=** Diagonal,
**5=** Libera
