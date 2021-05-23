# data_modeling_with_Apache_Cassandra

Hi,

In this project, I tried to create an ETL pipeline using Apache Cassandra. 

## Technology
The work is performed in Jupyter Notebook using Python 3. The packages used are Pandas, csv, cassandra, re, os, and glob. There is a custom function defined in order to gain the ability to see the CQL results neatly.

## Data
The data is made up of user, session, and song data related to a music application.

## Methodology and Structure
The process starts as it gathers the seperated event files under one csv file. Then it creates a cluster and a connection to a Cassandra instance. That is followed by a keyspace formation and setting. Thirdly, the tables are created with the focus of the exercise being on the PRIMARY KEY selection. Logic/conditions clarified by the query are defined right above the table creation cell for each case. That's being said , we address 3 cases. The PRIMARY KEY structure is discussed under each case. The next part is loading of the data into the table with INSERT method. And, the final sections are about verification of the cases and the dropping of tables along with the closing of the session.



Kind regards, 

Atahan
