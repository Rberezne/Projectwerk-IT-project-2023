tittel: Projectwerk: IT-project 

Vestigingsplaats

Een vestigingsplaats bestaat uit tenminste één lokaal met een switch en een access-point. Elk lokaal vormt een eigen VLAN waarbij het access-point geen deel uitmaakt van dit VLAN..
Elk access-point vormt een VLAN op zich. Dit vertaalt zich dus in 2 VLAN's per lokaal.De switch van het lokaal kan tot 20 tafels voorzien van een netwerkaansluiting (in een opstelling van één netwerkaansluiting per tafel).
Alle lokalen worden via ethernet (twisted-pair) verbonden met een router.Deze router verzorgt de verbinding met internet. Bovendien beschikt elke vestigingsplaats over een eigen Linux Ubuntu Server met een geïnstalleerde en geconfigureerde Moodle ELO.
De Moodle ELO bevat de lokale cursussen/modules. De gegevens van de studenten worden 's nachts uit de centrale server opgevraagd (via een API) en geïmporteerd in de lokale Ubuntu Server.
Op deze manier is de toegang voor geregistreerde studenten gegarandeerd.
Studenten die uitgeschreven zijn worden verwijderd uit de vestigingsplaats. Vanzelfsprekend worden enkel de studenten van een specifieke vestigingsplaats geïmporteerd, niet alle studenten van de hogeschool.
