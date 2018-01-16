# IPv4

## Geschichte



Die IPv4-Spezifikation, die vor rund dreißig Jahren eingeführt wurde, bietet einen Adressraum von etwa 4,3 Milliarden IP-Adressen, genauer gesagt von 2³², das sind 4.294.967.296 Adressen. Zur damaligen Zeit schien das für alle Beteiligten mehr als genug. Man konnte sich einfach nicht vorstellen, dass jemals all diese Adressen genutzt werden. Wer konnte aber auch zu dieser Zeit mit so einem ernormen Wachstum rechnen?

Hinzu kam, dass man am Anfang relativ schludrig mit der Vergabe der IP-Adressen umging. Ob man nun „ein paar“ Adressen unnötigerweise vergab, spielte keine Rolle, es war ja noch genügend übrig. So wurden die ersten Netze, in Class-A eingeteilt. Ein Class-A (Klasse A) Netz hat einen hohen Hostanteil, insgesamt rund 16,8 Millionen Adressen, aber einen kleinen Netzteil. Eins dieser sogenannten Class-A-Netze, bekam z.B. die University of California in Berkley zugesprochen. Klar, es ist unbestritten, dass so eine Universität einige Adresse benötigt, 16,8 Millionen wird aber nicht die größte Universität auf Erden verbrauchen. Dieser Unternehmen und Institute, die so eine große Anzahl an IP-Adressen bekamen, haben sie bis heute noch, ohne sie jemals voll ausnutzen zu können. So verfallen unnötigerweise unzählige Adressen.
----

## Adressierung

IPv4 Adresse besteht aus 8 Byte bzw 32 Bits.
Die IPv4 Adresse ist in 4 Teile unterteilt.
Diese Teile heissen Oktetten.
Die maximale Adressenzahl ist etwas mehr als 4 Milliarden.
IPv4 Adresse in einem privaten Netwerk sind nicht fest, wie eine MAC-Adresse.
Bei öffentlichen Netzen schon.
![IPv4](https://blog.keycdn.com/blog/wp-content/uploads/2016/07/ipv4-address.png "IPv4")
----
## Klassen (Mattias)
Zur IPv4 Adresse gehört auch die Subnetzmaske dazu. Diese gibt uns Auskunft,
welche Teile zum Netzwerk und welche zum Host gehören. Es gibt verschiedene
Klassen, ich werde etwas zu A,B und C Klasse sagen.
![Klassen](http://elektroniktutor.de/internet/net_pict/ipnum1.png "Klassen")
----

## Routing

Bei IPv4 wird nicht zwischen Hosts und Router unterschieden. Jedes Gerät kann sowohl Endgerät als auch Vermittlungsgerät sein.
IPv4 ist für LANs als Local Area Networks und WANs sprich Wide Area Networks gleichermassen geeignet.
Bei der Übertragung, kann ein Paket verschiedene Netzwerke durchlaufen. Anhand von individuellen Routingtabellen, wird der Netzwerkteil einem
Zielnetzwerk zugeordnet. Die Einträge können statisch oder dynamisch sein. Jedes Paket kann einzeln "geroutet" werden,
das erhöt die Ausfallsicherheit. Jedoch können daher einzelne Pakete verloren gehen oder verschiedene
Wege nehmen. Die Pakete können auch doppelt, und sogar fragmentiert beim Empfänger angkommen.
Wenn TCP eingesetzt wird, wird neben dem Aufheben der Längenbschränkung auch der Paketverlust
durch Wiederholung korrigiert, doppelte Pakete werden erkannt und verworfen.
Daher stellt die Kombination von TCP und IP eine zuverlässige, bidirektionale Verbindung dar.

=======
=======

![Anzahl](http://netzwerkassistent.de/upload/bilder/lernmodule/11-3_2.jpg)
----
## Blick in die Zukunft (IPv6)
IPv4 adressen sind restlos aufgebraucht es gibt insgesammt 4 Milliarden ipv4 adressen
den Technischenerfindern schien das 1980 für alle nur denkbaren Bedürfnisse mehr als ausreichend jedoch wurde ihnen anfang der 1990 jahre klar das die Adressen knapp wurden. Lösung hier für ist IPv6 diese bietet mehr als Sextillionen Adressen und ist seit 1998 standartisiert
=======
=======