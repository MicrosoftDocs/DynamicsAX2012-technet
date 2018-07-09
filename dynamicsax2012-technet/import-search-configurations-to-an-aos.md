---
title: Import Search configurations to an AOS
TOCTitle: Import Search configurations to an AOS
ms:assetid: e44a9235-9a03-446b-9bee-494abf6631ff
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh500184(v=AX.60)
ms:contentKeyID: 37820251
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Import Search configurations to an AOS [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to import Search configurations to an instance of Application Object Server (AOS) for Microsoft Dynamics AX. We recommend that you configure Search in a development environment, test the configurations, and then import the Search configurations to the AOS instance in the production environment.

## Before you begin

In a development environment, configure Application Object Tree (AOT) queries for Search. For more information, see [Add AOT queries to the Search configuration](add-aot-queries-to-the-search-configuration.md). Test the configurations before you complete the procedure in this topic.


> [!IMPORTANT]
> <P>The following procedure requires that you import an .xpo file to an AOS instance in the production environment. We recommend that you perform this procedure during off-peak hours, so that you do not affect the performance of clients that are connected to the server.</P>



## Import Search configurations

1.  Open the AOT in the development environment.

2.  Right-click the **Queries** node, and then click **Export**.

3.  Click the **Browse** button, specify the location where you want to export the .xpo file, and then click **OK**.

4.  Open the AOT on the AOS instance in the production environment.

5.  On the toolbar, click **Command**, and then click **Import**.

6.  Select the .xpo file that you exported earlier in this procedure, and then click **OK**.

The AOS instance in the production environment is now configured for Search. To make the queries and the underlying database tables available in Search results, you must publish the configurations to SharePoint in the production environment. For more information, see [Configure Enterprise Search by using the Search Configuration wizard](configure-enterprise-search-by-using-the-search-configuration-wizard.md).

## See also

[Checklist: Deploy Microsoft Dynamics AX Enterprise Search](checklist-deploy-microsoft-dynamics-ax-enterprise-search.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

