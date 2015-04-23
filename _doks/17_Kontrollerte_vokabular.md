---
title: Kontrollerte vokabular
id: 17
layout: default
---

## Krav til kontrollerte vokabular

Følgende er en liste over krav som er identifisert for kontrollerte vokabular som er anbefalt av den underliggende applikasjonsprofilen DCAT-AP. 

Kontrollerte vokabular bør: 

* være publisert under en åpen lisens. 

* brukes og / eller bli vedlikeholdt av en institusjon i Norge eller EU, av anerkjent standardiseringsorganisasjon eller en annen pålitelig organisasjon.

* være skikkelig dokumentert. 

* ha etiketter på flere språk 

* inneholde et relativt lite antall begrep (f.eks 10-25) som er generelle nok til at et bredt spekter av ressurser kan klassifiseres.

* har vilkår som er identifisert av URIer der hver URI viser til dokumentasjon av begrepet.

* har en varighets- og versjonspolicy. 

Disse kriteriene er ikke tenkt å definere et sett med krav til kontrollerte ordforråd generelt; de er kun ment brukt for utvelgelse av de kontrollerte vokabularene som er anbefalt for denne standarden

## Kontrollerte vokabular som skal brukes

Nedenfor er en rekke egenskaper oppført med kontrollerte vokabular som må brukes for de nevnte egenskapene.


### dcat:mediaType

Brukt i klasse
: Distribusjon

Navn på vokabular
: MDR File types Name Authority List

URI for vokabularet
: http://publications.europa.eu/mdr/authority/file-type/


### dcat:theme
Brukt i klasse
: Datasett
Navn på vokabular
: EuroVoc domains
URI for vokabularet
: http://eurovoc.europa.eu/


### dcat:themeTaxonomy

Brukt i klasse
: Katalog
Navn på vokabular
: EuroVoc
URI for vokabularet
: http://eurovoc.europa.eu/ 


### dct:accrualPeriodicity

Brukt i klasse
: Datasett

Navn på vokabular
: Dublin Core Collection Description Frequency Vocabulary

URI for vokabularet
: http://purl.org/cld/freq/ 


### dct:format

Brukt i klasse
: Distribusjon

Navn på vokabular
: MDR File Type Named Authority List

URI for vokabularet
: http://publications.europa.eu/mdr/authority/file-type/


### dct:language

Brukt i klasse
: Katalog, Datasett

Navn på vokabular
: MDR Languages Named Authority List

URI for vokabularet
: http://publications.europa.eu/mdr/authority/language/ 


### dct:publisher

Brukt i klasse
: Katalog, Datasett

Navn på vokabular
: MDR Corporate bodies Named Authority List

URI for vokabularet
: http://publications.europa.eu/mdr/authority/corporate-body/

Beskrivelse
: Skal brukes for europeiske institusjoner og et lite sett med internasjonale organisasjoner. Ved andre typer organisasjoner, bør nasjonale, regionale eller lokale vokabular brukes.


### dct:spatial

Brukt i klasse
: Katalog, Datasett

Navn på vokabular
: MDR Countries Named Authority List, MDR Places Named Authority List

URI for vokabularet
: http://publications.europa.eu/mdr/authority/country/, http://publications.europa.eu/mdr/authority/place/ 

Beskrivelse
: Vokabularet for land skal brukes hvis dekningsområde er et spesielt land. Vokabularet for steder skal brukes hvis dekningsområde er en del av et land.


### adms:status

Brukt i klasse
: Katalogpost

Navn på vokabular
: ADMS change type vocabulary

URI for vokabularet
: http://purl.org/adms/changetype/

Beskrivelse
: :created, :updated, :deleted


### adms:status

Brukt i klasse
: Distribusjon

Navn på vokabular
: ADMS status vocabulary

URI for vokabularet
: http://purl.org/adms/status/

Beskrivelse
: Listen over begrep i ADMS status-vokabularet er inkludert i ADMS-spesifikasjonen 


### dct:type

Brukt i klasse
: Enhet (agent) 

Navn på vokabular
: ADMS publisher type vocabulary

URI for vokabularet
: http://purl.org/adms/publishertype/Company 

Beskrivelse
: Listen over begrep i ADMS-vokabularet for utgivertype er inkludert i ADMS-spesifikasjonen


### dct:type 

Brukt i klasse
: Lisensdokument

Navn på vokabular
: ADMS licence type vocabulary

URI for vokabularet
: http://purl.org/adms/licencetype/ 

Beskrivelse
: Listen over begrep i ADMS-vokabularet for lisenstype er inkludert i ADMS spesifikasjonen


I tillegg til de foreslåtte felles vokabularene ovenfor, kan ytterligere domenespesifikke vokabular brukes. Selv om de ikke blir akseptert av generelle implementeringer av standarden, kan de bidra til å øke interoperabilitet på tvers av applikasjoner innenfor samme domene. Eksempler her er komplett sett med begreper i EuroVoc, CERIFs standardvokabular, Deweys desimalklassifikasjon og en rekke andre vokabular.