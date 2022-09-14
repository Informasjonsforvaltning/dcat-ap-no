# DCAT-AP-NO

## Bidra

For å bidra til utviklingen av denne standarden, må du clone den til din datamaskin og opprette en pull request.

### Clone til din datamaskin

For at det følgende skal virke på din maskin, må du ha programvare installert:  

- [Git](https://git-scm.com/)
- en tekst-editor, feks [Atom editor](https://atom.io/)

 Dersom du bruker Atom kan du gjøre som følger:  

- Trykk `Ctrl+Shift+P`
- Skriv `GitHub: Clone` og trykk Enter
- I Clone from legger du inn følgende url `https://github.com/Informasjonsforvaltning/dcat-ap-no.git`

Alternativt i kommando-linje:

```Shell
% git clone https://github.com/Informasjonsforvaltning/dcat-ap-no.git
% cd dcat-ap-no
% atom .                                # dersom du har installert Atom
```

### Gjøre endringer

Denne standarden er laget i [AsciiDoc](http://asciidoc.org/) med hjelp av verktøyet [Asciidoctor](https://asciidoctor.org/).

Alle endringer må gjøres ved å endre eller legge til filer i docs-folderen. Se for eksempel på følgende veileder for god AsciiDoc praksis: <https://asciidoctor.org/docs/asciidoc-recommended-practices>

En typisk git-arbeidsflyt vil vere som følger:

```Shell
% git checkout master
% git pull
% git checkout -b <ny branch>
% ... # gjør endringer i din valgte editor
% git add <filer som er endra>          # legger endringer klare for commit
% git commit -m "Fornuftig feilmeldng"  # utføre commit
% git push                              # publisere branch og gjøre klar for PR
```

Dersom du bruker Atom har du støtte for alt dette i Git-panelet.

Gå til <https://github.com/Informasjonsforvaltning/dcat-ap-no/pulls> og opprett `New pull request`

#### Forhåndsvisning

Dersom du bruker [Atom editor](https://atom.io/) kan du installere pakken [AsciiDoc Assistant Package](https://atom.io/packages/asciidoc-assistant).
Du vil da få syntax-uthevelse og forhåndsvisning.

#### Generer html og pdf lokalt

For at det følgende skal virke på din maskin, må du ha programvare installert:  

- [docker](https://www.docker.com/products/docker-desktop)

```Shell
% docker run -it -v $(pwd):/documents asciidoctor/docker-asciidoctor
bash-5.0# asciidoctor -D docs -o index.html -a lang=nb docs/main.adoc
bash-5.0# asciidoctor-pdf -D docs -o files/dcat-ap-no.pdf -a lang=nb docs/main.adoc
```

Åpne filen index.html i din nettleser.

#### Teste html i en webserver på din maskin

Dersom du vil teste html på en server på din maskin, kan du feks installere [Live Server](https://pypi.org/project/live-server/)
For dette trenger du å installere Python på din datamaskin:

- [python](https://www.python.org/downloads/)

```Shell
% python -m pip install --user live-server
% live-server docs
```

Åpne en nettleser og gå til <http://localhost:8888>
