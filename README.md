# On the definition of "dataset"

Discussion paper on the definition of dataset.

## Content

This folder contains the text for the Discussion Paper

* dp.adoc - the main Discussion Paper document with references to all sections
* remaining adocs - each section of the Discussion Paper document is in a separate document: follow directions in each document to populate
* figures - figures go here
* images - Image files for graphics go here. Image files for figures go in the "figures" directory. Only place in here images not used in figures (e.g., as parts of tables, as logos, etc.)
* UML - UML diagrams, if applicable

## Building

To produce the HTML of the Discussion Paper run `asciidoctor --safe -a data-uri -o <Discussion Paper name>.html dp.adoc`

To produce the PDF of the Discussion Paper run `asciidoctor-pdf --safe -o <Discussion Paper name>.pdf dp.adoc`

