# Handleiding events
Opmaak tips voor events aan te maken op de Heimdal website

## Opmaak

Dit stuk gaat over de opmaak van de beschrijving van het event. Onderstaande voorbeelden kan je gebruiken, deze zijn wel in de stijling van de Heimdal website ipv hoe je ze hier ziet.  

Als je `<>` tegenkomt met text tussen, zoals bvb text, link, etc; Dan moet je dit vervangen met de text die je wilt.  
Zo word `#### <titel>` bijvoorbeeld `#### Doop` 

### Titels 
hoofdtitel  
`#### <titel>`
#### Doop

subtitel  
`##### <Titel>`
##### Doop

### Text

cursief  
`*<text>*`  
*De doop van Heimdal*  

vetgedrukt  
`**<text>**`  
**De doop van Heimdal**  

quotatie  
`> <text>`
> “You shall (hoogstwaarschijnlijk) pass” - someone

### Lijsten
Ongeorderde lijst
```
- <item>
- <item>
- <item>
```
- Locatie
- Datum
- Prijs
- Inschrijving

Geordende lijst
```
1. <item>
2. <item>
3. <item>
```
1. vanillewafels
2. frangipanes
3. zeevruchten

### Links

via html (dankzij de target tag opent de link in een nieuw tabblad)  
`<a href="<link>" target="_blank"><naam link></a>`  
<a href="https://heimdal.be" target="_blank">Heimdal.be</a>  

via markdown (geen mogelijkheid om te openen in een nieuw tabblad)  
`[<naam link>](<link>)`
[Heimdal.be](https://heimdal.be)

#### Afbeeldingen

`![<beschrijving>](<link naar afbeelding>)`  
![Heimdal logo](https://heimdal.be/static/img/Heimdal%20Banner%20black.png)

### Pagina breaks  

Je kan een horizontale lijn toevoegen door `---` op een nieuwe regel te typen.
<br>
---

Om een enter in markdown te doen, moet je 2x op spatie drukken achter de lijn die je geschreven hebt. Als alternatief kan je `<br>` gebruiken indien je dit makkelijker vind.

## Banner's uploaden

Als je banners te groot zijn kan je ze proberen kleiner te maken met [Image Compressor](https://imagecompressor.com/)
