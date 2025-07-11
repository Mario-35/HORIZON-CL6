# HORIZON-CL6


The data structure is based on the ETL principle(Extract Transorm Load).

Three types of data have been identified :

    - The first are structured data that only need to be transformed into SensorThings format (https://www.ogc.org/standards/sensorthings/).

    - The second is semi-structured data, often extracted from Excel files, which require preparatory processing to structure them and then transform them in the same way as the previous data source.

    -The third and final data source is unstructured data, which requires a specific script or program to transform it and load it in SensorThings format.

All its data sources loaded in SensorThings format will constitute a different collection stored in different databases.

The use of OGC's STAC (https://stacspec.org/) to distribute these different SensorThings collections will be studied at a later date.

The use of the SensorThings API will enable data to be used and distributed via the tools already in place. Less effort will be needed to code and register the various tools and useful clients, and more effort will be needed to integrate specific scripts and an interface for ETL.
