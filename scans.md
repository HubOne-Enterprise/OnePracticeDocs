# Scans
Scans provides the means to significantly reduce the time spent by your staff filing scanned documents (or searchable PDF files) to client folders into SharePoint. 

The app combines state-of-the-art technologies to intelligently read, categorise and file scans from your scanner and organise them in SharePoint according to options you have configured. 

The following sections detail how to use Scans

- [Scans](#scans)
  - [Getting started](#getting-started)
    - [Installation](#installation)
    - [First Run](#first-run)
  - [Basic Usage](#basic-usage)
  - [Manual Processing](#manual-processing)
    - [Document Summary](#document-summary)
    - [Edit Document Details](#edit-document-details)
    - [Client Search](#client-search)
  - [Edit Metadata](#edit-metadata)

## Getting started

### Installation
1. Connect to https://software.hubone.com/OnePracticeScans/ and click Download Application.
2. Once downloaded, open the folder and click Extract all. Once extracted, double click setup.
3. Click **Install**

    ![InstallScans](img/clip0148.png)

4. Once complete, Scans will be installed.

> Scans uses Microsoft Click-Once technology which ensures your software is always kept up to date. Every time you run Scans, it will check to see if there are updates and if there are, the software will prompt you to update.

### First Run

The first run of Scans will require you to enter the following:

- Location of your document center
- A local folder to store the scanned documents

![Connection](img/scans-essentialconnectionsettings.PNG)

When complete, click **Login with Office 365**.

If you're not already logged into Office 365 in your browser, a popup window will appear and ask you to enter your username and password. You will be logged in and the popup will disappear. 

If you are already logged into Office 365 in your browser, the popup will appear, verify your credentials, complete the log in automatically and disappear.

> **Note** you can also Import and Export Settings

*All scanners have the facility to store scanned documents in a folder on a computer. To facilitate the operation of Scans, we recommend configuring your scanner as follows:*

1. *Document to Create: **Searchable PDF***
2. *Location to Save - Choose the local folder as above.*


Once you have completed the above settings, the application will look as per the image below:

![ScansHome](img/clip0150.png)

## Basic Usage

If you have configured Scans to work with your scanner correctly, simply scan a document and the following screen will appear:

![ProcessWindor](img/scans-processingwindow-editdocumentdetails.PNG)

This is **[Manual Processing](#manual-processing)**, and it allows you to control aspects of the file via the app before it saving. There is also the option for automatic matching but this should only be activated once you have a high degree of automatic success in Manual Processing.


In common operation, you will just click **Save to client**. However the following options are available.

- Document Summary - Provides information on the document.
- Edit document details - Allows editing of some document information including client and sub-folder.
- Edit metadata - Allows the entering and modification of metadata.
- Preview document - Allows the preview of the document.
- Process later - Does not process the document.
- Delete - Deletes the document.
- Save to DropOff - Saves to the DropOff Library.
- Save to client - Saves to the Client Folder as matched.

## Manual Processing

Manual processing mode is the default mode of operation for Scans. It allows for the verification of matching and other aspects before saving files.

The section on the left displays the list of scanned documents to be processed, as well as a count at the bottom. You can configure the number of documents listed here by updating the PDF processing setting. By default, a maximum of 6 can be displayed.

![ProcessWindowSummary](img/scans-processingwindow-documentsummary.PNG)

The different options are shown below:

### Document Summary

The Document summary tells you information about the document including:

- **Client Match** - The client matched by the software from information in the document.
- **Client Matched On** - Which field was used for matching.
- **Will Save to** - Which location the file will be saved to assuming the user clicks Save to client.
- **Will be named** - The final file name upon saving.
- **File Size** - The size of the file.

![ProcessWindowSummary](img/scans-processingwindow-documentsummary.PNG)

### Edit Document Details

The Edit document details section allows you to edit details about the document as follows:

- **Target Client** - Here you can change the client you wish to save to. Learn more about searching for the target client
- **Show Subfolders** - Shows subfolders (if any) for the specific chosen client folder.
- **Will be named** - This is the name of the file and you can simply edit it here.
- **Open Save Location**  - Opens the client folder (or subfolder) in your default browser.

![ProcessWindor](img/scans-processingwindow-editdocumentdetails.PNG)

### Client Search

If Scans has been unable to identify the client in your scanned document or it has detected a different entity, you will need to search for the client. 

![Search1](img/scans-targetclientsearch1.PNG)

Start by typing 3 characters into the search bar. 

![Search2](img/scans-targetclientsearch2.PNG)

A list will appear showing all clients that contain those 3 characters. You will also see a line under characters that match your search criteria.

As you type more characters, the list is refined. 

![Search3](img/scans-targetclientsearch3.PNG)

The list will also show clients within client groups that contain those characters. So even if the client name does not contain the searched characters, if the group does, you'll see a list of clients within the matched group.
| | |
| -- | -- |
 | ![Search5](img/scans-targetclientsearch5.PNG) | ![Search4](img/scans-targetclientsearch4.PNG) |

 If you hover over the list, you'll see which client group the client belongs to.

 ![Search6](img/scans-targetclientsearch6.PNG)

## Edit Metadata