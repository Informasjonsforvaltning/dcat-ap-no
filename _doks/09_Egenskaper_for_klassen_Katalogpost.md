---
title: Katalogpost
id: 09
layout: default
---

Egenskaper for klassen Katalogpost
 
### Katalogpost: primærtema
URI
: foaf:primaryTopic

Range
: dcat:Dataset

Beskrivelse
: Denne egenskapen lenker katalogposten til datasettet som er beskrevet i katalogposten 

Kardinalitet
: 1..1 

Status	
: Obligatorisk 

### Katalogpost: modifiseringsdato
URI
: dct:modified 

Range
: rdfs:Literal typed as xsd:date or xsd:dateTime

Beskrivelse
: Denne egenskapen inneholder den nyeste datoen for når katalogposten ble endret eller modifisert.

Kardinalitet
: 1..1

Status	
: Obligatorisk 

### Katalogpost: utlistingsdato
URI
: dct:issued

Range
: rdfs:Literal typed as xsd:date or xsd:dateTime

Beskrivelse
: Datoen for når beskrivelsen av datasett ble inkludert i datakatalogen. 

Kardinalitet
: 0..1 

Status	
: Anbefalt 
  
### Katalogpost: endringstype
URI
: adms:status 

Range
: skos:Concept 

Beskrivelse
: Type endring for siste revisjon av en datasettbeskrivelse i katalogen. MÅ ha en av verdiene :created, :updated eller :deleted avhengig av om denne siste revisjonen er et resultat av en ny post, oppdatering eller sletting.

Kardinalitet
: 0..1 

Status	
: Anbefalt 

### Katalogpost: beskrivelse
URI
: dct:description

Range
: rdfs:Literal

Beskrivelse
: Inneholder en fritekstbeskrivelse av katalogposten. Denne egenskapen kan gjentas for parallelle språkversjoner av beskrivelsen.

Kardinalitet
: 0..n 

Status	
: Valgfri 

### Katalogpost: tittel
URI
: dct:title 

Range
: rdfs:Literal 

Beskrivelse
: Navnet på katalogen. Denne egenskapen kan gjentas for parallelle språkversjoner av navnet. 

Kardinalitet
: 0..n

Status	
: Valgfri
