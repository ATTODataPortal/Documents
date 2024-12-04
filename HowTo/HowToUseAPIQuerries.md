# Introduction on how to use API’s to retrieve datasets for using in analyzing software

#

Authors: Marcus Guderle

Contact ATTO Data Management Team: <attodbm@mpi-mail.mpg.de>


## Table of content

[1. Overview](#1-overview)

[2. Application of APIs](#2-application-of-apis)

- [2.1 Get an overview of datasets and their attachements](#21-get-an-overview-of-datasets-and-their-attachements)
- [2.2 Add attachements to datasets](#22-add-attachements-to-datasets)
- [2.3 Get a list of dataset ids](#23-get-a-list-of-dataset-ids)
- [2.4 Add datasets via API](#24-add-datasets-via-API)
- [2.5 Get information about data quality](#25-get-information-about-data-quality)
- [2.6 Download dataset via dataset id](#26-download-dataset-via-dataset-id)
- [2.7 Get information about data statistics](#27-get-information-about-data-statistics)
- [2.8 Get a list of datasets with metadata](#28-get-a-list-of-datasets-with-metadata)
- [2.9 Get metadata of a dataset via dataset id](#29-get-metadata-of-a-dataset-via-dataset-id)
- [2.10 Get a list of data structure ids](#210-get-a-list-of-data-structure-ids)
- [2.11 Get data structure via data structure id](#211-get-data-structure-via-data-structure-id)

[3. rBExIS](#3-rBExIS)

- [3.1 Setup rBExIS](#31-Setup-rBExIS)
    - [3.1.1 Download rBExIS package and create R-project](#311-download-rBExIS-package-and-create-R-project)
    - [3.1.2 Install rBExIS package](#312-install-rBExIS-package)
- [3.2 Application of rBExIS](#32-application-of-rBExIS)
    - [3.2.1 Get a list of dataset ids](#321-get-a-list-of-dataset-ids)
    - [3.2.2 Import dataset via dataset id](#322-import-dataset-via-dataset-id)
    - [3.2.3 Get a list of datasets with metadata](#323-get-a-list-of-datasets-with-metadata)
    - [3.2.4 Get metadata of a dataset via dataset id](#324-get-metadata-of-a-dataset-via-dataset-id)
    - [3.2.5 Get a list of data structure ids](#325-get-a-list-of-data-structure-ids)
<br>

## 1 Overview

<p align="justify">
The term API is the short form of "application programming interface". The use of APIs offers a tool to create an interface between an analysis software like R or a browser and the database, where the content is dynamically integrated into the own program. The API is a machine-readable interface tailored for software.
Particularly in the ATTO Data Portal, data sets and metadata information can be exchanged quickly in a particularly easy to process and reduced form by using APIs.
</p>
<br>

> `Note:` Only primary data can be queried via APIs to which the respective user has read permission.
In the following HowTo we first give an introduction to the API usage on the ATTO Data Portal. It shows how the APIs can be tested and applied and how the queries are made via the browser.
<br>
<br>

<p align="justify">
In the second part rBexis is introduced, an R-Package which has been developed especially for querying data sets between R and Bexis instances.
</p>
<br>

## 2 Application of APIs

<p align="justify">
Every registered user can use APIs and gets a personal token, which is directly linked to the user account. This token is needed to query datasets via APIs. You can find the respective token by clicking on your username in the upper right corner of the menu. A drop-down menu will open where you can click on "Token" (Figure 1).
</p>
<br>

![](https://github.com/ATTODataPortal/Documents/blob/4487b678e436a059e6770863e8c10194dba1fadf/images_upload/image_API1.png?raw=true)*Figure 1: Drop-down menu for personal user “Profile”, “Token”, “Api” and to log off.*
<br>
<br>

<p align="justify">
If you click on "Token" a new page will open with your personalized 65 character long token (Figure 2). First copy it into the cache.
</p>
<br>

![](https://github.com/ATTODataPortal/Documents/blob/4487b678e436a059e6770863e8c10194dba1fadf/images_upload/image_API2.png?raw=true)*Figure 2: Personalized 65 character long token*
<br>
<br>

<p align="justify">
As mentioned earlier, APIs provide an interface to the database, which is mainly text-based. While using special software/online applications, the application of APIs can also be visualized. The Swagger UI, which can be used via any browser software, was integrated for testing requests of the ATTO APIs. Swagger can be accessed from the user drop-down menu by clicking on "API" (Figure 3).
</p>
<br>

![](https://github.com/ATTODataPortal/Documents/blob/4487b678e436a059e6770863e8c10194dba1fadf/images_upload/image_API3.png?raw=true)*Figure 3: Link to the Swagger UI for browser application is provided in the user drop-down menu via “API”*
<br>
<br>

<p align="justify">
You will now be directed to the ATTO-Swagger interface. First you have to copy your token (Figure 2) into the field "Jason Web Token" and click on the "Explore" button (Figure 4).
</p>
<br>
<p align="justify">
On the Swagger page you can see three categories: Data, Metadata and Structures. Click on the category to open the submenu. In each category there are two requests; one for a list of information about all existing datasets and one for information for specific datasets via the respective ID. The respective operations can be expanded either by clicking on "Get", on "/api/..." or on "Expand Operations".
</p>
<br>

![](https://github.com/ATTODataPortal/Documents/blob/dad768bfaa2b6c11323c4c74163e56d49a801531/images_upload/image_API4.png?raw=true)*Figure 4: Categories for API queries on the ATTO Swagger Browser Interface*
<br>
<br>

### 2.1 Get an overview of datasets and their attachements