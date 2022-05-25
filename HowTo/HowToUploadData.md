# Introduction on how to create and upload data in the ATTO Data Portal

#

Authors: Marcus Guderle

Contact ATTO Data Management Team: <attodbm@mpi-mail.mpg.de>


## Table of content

[1. Overview](#1-overview)

[2. Defining a data structure](#2-defining-a-data-structure)

[3. Data collection](#3-data-collection)

- [3.1 Create a dataset](#31-create-a-dataset)
- [3.2 Metadata](#32-metadata)
- [3.3 Upload primary data](#33-upload-primary-data)
- [3.4 Import primary data](#34-mport-primary-data)
- [3.4 Push big file](#34-push-big-file)
- [3.5 Add data or update dataset](#35-add-data-or-update-dataset)
- [3.6 Add attachments to datasets](#36-add-attachments-to-datasets)
- [3.7 Copy Metadata of an existing dataset](#37-copy-Metadata-of-an-existing-dataset)

[Appendix](#appendix)

## 1 Overview

Under Collect you find tools to create datasets. The basic functions are (Figure 1):

- Create Dataset
- Upload Data
- Import Data
- Push Big Files

![](https://user-images.githubusercontent.com/105857944/169483059-0a04acf5-2f6d-4e30-8759-5bfef30dc787.png)

Figure 1: Functions of the upload menu

## 2 Defining a data structure

Data structures contain all variables, which are part of the dataset to be uploaded. Prior to uploading a dataset, the data structure has to be defined in order to have a template for the upload process. Defined data structures can be used and should be used multiple times for long term data. This prevents that the same variable is defined several times with different names and units (e.g. time in seconds and in Universal time). This is essential to enable an extensive and consistent data management as well as exact search results. For this reason, the definition of data structures will be done by the data management team.



![](https://github.com/ATTODataPortal/Documents/blob/95fe99f01d5c3168ca0ba65b4ea2b5fa0b440d67/images_upload/image_Upload_2.png)

Figure 2: Example of a data structure


It is possible to create data structures for tabular (structured) data such as Excel tables, CSV-Files, etc. and for files such as images, videos, etc. Please send a request for a data structure including the header of your dataset with a clear description of each variable to the data management team (<attodbm@mpi-mail.mpg.de>). The respective data structure will be created according to the example in Figure 1. The data management team will send you an Excel Template similar to Figure 2, which can be filled with the respective data and used for their upload.
To open this template, you have to enable macros. Macros automate frequently-used tasks. Depending on what Microsoft version you use, enable or disable macros is a bit different. Macro security settings are generally located in the Trust Center.

Please insert the data in the respective column below the grey shaded area (Figure 3).


![](https://github.com/ATTODataPortal/Documents/blob/d1ec06e6fe2f67b1e3bb24198d887234a6a198fb/images_upload/image_Upload_3.png)

Figure 3: Example of an Excel Template for the data structure in Figure 2


## 3 Data collection

The Data Collection Module provides tools to create new datasets, enter metadata, upload data to the system, and import metadata structures. There are some workflows available under the “Collect” tab (see Figure 1):

- Create Dataset
- Upload Data
- Import Data
- Push Big File

Creating a new dataset with tabular data includes the following steps:

1.  [Create a new dataset](#31-create-a-dataset)
2.  [Fill out the metadata](#32-metadata)
3.  [Define data structure](#33-upload-primary-data)
4.  [Upload primary data](#33-upload-primary-data)
5.  [Add links to other datasets and publications (optional)](#36-add-attachments-to-datasets)
6.  [Add attachments (optional)](#36-add-attachments-to-datasets)


### 3.1 Create a dataset

To create a new dataset, please click on the “Collect” tab and choose “Create Dataset” (Figure 1). You will be directed to an upload wizard, which leads you through the process step by step. When you hover the mouse pointer over the orange “Select” buttons in the wizard (see Figure 4) an information field about the respective option will appear.
