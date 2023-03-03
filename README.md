# ICT-Architecture-GroepsOpdracht

## Opdracht

<details>
<summary>Casus</summary>

ACME corp heeft een Proof of Concept (PoC) module laten ontwikkelen voor het
hosten van afbeeldingen en videomateriaal. Gebruikers kunnen afbeeldingen en
video’s uploaden, bestaande items bekijken en items verwijderen. De module is
ontwikkeld als monolitische webapplicatie, met een front-end voor het uploaden
van afbeeldingen.
>>
ACME heeft plannen om deze module te gebruiken in haar websites en applicaties.
We spreken over een twintig-tal websites en applicaties. In totaal spreken we over
een databank van 2 miljoen afbeeldingen van ongeveer 5MB per stuk (volledige
resolutie) en 100.000 video’s van ong 500 MB per stuk (niet gecomprimeerd). Er
worden ongeveer duizend afbeeldingen en 100 video’s per dag toegevoegd. Er
worden naar schatting 1 miljoen afbeeldingen opgevraagd, veelal dezelfde
afbeeldingen. Deze afbeeldingen worden gecomprimeerd opgevraagd, dit komt
gemiddeld op 500kB per stuk. Verder worden er ongeveer 10.000 video’s
afgespeeld. Ook hier worden ze gecodeerd opgevraagd zodat de bestandsgrootte
ongeveer een tiende is van het origineel. Opladen en downloaden/afspelen
gebeurt voornamelijk tijdens de bedrijfsuren, van 9u tot 17u. 
>>
De IT directeur is bang dat de applicatie in productie onder belasting kan falen en
wil er zeker van zijn dat ze klaar is voor de productie werklast.

</details>

<details>
<summary>Vereisten</summary>

* De oplossing moet kost efficiënt zijn.
* De oplossing moet schaalbaar zijn op twee vlakken:
  + toevoegen van nieuwe content
  + het uitlezen van bestaande content (afbeeldingen inbedden in
bestaande applicaties, doorlinken naar video’s)
* Uitbreidbare workflow
* Piekbelasting
* High availability: alle onderdelen (compute, storage, database, … )
moeten highly available opgezet worden.
* AWS moet als cloudpartner gebruikt worden
* Testplan voor performance testing
* Onder de uitbreidbare workflow verstaan we dat de de module
functioneel moet kunnen uitgebreid worden met bijkomende
* Functionaliteiten:
  + Afbeeldingen herschalen
  + Video’s hercoderen
  + Content moderation: ongepaste afbeeldingen labelen
  
</details>

<details>
<summary>Deadline</summary>

Zondag 21 mei 23:55

</details>

## Opvolging

<details>
<summary>3 Maart</summary>

Inleiding git + Casus
>>
Opstellen README file

</details>
