# Krav til kontrollerte vokabular

Følgende er en liste over krav som er identifisert for kontrollerte vokabular som er anbefalt av den underliggende applikasjonsprofilen DCAT-AP.

Kontrollerte vokabular bør:

* være publisert under en åpen lisens.
* brukes og / eller bli vedlikeholdt av en institusjon i Norge eller EU, av anerkjent standardiseringsorganisasjon eller en annen pålitelig organisasjon.
* være skikkelig dokumentert.
* ha etiketter på flere språk.
* inneholde et relativt lite antall begrep (f.eks 10-25) som er generelle nok til at et bredt spekter av ressurser kan klassifiseres.
* har vilkår som er identifisert av URI for vokabularer der hver URI for vokabular viser til dokumentasjon av begrepet.
* har en varighets- og versjonspolicy.

Disse kriteriene er ikke tenkt å definere et sett med krav til kontrollerte ordforråd generelt; de er kun ment brukt for utvelgelse av de kontrollerte vokabularene som er anbefalt for denne standarden

## Kontrollerte vokabular som skal brukes

Nedenfor er en rekke egenskaper oppført med kontrollerte vokabular som må brukes for de nevnte egenskapene.

<hr>
URI
: dcat:mediaType

Brukt i klasse
: Distribusjon

Navn
: MDR File types Name Authority List

URI for vokabular
: http://publications.europa.eu/mdr/authority/file-type/
<hr>


URI
: dcat:theme

Brukt i klasse
: Datasett

Navn
: EuroVoc domains

URI for vokabular
: http://eurovoc.europa.eu/

<hr>
URI
: dcat:themeTaxonomy

Brukt i klasse
: Katalog

Navn
: EuroVoc

URI for vokabular
: http://eurovoc.europa.eu/

<hr>
URI
: dct:accrualPeriodicity

Brukt i klasse
: Datasett

Navn
: Dublin Core Collection Description Frequency Vocabulary

URI for vokabular
: http://purl.org/cld/freq/

<hr>
URI
: dct:format

Brukt i klasse
: Distribusjon

Navn
: MDR File Type Named Authority List

URI for vokabular
: http://publications.europa.eu/mdr/authority/file-type/

<hr>
URI
: dct:language

Brukt i klasse
: Katalog, Datasett

Navn
: MDR Languages Named Authority List

URI for vokabular
: http://publications.europa.eu/mdr/authority/language/

<hr>
URI
: dct:publisher

Brukt i klasse
: Katalog, Datasett

Navn
: MDR Corporate bodies Named Authority List

URI for vokabular
: http://publications.europa.eu/mdr/authority/corporate-body/

Beskrivelse
: Skal brukes for europeiske institusjoner og et lite sett med internasjonale organisasjoner. Ved andre typer organisasjoner, bør nasjonale, regionale eller lokale vokabular brukes.

<hr>
URI
: dct:spatial

Brukt i klasse
: Katalog, Datasett

Navn
: MDR Countries Named Authority List, MDR Places Named Authority List

URI for vokabular
: http://publications.europa.eu/mdr/authority/country/, http://publications.europa.eu/mdr/authority/place/

Beskrivelse
: Vokabularet for land skal brukes hvis dekningsområde er et spesielt land. Vokabularet for steder skal brukes hvis dekningsområde er en del av et land.

<hr>
URI
: adms:status

Brukt i klasse
: Katalogpost

Navn
: ADMS change type vocabulary

URI for vokabular
: http://purl.org/adms/changetype/

Beskrivelse
: :created, :updated, :deleted

<hr>
URI
: adms:status

Brukt i klasse
: Distribusjon

Navn
: ADMS status vocabulary

URI for vokabular
: http://purl.org/adms/status/

Beskrivelse
: Listen over begrep i ADMS status-vokabularet er inkludert i ADMS-spesifikasjonen

<hr>
URI
: dct:type

Brukt i klasse
: Enhet

Navn
: ADMS publisher type vocabulary

URI for vokabular
: http://purl.org/adms/publishertype/Company

Beskrivelse
: Listen over begrep i ADMS-vokabularet for utgivertype er inkludert i ADMS-spesifikasjonen

<hr>
URI
: dct:type

Brukt i klasse
: Lisensdokument

Navn
: ADMS licence type vocabulary

URI for vokabular
: http://purl.org/adms/licencetype/

Beskrivelse
: Listen over begrep i ADMS-vokabularet for lisenstype er inkludert i ADMS spesifikasjonen
<hr>

I tillegg til de foreslåtte felles vokabularene ovenfor, kan ytterligere domenespesifikke vokabular brukes. Selv om de ikke blir akseptert av generelle implementeringer av standarden, kan de bidra til å øke interoperabilitet på tvers av applikasjoner innenfor samme domene. Eksempler her er komplett sett med begreper i EuroVoc, CERIFs standardvokabular, Deweys desimalklassifikasjon og en rekke andre vokabular.
