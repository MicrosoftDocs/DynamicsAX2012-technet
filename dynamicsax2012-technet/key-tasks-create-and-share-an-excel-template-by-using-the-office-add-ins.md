---
title: 'Key tasks: Create and share an Excel template by using the Office Add-ins'
TOCTitle: 'Key tasks: Create and share an Excel template by using the Office Add-ins'
ms:assetid: ddd117d5-45aa-4b22-b99b-31d54536dea0
ms:mtpsurl: https://technet.microsoft.com/library/Hh575254(v=AX.60)
ms:contentKeyID: 39555418
author: Khairunj
ms.date: 04/30/2014
mtps_version: v=AX.60
f1_keywords:
- Excel
- template
- Office add-in
- spreadsheet
audience: Application User
ms.search.region: Global
---

# Key tasks: Create and share an Excel template by using the Office Add-ins 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX 2012 integrates automatically with Microsoft Excel. You can use tools and functionality in Excel to work with data in AX 2012. You can export data from AX 2012 to Excel, work with the data there, and then import the data back into AX 2012.

You can create an Excel workbook as a template that is structured so that it works with fields and tables in AX 2012. For example, you can create a budgeting template that lists the financial accounts and dimensions from your organization’s chart of accounts in AX 2012. You can then send a copy of the template to the individuals who are responsible for preparing a budget. When the budget information is complete, it can be imported into AX 2012.

If your system administrator creates a template library, you can save the Excel template to the library, and then reuse the template or copy it for a future budget period.

The data that you can include in a template is limited by the permissions that are associated with your assigned role. In general, if you can view and modify specific data in the Microsoft Dynamics AX client, you can view, add, and modify the same data in a template. If you share a template with other workers, those workers must also have permission to view and modify the data in the shared template.

Before you create a template, your system administrator must configure your personal settings so that you can update the data in the Excel template. For more information about how to view your settings for Excel, see [About using the Microsoft Dynamics AX Add-in for Excel](about-using-the-microsoft-dynamics-ax-add-in-for-excel.md).

To modify a template that was created by another person, you must save a copy of the template to your computer. If you use a template that was created by a system administrator, the template might contain columns and rows that you cannot modify. If you want to modify the design of a template, contact the person who created the template.

## What do you want to do?

Create an Excel template

Sharing an Excel template

Find related tasks

## Create an Excel template

1.  On a list page in Microsoft Dynamics AX, on the **Action Pane**, click **Export to Excel**.

2.  Enter a file name for the Excel workbook.
    

    > [!WARNING]
    > <P>If you select an existing file, the content is overwritten.</P>



3.  Save the file as an Excel template on a local computer.

4.  In Excel, on the ribbon, on the **Dynamics AX** tab, select the fields to include in the workbook:
    
    1.  Click **Field chooser**, select the field to add, and then click the **\>** button. To select multiple fields, hold down the CTRL key, select each field, and then click the **\>** button.
        
        If you want the template to use fields that do not appear in the left pane, click **Add data** \> **Add tables**.
        
        Beginning with cumulative update 7 for Microsoft Dynamics AX 2012 R2, if you add financial dimensions, only the dimensions that are specified in the **Financial dimension configuration for integrating applications** form are available.
    
    2.  To add objects, in the **Selected objects** pane, select the table, and then click the **\>** button. To select multiple tables, hold down the CTRL key, select each table, and then click the **\>** button.
    
    3.  To remove all objects that were previously selected, click the **\<\<** button.

5.  In the left pane, select the fields to add to the template.

6.  Save the file to your computer. If your system administrator has created a template library for AX 2012, you can send the template to the system administrator to save to the library.

Back to top

## Sharing an Excel template

If you create an Excel workbook to import information into AX 2012, you can save the workbook as a template and then share the template with other workers. For example, your organization completes an annual budget by department, and the departments are set up in AX 2012 as financial dimensions. You can create a budgeting template that lists the financial accounts, and then make a copy of the workbook template for each department or dimension. Each department can then use its copy of the workbook template to prepare the departmental budget.

After you create and save the workbook on a local computer, a system administrator can save it to a template library or other file sharing location.

If you are using Microsoft Dynamics AX 2012 R3 or cumulative update 6 or later for AX 2012 R2, a system administrator can set the export location to a Microsoft Office 365 SharePoint folder. After the template is saved to the SharePoint Online folder, you can open the template from the SharePoint folder if you are using the Office 365 version of Excel. To determine the location that is set up for exported files, click **File** \> **Tools** \> **Options**. In the **Options** form, on the **General** tab, in the **Miscellaneous** section, the **Export location** field displays the location.

Back to top

## Find related tasks

[Using the Microsoft Dynamics AX Add-in for Excel](using-the-microsoft-dynamics-ax-add-in-for-excel.md)

[About importing data from Microsoft Excel](about-importing-data-from-microsoft-excel.md)

[Set up integration with Microsoft Office Add-ins](set-up-integration-with-microsoft-office-add-ins.md)

[Set up financial dimensions for integrating applications (Excel and Management Reporter)](set-up-financial-dimensions-for-integrating-applications-excel-and-management-reporter.md)

  


