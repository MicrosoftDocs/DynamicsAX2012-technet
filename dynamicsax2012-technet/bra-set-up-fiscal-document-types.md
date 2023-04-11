---
title: (BRA) Set up fiscal document types
TOCTitle: (BRA) Set up fiscal document types
ms:assetid: 341783fd-f258-429c-a3e4-61f72b24cae9
ms:mtpsurl: https://technet.microsoft.com/library/JJ710450(v=AX.60)
ms:contentKeyID: 49384341
author: tfehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- brazil
- fiscal document types
- fiscal documents
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up fiscal document types 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create fiscal document types that can be used in sales and purchase transactions. The fiscal document type defines the number sequence, series, and layout of fiscal documents.


> [!NOTE]
> <P>You cannot modify or delete a fiscal document type that is already used in a transaction.</P>



1.  Click **Organization administration** \> **Setup** \> **Brazil** \> **Fiscal document types**.

2.  Create a record.

3.  In the **Fiscal document type**, **Name**, and **Series** fields, enter the identifier, name, and series of the fiscal document type.

4.  Click the **General** FastTab, and then, in the **Fiscal establishment ID** field, select a fiscal establishment ID for the fiscal document type.

5.  In the **Fiscal document number sequence** field, select the number sequence to use for the fiscal document type.

6.  In the **Fiscal document issue date** field, select the date when the fiscal document is issued. This field is available even if transactions have been created that use the fiscal document type.

7.  In the **Reference** field group, enter information in the following fields:
    
      - In the **Document model** field, select the fiscal document model for fiscal documents.
    
      - In the **Specie** field, select the specie of the fiscal documents.

8.  If the fiscal document type is created for an electronic fiscal document, enter information in the following fields:
    
    1.  Select the **Electronic fiscal document for services** check box to specify that the fiscal document type is for an electronic fiscal document for services.
        

        > [!NOTE]
        > <P>If you select this check box, the <STRONG>NF-e federal</STRONG> check box and the fields on the <STRONG>Setup</STRONG> FastTab are not available.</P>

    
    2.  In the **Export file layout group** field, select the configurator layout group to use to export the electronic fiscal document for services.
        

        > [!NOTE]
        > <P>This field is available only when you select the <STRONG>Electronic fiscal document for services</STRONG> check box.</P>

    
    3.  In the **Return file layout group** field, select the configurator layout group to use to import the electronic fiscal document for services.
        

        > [!NOTE]
        > <P>This field is available only when you select the <STRONG>Electronic fiscal document for services</STRONG> check box.</P>



9.  Select the **NF-e federal** check box to specify that the fiscal document type is created for a nota fiscal electrônica federal (NF-e (federal)).
    

    > [!NOTE]
    > <P>If you select this check box, the <STRONG>Electronic fiscal document for services</STRONG> check box and the fields on the <STRONG>Setup</STRONG> FastTab are not available.</P>



10. Click the **Setup** FastTab, and then, in the **Item table** field group, enter information in the following fields:
    
    1.  In the **Max. item lines** field, enter the maximum number of item lines that can be included in the preprinted fiscal document.
    
    2.  In the **Max. item description size** field, enter the maximum number of characters per line that can be included in the item description and texts.

11. In the **Service table** field group, enter information in the following fields:
    
    1.  In the **Max. service item lines** field, enter the maximum number of service item lines that can be included in the preprinted fiscal document.
    
    2.  In the **Max. service item description size** field, enter the maximum number of characters per line that can be included in the service item description.

12. In the **Additional data table** field group, enter information in the following fields:
    
    1.  In the **Max. memo lines** field, enter the maximum number of memo lines that can be included in the preprinted fiscal document.
    
    2.  In the **Max. memo description size** field, enter the maximum number of characters per line that can be included in the memo description.

## See also

[(BRA) Fiscal document types (form)](https://technet.microsoft.com/library/jj710551\(v=ax.60\))

[(BRA) Assign fiscal document types (form)](https://technet.microsoft.com/library/jj710506\(v=ax.60\))

[(BRA) Assign fiscal document types for customers or vendors](bra-assign-fiscal-document-types-for-customers-or-vendors.md)

  


