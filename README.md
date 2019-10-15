# tei_openiti

This repository contains a TEI customization for representing the OpenITI mARkdown scheme in TEI XML.

## The ODD

`tei_openiti.odd` is the main customization file that includes both prose documentation and the code for generating an schema for validating XML documents.

## How to generate the schema and the documentation

### With Roma
Use the TEI customization website called "Roma". Find the newest version at romabeta.tei-c.org or the legacy version at roma.tei-c.org.

### With OxGarage
OxGarage offers both a web UI and an API to perform TEI transformation tasks. Find it at oxgarage.tei-c.org.

### With the TEI Stylesheets

For the schema
```
$ bin/teitorelaxng tei_openiti.odd tei_openiti.rng
```
For the documentation
$ bin/teitohtml tei_openiti.odd

