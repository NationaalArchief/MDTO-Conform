# MDTO-conform

Er zijn twee niveaus van MDTO-conform. Minimaal MDTO-conform betekent dat de MDTO-metagegevens zijn vastgelegd en beschikbaar zijn. Maar het zegt niks over de vorm waarin deze metagegevens beschikbaar zijn. Volledig MDTO-conform voegt daaraan toe eisen over de vorm waarin de MDTO-metagegevens beschikbaar zijn en geïmporteerd worden.

Het onderscheid tussen twee niveaus biedt de mogelijkheid om bij regels voor het toepassen van MDTO onderscheid te maken. Bijvoorbeeld door een langere termijn toe te staan waarbinnen een informatiesysteem volledig MDTO-conform moet zijn.

Hieronder wordt met ‘een informatiesysteem voor bepaalde informatieobjecten’ bedoeld een specifiek informatiesysteem en daarbinnen nader beschreven informatieobjecten waarvoor ergens aangegeven is dat deze MDTO-conform (moeten) zijn. Zoals bijvoorbeeld in “DMS-X is voor alle daarin beheerde bestanden, mappen en zaakgegevens volledig MDTO-conform”.  

## Minimaal MDTO-conform
Een informatiesysteem is voor bepaalde informatieobjecten ‘minimaal MDTO-conform’ als geldt:

<ol>
<li><strong>MDTO-metagegevens vastgelegd:</strong> Gedurende de gehele levenscyclus worden bij de informatieobjecten de metagegevens vastgelegd die in het MDTO-metagegevensschema verplicht zijn.</li>
<li><strong>Vertaling naar metagegevensschema:</strong> De vastgelegde MDTO-metagegevens kunnen eenduidig en zonder verlies van informatie vertaald worden naar de structuur, betekenis en regels zoals beschreven in het MDTO-metagevensschema (ook wel mapping genoemd).</li> 
<li><strong>Weergave metagegevens:</strong> Er is een functie waarmee alle gebruikers van het informatiesysteem bij de informatieobjecten een weergave van de vastgelegde MDTO-metagegevens kunnen opvragen.</li> 
<li><strong>Export metagegevens:</strong> Er is een functie waarmee alle gebruikers van het informatiesysteem bij de informatieobjecten een export van de vastgelegde MDTO-metagegevens kunnen opvragen, in een automatisch verwerkbaar formaat.</li>
</ol>

## Volledig MDTO-conform

Een informatiesysteem is voor bepaalde informatieobjecten  ‘volledig MDTO-conform’ als het minimaal MDTO-conform is, en de vastgelegde metagegevens op de volgende manieren uitgewisseld kunnen worden: 

<ol>
<li><strong>Weergave metagegevens:</strong> Er is een functie waarmee alle gebruikers van het informatiesysteem bij de informatieobjecten een weergave van de vastgelegde MDTO-metagegevens kunnen opvragen. In deze weergave zijn de metagegevens volgens het metagegevensschema gestructureerd en worden de labels gebruikt zoals aangegeven in het metagegevensschema.</li> 
<li><strong>Export metagegevens:</strong> Er is een functie waarmee alle gebruikers van het informatiesysteem bij de informatieobjecten een export van de vastgelegde MDTO-metagegevens kunnen opvragen, in een een XML-bestand conform het XML-schema van MDTO.</li> 
<li><strong>Import metagegevens:</strong> Als er een importfunctie is voor de metagegevens bij een informatieobject, dan kunnen deze metagegevens in een XML-bestand conform het XML-schema van MDTO geïmporteerd worden. Waarbij de metagegevens zonder verlies van informatie vastgelegd worden.</li> 
<li><strong>Export of import Submission Information Package:</strong> Als er een export- en/of importfunctie is voor SIP’s, dan ondersteunen deze het MDTO SIP-formaat.</li> 
</ol>
Het is toegestaan dat een volledig MDTO-conform informatiesysteem in aanvulling hierop ook op andere manieren metagegevens uitwisselt. Bijvoorbeeld door ook een andere weergavefunctie aan te bieden of bij de export of import van een SIP ook een ander XML-formaat te ondersteunen.

## Verplicht indien bekend
Een klein aantal metagegevens is verplicht binnen MDTO (dit is aangegeven in het metagegevensschema). Deze moeten altijd vastgelegd zijn. Voor de rest van de metagegevens geldt ‘verplicht, indien bekend’. Dat betekent dat deze gegevens vastgelegd moeten zijn als ze bekend zijn binnen de verantwoordelijke organisatie of afgeleid kunnen worden van andere bekende gegevens. Tenzij de verantwoordelijke organisatie hiervoor kosten moet maken die niet in verhouding staan tot het doel van het vastleggen van de metagegevens. 

Met ‘bekend zijn’ wordt bedoeld dat een gegeven al ergens binnen de organisatie bekend is omdat dat voor het uitvoeren van het werk- en beheerproces noodzakelijk is. Bijvoorbeeld het onderwerp of de datum van ontvangst moet vaak bekend zijn om een ontvangen stuk te kunnen verwerken. Met ‘afgeleid worden’ wordt bedoeld dat het gegeven bepaald kan worden door andere bekende gegevens te combineren. Bijvoorbeeld de activiteit waar een document uit voortkomt kan vaak afgeleid worden van het dossier waarin het is opgenomen. 

De conditie ‘indien bekend’ is opgenomen om te voorkomen dat medewerkers metagegevens moeten vastleggen alleen om aan MDTO te voldoen, maar die voor hun werk- of beheerproces niet noodzakelijk zijn. Dit zou een onredelijke administratieve belasting vormen. En leidt bovendien vaak tot een slechte kwaliteit metagegevens. 

## Aanvullende metagegevens
Het is mogelijk om vanuit MDTO-metagegevens te verwijzen naar aanvullende metagegevens die niet binnen het metagegevensschema vallen. Mits deze aanvullende metagegevens gedocumenteerd zijn zoals in het metagegevensschema voorgeschreven. Dit gaat om het attribuut ‘aanvullendeMetagegevens’.

## Aanvullende waarden
Bij een aantal MDTO-metagegevens is het toegestaan om waarden te gebruiken die niet binnen MDTO zijn gespecificeerd (bij de attributen met een zogenaamde vrije of open begrippenlijst). Mits deze aanvullende waarden gedocumenteerd zijn zoals in het metagegevensschema voorgeschreven.

Dit betekent dat een importfunctie er rekening mee moet houden dat er bij deze attributen waarden aangeboden kunnen worden die niet in MDTO zijn gespecificeerd. Ook deze waarden moeten dan vastgelegd worden.
