---
title: 'Checklist: Deploy Microsoft Dynamics AX Enterprise Search'
TOCTitle: 'Checklist: Deploy Enterprise Search'
ms:assetid: 5e416444-e326-4097-b95b-9e378acbd1cc
ms:mtpsurl: https://technet.microsoft.com/library/Gg731811(v=AX.60)
ms:contentKeyID: 35132657
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Checklist: Deploy Microsoft Dynamics AX Enterprise Search 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The following checklist can help you deploy Enterprise Search.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Install and configure Search prerequisites.</p></td>
<td><p><a href="install-and-configure-search-prerequisites.md">Install and configure Search prerequisites</a></p></td>
</tr>
<tr class="even">
<td><p>Install the Microsoft Dynamics AX client, database, and Application Object Server (AOS) in the environment before you install Enterprise Search, and then complete the initialization checklist. If you attempt to install Enterprise Search before you complete these other tasks, the installation fails.</p>
<p></p></td>
<td><p><a href="install-microsoft-dynamics-ax-2012.md">Install Microsoft Dynamics AX 2012</a></p></td>
</tr>
<tr class="odd">
<td><p>Configure the domain account that is used to crawl search data.</p></td>
<td><p><a href="configure-the-search-crawler-account.md">Configure the Search Crawler account</a></p></td>
</tr>
<tr class="even">
<td><p>Configure logging to conserve disk space.</p></td>
<td><p><a href="configure-sharepoint-services-logging.md">Configure SharePoint Services logging</a></p></td>
</tr>
<tr class="odd">
<td><p>Specify which queries (and the underlying database tables) are crawled and indexed for Search. Or, if Search is already configured on a different AOS, you can import Search configurations to a new AOS.</p></td>
<td><p><a href="add-aot-queries-to-the-search-configuration.md">Add AOT queries to the Search configuration</a></p>
<p>or</p>
<p><a href="import-search-configurations-to-an-aos.md">Import Search configurations to an AOS</a></p></td>
</tr>
<tr class="even">
<td><p>Deploy Search in the environment by using Setup. By default, Setup publishes queries that are configured for Search to the SharePoint Business Data Connectivity Service (BDS). The BDS then crawls and indexes Search data for Microsoft Dynamics AX.</p></td>
<td><p><a href="install-search.md">Install Search</a></p>
<p>or</p>
<p><a href="install-enterprise-search-on-fast-search-server.md">Install Enterprise Search on FAST Search Server</a></p></td>
</tr>
<tr class="odd">
<td><p>Publish searchable queries to the Business Data Connectivity Service, so that the queries can be crawled by Microsoft SharePoint Services. This option is necessary if you configured additional AOT queries for Search after you installed Search. If you did not configure additional AOT queries for Search after you installed Search, you can skip this step.</p></td>
<td><p><a href="configure-enterprise-search-by-using-the-search-configuration-wizard.md">Configure Enterprise Search by using the Search Configuration wizard</a></p></td>
</tr>
<tr class="even">
<td><p>Verify that Search is installed and data is discoverable in Search results.</p></td>
<td><p>Open the Microsoft Dynamics AX client, enter a word such as a customer name in the <strong>Search</strong> box, and press Enter.</p></td>
</tr>
</tbody>
</table>


## See also

[Enterprise Search architecture](enterprise-search-architecture.md)

[Troubleshoot installation issues with Enterprise Search](troubleshoot-installation-issues-with-enterprise-search.md)

  


