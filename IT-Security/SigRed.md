# CVE-2020-1350 - SigRed

SIGRed (CVE-2020-1350) ist kritische Schwachstelle im Windows DNS server welche alle Windows Server Versionen ab 2003 bis 2019 betrifft. Sie kann durch eine schädliche DNS-Antwort ausgelöst werden und aufgrund der Tatsache, dass der DNS Dienst mit erhöhten Rechten ausgeführt wird (SYSTEM-Rechten), dass ein Angreifer sich Domänen-Administratorrechte aneignen kann, was letztendlich zur Kompromitierung der gesamten Unternehmens-Infrastruktur führt.

## Offizieller Blog von Checkpoint zu Hintergründen und der Entdeckung der Lücke (englisch)

https://research.checkpoint.com/2020/resolving-your-way-into-domain-admin-exploiting-a-17-year-old-bug-in-windows-dns-servers/

## Microsoft CVE-2020-1350 | Windows DNS Server Remote Code Execution Vulnerability - Security Patch und Workaround (englisch)

https://portal.msrc.microsoft.com/en-US/security-guidance/advisory/CVE-2020-1350 

## Timeline
* 24 April 2003 - das älteste, von der Schwachstelle betroffene Betriebssystem (Windows Server 2003) wird von Microsoft veröffentlicht
* 17 Jahre bleibt die Schwachstelle offenbar unentdeckt bzw. konnte ausgenutzt werden
* 19 Mai 2020 – Initiale Meldung des Schwachstellenfund durch Checkpoint an Microsoft
* 18 Juni 2020 – Microsoft vergibt CVE-2020-1350 für diese Schwachstelle
* 09 Juli 2020 – Microsoft bestätigt die Entdeckung als wurmfähige (wormable), kritische Schwachstelle mit einem CVSS score von 10.0
* 14 Juli 2020 – Microsoft veröffentlicht einen Fix zum "Patch Tuesday"
