---
title: Innledning
id: 02
layout: default
---
Dokumentet beskriver “Standard for beskrivelse av datasett og datakataloger (DCAT-AP-NO)” som skal sikre at beskrivelser av offentlige data utføres på en felles, strukturert måte og i en maskinlesbar form. Standarden stiller krav til hva som skal, bør og kan være med i beskrivelsene, med spesifikasjon av dataformat.

Formålet med standarden er å legge tilrette for utveksling av beskrivelser av datasett, og å lette søk etter datasett. Standarden vil gjelde datasett som forvaltes av offentlig sektor, og som beskrives med tanke på oppføring i en katalog eller «inventarliste» . Standarden vil støtte søking i og deling av datasett på tvers av offentlig sektor (gjenbruk) og legge til rette for viderebruk i privat sektor. Standarden er således nyttig både for offentlig sektor selv og for næringsliv og sivilsamfunn for øvrig. 

Arbeidet med informasjonsforvaltning i offentlig sektor har vist at det er behov for beskrivelser av alle datasett i forvaltningen, og det vil være hensiktsmessig at disse datasettene beskrives på en helhetlig måte. Standarden vil således være nyttig for etatens forvaltning av egen informasjon, og for andre etater, næringsliv og sivilsamfunn som har behov for å vite hvilke data etaten forvalter. DCAT-AP-NO skal derfor brukes i beskrivelsen av både åpne og ikke-åpne data selv om DCAT-AP primært er utviklet for åpne data. 

Ettersom standarden anbefaler formater som er beregnet for bruk i et Lenkede data-miljø, bør utgivere vurdere anbefalingene i W3C Notes [Best Practice Recipes for Publishing RDF Vocabularies](http://www.w3.org/TR/swbp-vocab-pub/ "Best Practice Recipes for Publishing RDF Vocabularies"), [Best Practices for Publishing Linked Data](http://www.w3.org/TR/ld-bp "Best Practices for Publishing Linked Data")  og ISA-rapporten [10 Rules for Persistent URIs](https://joinup.ec.europa.eu/community/semic/document/10-rules-persistent-uris "10 Rules for Persistent URIs"). Utgivere bør også vurdere å tildele URIer til alle forekomster av klassene som er beskrevet i standarden. Språk bør angis for alle literaler i tråd med [ISO 639](http://www.loc.gov/standards/iso639-2/php/code_list.php "Codes for the Representation of Names of Languages").

DCAT-AP-NO er basert på den europeiske DCAT-profilen [DCAT application profile for data portals in Europe](https://joinup.ec.europa.eu/asset/dcat_application_profile/description "DCAT application profile for data portals in Europe") som er forvaltet av [EU-kommisjonens ISA-program](http://ec.europa.eu/isa/ "EU-kommisjonens ISA-program"). *S*iden standarden legger til rette for internasjonal utveksling, skal engelske egenskapsnavn i form av URIer benyttes.

Egenskapsnavnene fra den underliggende DCAT-AP v1.01 er i «Norsk standard for beskrivelse av datasett og datakataloger» gitt norske navn. 

Avvikene fra den europeiske DCAT-AP v1.01 er i gjeldende versjon (DCAT-AP-NO 1.0) disse: 

* For klassen Datasett er «tilgangsnivå» lagt til som anbefalt egenskap

* For klassen Datasett er «skjermingshjemmel» lagt til som anbefalt egenskap

* JSON-LD er lagt til som anbefalt publiseringsformat i tillegg til RDF/XML

* Egenskapene er gitt norske navn (URIer skal brukes - ikke navnet på egenskapene)

De to første tilleggene ivaretar behov knyttet til at standarden også skal brukes på ikke-åpne data

Vi gjør oppmerksom på at ISA har startet arbeidet med en revisjon av DCAT-AP. Fremtidige versjoner av DCAT-AP-NO vil ta opp i seg endringene for DCAT-AP. Det er sannsynlig at det kommer flere særnorske utvidelser i neste versjon av DCAT-AP-NO. Disse er omtalt i utredningen for standarden.
