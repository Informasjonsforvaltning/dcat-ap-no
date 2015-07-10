---
title: Klasser i standarden
id: 06
layout: default
---

### Enhet
Engelsk
: Agent

Beskrivelse
: Enhet som er assosiert med katalogen og/eller datasettene. Dersom enheten er en organisasjon er det anbefalt å bruke «Organization Ontology»

URI
: foaf:Agent

Referanse
: [http://xmlns.com/foaf/spec/#term_Agent](http://xmlns.com/foaf/spec/#term_Agent) , [http://www.w3.org/TR/vocab-org/](http://www.w3.org/TR/vocab-org/)

Status
: Obligatorisk

### Kategori

Engelsk
: Category

Beskrivelse
: Et emne for et datasett

URI
: SKOS:Consept

Referanse
: [http://www.w3.org/TR/2013/WD-vocab-dcat-20130312/#class-category-and-category-scheme](http://www.w3.org/TR/2013/WD-vocab-dcat-20130312/#class-category-and-category-scheme)

Status
: Obligatorisk


### Kategoriskjema
Engelsk
: Category

Beskrivelse
: Et emne for et datasett

URI
: SKOS:Consept

Referanse
: http://www.w3.org/TR/2013/WD-vocab-dcat-20130312/#class-category-and-category-scheme

Status
: Obligatorisk

### Katalog
Engelsk
: Catalogue

Beskrivelse
: En katalog eller repository som inneholder datasettene som er beskrevet.

URI
: dcat:Catalog

Referanse
: [http://www.w3.org/TR/2013/WD-vocab-dcat-20130312/#class-catalog](http://www.w3.org/TR/2013/WD-vocab-dcat-20130312/#class-catalog)

Status
: Obligatorisk

### Datasett {#klasserdatasett}
Engelsk
: Dataset

Beskrivelse
: En konseptuell enhet som representerer informasjonen som publiseres

URI
: dcat:Dataset

Referanse
: [http://www.w3.org/TR/2013/WD-vocab-dcat-20130312/#class-dataset](http://www.w3.org/TR/2013/WD-vocab-dcat-20130312/#class-dataset)

Status
: Obligatorisk

### Literal
Engelsk
: Literal

Beskrivelse
: En literal-verdi slik som en streng eller integrer (0 og heltall). Literaler kan inneholde datatype, og f.eks være formatert som en dato. Literaler som innholder maskinlesbar tekst har en valgfri språk-tag, definert av BCP47 (no=norsk, nb=bokmål, nn=nynorsk, en=engelsk)

URI
: rdfs:Literal

Referanse
: [http://www.w3.org/TR/rdf-concepts/#section-Literals](http://www.w3.org/TR/rdf-concepts/#section-Literals)

Status
: Obligatorisk

### Ressurs
Engelsk
: Resource

Beskrivelse
: Objekter som ikke er strenger eller primitiver med datatyper.

URI
: rdfs:Resource

Referanse
: [http://www.w3.org/TR/rdf-schema/#ch_resource](http://www.w3.org/TR/rdf-schema/#ch_resource)

Status
: Obligatorisk

### Distribusjon
Engelsk
: Distribution

Beskrivelse
: En fysisk utførelse av datasettet i et bestemt format.

URI
: dcat:Distribution

Referanse
: [http://www.w3.org/TR/2013/WD-vocab-dcat-20130312/#class-distribution](http://www.w3.org/TR/2013/WD-vocab-dcat-20130312/#class-distribution)

Status
: Anbefalt

### Katalogpost {#klasser-katalogpost}
Engelsk
: Catalogue Record

Beskrivelse
: En beskrivelse av en datasettoppføring i katalogen.

URI
: dcat:CatalogRecord
  
Referanse
: [http://www.w3.org/TR/2013/WD-vocab-dcat-20130312/#class-catalog-record](http://www.w3.org/TR/2013/WD-vocab-dcat-20130312/#class-catalog-record)

Status
: Valgfri
  

### Dokument
Engelsk
: Document
  
Beskrivelse
: En tekstlig ressurs beregnet på mennesker som inneholder informasjon. For eksempel en nettside om et datasett.
  
URI
: foaf:Document

Referanse
: [http://xmlns.com/foaf/spec/#term_Document](http://xmlns.com/foaf/spec/#term_Document)

Status
: Valgfri

### Frekvens {#klasser-frekvens}
Engelsk
: Frequency

Beskrivelse
: En frekvensen om noe som gjentar seg, f.eks publisering av et datasett.

URI
: dct:Frequency

Referanse
: [http://dublincore.org/documents/dcmi-terms/#terms-Frequency](http://dublincore.org/documents/dcmi-terms/#terms-Frequency)

Status
: Valgfri

### Indentifikator
Engelsk
: Identifier

Beskrivelse
: En identifikator i en bestemt kontekst, bestående av strengen som er identifikatoren; en valgfri identifikator for identifikatorsystemet; en valgfri identifikator for versjonen av identifikatorsystemet; en valgfri identifikator for etaten som administrerer identifikatorsystemet
  
URI
: adms:Identifier

Referanse
: [http://www.w3.org/TR/vocab-adms/#identifier](http://www.w3.org/TR/vocab-adms/#identifier)

Status
: Valgfri

### Lisensdokument
Engelsk
: License document

Beskrivelse
: En juridisk dokument som gir offisiell tillatelse til å gjøre noe med en ressurs.
  
URI
: dct:LicenseDocument
  
Referanse
: [http://dublincore.org/documents/2012/06/14/dcmi-terms/?v=terms#LicenseDocument](http://dublincore.org/documents/2012/06/14/dcmi-terms/?v=terms#LicenseDocument)

Status
: Valgfri

### Språksystem
Engelsk
: Linguistic system

Beskrivelse
: Et system av tegn, symboler, lyder, gester, eller regler som brukes i kommunikasjon, f.eks et språk

URI
: dct:LinguisticSystem

Referanse
: [http://dublincore.org/documents/dcmi-terms/#terms-LinguisticSystem](http://dublincore.org/documents/dcmi-terms/#terms-LinguisticSystem)

Status
: Valgfri

### Lokasjon
Engelsk
: Location

Beskrivelse
: En region eller et navngitt sted. Det kan representeres ved hjelp av et kontrollert vokabular eller med geografiske koordinater.

URI
: dct:Location

Referanse
: [http://dublincore.org/documents/dcmi-terms/#terms-Location](http://dublincore.org/documents/dcmi-terms/#terms-Location)

Status
: Valgfri

### Mediatype eller omfang
Engelsk
: Media type or extent

Beskrivelse
: En medietype eller omfang, f.eks formatet til en datafil

URI
: dct:MediaTypeOrExtent

Referanse
: [http://dublincore.org/documents/dcmi-terms/#terms-MediaTypeOrExtent](http://dublincore.org/documents/dcmi-terms/#terms-MediaTypeOrExtent)

Status
: Valgfri

### Tidsperiode {#klasser-tidsperiode}
Engelsk
: Period of time

Beskrivelse
: Et tidsintervall som er navngitt eller definert av en start- og sluttdato.

URI
: dct:PeriodOfTime

Referanse
: [http://dublincore.org/documents/dcmi-terms/#terms-PeriodOfTime](http://dublincore.org/documents/dcmi-terms/#terms-PeriodOfTime)

Status
: Valgfri

### Utgiver type
Engelsk
: Publisher type

Beskrivelse
: Type organisasjon som fungerer som en utgiver

URI
: skos:Concept

Referanse
: [http://www.w3.org/TR/vocab-adms/#dcterms-type](http://www.w3.org/TR/vocab-adms/#dcterms-type)

Status
: Valgfri

### Rettighetsutsagn
Engelsk
: Rights statement

Beskrivelse
: En utsagn om immaterielle rettigheter knyttet til en ressurs, et juridisk dokument som gir offisiell tillatelse til å  gjøre noe med en ressurs, eller en uttalelse om tilgangsrettigheter.

URI
: dct:RightsStatement

Referanse
: [http://dublincore.org/documents/dcmi-terms/#terms-RightsStatement](http://dublincore.org/documents/dcmi-terms/#terms-RightsStatement)

Status
: Valgfri

### Standard
Engelsk
: Standard

Beskrivelse
: En standard eller annen spesifikasjon som et datasett er i samsvar med

URI
: dct:Standard

Referanse
: [http://dublincore.org/documents/dcmi-terms/#terms-Standard](http://dublincore.org/documents/dcmi-terms/#terms-Standard)

Status
: Valgfri

### Status {#klasserstatus}
Engelsk
: Status

Beskrivelse
: En indikasjon på modenhet for en distribusjon

URI
: skos:Concept

Referanse
: [http://www.w3.org/TR/vocab-adms/#status](http://www.w3.org/TR/vocab-adms/#status)

Status
: Valgfri

### VCard
Engelsk
: Vcard

Beskrivelse
: En beskrivelse etter vCard-spesifikasjon, f.eks  telefonnummer og e-post adresse for et kontaktpunkt.

URI
: v:VCard

Referanse
: [http://www.w3.org/2006/vcard/ns-2006.html#VCard](http://www.w3.org/2006/vcard/ns-2006.html#VCard)

Status
: Valgfri
