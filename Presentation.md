# IPv4

## Geschichte
(Heze)
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
## Klassen
(Mattias)
----
## Routing
(Jones)

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

----
## Blick in die Zukunft (IPv6)
IPv4 adressen sind restlos aufgebraucht es gibt insgesammt 4 Milliarden ipv4 adressen
den Technischenerfindern schien das 1980 für alle nur denkbaren Bedürfnisse mehr als ausreichend jedoch wurde ihnen anfang der 1990 jahre klar das die Adressen knapp wurden. Lösung hier für ist IPv6 diese bietet mehr als Sextillionen Adressen und ist seit 1998 standartisiert
=======
