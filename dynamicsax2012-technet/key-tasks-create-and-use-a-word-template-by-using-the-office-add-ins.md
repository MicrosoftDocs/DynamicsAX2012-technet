---
title: 'Key tasks: Create and use a Word template by using the Office Add-ins'
TOCTitle: 'Key tasks: Create and use a Word template by using the Office Add-ins'
ms:assetid: 599b8e31-d13c-462f-97a8-450371f5de1a
ms:mtpsurl: https://technet.microsoft.com/library/Hh781090(v=AX.60)
ms:contentKeyID: 43894499
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- add in
- add ins
- add-ins
- template
- templates
- word
- office
- add-in
audience: Application User
ms.search.region: Global
---

# Key tasks: Create and use a Word template by using the Office Add-ins 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the Office Add-ins for Microsoft Dynamics AX to export information from Microsoft Dynamics AX to Microsoft Word. If your organization uses the Office Add-ins, a tab for Microsoft Dynamics AX is added to the ribbon in Word.

The Office Add-in for Word lets you create document templates that you can reuse. If your organization uses a template library, you can share the Word template with other workers by saving your template into the template library.

The data that you can include in a document template is limited by the permissions that are associated with your assigned role. Generally, if you can view and modify specific data in the Microsoft Dynamics AX client, you can view, add, and modify the same data in a template. If you share a template with other workers, those workers must also have permission to view and modify the data in the shared template.

## What do you want to do?

Create a Word template from a Microsoft Dynamics AX document

Import Microsoft Dynamics AX data into a Word template

Find form help

Find related tasks

## Create a Word template from a Microsoft Dynamics AX document

1.  In Microsoft Dynamics AX, open the document that you want to save as a Word template.

2.  Press CTRL+P to create an auto-report of the document. For more information about how to create an auto-report, see [Create a report by using the Microsoft Dynamics AX auto-report wizard](create-a-report-by-using-the-microsoft-dynamics-ax-auto-report-wizard.md).

3.  Click **OK**.

4.  In the **Autoreport** form, on the top menu, click the **Export** button, and then click **Word**.

5.  Select a location in which to save the file.

6.  Enter a name for the file. In the **Save as type** field, select **Word Template**, and then click **Save**.

7.  Open the Word template from the location that you entered in step 5.

8.  Optional: Add text, images, and other content to the document.

The template contains the optional text and images that you add in step 8, and XML tags in place of the data that you specified in the **Autoreport** form. To share the template with other users, contact a system administrator to save the template to the template library.

Back to top

## Import Microsoft Dynamics AX data into a Word template

1.  Save a Word template that was created by using the Office Add-in for Word to your local computer.
    

    > [!NOTE]
    > <P>You must save the file to your computer to modify it.</P>



2.  Open the Word template. The file opens as a Word document.

3.  Optional: To add more fields to your copy of the template, do the following:
    
    1.  On the ribbon, on the **Dynamics AX** tab, click **Add Data**.
    
    2.  In the **Add Data** form, select the data sources that you want to add to the document.
    
    3.  In the left pane, click a node to view the fields that are available in the selected node.
    
    4.  In the Word document, tab to the location where you want to add data from the Microsoft Dynamics AX client.
    
    5.  To add a field to the Word document, double-click the field in the left pane, or drag the field onto the Word document.
    
    6.  Save the Word document, but do not close the file.

4.  Click the **Filter** button to search for a specific value for a selected field. In the **Filter** form, select the conditions to filter by.

5.  Click the **Merge Document** button. The selected data is displayed in a new Word document.

6.  Save the document.

Back to top

## Find form help

[Export document types (class form)](https://technet.microsoft.com/library/aa616371\(v=ax.60\))

## Find related tasks

[Create Microsoft Word documents from Microsoft Dynamics AX](create-microsoft-word-documents-from-microsoft-dynamics-ax.md)

  


