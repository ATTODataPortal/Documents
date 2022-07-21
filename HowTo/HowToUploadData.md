
# Introduction on how to create and upload data in the ATTO Data Portal

#

Authors: Marcus Guderle

Contact ATTO Data Management Team: <attodbm@mpi-mail.mpg.de>


## Table of content
<br>

[1. Overview](#1-overview)

[2. Defining a data structure](#2-defining-a-data-structure)

[3. Data collection](#3-data-collection)

- [3.1 Create a dataset](#31-create-a-dataset)
- [3.2 Metadata](#32-fill-out-metadata)
- [3.3 Upload primary data](#33-upload-primary-data)
- [3.4 Import primary data](#34-mport-primary-data)
- [3.5 Push big file](#35-push-big-file)
- [3.6 Add data or update dataset](#36-add-data-or-update-dataset)
- [3.7 Add attachments to datasets](#37-add-attachments-to-datasets)
- [3.8 Copy Metadata of an existing dataset](#38-copy-Metadata-of-an-existing-dataset)

[Appendix](#appendix)
<br>

## 1 Overview
<br>

Under Collect you find tools to create datasets. The basic functions are (Figure 1):

- Create Dataset
- Upload Data
- Import Data
- Push Big Files

![](https://github.com/ATTODataPortal/Documents/blob/9d49bebc0f08b7326011e42231c4d93f9115fc41/images_upload/image_Upload_1.png)*Figure 1: Functions of the upload menu*
<br>

## 2 Defining a data structure
<br>
Data structures contain all variables, which are part of the dataset to be uploaded. Prior to uploading a dataset, the data structure has to be defined in order to have a template for the upload process. Defined data structures can be used and should be used multiple times for long term data. This prevents that the same variable is defined several times with different names and units (e.g. time in seconds and in Universal time). This is essential to enable an extensive and consistent data management as well as exact search results. For this reason, the definition of data structures will be done by the data management team.
<br>

![](https://github.com/ATTODataPortal/Documents/blob/95fe99f01d5c3168ca0ba65b4ea2b5fa0b440d67/images_upload/image_Upload_2.png)*Figure 2: Example of a data structure*
<br>

It is possible to create data structures for tabular (structured) data such as Excel tables, CSV-Files, etc. and for files such as images, videos, etc. Please send a request for a data structure including the header of your dataset with a clear description of each variable to the data management team (<attodbm@mpi-mail.mpg.de>). The respective data structure will be created according to the example in Figure 1. The data management team will send you an Excel Template similar to Figure 2, which can be filled with the respective data and used for their upload.
To open this template, you have to enable macros. Macros automate frequently-used tasks. Depending on what Microsoft version you use, enable or disable macros is a bit different. Macro security settings are generally located in the Trust Center.

Please insert the data in the respective column below the grey shaded area (Figure 3).
<br>

![](https://github.com/ATTODataPortal/Documents/blob/d1ec06e6fe2f67b1e3bb24198d887234a6a198fb/images_upload/image_Upload_3.png)*Figure 3: Example of an Excel Template for the data structure in Figure 2*
<br>

## 3 Data collection
<br>

The Data Collection Module provides tools to create new datasets, enter metadata, upload data to the system, and import metadata structures. There are some workflows available under the “Collect” tab (see Figure 1):

- Create Dataset
- Upload Data
- Import Data
- Push Big File

Creating a new dataset with tabular data includes the following steps:
<br>

1.  [Create a new dataset](#31-create-a-dataset)
2.  [Fill out metadata](#32-fill-out-metadata)
3.  [Upload primary data](#33-upload-primary-data)
4.  [Add links to other datasets and publications (optional)](#36-add-attachments-to-datasets)
5.  [Add attachments (optional)](#36-add-attachments-to-datasets)
<br>

### 3.1 Create a dataset
<br>

To create a new dataset, please click on the “Collect” tab and choose “Create Dataset” (Figure 1). You will be directed to an upload wizard, which leads you through the process step by step. When you hover the mouse pointer over the orange “Select” buttons in the wizard (see Figure 4) an information field about the respective option will appear.

If you want to upload a new dataset, please select “New Dataset” in the “Dataset” field. In case you want to use an already existing dataset (for example form your time series), you have two options to make a selection. First, you can click on the “Select from table” button and choose the respective dataset. Second, you can click on the text field above the “Select from table” button and choose the preferred dataset from the drop-down menu.
In the next step you can choose whether to upload a new tabular data or a file. In both cases a new data structure will be created. In case you have been assigned a data structure by the data management team, please use the option "Existing tabular data structure" or "Existing file data structure" and select the appropriate data structure from the drop-down menu. The next step is to define the metadata structure. In our case there is only one predefined one called "ATTO".
<br>

![](https://github.com/ATTODataPortal/Documents/blob/747a480ae8070b162e6c014539f101972b7edde7/images_upload/image_Upload_4.png)*Figure 4: Overview of Data Collection Wizard*
<br>

In order to continue the data creation process please click the “Next” button. You will be directed to the metadata form, which will be explained in the following section.
<br>

### 3.2 Fill out metadata
<br>

The following section introduces the metadata schema for the ATTO consortium and gives an over-view of the individual information required.
In case you want to upload a new dataset to an existing data structure and comprehansive metadata information have thus already been uploaded previously, the respective metadata sheme can be requested from the data management team. You will receive a .xml file, which can be imported via the "Import" button (see Figure 5). You then have to change the appropriate information for your new dataset that differ from previous ones, such as collection dates, layers etc.
<br>

![](https://github.com/ATTODataPortal/Documents/blob/4cf133808ed0268b485c39ec934623c1d4503641/images_upload/image_Upload_5.png)*Figure 5: Overview of metadata form*
<br>

The metadata structure contains four main sections:

- Dataset Level Metadata: Basic information on the data like title, abstract, owner, methods etc.
- Environmental Level Metadata: Detailed georeferenced information on the location, where the data were collected.
- Published In: DOI if dataset is already published in a data repository or in context of a scientific publication.
- Project: Information of the project, in which context the dataset was collected, including funding for the project.

Some fields are a free-text field, which have to be filled in by the data creator. Others have, drop-down menus and an autocomplete function that helps to fill in the form swiftly.
<br>

> *Note*: Completely filled metadata are essential for finding datasets within the ATTO data portal and allows an easy publishing process through the Max Planck Digital Library (MPDL).
<br>


Table 1 in the Appendix gives an overview and explanation of each variable of the metadata form. You also get this information by hovering the mouse pointer over the respective variable name left side of the text boxes and the green header of the subsections. All fields marked with a red asterisks * are mandatory for a valid metadata form.

After you complete the form, you can validate (see Figure 6) the entries and the system will give you further information in case any entries are wrong or whether more entries are required.
<br>

![](https://github.com/ATTODataPortal/Documents/blob/ea686fcf7c46edb7022a6be3b4071678f0db6214/images_upload/image_Upload_6.png)*Figure 6: Bottom of Metadata form with "Validate" and “Save” button*  
<br>

When you completed and validated the metadata form, please click “Save” in order to finish the creation of the dataset. If there are metadata entries missing, the window shown in Figure 7 will pop up. In this case it is recommended that you click on “Cancel” to fill in the missing. However, while clicking on the “OK” button, the metadata form will be saved and you have the possibility to edit the form at a later point of time – even after primary data are already uploaded.

> *Note*: After a dataset is published with an assigned DOI, do not change any part of the dataset. Please contact the data management team (attodbm@mpi-mail.mpg.de) for help.
<br>

![](https://github.com/ATTODataPortal/Documents/blob/992edd46cf0c43b59363d0d9b9c3540b0e03acd2/images_upload/image_Upload_7.png)*Figure 7: Warning if metadata information is missing*
<br>

### 3.3 Upload primary data
<br>

After the metadata form is saved, you will be automatically directed to the top of the page where you will find a link to the Primary Data and thus the Data Upload Wizard (see Figure 8 & 9). If you want to upload your data as tabular data (.xlsm, .txt, .csv) now, please click on the link. The term "Tabular data" is used for all datasets where the internal structure of the data is "known" to the system. For example, in a data table the header, which defines the columns (i.e. variables) is the structure of the data. Before uploading/importing data to the system the data structure needs to be created by the data management team (see also paragraph 2 - Defining a data structure).
<br>

![](https://github.com/ATTODataPortal/Documents/blob/3fa25a00e84451d35694b17166d6a9830d5932b7/images_upload/image_upload_8.png)*Figure 8: Redirection to the link of the Primary Data*
<br>

![](https://github.com/ATTODataPortal/Documents/blob/3fa25a00e84451d35694b17166d6a9830d5932b7/images_upload/image_upload_9.png)*Figure 9: Data Upload Wizard*
<br>

First, please select an existing file containing your data. You can either select a file from your local computer or a file that has been uploaded to the server prior to starting the Data Upload Wizard (see Figure 10). The second option is designed for files larger than 4 MB that may take several minutes to transfer. The wizard supports file formats of Microsoft Excel (.xlsm) or ASCII (.txt, .csv). Once a file was successfully selected, click the "Next" button and proceed to the next step.
<br>

![](https://github.com/ATTODataPortal/Documents/blob/8d8ee8546c325562dd98deb4676b98b804a9cd56/images_upload/image_upload_10.png)*Figure 10: Data Upload Wizard - file selection*
<br>

For all ASCII files you need to provide information on the formatting and file structure (Figure 11).

- Separator: Please choose which separator is used to separate data values from each other in the ASCII file.
- Decimal: Please choose the punctuation, which is used for decimal values. This is depending on your language settings of your computer.
- TextMarker: Please choose how text is marked in your data file.
- Orientation: Please choose if your data is oriented column-wise or row-wise.
- Offset: Define whether your dataset contain empty rows or columns on top or to the left before the header and the actual data values start.
- Variables: Please define the row/column where the header starts. Usually, datasets contain of a header, which defines variable names, types etc.
- Data: Please specify the row/column where the primary data starts.

More information can also be found in the online Help via “Data Collection”.
<br>

![](https://github.com/ATTODataPortal/Documents/blob/2617502546188b9e330f8b817063065a9a046759/images_upload/image_upload_11.png)*Figure 11: Data Upload Wizard - file information*
<br>

Next, the created data set must be specified once again, to which the data to be uploaded should be assigned.
<br>

![](https://github.com/ATTODataPortal/Documents/blob/2617502546188b9e330f8b817063065a9a046759/images_upload/image_upload_12.png)*Figure 12: Data Upload Wizard - dataset information*
<br>

After defining the required information, click “Next” and you are asked to validate your dataset (Figure 13). In this step, the system checks whether the header information and the number of variables matches with the predefined data structure. If this is the case, you will see the green stroke “Validated!!” on the top of the page. Please click “Next” to get a summary of your created dataset and to finalize the upload process by clicking “Finish”.
<br>

![](https://github.com/ATTODataPortal/Documents/blob/2617502546188b9e330f8b817063065a9a046759/images_upload/image_upload_13.png)*Figure 13: Data Upload Wizard - Validation*
<br>

In case you want to upload your primary data at a later point of time and assign them to your prior defined metadata, you can use the "Upload" option via the "Collect" tab (Figure 1). Here you can chose as well, whether you want to upload tabular data or files like images or other data associated to your dataset (.avi, .bmp, .csv, .dbf, .doc, .docx, .gif, .jpg, .jpeg, .mp3, .mp4, .pdf, .png, .shp, .shx, .tif, .txt, .xls, .xlsm, .xlsx, .xsd, .zip). The uploading process is similar to the application of the Upload Data Wizard described above.
<br>

### 3.4 Import primary data
<br>

Using the Import Data Wizard is another possibility to create a dataset including metadata in one workflow. Please click "Import Data" via the “Collect” tab (Figure 1). After you selected a file from your local computer or a prior uploaded file, you have to choose the "ATTO" metadata schema. The title is by default the name of your file, but can be changed in the textbox "Title" (Figure 14).
<br>

![](https://github.com/ATTODataPortal/Documents/blob/29f2f19fd71c170a0358e3fbcd9c0724d7a351ae/images_upload/import_data_1.png)*Figure 13: Import Data Wizard*
<br>

![](https://github.com/ATTODataPortal/Documents/blob/29f2f19fd71c170a0358e3fbcd9c0724d7a351ae/images_upload/import_data_2.png)*Figure 14: Define metadata schema & title*
<br>

You will be directed to a table, which represents your selected file. Here you can define which parts of the file contain the variables/header and which part are the primary data. Please select the row with variables/header and click the "Header" button (see Figure 15). The selected part will be highlighted in red. In order to specify the data, select multiple rows which contain the primary data and click the "Data" button (see Figure 15). If you want to skip some parts of your data you can just mark the rows above and below the respective parts. With the "Expand Selection" button you can expand the last selection of your data to the last row of the file. This is  recommended for large datasets
<br>

![](https://github.com/ATTODataPortal/Documents/blob/29f2f19fd71c170a0358e3fbcd9c0724d7a351ae/images_upload/import_data_3.png)*Figure 15: Select areas in the Import Data Wizard*
<br>

You also have the option to import data from another worksheet of your file with the "Change Worksheet" button on the right side. Please note that only data from one sheet can be uploaded at a time.

When you finished the selection, click the "Next" button to proceed to the verification step, where you have to define the units and datatypes of the variables in the dataset you want to upload (Figure 16). A table with a dropdown menu shows you the variables in the dataset and provides you suggestions for the respective definition of units and datatypes based on other already uploaded datasets. While choosing one of the suggestions, the respective unit and datatype are automatically filled in. You also can define these attributes by yourself by entering free text. With the "Validate" button (see Figure 16) you can verify whether the selected datatypes are suitable for the dataset or if you have to adjust a particular specification.

With a click on the "Next" button you can proceed to a summary of your upload process, which provides an overview of your dataset. Please click the "Finish" button and the data structure and the dataset will be created. In the next step, you will be redirected to the new dataset and you can fill in the metadata form as described in section 3.2 Metadata.
<br>

![](https://github.com/ATTODataPortal/Documents/blob/29f2f19fd71c170a0358e3fbcd9c0724d7a351ae/images_upload/import_data_4.png)*Figure 16: Verification process in the Import Data Wizard*
<br>

### 3.5 Push big file
<br>

In case you want to upload a big file, you can use the "Push Big File" option via the "Collect" tab. Datasets with the following formats are supported: .avi, .bmp, .csv, .dbf, .doc, .docx, .gif, .jpg, .jpeg, .mp3, .mp4, .pdf, .png, .shp, .shx, .tif, .txt, .xls, .xlsm, .xlsx, .xsd, .zip.
<br>

![](https://github.com/ATTODataPortal/Documents/blob/2cbd5fed32ddd6942e83b9ea39ca2421981502e3/images_upload/push_big_file_1.png)*Figure 17: Push Big File*
<br>

Each registered user can upload files to a personal folder where files are stored temporary. An overview of these files is given on the left side of the Push Big File Wizard (see Figure 17). You can delete these files by clicking on the small bin next to the file name. For uploading a dataset, please click on the “Select” button to select a file from your local computer and then click “Push” .
<br>

### 3.6 Add data or update dataset
<br>

The system allows to add data to an already existing dataset or to update datasets in case the processing standard was updated. The first case might mainly apply for continuous measurements of time series like temperature profiles or radiation etc. and allows extending the already uploaded time series with the fresh data.

Please click on the "Collect2 tab in the main menu (see Figure 1) and choose "Upload Data". In the Upload Data Wizard you first have to choose whether your data are tabular data or a file.
<br>

![](https://github.com/ATTODataPortal/Documents/blob/b89a6644b8f2850e6c3ce984b456b09b9604c58d/images_upload/update_data_1.png)*Figure 18: Upload Data Wizard*
<br>

The file selection is same as described in section 3.3 Upload primary data. After you selected your data/file either from your local computer (or from the server in case it was uploaded before) the file information have to be defined (see section 3.3 Figure 11). In the next step, please specify the dataset to which the uploaded data should be added. A list of all datasets (dataset-ID and title) is shown in a dropdown menu (Figure 19).
<br>

![](https://github.com/ATTODataPortal/Documents/blob/b89a6644b8f2850e6c3ce984b456b09b9604c58d/images_upload/update_data_2.png)*Figure 19: Upload Data Wizard - specify dataset*
<br>

Click next and define the primary keys of the dataset to be uploaded. Please check the selected variables before clicking next. In case all primary keys are defined accordingly, they are displayed in green in the upper right corner of the webpage. 

Click "Next" and you are asked to validate your dataset. In this step, the system checks whether the header information and the number of variables matches with the predefined data structure. If this is the case, you will see the green stroke "Validated!!" on the top of the page. Please click "Next" to get a summary of your created dataset and to finalize the upload process by clicking "Finish".
<br>

> *Note:* A dataset ID and a dataset version ID are assigned to the uploaded datasets. During each change of the metadata and/or the primary data, the dataset version ID is updated while the dataset ID is always the same. However, all dataset versions are stored on the server. Furthermore, while downloading data, the dataset version ID is taken into account. Please consider the change of datasets before publishing the dataset with assigned DOI since the link to the DOI has to be updated as well after this process. Further information regarding data publication can be found in a separate document.
<br>

### 3.7
<br>
