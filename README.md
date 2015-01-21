# collection_builder

## Function
The source code enables an automatic transformation of .bib files to files for Jekyll collection. 
For each entry in the .bib file, a collection entry is created with file name "[id].md", where "id" is the bibtex key. 

## Usage
For proper use of the functions, bibtexparser package is needed. 
Detailed installation guide and documentation can be found at
https://bibtexparser.readthedocs.org/en/latest/install.html

## Updates
Added sort_key for support of ordering of bibliography
For example:
 (site.publications | sort: 'sort_key')
will sort the collection site.publications by the value in site.publication.sort_key

## Roadmap
1. Make a standalone command line tool 

