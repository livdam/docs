---
section: Hjälptexter katalogisering
title: Relationer till agenter, delar och verk
order: 34
date: 2018-09-28
tags:
- editor
- under arbete
---

## Relationer till agenter, delar och verk 
(7XX)

700, 710 och 711 är komplicerade fält i MARC21 som kan uttrycka olika saker om en agent, medverkande, relationer, och att en instans innehåller flera verk. Den här hjälpen visar hur man skapar olika typer av relationer. 

Länka i första hand till befintliga auktioriteter för personer, organisationer och möten. Om det inte finns en auktoritet så kan du skapa en auktoritet. Se hjälptexterna för att [Skapa ny agent Person](https://libris.kb.se/katalogisering/help/workflow-agent-person-new) samt för [Organisation](https://libris.kb.se/katalogisering/help/workflow-agent-organisation-new). Det finns även hjälp för att redigera befintliga auktoriteter. Se även hjälp för att [Lägga till Agent - Organisation](https://libris.kb.se/katalogisering/help/workflow-agent-org-instance)

*I de första versionerna av nya Libris bör man inte länka till eller skapa nya verk, det är under utveckling.*


[Relation uttryckt som Funktion](#relation-uttryckt-som-funktion)

[Relation till verk uttryckt genom text](#relation-till-verk-uttryckt-genom-text)

[Obestämd relation till verk](#obestämd-relation-till-verk)

[Samlingsverk](#Samlingsverk)


## Relationer

#### Relation uttryckt som Funktion 
Utgå ifrån Instans av Verk / Medverkande och funktion / Medverkan

Välj Medverkan när en agent har en relation till det verk som beskrivs i instansen.
* Medverkan och funktion / Medverkan / Agent / Person (700 1/- ‡a)
  Länka till entitet.

  I undantagsfall, skapa lokal entitet och välj Person
   * Lägg till Efternamn
   <br/>```Exempel: Andersson```
  
   * Förnamn
   <br/>```Exempel: Frans```
   
   * Levnadsår (700 ‡d)
    <br/>```Exempel: 1974-```

  * Funktion - klicka på plustecknet intill Funktion (700 ‡4)
    Länka till entitet.
    <br/>```Exempel: relator/trl (= översättare)```
    

#### Relation till verk uttryckt genom text 
Det finns fasta termer i RDA för att uttrycka en relation till ett verk och som motsvarar delfält i i Exportformatet. Det är ännu inte möjligt att länka till dessa i nya Libris. Svensk översättning för relationerna behöver gås igenom.

Relation till ett verk av en författare (700 1/_ ‡i a  ‡d ǂt)
* Välj Relation (Relationship) vid plustecknet vid Verksdelen
* Välj typ Relation (Relationship) i sidopanelen
* Välj Relation (Relation) vid plustecknet vid Relation (Relationship)

Lägg till Entitet / Skapa lokalt / Verk / Benämning
*  Benämning
  <br/>```Exempel: Parafraserar```
  
 *  Har titel/ Titel / Huvudtitel
  <br/>```Exempel: Pride and prejudice```
 
Välj Primär medverkan när en agent har en relation till verk som beskrivs som relaterat.
* Medverkan och funktion / Primär medverkan / Agent/ Person (700 1/_ ‡a  ǂd )
  Länka i första hand till en agent.
    <br/>```Exempel: Austin,  Jane, 1775-1817```
 

#### Obestämd relation till verk 
Om relationen är viktig att beskriva och inte kan beskrivas på annat sätt, gör en allmän anmärkning (500 ‡a)

* Anmärkning (hasNote) br/>```Exempel:Bygger på förf:s diss. med titeln: En sund själ i en sund kropp : hälsopolitik i Stockholms folkskolor 1880-1930```

* Välj Relation vid plustecknet  vid Verk
* Välj typ Relation i menyn
* Välj Entitet vid plustecknet vid Relation

Lägg till Entitet / Skapa lokalt / Verk 
*  Har titel/ Titel / Huvudtitel
  <br/>```Exempel: En sund själ i en sund kropp```
 
Välj Primär medverkan när en agent har en relation till verk som beskrivs som relaterat.
* Medverkan och funktion / Primär medverkan / Agent/ Person (700 1/_ ‡a ǂd )
   
 Länka i första hand till auktoritet.
   <br/>```Exempel: Hammarberg, Lena, 1943-```
 

#### Samlingsverk
Medverkan och funktion / Har del / Primär medverkan (700 1/2 ‡a ǂd ǂt )

Välj Primär medverkan när agenten har relation till ett annat verk än det som beskrivs i instansen

  * Har del / skapa lokal entitet - sök upp och välj Verk
    * Har titel / Titel / Huvudtitel 
  Skriv in titeln ```Exempel:  Mind over matter```

  Lägg därefter till Agenten:
    * Medverkan och medverkan / Primär medverkan / Agent/ Person
  Länka i första hand till agent. För att lägga till som lokal entitet:
  
  * Medverkan och funktion / Primär medverkan / Agent / Person / Efternamn
    <br/>```Exempel: Roberts```

  * Medverkan och funktion / Primär medverkan / Agent/ Förnamn
    <br/>```Exempel: Nora```
    
    
    ####  Fler delfält
  Fler delfält att lägga till vid plustecknet för Titeln som rör titeln:
  * Specificering i form av grupptitel (700 ‡k)
  * Delbeteckning (700 ‡n)
  * Deltitel (700 ‡p)
  
  Fler delfält att lägga till vid plustecknet för Verk som rör titeln:
  * Tid för verket (700 ‡f)
  * Språk  / Benämning (700 ‡l)
  * Besättning för framförande (700 ‡m) *Under utveckling*
  * Version (700 ‡o)
  * Tonart (700 ‡r)
  * (700 ‡s) *Under utveckling*
  
