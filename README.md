# Azure Data Lake Storage (Gen 2)

**Data Lake Storage Gen 2** is the best storage solution for big data analytics in Azure. With its Hadoop compatible access, it is a perfect fit for existing platforms like Databricks, Cloudera, Hortonworks, Hadoop, HDInsight and many more.


## Exploration

<img src="/pictures/adsl.png" title="adsl"  width="800">

With the above settings, you only have a regular **Storage Account**. In order to get an ADLS out of this, you need to go to the *advanced settings* and enable h*ierarchical namespace*.

<img src="/pictures/adsl2.png" title="adsl"  width="800">

Everything that you get in the end is pretty much the same that you get for a regular **Blob Storage**.

<img src="/pictures/adsl3.png" title="adsl"  width="800">

The only difference lays in the containers. You now have access management (read, write, execute) for each file :

<img src="/pictures/access_management.png" title="access management"  width="800">

You can add a user to a group :

<img src="/pictures/access_management2.png" title="access management"  width="800">

You can also do the same at the container level :

<img src="/pictures/access_management3.png" title="access management"  width="800">

You can also create folders :

<img src="/pictures/create_folder.png" title="create folder"  width="800">


## Power BI

**Power BI** can connect to ADLS in two ways. 

1. Get Data / Azure / Azure Datalake Storage Gen 2

<img src="/pictures/powerbi.png" title="power BI"  width="800">

You need the full url address for **Azure Datalake Storage Gen 2**. You will find it in the *Endpoint* section :

<img src="/pictures/powerbi2.png" title="power BI"  width="800">


2. Get Data / Azure / Azure Blob Storage

Just provide the name of the storage account. You can grab the key in the **Access Keys** section.

<img src="/pictures/powerbi3.png" title="power BI"  width="800">

Clic *Transform Data*

<img src="/pictures/powerbi4.png" title="power BI"  width="800">

