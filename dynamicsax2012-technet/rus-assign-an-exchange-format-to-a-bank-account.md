---
title: (RUS) Assign an exchange format to a bank account
TOCTitle: (RUS) Assign an exchange format to a bank account
ms:assetid: ce417e03-1615-4a42-b00b-3894cb530f29
ms:mtpsurl: https://technet.microsoft.com/library/JJ711633(v=AX.60)
ms:contentKeyID: 49387957
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- exchange format
audience: Application User
ms.search.region: Russia
---

# (RUS) Assign an exchange format to a bank account 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to assign an exchange format for a client bank to a bank account. For each type of exchange, you can create only one active exchange format for a bank account. The exchange types are export, import, and import of account balance.

1.  Click **Cash and bank management** \> **Common** \> **Bank accounts**.

2.  Select a bank account, and then click **Edit**.

3.  In the **Bank accounts** form, click the **Set up** tab.

4.  On the **Action Pane**, in the **Client-bank** action group, click **Exchange formats for settlement account**.

5.  Click **New**, and then, in the **Exchange format code** field, select the exchange format code for the client bank. You can create an exchange format code in the **Exchange formats of client-bank** form.
    

    > [!NOTE]
    > <P>The <STRONG>Bank account</STRONG> field is updated with the bank account code.</P>



6.  In the **File name** field, enter the name of the exchange data file. Include the file name extension. For example, enter Bm\_pvl.txt.

7.  Click the **General** FastTab, and then select the **Import** check box to indicate that the exchange file is used to import documents.
    

    > [!NOTE]
    > <P>You can select the <STRONG>Import</STRONG> or <STRONG>Import of account balance</STRONG> check box only if you selected <STRONG>By row</STRONG> in the <STRONG>Type of exchange format</STRONG> field in the <STRONG>Exchange formats of client-bank</STRONG> form.</P>



8.  In the **Folder for export** field, specify the path of a folder that is used to store exported files. You must specify a path if you selected the **Export** check box in the **Exchange formats for settlement account** form.

9.  In the **Folder for import** field, specify the path of a folder that is used to store imported files and bank statements. You must specify a path if you selected the **Import** or **Import of account balance** check box.

10. Click the **Other** FastTab, and then, in the **Prefix export** and **Prefix import** fields, enter the prefixes that are used for the names of export files and import files. The length of file name prefixes cannot exceed 10 characters. If you specify a prefix, the prefix is added to the file name.

11. Select the **Archive the file** check box to move an imported file to the archive folder.

12. In the **Archive of import** field, specify the path of the archive folder that is used to store imported files.

## See also

[(RUS) Exchange formats for settlement account (form)](https://technet.microsoft.com/library/jj733282\(v=ax.60\))

[(RUS) Create a document type code to export or import payments](rus-create-a-document-type-code-to-export-or-import-payments.md)

  


