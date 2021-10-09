#Dag verslagen
## Maandag 2021-10-04
Rondleiding gekregen in het bedrijf. 
### serverkamer:
Hieronder op de foto's zie de serverkamer die van de twee verdiepen (7 en 8) het internet en vaste telefoons regelt. Deze kamer legt ook de verbinding met de datacenters in het buitenland. Deze kamer wordt volledig gekoeld om de levensduur van de apparaten zo lang mogelijk te maken en ook te voorzien dat deze niet gaan oververhitten. 
De meeste hardware is vervangen door een VM (=Virtual machine) dit doe ze zodat als er iets misloopt dat ze nog altijd terug kunnen gaan naar snapschot of een back-up. Hierdoor hebben ze ook minder hardware waar dan ook weer zou moeten onderhouden worden. 

<img src="https://user-images.githubusercontent.com/77328028/135809640-dd69f3e3-c89e-4baf-aff4-64e69f9a1fc6.jpg" width="250" />  <img src="https://user-images.githubusercontent.com/77328028/135809646-9234d508-d2b7-4cf9-ade3-aa3547f37553.jpg" width="250" />  <img src="https://user-images.githubusercontent.com/77328028/135809651-0f521306-17f1-448d-8917-32bed23ee00e.jpg" width="250" />

### Bedrijfsnetwerk:  
#### Internet:
Werken met één groot bedrijfsnetwerk. Dit gebeurt door een service die proximus aanbiedt genaamd `Explore`.  
> Explore is een MPLS privenetwerk (Multiprotocol Label Switching) dat enkel toegankelijk is voor u en uw medewerkers, in België en in het buitenland. Bovendien is de netwerkverbinding snel, ongeacht het aantal aangesloten toestellen, en biedt het een waaier aan extra diensten zoals QoS (Quality of Service).  

Dit gebruiken ze omdat ze dan tussen al de vestigingen één groot netwerk kunnen behouden. Ze hebben dan ook ineens dan een perfecte verbinding voor de mensen die thuis werken en diegenen die op de laptops werken van op afstand. Dan kunnen ze hier ook verbinding meemaken. 

Ze hebben ook een back-up lijn moest het internet wegvallen dat ze nog op andere manier hun internet toch kunnen behouden. Deze back-up lijn heeft ook zijn eigen serverkamer.

#### Vaste lijn telefoons:
Deze werken allemaal via VOIP (=Voice over IP). Dit is het makkelijkste om te installeren en in gebruik te nemen omdat dit maar één kabel nodige heeft en dat is dan een netwerkkabel met POE (=Power Over Ethernet).

#### Op bouwwerven:
Op bouwwerven nemen ze microservers mee die dan een connectie leggen met de domeinserver op vestiging Antwerpen. Daardoor heeft deze volledige toegang tot het bedrijfsnetwerk waar deze toegang tot krijgen. Dit het makkelijkste mee te nemen om dat het ook maar voor 2-5 mensen is en daarvoor een volledige server mee veel te veel werk om dit volledig geïnstalleerd te krijgen.

<img src="https://tweakers.net/i/Xb2mifnLyeMoRh4bZMb1tZxdl9I=/i/2000899002.png" width="250" />

Gebruikte website: \
[https://www.proximus.be/nl/id_cl_explore/bedrijven-en-overheden/netwerken/bedrijfsnetwerken/explore.html](https://www.proximus.be/nl/id_cl_explore/bedrijven-en-overheden/netwerken/bedrijfsnetwerken/explore.html) \
[https://tweakers.net/pricewatch/463569/hp-proliant-microserver-gen8-g1610t/specificaties/](https://tweakers.net/pricewatch/463569/hp-proliant-microserver-gen8-g1610t/specificaties/) 

## Dinsdag 2021-10-04
- Bespreking gehad over de hele werking van IT op het internationaal vlak. Deze uitleg komt voorin de Casestudie.
- Scott leren kennen: met achter de schermen hun Itms `(Information Technology management service)` een programma voor eigenlijk het volledige support gedeelte ticket management. Ook hebben ze hier een systeem dat de gekoppeld is aan een soort interne webshop. Deze webshop ik gemaakt voor medewerkers bedrijfstelefoons, ... te laten aanschaffen. 

## Woensdag 2021-10-06
- Mezelf nog meer verdiept in de werking van het bedrijfsnetwerk lokaal te Antwerpen. Verder gewerkt aan de casestudie. 

## Donderdag 2021-10-07
- analyse gedaan van hoe de SOM (Self-Oder Mamagement) in het ITSM (IT Service Management) werk.
- analyse gedaan hoe een andere deel van scot werk.

## Vrijdag 2021-10-08
- Afwerking van casestudies
- kleine casestudie verschillen tussen oude en nieuwe dockstations.
- Afsluiting week
