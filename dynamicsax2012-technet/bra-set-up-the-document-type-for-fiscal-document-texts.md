---
title: (BRA) Set up the document type for fiscal document texts
TOCTitle: (BRA) Set up the document type for fiscal document texts
ms:assetid: 9f8a02ae-2fd9-4b21-a197-8df36cd4e931
ms:mtpsurl: https://technet.microsoft.com/library/JJ710574(v=AX.60)
ms:contentKeyID: 49384465
author: tfehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Brazil
- (BRA)
- fiscal document
- fiscal document text
- set up fiscal document text
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up the document type for fiscal document texts 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You must set up the document type for fiscal document texts before you attach the fiscal document texts to a sales order, purchase order, or free text invoice. You must first create a document type in the **Document types** form, and then you can attach the document type to fiscal document texts by using the **Brazilian parameters** form.

1.  Click **Organization administration** \> **Setup** \> **Document management** \> **Document types**.

2.  Create a document type. For more information, see [Configure document management](configure-document-management.md).

3.  In the **Category** field, select the category that the fiscal document belongs to.

4.  Close the form.

5.  Click **Organization administration** \> **Setup** \> **Brazil** \> **Brazilian parameters**.

6.  In the left pane, click **Fiscal document**.

7.  In the **Fiscal document** area, in the **Document type** field, select the document type for the fiscal document texts. You can select a document type that is not used in an attachment in fiscal documents.
    

    > [!NOTE]
    > <P>You cannot modify the document type if a fiscal document text is attached to a fiscal document.</P>



## See also

[(BRA) Brazilian parameters (form)](https://technet.microsoft.com/library/jj822920\(v=ax.60\))

  


