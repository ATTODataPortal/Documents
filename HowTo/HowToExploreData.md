# Introduction on how to explore uploaded data on the ATTO data portal

#

Authors: Marcus Guderle

Contact ATTO Data Management Team: <attodbm@mpi-mail.mpg.de>


## Table of content

[1. Search User Interface](#1-search-user-interface)

[2. View and explore datasets](#2-view-and-explore-datasets)

[3. Request Primary Data](#3-request-primary-data)

[4. Download Primary Data](#4-download-primary-data)

[5. Attachments](#5-attachments)

[6. Filter Primary Data](#6-filter-primary-data)


## 1 Search User Interface

<p align="justify">
After logging into the ATTO data portal, you will be automatically directed to the Search User Interface (UI, Figure 1). You can navigate back to the search function from any other subpage by clicking "Search" in the menu bar at the top of the site. By default, the search shows all available datasets. By activating the check mark "public only", only publically available datasets are displayed (Figure 2).
</p>
<br>
<p align="justify">
The main nodes of the Search UI are based on metadata entered. Thus, completely filled metadata are essential for finding datasets within the ATTO data portal.
</p>
<br>

![](https://github.com/ATTODataPortal/Documents/blob/e9874074da2d9d6e2c3d7a853bafbe443bc1eb40/images_upload/image_explore1.png?raw=true)*Figure 1: Search User Interface showing only data which are public*
<br>
<br>

<p align="justify">
The Search UI contains of the following features, which help to filter uploaded data according to owners, location, keywords, etc.:
</p>
<br>

- <p align="justify">Categories/Facets: The main categories like “Person”, “Location”, etc. are based on main metadata entries. The numbers next to the categories indicate the number of existing datasets in the ATTO data portal with the respective entries.</p>

- <p align="justify">Properties: This function allows to use predefined dropdown components to filter datasets according to properties. There is only one possible choice for every component. Results and facets are updated accordingly.</p>

- <p align="justify">Free text search: In the free text search, you can either search for keywords in all predefined categories or you can choose a specific category from the dropdown menu on the left. It uses autocomplete for predicting words and phrases once three letters are entered.</p>

- <p align="justify">Filter: Filter datasets in order to display records, which match certain criteria. The filter can be activated/deactivated by clicking on the filter-symbol next to the respective category. You can filter data for self-defined values and choose different queries like “Is equal to”, “Is not equal to”, “Starts with”, “Contains”, etc.</p>

- <p align="justify">Results: The matching results are displayed in a table view, where basic functions like filtering, sorting, paging are available in the header of the table. By clicking right on the header, you can choose the visibility of the individual columns. By clicking on the respective header caption, the sorting function is activated. You also can define the number of displayed datasets per page via the grey box at the top and the bottom of the table.</p>
<br>
<br>

![](https://github.com/ATTODataPortal/Documents/blob/e9874074da2d9d6e2c3d7a853bafbe443bc1eb40/images_upload/image_explore3.png?raw=true)*Figure 2: Search User Interface*
<br>
<br>

## 2. View and explore datasets

<p align="justify">
Details of each dataset can be found by clicking on the small eye-icon in the very right column of the dataset table view (see Figure 3).
</p>
<br>

![](https://github.com/ATTODataPortal/Documents/blob/df50ecb1035772b78fd33f0f08664019684ab9fc/images_upload/image_explore4.png?raw=true)*Figure 3: Directing to detailed information of specific datasets*
<br>
<br>

<p align="justify">
You will be directed to the main page of the chosen dataset, where details on Metadata, Primary Data, Data Structure, Dataset Permissions, publication and attachments to the respective dataset are given in different tabs (see Figure 4). Each user is allowed to see the metadata of each dataset independent of the respective rights as well as download the metadata as html- or XML-format via the “Download Metadata”-button. If users have rights on the dataset, they are allowed to edit and copy the metadata, to check and download primary data, to see the data structure and dataset permission, and to click on the “Publish”-tab. However, in case users do not have rights on the respective dataset, only metadata and the data structure can be seen, all other tabs are greyed out (Figure 4).
</p>
<br>

![](https://github.com/ATTODataPortal/Documents/blob/8661af4872b94534e7ff25cb0502c25d0f251c05/images_upload/image_explore5.png?raw=true)*Figure 4: Overview of dataset details and metadata information*
<br>
<br>

<p align="justify">
Figure 5 shows the “Data Structure” tab, which gives an overview of the variables of the selected dataset. Information like variable name, ID, a short name, a description of the respective variable, unit and data type are given. The data structure has to be defined by the data manager before uploading data. A detailed description on this workflow will be given in the document “03_Introduction how to create dataset and upload data”.
</p>
<br>

![](https://github.com/ATTODataPortal/Documents/blob/38109ea9757c2b8b82773a00cf89f0f2e0d4573c/images_upload/image_explore45.png?raw=true)*Figure 5: Overview of data structure*
<br>
<br>


## 3. Request Primary Data

<p align="justify">
In case you are interested in a specific dataset, which is not publicly available, you can request this specific dataset via the request button (Figure 4 & 5). By filling in the intention of data usage and clicking the request button, a request is made to the data owners, who are informed of the request by e-mail. A list of the open requests will be displayed in the dashboard of the respective data owner. Once the data owner accepts the request, the user who made the request is automatically granted read and download rights.
</p>
<br>

## 4. Download Primary Data

<p align="justify">
Datasets, which are open for consortium members or which are already published with an assigned DOI, can be freely downloaded without sending a request to the data owners. To do so, click on the “Primary Data” tab where you find the activated “Download” buttons. You can download the data as an Excel file, as comma separated file or as tab separated text file (Figure 6) or as zipped package, which includes the primary data (either as template file, excel file, csv file or as text file), the data structure, the metadata as html file and the respective attachments ( Figure 6). To get an overview of all columns of a large dataset you can click on the option "Fit table to screen".
</p>
<br>

![](https://github.com/ATTODataPortal/Documents/blob/8661af4872b94534e7ff25cb0502c25d0f251c05/images_upload/image_explore_5.png?raw=true)*Figure 6: Overview of primary data with activated download buttons*
<br>
<br>

## 5. Attachments

<p align="justify">
The attachment-tab (Figure 7) allows users, who have upload rights to dataset to attach files such as descriptions, images, etc. to the respective dataset. Other users can only see or download these attachments.
</p>
<br>

![](https://github.com/ATTODataPortal/Documents/blob/38109ea9757c2b8b82773a00cf89f0f2e0d4573c/images_upload/image_explore6.png?raw=true)*Figure 7: View and download attachments to datasets*
<br>
<br>

## 6. Filter Primary Data

<p align="justify">
In the Primary data view it is possible to filter the data by column or by row or both. In order to filter specific columns the mouse pointer must be navigated to one of the funnel symbols and a right click opens a drop down menu with all column names. These can now be activated or deactivated with a check mark (Figure 8).
</p>
<br>

![](https://github.com/ATTODataPortal/Documents/blob/38109ea9757c2b8b82773a00cf89f0f2e0d4573c/images_upload/image_explore7.png?raw=true)*Figure 8: Filter function by columns*
<br>
<br>

<p align="justify">
A left click on the respective funnel symbol opens another menu for filtering the rows by data. This filter works via different database queries like “Is equal to”, “Is greater than or equal to”, “Is greater than”, “Is less than or equal to” and so on (Figure 9).
</p>
<br>

![](https://github.com/ATTODataPortal/Documents/blob/38109ea9757c2b8b82773a00cf89f0f2e0d4573c/images_upload/image_explore8.png?raw=true)*Figure 9: Filter function by rows*
<br>
<br>

<p align="justify">
The respective filtered data can be downloaded via the Download button either as Excel or as text file (Figure 9 ). The “Download Dataset” button can be used to download the entire unfiltered dataset.
</p>
<br>