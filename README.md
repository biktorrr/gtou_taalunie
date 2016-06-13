# gtou_taalunie
Data and resources for the VRT/Beeld en Geluid project Gemeenschappelijke Thesaurus  voor  Uniforme Ontsluiting - Taalunie

The goal of this project was to 1) convert the VRT (Flemish Broadcasting Corp) thesaurus to SKOS; 2) to establish an alignment between the VRT thesaurus and the GTAA (Gemeenschappelijke Thesaurus Audiovisuele Archieven: http://gtaa.beeldengeluid.nl) and 3) to show the value of this mapping through a demonstrator. 

This repository contains versions of the two thesauri in RDF/Turtle format. This version of the GTAA is a zipped version of an out-of-synch data dump. The latest version is always found at http:/gtaa.beeldengeluid.nl. The VRT thesaurus file contains a  version of thesaurus produced in the context of this project. It is not an officially published version. 

The '''alignments''' folder of this repository contains the actual mappings produced in the context of the project. These were established using a semi-automatich alignemnt procedure using the CultuurLINK tool (http:/cultuurlink.beeldengeluid.nl), built by Spinque (http://spinque.com). The alignment strategies result in a number of RDF/Turtle mapping files containing correspondences between the two thesauri, implemented using skos:exactMatch properties. 

