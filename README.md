## NanoLinks-KG: FAIRified nanosafety datasets

This repository is part of the research output of the paper "Interoperable nanosafety data using semantic modeling and linked data knowledge graphs".

The repository contains five FAIRified datasets (numbered folders), originally published as supplementary materials for nanosafety related literature, then converted to RDF and made availabe on Zenodo.


In each dataset folder, the following folders are provided:

- "mapping": contains the mapping rules (in YARRRML format) to convert the original datasets from a semi-structured format to RDF.
- "mapping/ttl" contains the converted mapping rules int RML turtle format.
- "rdf" contains the output RDF generated from the RML mapping rules following the NanoLinks Semantic Model.
- "data.csv" this is the dataset file used as input for RML-Mapper in order to convert to RDF. Dataset 03 does not contain this file since it is a collection of gene expression datasets. Alernatively, a folder named "ENM_public_data" is where the data reside. 

Moreover, inside the folder "properties" is the file "mapToIRI.tsv" which is used to annotate string values from datasets with ontology classes. New annotations can be added to this file.

Finally, inside the folder "validation" is the ShEx model used to validate the generated RDF against the NanoLinks semantic model.

