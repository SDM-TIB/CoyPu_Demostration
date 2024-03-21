# CoyPu Demostrations

Supported dataset for RDF KG creation (icews, lei, country and worldbank)

Install packages and run notebooks in `notebooks` folder

```shell
pip install -r requirements.txt
```

## Make Commands
```
help                 dataset availabe for make commands icews, lei, country
load                 load data (e.g. make load data=icews )
upload               upload data, location tib, skynet (e.g. make upload data=icews )
preproc              preprocess data (e.g. make preproc data=icews )
semantify            semantify data or create rdf KG ( e.g. make semantify data=icews )
clean-kg             delete sematified data ( e.g. make clean-kg data=icews )
clean-data           delete downloaded data ( e.g. make clean-data data=icews )
clean-all            deleted downloaded data and rdf data (e.g. make clean-all data=icews)
install              install required packages
```