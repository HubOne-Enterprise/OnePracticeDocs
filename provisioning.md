# Provisioning

Provisioning involves the installation and configuration of <%PRODUCT_NAME%> in an existing Office 365 environment. <%PRODUCT_NAME%> requires a clean SharePoint Online Site Collection and will use the root site. 

Whilst the provisioning process does not delete files, it may change the look and feel of an existing chosen site collection, so take care when implementing it.

The following sections detail the steps to provision <%PRODUCT_NAME%>:

- [Provisioning](#provisioning)
  - [Purchasing & Licensing](#purchasing--licensing)
  - [Installation of OnePractice PreRequisites](#installation-of-onepractice-prerequisites)
  - [Provisioning Process](#provisioning-process)

## Purchasing & Licensing

In order to license OnePractice, please follow the procedure below:


1. Navigate to the [License form](https://form.jotform.co/73236397529871)
    ![License Form](img/clip0033.png)
   1. Enter the Customer's Business Name.
   2. Enter the SharePoint URL **(Leave off https:// or http://)**.<br/>
   3. Enter the Partner Name.<br/>
   4. Enter the number of seats or users the customer has.<br/>
   5. Click Submit.
2. Once submitted, you can continue with the provisioning process via the app
    ![License Submit](img/clip0034.png)
3. You will receive an email once the license has been generated.

## Installation of OnePractice PreRequisites

The following procedure details how to install OnePractice prerequisites

1. Navigate to [https://software.hubone.com](https://software.hubone.com)
2. Click **Portal Provisioning Tool.**
    ![HubOne Software Site](img/clip0008.png) 
3. Click **Download Application**
   ![Download Tool](img/Provisioningtool_download.png)
4. The application will download as a Zip file. Once it has downloaded, click the Zip File.
   ![Zip File](img/clip0010.png)

5. Click Extract all in the zip file.
   
   ![Zip Files](img/clip0011.png)
6. Once the files have been extracted, double click **setup**.
7. If you see the error message as shown below, check out this [Microsoft article](https://msdn.microsoft.com/en-us/library/ee308453.aspx) for instructions how to resolve.
   ![ErroMessage](img/provisioningtool-possibleerrormsg.png)
8. If the Windows Defender App appears, click **More Info**
   ![Defender1](img/clip0012.png)
9. Click **Run Anyway**
    
    ![Defender2](img/clip0013.png)

10. Click **Install**
    
    ![Install](img/clip0014.png)

11. The OnePractice Provisioning Portal will download and install. When complete, there will be a pause and the dialog will disappear.
12. Shortly after the OnePractice Provisioning Manager will run.
    ![ProvisioningStep0](img/clip0031.png)
13. If you are using a demo environment you just created, you can mark that user as a global administrator. If not, please confirm the user account you are using is a global administrator.
    ![ProvisioningStep0a](img/clip0016.png)
14. Ensure your user has a valid Office 365 license.
    You can check this by navigating to [https://portal.office.com/adminportal/home#/users](https://portal.office.com/adminportal/home#/users) and reviewing the user's role.
    If they do not have a license, assign a Business Premium, E3 or E5 license. Wait up to 30 minutes for Microsoft to apply the license then move to the next step.
    ![Office365Portal](img/clip0017.png)
15. Go back to the Provisioning Manager and mark that your user has a valid license.
    ![ProvisioningStep0b](img/clip0018.png)
16. Ensure your user is a SharePoint Site Collection Administrator.
    This will be true if you setup a new tenancy or if they are Global Administrators and have been granted site administration permissions in the SharePoint admin center.
    ![ProvisioningStep0c](img/clip0019.png)
17. Next, enable Custom Scripting on the SharePoint Library.
    
    **Please Note** The next step assumes you do not have the required components installed on your device. If this is the second time you have this procedure, you will not need to install new components.
18. To enable custom scripting click **How do I do this?** to obtain the latest instructions.
    
    Once you have the required components, these instructions assume you have a little proficiency in the use of PowerShell.
    
    Once you have completed the instructions, mark the checkbox
    ![ProvisioningStep0d](img/clip0030.png)
19. Next you will need to create a SharePoint App Catalog. 
    
    Click **How do I do this?** next to the App Catalog checkbox to obtain a set of instructions.

    Once you have completed those instructions, mark the checkbox
    ![ProvisioningStep0e](img/clip0032.png)

**PROCEDURE COMPLETE**

## Provisioning Process

The following steps complete the installation of OnePractice

1. Go to Provisioning Manager and click the right arrow at the bottom of the page
   ![ProvisioningStep1a](img/clip0032.png)
2. Enter the following information:
   
   - **Tenant Admin URL** - The admin link for the client's SharePoint Site, e.g. ```https://mysite-admin.sharepoint.com```
   - **Admin User** - A global admin user login e.g. ```admin@<designator>.onmicrosoft.com```
   - **Admin Password** - the user's password
   - **Log File Location** - the provisioning tool creates comprehensive logs. Choose a location to store them.
  
    Once complete, click the Right arrow at the bottom.
    ![ProvisioningStep1b](img/clip0036.png)
3. The Provisioning Manager will check the Office 365 environment and permissions. Once complete, the next screen will appear.
   ![ProvisioningStep1c](img/clip0037.png)
   - Select **SharePoint**
   - For Production use, ensure **Add Sample data to my lists** is not checked, for test use, feel free to check that button
    
    Click the Right arrow at the bottom of the screen
4. Accept the defaults for portal URL, Document Center URL and Display Name. 
   ![ProvisioningStep1d](img/configurationskin.JPG)
   Complete the following:
   - **Configuration and Skin** - Choose the appropriate configuration and skin for the installation you are deploying.
   - **Company Specific Settings** - 