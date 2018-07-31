---
title: Maintain record templates
TOCTitle: Maintain record templates
ms:assetid: 0dcce7f1-b62e-4c16-b230-e732babd1bd5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg230906(v=AX.60)
ms:contentKeyID: 36676367
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- record templates
- record template
audience: Application User
ms.search.region: Global
---

# Maintain record templates 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Record templates can help you create records more quickly in Microsoft Dynamics AX. You can create record templates for only some of the record types in Microsoft Dynamics AX.

You can apply templates only for the areas of Microsoft Dynamics AX that you have access to. However all template titles are visible to you when you create a new record, and to other users, also, if you are creating templates that will be available for all users. Be sure to consider this when naming templates. For example, avoid using names that include words, such as "commission," if is confidential that some employees in the company have commission-based salaries.

When one or more templates that you have access to exist for a specific form and you attempt to create a new record in the form, the **Select a template for…** form is displayed. When you select a template from the list, the new record is created and contains default information that is based on the template that you selected.

If you do not want to use templates when you create new records, select the **Do not ask again** check box in the **Select a template for…** form.


> [!NOTE]
> <P>To display the template selection dialog box again, right-click any record, click <STRONG>Record info</STRONG>, and then click <STRONG>Show template selection</STRONG>.</P>



## Create a record template

1.  Open a form that contains the data to include in the new template for the form.

2.  Right-click the form, and then click **Record info**.

3.  In the **Record information** form, select the button for the type of template to create. You can create the following types of templates:
    
      - **User template** – Templates that are available only to you.
    
      - **Company accounts template** – Templates that are available to all users in the legal entity that you are currently logged on to.
    
      - **System template** – Templates that are related to system forms, such as the **User** form.
        

        > [!NOTE]
        > <P>Only the administrator should modify and delete company accounts and system templates because these templates affect all users in the current legal entity and all companies, respectively.</P>



4.  Type a name and a description for the template, and then click **OK**.

## Modify a record template


> [!NOTE]
> <P>You cannot modify user record templates and templates for records with effective dates.</P>



1.  Click **Home** \> **Setup** \> **Record templates**.
    

    > [!NOTE]
    > <P>If you have Enterprise Portal for Microsoft Dynamics AX installed, click <STRONG>Home</STRONG> and on the navigation pane, click <STRONG>Home</STRONG> &gt; <STRONG>Area page</STRONG> to display the Home area page. You can open the <STRONG>Record templates</STRONG> form from the <STRONG>Setup</STRONG> area of the Home area page.</P>



2.  Select the table that contains the template to modify.

3.  Click the **Templates** tab and select the template to modify.

4.  Click **Edit** to open the template and make the changes. Save your changes.

## Delete a system record template

1.  Click **Home** \> **Setup** \> **Record templates**.
    

    > [!NOTE]
    > <P>If you have Enterprise Portal installed, click <STRONG>Home</STRONG> and on the navigation pane, click <STRONG>Home</STRONG> &gt; <STRONG>Area page</STRONG> to display the Home area page. You can open the <STRONG>Record templates</STRONG> form from the <STRONG>Setup</STRONG> area of the Home area page.</P>



2.  Select the **System record templates** check box to display system templates.

3.  Click the **Templates** tab, select the template to delete, and press ALT+F9.

## Delete a user record template

1.  Open the form that contains the user template to delete.

2.  Press CTRL+N to display the list of available templates.

3.  Select the template to delete and press ALT+F9.

4.  Press ESC to close the list of available templates.

## See also

[Transaction information or Record information (form)](https://technet.microsoft.com/en-us/library/aa615677\(v=ax.60\))

[Select a template for... (form)](https://technet.microsoft.com/en-us/library/aa586632\(v=ax.60\))

[Create template (form)](https://technet.microsoft.com/en-us/library/aa591516\(v=ax.60\))

  


