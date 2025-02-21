# RAID (Redundant Array of Independent Disks)

https://www.enterprisestorageforum.com/management/raid-levels-explained/

## Unterschied Soft- und Hardware RAID

- https://de.wikipedia.org/wiki/RAID#Hardware-RAID
- https://de.wikipedia.org/wiki/RAID#Software-RAID

## gebräuchliche RAID Level

- RAID 0 (Striping)
- RAID 1 (Mirroring)
- RAID 5 (Parity)
- RAID 6 (Double Parity)

## JBOD (Just a Bunch of Disks)

- https://de.wikipedia.org/wiki/RAID#JBOD
- 
**1. Unterschied zwischen Software- und Hardware-RAID**

**Hardware-RAID** 

-Wird durch einen dedizierten RAID-Controller realisiert. 

-Entlastet die CPU, da die Berechnungen von einem eigenen Prozessor auf dem Controller übernommen werden. 

-Bietet oft zusätzliche Funktionen wie Hot-Swap und Batterie-gestützten Cache. 

-Teurer als Software-RAID. 

**Software-RAID**

-Wird durch das Betriebssystem verwaltet. 

-Kostengünstig, da keine zusätzliche Hardware benötigt wird. 

-Belastet die CPU, da die Berechnungen vom Hauptprozessor durchgeführt werden. 

-Flexibler, da es unabhängig von der Hardware verwendet werden kann. 

## 2. Gebräuchliche RAID-Level 

**RAID 0 (Striping)** 

-Daten werden auf mehrere Festplatten verteilt (Stripe-Set), wodurch die Schreib- und Lesegeschwindigkeit steigt. 

-Keine Redundanz: Wenn eine Festplatte ausfällt, sind alle Daten verloren. 

-Anwendung: Performance-kritische Umgebungen, z. B. Videobearbeitung. 

**RAID 1 (Mirroring)** 

-Alle Daten werden 1:1 auf zwei oder mehr Festplatten gespiegelt. 

-Hohe Ausfallsicherheit, da eine defekte Festplatte ersetzt werden kann, ohne Datenverlust. 

-Kostenintensiv, da nur 50 % der Speicherkapazität genutzt werden können. 

-Anwendung: Systeme mit hoher Datensicherheit, z. B. Server oder Backup-Systeme. 

**RAID 5 (Parity-Verfahren)** 

-Mindestens drei Festplatten erforderlich. 

-Daten und Paritätsinformationen werden verteilt gespeichert. 

-Eine Festplatte kann ausfallen, ohne Datenverlust. 

-Gute Kombination aus Performance, Speichereffizienz und Ausfallsicherheit. 

-Anwendung: Datenbanken und Server mit mittlerem Sicherheitsbedarf. 

**RAID 6 (Double Parity)**

-Ähnlich wie RAID 5, aber mit zwei Paritätsblöcken. 

-Kann zwei gleichzeitige Festplattenausfälle überstehen. 

-Erfordert mindestens vier Festplatten. 

-Anwendung: Unternehmensserver mit hohen Sicherheitsanforderungen. 

**JBOD (Just a Bunch of Disks)** 

-Keine RAID-Funktionalität, sondern eine einfache Aneinanderreihung von Festplatten. 

-Jede Festplatte wird als eigenes Laufwerk angezeigt oder als ein großes Volume kombiniert. 

-Keine Redundanz oder Performance-Verbesserung. 

-Anwendung: Speichererweiterung ohne Redundanzbedarf. 

## Fazit 

Die Wahl des richtigen RAID-Levels hängt von den individuellen Anforderungen an Performance, Datensicherheit und Kosten ab. RAID 0 bietet hohe Geschwindigkeit, aber keine Redundanz. RAID 1, 5 und 6 kombinieren unterschiedliche Grade an Sicherheit und Effizienz. JBOD ist eine einfache Alternative, wenn keine Redundanz benötigt wird. 

 
![image](https://github.com/user-attachments/assets/a0b2c7ff-28fe-427d-b429-1fee78b6b41c)




