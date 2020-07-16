# CVE-2020-1350 - SigRed

SIGRed (CVE-2020-1350) ist kritische Schwachstelle im Windows DNS server welche alle Windows Server Versionen ab 2003 bis 2019 betrifft. Sie kann durch eine schädliche DNS-Antwort ausgelöst werden und aufgrund der Tatsache, dass der DNS Dienst mit erhöhten Rechten ausgeführt wird (SYSTEM-Rechten), dass ein Angreifer sich Domänen-Administratorrechte aneignen kann, was letztendlich zur Kompromitierung der gesamten Unternehmens-Infrastruktur führt.

## Offizieller Blog von Checkpoint zu Hintergründen und der Entdeckung der Lücke (englisch)

https://research.checkpoint.com/2020/resolving-your-way-into-domain-admin-exploiting-a-17-year-old-bug-in-windows-dns-servers/

## Microsoft CVE-2020-1350 | Windows DNS Server Remote Code Execution Vulnerability - Security Patch und Workaround (englisch)

https://portal.msrc.microsoft.com/en-US/security-guidance/advisory/CVE-2020-1350 

## Disclosure Timeline
* 19 May 2020 – Initial report to Microsoft.
* 18 Jun 2020 – Microsoft issued CVE-2020-1350 to this vulnerability.
* 09 Jul 2020 – Microsoft acknowledged this issue as a wormable, critical vulnerability with a CVSS score of 10.0.
* 14 Jul 2020 – Microsoft released a fix (Patch Tuesday).
