# How to activate Microsoft Office 365 user details for your templates
With the release of version6.3, the Templates application allows you to include Microsoft account information for the user that's logged in, to your templates by adding a new type of template field. These fields are visible in the Templates Field Builder tool when the App catalog is updated. 

As these fields access a more restricted level of privacy, Templates needs to be re-installed on the tenancy and updated in the Document Center. Do this by following these quick steps:

- Download the relevant Templates manifest file from https://software.hubone.com/Templates
- Unzip the folder
- Navigate to your SharePoint App Catalog site which should be at an address like https://<yourdomain>.sharepoint.com/sites/apps
- Click on Apps for SharePoint located in the menu to the left of the page
- Delete any version of HubOne OnePractice Templates or CCH Templates
- Drag and drop the new app manifest you downloaded in step 1 and 2, into the browser
- Navigate to your document center
- Go to Settings Cog > Site Contents
- Scroll down until you find the Templates app
- Click on the 3 dots to the right of the app name to show actions
- Select Details
- On this screen, you will see that there is a newer version available. Select Add it
- A popup will appear and ask you to accept the new permissions
- Once you have accepted, the Microsoft user information fields should now work in your templates

>If Templates displays an error after the upgrade, simply edit the Document Center page, remove and re-add the app. 
If you are unsure how to do this, please contact your SharePoint/systems administrator to complete this action.
