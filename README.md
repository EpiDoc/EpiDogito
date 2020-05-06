# EpiDogito
EpiDoc / Recogito

This project contains templates and planning docs for the integration of EpiDoc integration with the [Recogito](http://recogito.pelagios.org/) annotation tool from Pelagios. Currently this only involves the creation of templates for the export of annotated text from Recogito into a minimal TEI-EpiDoc validating XML file. At a later stage we might also discuss:

1. Import of EpiDoc file into Recogito, and the preservation of EpiDoc encoding in the annotated file exported at the end of the pipeline
1. Transformation of [Leiden Conventions](https://en.wikipedia.org/wiki/Leiden_Conventions) sigla in the text field of an imported text file, so that simple TEI-EpiDoc tags (e.g. `<supplied>`, `<unclear>`, `<abbr>`, etc.) are included in the EpiDoc export

## Authors

* Gabriel Bodard
* Rainer Simon

## License

EpiDoc/EpiDogito is licensed under the [GNU General Public License v3.0](LICENSE).
