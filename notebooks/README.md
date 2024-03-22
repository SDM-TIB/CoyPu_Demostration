# Federated Exploration of Resilient Supply Value Chains - Demo Notebooks

## Data Sources, Ontology, and Endpoints 

### Datasets

- [WorldBank](https://www.worldbank.org/en/home)
- [ICEWS](https://dataverse.harvard.edu/dataverse/icews) - Integrated Crisis Early Warning System
- [GLEIF](https://www.gleif.org/en) -  Global Legal Entity Identifier Foundation
- [Country Data](https://github.com/lukes/ISO-3166-Countries-with-Regional-Codes/blob/master/all/all.csv)

### Ontology

- [Coy-Ontology](https://coypu-project.gitlab.io/coy-documentation/)

### Public Endpoints

- [WorldBank](https://labs.tib.eu/sdm/worldbank_endpoint/sparql/)
- [Wikidata](https://query.wikidata.org/)
- [DBpedia](https://dbpedia.org/sparql)
- [ICEWS](https://labs.tib.eu/sdm/icews_endpoint/sparql)
- [GLEIF](https://labs.tib.eu/sdm/lei_endpoint/sparql)

### Private Endpoints
- [Skynet (Private KG)](https://skynet.coypu.org)

## Demo Endpoints

### [SHACL-ACL and DeTrusty Demo](./shaclacl_detrusty.ipynb)

This demo illustrates the execution of federated queries and queries with access registrictions. This demo uses two tools: SHACL-ACL and Detrusty.

- SHACL-ACL
  - The demo generates a virtual to which multiple of queries are executed over. Additionally, a series of SHACL shapes defined to registric the access to virtual knowledge graph. Therefore, some of the quieries will be denied acces.
- DeTrusty
  - The demo creates a federation of endpoints comprised of CoyPu KG (i.e., Skynet), Wikidata, and DBpedia. Afterwards, a series a queries are executed over the federation of endpoints.

### [SDM-Tools Demo](./shaclacl_detrusty.ipynb)

This demo illustrates data preprocessing, knowledge graph creation, and storage of datasets. For this demo three tools are used: Leibniz Data Manager, Dragoman, and SDM-RDFizer.

- Leibniz Data Manager
  - A series of steps are given to aid the user to create a dataset in the Leibniz Data Manager. The user must create an account and user in the [Leibniz Data Manager](https://service.tib.eu/ldmservice/) beforehand.
- Dragoman
  - RML+FnO [mappings](../mappings) and [configuration files](../configs/config_func.ini) are made available for the execution of [Dragoman](https://github.com/SDM-TIB/Dragoman).
- SDM-RDFizer
  - RML [mapping](../mappings) and [configuration files](../configs/config.ini) are made available for the execution of SDM-RDFizer.