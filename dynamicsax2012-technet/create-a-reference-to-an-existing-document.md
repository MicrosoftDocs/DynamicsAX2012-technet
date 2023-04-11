---
title: Create a reference to an existing document
TOCTitle: Create a reference to an existing document
ms:assetid: 837ea7d5-2509-463a-8549-153c71636e0b
ms:mtpsurl: https://technet.microsoft.com/library/Aa571562(v=AX.60)
ms:contentKeyID: 43976718
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create a reference to an existing document 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you can create a reference to an existing document, you must set up a new document type. The new document type will attach existing documents to a form instead of creating new documents.

## Create a document type to attach files

1.  Click **Organization administration** \> **Setup** \> **Document management** \> **Document types**.

2.  Press CTRL+N to create a new document type.

3.  In the **Type** field, type an identifier for the new document type.

4.  In the **Name** field, type a name for the new document type.

5.  In the **Group** list, select **File**.

## Create a reference to an existing document

1.  Select an existing record.

2.  On the **Command** menu, click **Document handling**.

3.  Click **New** and select a document type where the **Class description** is **File**.

4.  Select the file to attach, and then click **Open**.
    
    The name of the attached file is automatically entered into the **Description** field.

5.  Optional: Enter a note about the attached document into the note text pane at the bottom of the form.

  


