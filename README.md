# ![LOGO](logo.png) Rat Genome Database **flow**ground Connector

## Description

A generated **flow**ground connector for the Rat Genome Database API (version 1.1).

Generated from: https://api.apis.guru/v2/specs/mcw.edu/1.1/swagger.json<br/>
Generated at: 2019-05-07T17:42:57+03:00

## API Description

The RGD REST API provides programmatic access to information and annotation stored in the Rat Genome Database

## Authorization

This API does not require authorization.

## Actions

### Get gene allele records submitted by RGD to AGR by taxonId

*Tags:* `AGR`

#### Input Parameters
* `taxonId` - _required_ - The taxon ID for species

### Get expression annotations submitted by RGD to AGR by taxonId

*Tags:* `AGR`

#### Input Parameters
* `taxonId` - _required_ - The taxon ID for species

### Get phenotype annotations submitted by RGD to AGR by taxonId

*Tags:* `AGR`

#### Input Parameters
* `taxonId` - _required_ - The taxon ID for species

### Get gene records submitted by RGD to AGR by taxonId

*Tags:* `AGR`

#### Input Parameters
* `taxonId` - _required_ - The taxon ID for species

### Return a list of genes annotated to an ontology term

*Tags:* `Annotation`

### Returns a list ontology term accession IDs annotated to an rgd object

*Tags:* `Annotation`

#### Input Parameters
* `rgdId` - _required_ - RGD ID

### Returns annotation count for ontology accession ID

*Tags:* `Annotation`

#### Input Parameters
* `accId` - _required_ - Ontology term accession ID
* `includeChildren` - _required_ - true: return annotations for the term and children, false: return annotations for the term only 

### Returns annotation count for ontology accession ID and speicies

*Tags:* `Annotation`

#### Input Parameters
* `accId` - _required_ - Ontology term accession ID
* `speciesTypeKey` - _required_ - A list of species type keys can be found using the lookup service
* `includeChildren` - _required_ - true: return annotations for the term and children, false: return annotations for the term only 

### Returns annotation count for ontology accession ID and object type

*Tags:* `Annotation`

#### Input Parameters
* `accId` - _required_ - Ontology term accession ID
* `speciesTypeKey` - _required_ - A list of species type keys can be found using the lookup service
* `includeChildren` - _required_ - true: return annotations for the term and children, false: return annotations for the term only 
* `objectType` - _required_ - A list of object types can be found using the lookup service

### Returns a list of annotations for a reference

*Tags:* `Annotation`

#### Input Parameters
* `refRgdId` - _required_ - Reference RGD ID

### Returns a list of annotations by RGD ID

*Tags:* `Annotation`

#### Input Parameters
* `rgdId` - _required_ - RGD ID

### Returns a list of annotations by RGD ID and ontology prefix

*Tags:* `Annotation`

#### Input Parameters
* `rgdId` - _required_ - RGD ID
* `ontologyPrefix` - _required_ - Ontology Prefix.  The prefix can be found left of the semicolon in an ontology term accession ID.  As an example, term accession PW:0000034 has the ontology prefix PW

### Returns a list of annotations by RGD ID and ontology term accession ID

*Tags:* `Annotation`

#### Input Parameters
* `accId` - _required_ - Ontology Term Accession ID
* `rgdId` - _required_ - RGD ID

### Returns a list annotations for an ontology term or a term and it's children

*Tags:* `Annotation`

#### Input Parameters
* `accId` - _required_ - Ontology term accession ID
* `speciesTypeKey` - _required_ - A list of species type keys can be found using the lookup service
* `includeChildren` - _required_ - true: return annotations for the term and children, false: return annotations for the term only 

### Return a list of genes for an affymetrix ID

*Tags:* `Gene`

#### Input Parameters
* `affyId` - _required_ - Affymetrix ID
* `speciesTypeKey` - _required_ - A list of RGD species type keys can be found in the lookup service

### Return a list of genes for an alias and species

*Tags:* `Gene`

#### Input Parameters
* `aliasSymbol` - _required_ - Gene alias symbol
* `speciesTypeKey` - _required_ - A list of RGD species type keys can be found in the lookup service

### Return a list of gene alleles

*Tags:* `Gene`

#### Input Parameters
* `rgdId` - _required_ - RGD ID of gene

### Return a list of genes annotated to an ontology term

*Tags:* `Gene`

### Return a list of genes annotated to an ontology term

*Tags:* `Gene`

#### Input Parameters
* `accId` - _required_ - Accesstion ID

### Return a list of genes annotated to an ontology term

*Tags:* `Gene`

#### Input Parameters
* `accId` - _required_ - Ontology term accession ID
* `speciesTypeKey` - _required_ - Species type key.  A list of species type keys can be found in the lookup service

### Return a list of genes by keyword and species type key

*Tags:* `Gene`

#### Input Parameters
* `keyword` - _required_ - Search keyword
* `speciesTypeKey` - _required_ - Species type key.  A list of species type keys can be found in the lookup service

### Return a list of all genes with position information for an assembly

*Tags:* `Gene`

#### Input Parameters
* `mapKey` - _required_ - A list of RGD assembly map keys can be found in the lookup service

### Return a list of gene orthologs

*Tags:* `Gene`

### Return a list of gene orthologs

*Tags:* `Gene`

#### Input Parameters
* `rgdId` - _required_ - RGD ID of a gene

### Return a list of all genes for a species in RGD

*Tags:* `Gene`

#### Input Parameters
* `speciesTypeKey` - _required_ - A list of RGD species type keys can be found in the lookup service

### Return a list of genes position and map key

*Tags:* `Gene`

#### Input Parameters
* `chr` - _required_ - Chromosome
* `start` - _required_ - Start Position
* `stop` - _required_ - Stop Position
* `mapKey` - _required_ - A list of RGD assembly map keys can be found in the lookup service

### Get a gene record by RGD ID

*Tags:* `Gene`

#### Input Parameters
* `rgdId` - _required_ - The RGD ID of a Gene in RGD

### Get a gene record by symbol and species type key

*Tags:* `Gene`

#### Input Parameters
* `symbol` - _required_ - Gene Symbol
* `speciesTypeKey` - _required_ - Species type key.  A list of species type keys can be found in the lookup service

### Returns a list of gene types avialable in RGD

*Tags:* `Lookup`

### Translate RGD IDs to Ensembl Gene IDs

*Tags:* `Lookup`

### Translate an RGD ID to an Ensembl Gene  ID

*Tags:* `Lookup`

#### Input Parameters
* `rgdId` - _required_ - RGD ID

### Translate RGD IDs to Ensembl Protein IDs

*Tags:* `Lookup`

### Translate an RGD ID to an Ensembl Protein ID

*Tags:* `Lookup`

#### Input Parameters
* `rgdId` - _required_ - RGD ID

### Translate RGD IDs to Ensembl Transcript IDs

*Tags:* `Lookup`

### Translate an RGD ID to an Ensembl Transcript ID

*Tags:* `Lookup`

#### Input Parameters
* `rgdId` - _required_ - RGD ID

### Translate RGD IDs to GTEx IDs

*Tags:* `Lookup`

### Translate an RGD ID to an GTEx ID

*Tags:* `Lookup`

#### Input Parameters
* `rgdId` - _required_ - RGD ID

### Translate RGD IDs to GenBank Nucleotide IDs

*Tags:* `Lookup`

### Translate an RGD ID to a GenBank Nucleotide ID

*Tags:* `Lookup`

#### Input Parameters
* `rgdId` - _required_ - RGD ID

### Translate RGD IDs to GenBank Protein IDs

*Tags:* `Lookup`

### Translate an RGD ID to a GenBank Protein ID

*Tags:* `Lookup`

#### Input Parameters
* `rgdId` - _required_ - RGD ID

### Translate RGD IDs to HGNC IDs

*Tags:* `Lookup`

### Translate an RGD ID to an HGNC ID

*Tags:* `Lookup`

#### Input Parameters
* `rgdId` - _required_ - RGD ID

### Translate RGD IDs to MGI IDs

*Tags:* `Lookup`

### Translate an RGD ID to an MGI ID

*Tags:* `Lookup`

#### Input Parameters
* `rgdId` - _required_ - RGD ID

### Translate RGD IDs to NCBI Gene IDs

*Tags:* `Lookup`

### Translate an RGD ID to an NCBI Gene ID

*Tags:* `Lookup`

#### Input Parameters
* `rgdId` - _required_ - RGD ID

### Translate RGD IDs to UniProt IDs

*Tags:* `Lookup`

### Translate an RGD ID to a UniProt ID

*Tags:* `Lookup`

#### Input Parameters
* `rgdId` - _required_ - RGD ID

### Return a list assembly maps for a species

*Tags:* `Lookup`

#### Input Parameters
* `speciesTypeKey` - _required_ - RGD species type key. A full list of keys is available throught the lookup service.  1=human, 2=mouse, 3=rat,ect

### Return a Map of species type keys available in RGD

*Tags:* `Lookup`

### Returns term for Accession ID

*Tags:* `Ontology`

#### Input Parameters
* `accId` - _required_ - Term Accession ID

### Return a list of pathways based on search term

*Tags:* `Pathway`

#### Input Parameters
* `searchString` - _required_ - Free text search string

### Return a list of pathways based on category provided

*Tags:* `Pathway`

#### Input Parameters
* `category` - _required_ - Pathway Category

### Return a list of quantitative phenotypes values based on a combination of Clinical Measurement, Experimental Condition, Rat Strain, and/or Measurement Method ontology terms.  Results will be all records that match all terms submitted.  Ontology ids should be submitted as a comma delimited list (ex. RS:0000029,CMO:0000155,CMO:0000139).  Species type is an integer value (3=rat, 4=chinchilla)

*Tags:* `Quantitative Phenotype`

#### Input Parameters
* `speciesTypeKey` - _required_ - Species Type Key - 3=rat 4=chinchilla 
* `termString` - _required_ - List of term accession IDs

### Returns a list QTL for given position and assembly map

*Tags:* `QTL`

#### Input Parameters
* `chr` - _required_ - Chromosome
* `start` - _required_ - Start Position
* `stop` - _required_ - Stop Position
* `mapKey` - _required_ - A list of assembly map keys can be found using the lookup service

### Return a QTL for provided RGD ID

*Tags:* `QTL`

#### Input Parameters
* `rgdId` - _required_ - RGD ID

### Count of active objects by type, for specified species and date

*Tags:* `Statistics`

#### Input Parameters
* `speciesTypeKey` - _required_ - speciesTypeKey
* `dateYYYYMMDD` - _required_ - dateYYYYMMDD

### Count of gene types, for specified species and date

*Tags:* `Statistics`

#### Input Parameters
* `speciesTypeKey` - _required_ - speciesTypeKey
* `dateYYYYMMDD` - _required_ - dateYYYYMMDD

### Count of objects with given status, for specified species and date

*Tags:* `Statistics`

#### Input Parameters
* `speciesTypeKey` - _required_ - speciesTypeKey
* `dateYYYYMMDD` - _required_ - dateYYYYMMDD

### Count of objects with reference sequence(s), by object type, for specified species and date

*Tags:* `Statistics`

#### Input Parameters
* `speciesTypeKey` - _required_ - speciesTypeKey
* `dateYYYYMMDD` - _required_ - dateYYYYMMDD

### Count of objects with reference, by object type, for specified species and date

*Tags:* `Statistics`

#### Input Parameters
* `speciesTypeKey` - _required_ - speciesTypeKey
* `dateYYYYMMDD` - _required_ - dateYYYYMMDD

### Count of objects with external database ids, by database id, for specified species, object type and date

*Tags:* `Statistics`

#### Input Parameters
* `speciesTypeKey` - _required_ - speciesTypeKey
* `objectKey` - _required_ - objectKey
* `dateYYYYMMDD` - _required_ - dateYYYYMMDD

### Count of protein interactions, for specified species and date

*Tags:* `Statistics`

#### Input Parameters
* `speciesTypeKey` - _required_ - speciesTypeKey
* `dateYYYYMMDD` - _required_ - dateYYYYMMDD

### Count of strains, by qtl inheritance type, for specified species and date

*Tags:* `Statistics`

#### Input Parameters
* `speciesTypeKey` - _required_ - speciesTypeKey
* `dateYYYYMMDD` - _required_ - dateYYYYMMDD

### Count of retired objects by type, for specified species and date

*Tags:* `Statistics`

#### Input Parameters
* `speciesTypeKey` - _required_ - speciesTypeKey
* `dateYYYYMMDD` - _required_ - dateYYYYMMDD

### Count of strain types, for specified species and date

*Tags:* `Statistics`

#### Input Parameters
* `speciesTypeKey` - _required_ - speciesTypeKey
* `dateYYYYMMDD` - _required_ - dateYYYYMMDD

### Count of withdrawn objects by type, for specified species and date

*Tags:* `Statistics`

#### Input Parameters
* `speciesTypeKey` - _required_ - speciesTypeKey
* `dateYYYYMMDD` - _required_ - dateYYYYMMDD

### Count of external database ids, for specied species and date

*Tags:* `Statistics`

#### Input Parameters
* `speciesTypeKey` - _required_ - speciesTypeKey
* `dateYYYYMMDD` - _required_ - dateYYYYMMDD

### Count difference of active objects, by type, for specified species and date range

*Tags:* `Statistics`

#### Input Parameters
* `speciesTypeKey` - _required_ - speciesTypeKey
* `dateFromYYYYMMDD` - _required_ - dateFromYYYYMMDD
* `dateToYYYYMMDD` - _required_ - dateToYYYYMMDD

### Count difference of gene types, for specified species and date range

*Tags:* `Statistics`

#### Input Parameters
* `speciesTypeKey` - _required_ - speciesTypeKey
* `dateFromYYYYMMDD` - _required_ - dateFromYYYYMMDD
* `dateToYYYYMMDD` - _required_ - dateToYYYYMMDD

### Count difference of objects with given status, for specified species and date range

*Tags:* `Statistics`

#### Input Parameters
* `speciesTypeKey` - _required_ - speciesTypeKey
* `dateFromYYYYMMDD` - _required_ - dateFromYYYYMMDD
* `dateToYYYYMMDD` - _required_ - dateToYYYYMMDD

### Count difference of objects with reference sequence(s), by object type, for specified species and date range

*Tags:* `Statistics`

#### Input Parameters
* `speciesTypeKey` - _required_ - speciesTypeKey
* `dateFromYYYYMMDD` - _required_ - dateFromYYYYMMDD
* `dateToYYYYMMDD` - _required_ - dateToYYYYMMDD

### Count difference of objects with reference, by object type, for specified species and date range

*Tags:* `Statistics`

#### Input Parameters
* `speciesTypeKey` - _required_ - speciesTypeKey
* `dateFromYYYYMMDD` - _required_ - dateFromYYYYMMDD
* `dateToYYYYMMDD` - _required_ - dateToYYYYMMDD

### Count difference of objects with external database ids, by database id, for specified species, object type and date range

*Tags:* `Statistics`

#### Input Parameters
* `speciesTypeKey` - _required_ - speciesTypeKey
* `objectKey` - _required_ - objectKey
* `dateFromYYYYMMDD` - _required_ - dateFromYYYYMMDD
* `dateToYYYYMMDD` - _required_ - dateToYYYYMMDD

### Count difference of protein interactions, for specified species and date range

*Tags:* `Statistics`

#### Input Parameters
* `speciesTypeKey` - _required_ - speciesTypeKey
* `dateFromYYYYMMDD` - _required_ - dateFromYYYYMMDD
* `dateToYYYYMMDD` - _required_ - dateToYYYYMMDD

### Count difference of strains, by qtl inheritance type, for specified species and date range

*Tags:* `Statistics`

#### Input Parameters
* `speciesTypeKey` - _required_ - speciesTypeKey
* `dateFromYYYYMMDD` - _required_ - dateFromYYYYMMDD
* `dateToYYYYMMDD` - _required_ - dateToYYYYMMDD

### Count difference of retired objects, by type, for specified species and date range

*Tags:* `Statistics`

#### Input Parameters
* `speciesTypeKey` - _required_ - speciesTypeKey
* `dateFromYYYYMMDD` - _required_ - dateFromYYYYMMDD
* `dateToYYYYMMDD` - _required_ - dateToYYYYMMDD

### Count difference of strain types, for specified species and date range

*Tags:* `Statistics`

#### Input Parameters
* `speciesTypeKey` - _required_ - speciesTypeKey
* `dateFromYYYYMMDD` - _required_ - dateFromYYYYMMDD
* `dateToYYYYMMDD` - _required_ - dateToYYYYMMDD

### Count difference of withdrawn objects, by type, for specified species and date range

*Tags:* `Statistics`

#### Input Parameters
* `speciesTypeKey` - _required_ - speciesTypeKey
* `dateFromYYYYMMDD` - _required_ - dateFromYYYYMMDD
* `dateToYYYYMMDD` - _required_ - dateToYYYYMMDD

### Count difference of external database ids, for specified species and date range

*Tags:* `Statistics`

#### Input Parameters
* `speciesTypeKey` - _required_ - speciesTypeKey
* `dateFromYYYYMMDD` - _required_ - dateFromYYYYMMDD
* `dateToYYYYMMDD` - _required_ - dateToYYYYMMDD

### getTermStats

*Tags:* `Statistics`

#### Input Parameters
* `accId` - _required_ - accId
* `filterAccId` - _required_ - filterAccId

### Return all active strains in RGD

*Tags:* `Rat Strain`

### Return all active strains by position

*Tags:* `Rat Strain`

#### Input Parameters
* `chr` - _required_ - Chromosome
* `start` - _required_ - Start Position
* `stop` - _required_ - Stop Position
* `mapKey` - _required_ - RGD Map Key (available through lookup service)

### Return a strain by RGD ID

*Tags:* `Rat Strain`

#### Input Parameters
* `rgdId` - _required_ - RGD ID of the strain

## License

**flow**ground :- Telekom iPaaS / mcw-edu-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
