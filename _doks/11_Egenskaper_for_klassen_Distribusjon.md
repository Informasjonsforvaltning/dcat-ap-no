---
title: Distribusjon
id: 11
layout: default
---

Egenskaper for klassen Distribusjon (anbefalt)

### Distribusjon: tilgangsURL
URI
: dcat:accessURL

Range
: rdfs:Resource

Beskrivelse
: En URL som gir tilgang til en distribusjon av datasettet. Ressursen det pekes til kan gi informasjon om hvordan en kan få tilgang til i datasettet

Kardinalitet
: 1..n

Status	
: Obligatorisk

### Distribusjon: beskrivelse
URI
: dct:description

Range
: rdfs:Literal

Beskrivelse
: Fritekstbeskrivelse av distribusjonen. Kan repeteres for parallelle språkversjoner

Kardinalitet
: 0..n

Status	
: Anbefalt 

### Distribusjon: format
URI
: dct:format

Range
: dct:MediaTypeOrExtent

Beskrivelse
: Referanse til distribusjonens filformat

Kardinalitet
: 0..1

Status	
: Anbefalt

### Distribusjon: lisens
URI
: dct:license

Range
: dct:LicenseDocument

Beskrivelse
: Referanse til lisensen distribusjonen er gjort tilgjengelig under. Bør oppgis som URI, feks [http://data.norge.no/nlod/no/1.0](http://data.norge.no/nlod/no/1.0)

Kardinalitet
: 0..1

Status	
: Anbefalt

### Distribusjon: filstørrelse
URI
: dcat:byteSize

Range
: rdfs:Literal typed as xsd:decimal

Beskrivelse
: Distribusjonens størrelse oppgitt i bytes

Kardinalitet
: 0..1

Status	
: Valgfri

### Distribusjon: nedlastningslenke
URI
: dcat:downloadURL

Range
: rdfs:Resource

Beskrivelse
: Direktelenke (URL) til en nedlastbar fil i et gitt format

Kardinalitet
: 0..n

Status	
: Valgfri

### Distribusjon: mediatype
URI
: dcat:mediaType, subproperty of dct:format

Range
: dct:MediaTypeOrExtent

Beskrivelse
: Referer til distribusjonens medietype dersom denne er definert i IANA

Kardinalitet
: 0..1 

Status	
: Valgfri

### Distribusjon: utgivelsesdato
URI
: dct:issued

Range
: rdfs:Literal typed as xsd:date or xsd:dateTime 

Beskrivelse
: Dato for formell utgivelse/publisering av distribusjonen

Kardinalitet
: 0..1 

Status	
: Valgfri

### Distribusjon: rettigheter
URI
: dct:rights 

Range
: dct:RightsStatement

Beskrivelse
: Viser til en uttalelse som angir rettigheter knyttet til distribusjonen.

Kardinalitet
: 0..1

Status	
: Valgfri

### Distribusjon: status
URI
: adms:status

Range
: skos:Concept

Beskrivelse
: Distribusjonens modenhet (fullført, under utvikling, utgått, trekt tilbake)

Kardinalitet
: 0..1

Status	
: Valgfri


### Distribusjon: tittel
URI
: dct:title

Range
: rdfs:Literal

Beskrivelse
: Navn på distribusjonen

Kardinalitet
: 0..n

Status	
: Valgfri


### Distribusjon: modifiseringsdato
URI
: dct:modified

Range
: rdfs:Literal typed as xsd:date or xsd:dateTime

Beskrivelse
: Dato for siste modifisering av distribusjonen

Kardinalitet
: 0..1

Status	
: Valgfri
