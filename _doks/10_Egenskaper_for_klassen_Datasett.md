---
title: Datasett {#Datasett}
id: 10
layout: default
---

Egenskaper for klassen Datasett

### Datasett: beskrivelse
URI
: dct:description 

Range
: rdfs:Literal

Beskrivelse
: Inneholder fritekstbeskrivelse av datasettet. Kan gjentas for parallelle språkversjoner

Kardinalitet
: 1..n 

Status
: Obligatorisk 

### Datasett - tittel
URI
: dct:title 

Range
: rdfs:Literal

Beskrivelse
: Inneholder navnet på datasettet. Kan gjentas for parallelle språkversjoner av navnet

Kardinalitet
: 1..n

Status
: Obligatorisk

### Datasett - kontaktpunkt
URI
: adms:contactPoint

Range
: v:Vcard

Beskrivelse
: Inneholder kontaktinformasjon som kan brukes for å melde om feil i datasettet eller sende kommentarer

Kardinalitet
: 1..n

Status
: Anbefalt

### Datasett - datasett distribusjon
URI
: dcat:distribution

Range
: dcat:Distribution

Beskrivelse
: Koblingen mellom datasettet og en tilgjengelig distribusjon

Kardinalitet
: 0..n

Status
: Anbefalt

### Datasett - emneord
URI
: dcat:keyword 

Range
: rdfs:Literal 

Beskrivelse
: Inneholder emneord (eller tag) som beskriver datasettet

Kardinalitet
: 0..n

Status
: Anbefalt

### Datasett - utgiver
URI
: dct:publisher 

Range
: foaf:Agent

Beskrivelse
: Refererer til en enhet (organisasjon) som er ansvarlig for å gjøre datasettet tilgjengelig. Bør være autoritativ URI for enhet, sekundært organisasjonsnummer.

Kardinalitet
: 1..n

Status
: Anbefalt 

### Datasett - tema
URI
: dcat:theme, subproperty of dct:subject 

Range
: skos:Concept

Beskrivelse
: Referanse til en tema/kategori for datasettet. Et datasett kan assosieres med flere tema

Kardinalitet
: 1..n

Status
: Anbefalt

### Datasett - tilgangsnivå
URI
: pod:accessLevel 

Range
: rdfs:Literal 

Beskrivelse
: Dette feltet angir i hvilken grad datasettet kan bli gjort tilgjengelig for allmennheten, uten hensyn til om det er publisert eller ikke. Obligatoriske verdier : «offentlig», «begrenset offentlighet», «unntatt offentlighet». Ved bruk av verdiene «begrenset offentlighet» og «unntatt offentlighet» er egenskapen «skjermingshjemmel» anbefalt 

Kardinalitet
: 1..n

Status
: Anbefalt 

### Datasett - skjermingshjemmel
URI
: dct:accessRights

Range
: dct:RightsStatement

Beskrivelse
: Henvisning til hjemmel (kilde for påstand) i offentlighetsloven, sikkerhetsloven, beskyttelsesinstruksen eller annet loverk som ligger til grunn for vurdering av tilgangsnivå. Egenskapen er anbefalt dersom «tilgangsnivå» har verdiene «begrenset offentlighet» eller «unntatt offentlighet»

Kardinalitet
: 0..n 

Status
: Anbefalt 

### Datasett - i samsvar med
URI
: dct:conformsTo 

Range
: dct:Standard 

Beskrivelse
: Referer til en implementasjons-regel eller annen spesifikasjon, for eksempel lovhjemmel som ligger til grunn for opprettelsen av datasettet

Kardinalitet
: 0..n

Status
: Valgfri

### Datasett - frekvens
URI
: dct:accrualPeriodicity

Range
: dct:Frequency

Beskrivelse
: Referer til oppdateringsfrekvensen for datasettet

Kardinalitet
: 0..1

Status
: Valgfri

### Datasett - identifikator
URI
: dct:identifier

Range
: rdfs:Literal

Beskrivelse
: Hovedindentifikator for datasettet, feks URIen eller annen identifikator som er unik i kontekst av katalogen

Kardinalitet
: 0..n

Status
: Valgfri

### Datasett - landingsside
URI
: dcat:landingPage

Range
: foaf:Document

Beskrivelse
: Referanse til nettside som gir tilgang til datasettet, dets distribusjoner og/eller tilleggsinformasjon. Dokumentasjon som ikke er spesifikt definisjon av felter, hører hjemme her.

Kardinalitet
: 0..1

Status
: Valgfri

### Datasett - språk
URI
: dct:language

Range
: dct:LinguisticSystem

Beskrivelse
: Referanse til språket som datasettet er på. Kan repeteres dersom det er flere språk i datasettet

Kardinalitet
: 0..n

Status
: Valgfri

### Datasett - annen identifikator
URI
: adms:identifier 

Range
: adms:Identifier

Beskrivelse
: Referanse til en sekundær identifikator av datasettet som MAST/ADS, DataCite, DOI, EZID eller W3ID.

Kardinalitet
: 0..n

Status
: Valgfri

### Datasett - utgivelsesdato
URI
: dct:issued 

Range
: rdfs:Literal typed as xsd:dateTime 

Beskrivelse
: Dato for den formelle utgivelsen av datasettet 

Kardinalitet
: 0..1

Status
: Valgfri

### Datasett - dekningsområde
URI
: dct:spatial

Range
: dct:Location

Beskrivelse
: Referanse til et geografisk område datasettet gjelder for

Kardinalitet
: 0..n

Status
: Valgfri

### Datasett - tidsperiode
URI
: dct:temporal 

Range
: dct:PeriodOfTime

Beskrivelse
: Referanse til en tidsperiode datasettet gjelder for (startdato og sluttdato)

Kardinalitet
: 0..n

Status
: Valgfri

### Datasett - modifisert
URI
: dct:modified

Range
: rdfs:Literal typed as xsd:date or xsd:dateTime

Beskrivelse
: Dato for siste oppdatering av datasettet

Kardinalitet
: 0..1

Status
: Valgfri

### Datasett - versjon
URI
: adms:version

Range
: rdfs:Literal 

Beskrivelse
: Et versjonsnummer eller annen versjonsbetegnelse for datasettet

Kardinalitet
: 0..1

Status
: Valgfri 

### Datasett - versjonsnote
URI
: adms:versionNotes

Range
: rdfs:Literal

Beskrivelse
: En beskrivelse av endringene fra forrige versjon til denne versjonen av datasettet

Kardinalitet
: 0..1

Status
: Valgfri
