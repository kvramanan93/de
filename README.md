# de

Orchestration tools 
Meddelion architecture

Data sourced from Github -> Ingestion(Azure Datafactory) -> dataStorage(Bronze Medal) -> Transformation(databricks) -> Synapse(Serving)(Gold Layer) -> Reporting (PowerBi)



Data source -  Adv works -> full of tables , joins, lookups, transformations


Azure - Tags - to categorize resources like billing structure , billing details we add tags for these

data redundancy - replicates data within diff geographies (GeoRed Storage)
LRS - store replica of data in same datacenter

Q - By default - blob storage acc not data lake

Blob vs datalake - In both acc we got containers  and within these we save our files, But we cant create heirarchy of folders in blob storage. 

datalake -> datafactory -> containers

Pipeline - need source and destination 