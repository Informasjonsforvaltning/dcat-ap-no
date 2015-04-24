---
title: Datakatalog
id: 08
layout: default
---

Egenskaper for klassen Datakatalog:

### Datakatalog: datasett
URI
: dcat:dataset

Range
: dcat:Dataset

Beskrivelse
: Kobler katalogen til datasett som er en del av katalogen

Kardinalitet
: 1..n

Status	
:  Obligatorisk 
    
### Datakatalog: beskrivelse
URI
: dct:description

Range
: rdfs:Literal

Beskrivelse
: Fritekst-beskrivelse av innholdet i katalogen. Egenskapen kan bli gjentatt for parallelle språkversjoner av beskrivelsen.

Kardinalitet
: 1..n

Status	
: Obligatorisk
 
### Datakatalog: utgiver
URI
: dct:publisher

Range
: foaf:Agent

Beskrivelse
: Referer til en enhet (organisasjon) som er ansvarlig for å gjøre katalogen tilgjengelig. Bør være autoritativ URI for enhet, sekundært organisasjonsnummer.

Kardinalitet
: 1..1

Status	
: Obligatorisk

### Datakatalog: tittel
URI
: dct:title

Range
: rdfs:Literal

Beskrivelse
: Inneholder navnet på katalogen. Egenskapen kan bli gjentatt for parallelle språkversjoner av navnet.

Kardinalitet
: 1..n

Status	
: Obligatorisk  

### Datakatalog: hjemmeside

URI
: foaf:homepage

Range
: foaf:Document

Beskrivelse
: Nettside som fungerer som hovedside for katalogen

Kardinalitet
: 0..1

Status	
: Anbefalt

### Datakatalog: språk 
URI
: dct:language

Range
: dct:LinguisticSystem

Beskrivelse
: Viser til et språk som brukes i tekstlige metadata som beskriver titler, beskrivelser, osv av datasettene i katalogen. Egenskapen kan gjentas hvis metadata er gitt i flere språk.

Kardinalitet
: 0..n

Status	
: Anbefalt

### Datakatalog: lisens
URI
: dct:license

Range
: dct:LicenseDocument

Beskrivelse
: Viser til lisens for datakatalogen som beskriver hvordan den kan viderebrukes.

Kardinalitet
: 0..1

Status	
: Anbefalt

### Datakatalog: utgivelsesdato
URI
: dct:issued

Range
: rdfs:Literal typed as xsd:date or xsd:dateTime

Beskrivelse
: Dato for formell utgivelse (publisering) av katalogen.

Kardinalitet
: 0..1

Status	
: Anbefalt

### Datakatalog: temaer
URI
: dcat:themeTaxonomy

Range
: skos:ConceptScheme

Beskrivelse
: Referer til et kunnskapsorganiseringssystem (KOS) som er brukt for å klassifisere katalogens datasett

Kardinalitet
: 0..n

Status	
: Anbefalt   
	
### Datakatalog: modifiseringsdato

URI
: dct:modified

Range
: rdfs:Literal typed as xsd:date or xsd:dateTime

Beskrivelse
: Dato for siste oppdatering/endring av katalogen

Kardinalitet
: 0..1

Status	
: Anbefalt

### Datakatalog: katalogpost
URI
: dcat:record

Range
: dcat:CatalogRecord

Beskrivelse
: Referer til en katalogpost som er del av katalogen

Kardinalitet
: 0..n

Status	
: Valgfri

### Datakatalog: rettigheter
URI
: dct:rights

Range
: dct:RightsStatement

Beskrivelse
: Uttalelse som spesifiserer rettigheter knyttet til katalogen

Kardinalitet
: 0..1

Status	
: Valgfri

### Datakatalog: dekningsområde
URI
: dct:spatial

Range
: dct:Location

Beskrivelse
: Referanse til et geografisk område som er dekket av katalogen

Kardinalitet
: 0..n

Status	
: Valgfri
