# Data Management

The system stores each created workflow in a relational database (PostgreSQL), including unique identifiers for each case and the corresponding labels. Following annotation, labels are uploaded back to the PACS server. Detailed metadata, such as the Series Instance UID and other relevant attributes, are stored in the database.

The platform prepares the dataset for the self-configuring model by transferring data from the PACS server to the segmentation server, organizing the data, and setting up the computational environment and resource allocations.