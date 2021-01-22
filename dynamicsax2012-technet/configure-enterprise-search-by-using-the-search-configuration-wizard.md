---
title: Configure Enterprise Search by using the Search Configuration wizard
TOCTitle: Configure Enterprise Search by using the Search Configuration wizard
ms:assetid: e52f66f3-7ed0-4ad7-8fe3-f8db8b75c779
ms:mtpsurl: https://technet.microsoft.com/library/Gg732177(v=AX.60)
ms:contentKeyID: 35133130
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Configure Enterprise Search by using the Search Configuration wizard 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to configure Microsoft Dynamics AX Enterprise Search by using the Search Configuration Wizard.

## Before you configure Enterprise Search

You must complete the following tasks before you can configure Enterprise Search by using the Search Configuration Wizard:

1.  Deploy Enterprise Search. For more information, see [Install Microsoft Dynamics AX Enterprise Search](install-microsoft-dynamics-ax-enterprise-search.md).

2.  In the **Queries** node of the Application Object Tree (AOT), designate the queries that are available in search results by setting the **Searchable** property to True. For more information, see [Add AOT queries to the Search configuration](add-aot-queries-to-the-search-configuration.md)

## Configure Enterprise Search

The Search Configuration Wizard helps you publish Microsoft Dynamics AX queries to the Microsoft SharePoint Business Data Connectivity Service (BCS). The wizard lists the queries that passed all checks for best practices, and for which the **Searchable** property is set to True. You can select which queries and table fields you want to publish to the BCS. After you complete the wizard, the queries are published to the BCS, so that SharePoint can crawl the selected tables in the Microsoft Dynamics AX database. After the crawl is completed, users can view search results either in the Microsoft Dynamics AX 32-bit client or in Enterprise Portal.


> [!NOTE]
> <P>You can run the Search Configuration Wizard on a server where Enterprise Search is installed from the Microsoft Dynamics AX client or by double-clicking AXSearchSetup.exe in the following directory: %systemdrive%\Program Files\Microsoft Dynamics AX\60\SetupSupport.</P>



1.  Click **System administration** \> **Setup** \> **Search** \> **Search configuration**.

2.  Complete the wizard. Microsoft Dynamics AX informs you that the queries were successfully published to the BCS.

If one or more queries were not published to the BCS, an error message is displayed. Review the log file at the following location: %systemdrive%\\ProgramData\\Microsoft\\Dynamics AX\\Dynamics AX Setup Logs\\.

After the queries are published to the BCS, you can view the list of queries and the status of the database crawl in SharePoint Central Administration.

1.  Click **Start**, and then click **SharePoint Central Administration**.

2.  Under **Application Management**, click **Manage service applications**, and then click **Search Service Application**.

3.  In the left pane, under **Crawling**, click **Content Sources**.

4.  To view the details, click either the content source for Microsoft Dynamics AX or the content source for Microsoft Dynamics AX metadata.


> [!IMPORTANT]
> <P>By default, SharePoint schedules incremental crawls of the Microsoft Dynamics AX database. The incremental crawl only updates records if a parent table is modified. To ensure that the crawler updates records from joined tables, you should periodically perform a full crawl of the database.</P>



## See also

[Enterprise Search operations](enterprise-search-operations.md)

  


