# dcat-ap-no - Standard for beskrivelse av datasett og datakataloger

Repo for revisjon av standarden.

Gjeldende versjon: http://doc.difi.no/dcat-ap-no/
Høringsutkast (under arbeid): https://doc.difi.no/review/dcat-ap-no/  

Standarden er under revisjon høsten 2019. Meld inn behov som Issues innen 1. september 2019. 

Endringer i forbindelse med revisjonsprosessen utføres mot "review"-greina og blir eksponert i html her https://doc.difi.no/review/dcat-ap-no/

Tekst formateres som AsciiDoc. Se detaljer om syntaks her: https://asciidoctor.org/docs/asciidoc-syntax-quick-reference/

[Properties] er lagt til som egendefinert attributt i syntaksen for kunne malstyre (i CSS) hvordan _egenskapene_ i standarden blir seende ut i html. Eksempel:

````
== Datasett: tittel [[datasett-tittel]]

[properties]
URI:: dct:title
Range:: rdfs:Literal
Beskrivelse:: Inneholder navnet på datasettet. Kan gjentas for parallelle språkversjoner av navnet
Kardinalitet:: 1..n
Status:: Obligatorisk
````

For å synliggjøre hva som er nytt, endret og slettet i standarden skal du gjøre følgende:

For nye egenskaper legges "(ny)" til i tittelen slik (fiktivt eksempel): 
````
== Datasett: Alternativ tittel (ny) [[datasett-alt-tittel]]
````
For egenskaper som er endret legges (endret) og (slettet) til på samme måte.

## Tips til editor

For å redigere i adoc-dokumenter med forhåndsvisning av output kan du for eksempel bruke Asciidic FX  (https://asciidocfx.com/) eller Atom (https://atom.io/). For Atom-brukere anbefales å installere  "AsciiDoc Preview"-tillegget. Merk at stylingen i editor-preview vil avvike noe fra https://doc.difi.no/review/dcat-ap-no/  
