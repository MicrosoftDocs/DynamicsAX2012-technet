---
title: Create a document template and associate it with a document type
TOCTitle: Create a document template and associate it with a document type
ms:assetid: 5390e4bb-9911-4841-82e5-81cae96c7664
ms:mtpsurl: https://technet.microsoft.com/library/Aa548928(v=AX.60)
ms:contentKeyID: 36057298
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- bookmarks
- template integration
audience: Application User
ms.search.region: Global
---

# Create a document template and associate it with a document type 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you create a new document, you can transfer data from tables in Microsoft Dynamics AX to bookmarks in the new document. To do this, you create a template that contains some standard text and some bookmarks where the data is to be inserted. For example, you can transfer the address and contact information for a customer to the letter header in a Microsoft Word document when you create a new letter for that customer.

Before you begin, you must create a Word template that contains bookmarks where the data should be inserted. Then you set up the document type by linking the document type to the template and adding the data fields that should be transferred to the individual bookmarks.

## Create a new Word template

1.  From the **Start** menu on your computer, click **All Programs** \> **Microsoft Office** \> **Microsoft Office Word**.

2.  In the new template, add the text and graphics that should appear in all new documents that you base on the template.

3.  Place the cursor where data should be inserted from Microsoft Dynamics AX, and then click **Insert** \> **Bookmark**.

4.  Type a name for the bookmark, and then click **Add**.

5.  Repeat steps 3 through 4 for each bookmark to include in the template.

6.  On the **File** menu, click **Save As**.

7.  In the **File name** field, enter a name for the new template.
    

    > [!IMPORTANT]
    > <P>The file name must not contain any spaces.</P>



8.  In the **Save as type** field, click **Document Template**, and then click **Save**.

## Link a template to a document type

1.  Click **Organization administration** \> **Setup** \> **Document management** \> **Document types**.

2.  Select the document type to link to a template.

3.  Click **Options**.

4.  In the **Table** field, select the table to associate with the template.

5.  In the **Template file** field, enter the path for the template file.

## Add bookmark information to table fields

1.  Click **Organization administration** \> **Setup** \> **Document management** \> **Document types**.

2.  Select a document type, and then click **Options** to open the **Setup** form.

3.  Select the table that is linked to the template to use, and then click the **Field:** tab.

4.  Press CTRL+N to add a field to be transferred.

5.  In the **Data table** field, select a table to obtain data from.

6.  In the **Data field** field, select a field to obtain data from.

7.  In the **Bookmark** field, type the name of the bookmark that you inserted in the document template.

8.  Optional: Select the **Hard return** check box to insert a line break after the data is inserted.

9.  Repeat steps 4 through 8 to add more data fields to the list.


> [!NOTE]
> <P>The table that you get the data from does not need to match the table that you selected on the <STRONG>Overview</STRONG> tab, but the two tables must be related.</P>


  


