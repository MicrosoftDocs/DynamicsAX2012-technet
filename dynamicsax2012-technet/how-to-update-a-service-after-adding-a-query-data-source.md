---
title: 'How to: Update a Service After Adding a Query Data Source'
TOCTitle: 'How to: Update a Service After Adding a Query Data Source'
ms:assetid: 4cef13e1-3dbf-4904-9970-1feac481b1ca
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg840400(v=AX.60)
ms:contentKeyID: 35243397
ms.date: 01/29/2014
mtps_version: v=AX.60
---

# How to: Update a Service After Adding a Query Data Source [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX, if you add a data source to a query that is the foundation for a document service, you must update the service to reflect these changes. For more information about the document services classes, see [Document Services Classes](document-services-classes.md). This process creates an Ax \<Table\> class (also called an AxBC class) for the new data source and updates the data object classes.

### Update the service

1.  After you have added the query data source, open the **Update document service** form. In a Development Workspace, click **Tools** \> **Application Integration Framework** \> **Update document service**.

2.  In the **Service class** name field, select the service class.

3.  In the **Supporting classes** area, select the **Regenerate data object classes** box.

4.  Select the **Update AxBC classes** box.

5.  Click **OK**.

After you complete these steps, the table, the Ax \<Table\> class, and the data object classes will be synchronized. Next, you must refresh the services.

### Refresh the services

1.  In a Development Workspace, expand the **Forms** node in the AOT.

2.  Right-click **AifService**, click **Open**, and then click **Refresh**.


> [!NOTE]
> <P>You can also refresh the services from the <STRONG>Inbound ports</STRONG> form. Click <STRONG>System administration &gt; Setup &gt; Services and Application Integration Framework &gt; Inbound ports</STRONG>, click <STRONG>File</STRONG>, and then click <STRONG>Refresh</STRONG>.</P>


