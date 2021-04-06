# Schutzziele

https://www.kryptowissen.de/schutzziele.php

# CIA Triade

## C = Confidentiality = Vertraulichkeit

Eine gewisse Information darf nur den Berechtigten zugänglich sein oder durch diese anderen zur Ansicht verfügbar gemacht werden. 

Unterkategorieren können sein:
* Unverkettbarkeit (unlinkability)
* Unbeobachtbarkeit (unobservability)
* Nicht-Verfolgbarkeit (untraceability)

##### Angriffsarten
* Spyware
* Advanced Persistant Threads (APT)
* Spionage
* Social Engineering
* Phishing

##### Schutzmaßnahmen
* Sensibilisierung der Mitarbeiter
* Mailgateways um Phishing Mails / Mails mit schädlichem Inhalt / Anhängen noch vor der Zustellung zum Mailserver blockieren zu können
* Zugangskontrolle
* Verschlüsselung der Daten

## I = Integrity = Integrität

Es wird unterschieden zwischen Integrität der Daten (es ist entweder sichergestellt, dass keine Änderung der Daten durchgeführt werden kann *starke Integrität* oder eine Änderung nicht unbemerkt stattfinden kann (*schwache Integrität*] ) bzw. Integrität der Systeme mit denen Daten verarbeitet werden.

##### Angriffsarten
* Man in the Middle Angriffe
* Einbruch / Platzieren von Malware
* Drive-by-Exploits
* Schadsoftware

##### Schutzmaßnahmen
* Zutrittskontrolle
* Prüfsummen / Hash-Werte der Daten
* (digitales) Signieren der Daten

## A = Availability = Verfügbarkeit

Das Schutzziel der Verfügbarkeit kann ebenfalls in Verfügbarkeit der Daten bzw. Verfügbarkeit der Systeme um auf die Daten zuzugreifen unterteilt werden. Meist versuchen Angreifer über Denial of Service Angriffe (oder sogar Distributed Denial of Service Angriffe

##### Angriffsarten
* Ransomware (Verschlüsselungstrojaner)
* Sabotage
* Schadsoftware
* Denial of Service oder Distributed Denial of Serivce Angriffe

##### Schutzmaßnahmen
* Datensicherungen
* Next Generation Anti-Malware Lösungen
* Lastverteilung / Private Cloud
* Stand-by Systeme
* Reverse Proxy mit Verhaltenserkennung
* Systemhärtung
