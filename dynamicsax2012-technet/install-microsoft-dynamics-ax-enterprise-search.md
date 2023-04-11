---
title: Install Microsoft Dynamics AX Enterprise Search
TOCTitle: Install Enterprise Search
ms:assetid: 36f61f99-a708-411e-8808-de637f669fc7
ms:mtpsurl: https://technet.microsoft.com/library/Gg731778(v=AX.60)
ms:contentKeyID: 35132604
author: tonyafehr
ms.date: 05/28/2014
mtps_version: v=AX.60
---

# Install Microsoft Dynamics AX Enterprise Search 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to install Microsoft Dynamics AX Enterprise Search. You must complete the installation procedure on each search server.

## Before you install Enterprise Search

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Details</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Verify required services</p></td>
<td><p>Verify that required SharePoint services are configured correctly and are running. For more information, see <a href="install-and-configure-search-prerequisites.md">Install and configure Search prerequisites</a>.</p></td>
</tr>
<tr class="even">
<td><p>Install Microsoft Dynamics AX</p></td>
<td><p>Install the Microsoft Dynamics AX client, database, and Application Object Server (AOS) in the environment before you install Enterprise Search, and then complete the initialization checklist. If you attempt to install Enterprise Search before you complete these other tasks, the installation fails. For more information, see <a href="install-microsoft-dynamics-ax-2012.md">Install Microsoft Dynamics AX 2012</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Create a domain account</p></td>
<td><p>Create a domain account for Enterprise Search. This account must be configured as a Microsoft Dynamics AX user. The user account must be assigned to the <strong>Search crawler</strong> role before you install search. For more information, see <a href="configure-the-search-crawler-account.md">Configure the Search Crawler account</a>.</p></td>
</tr>
<tr class="even">
<td><p>Verify web application requirement</p></td>
<td><p>Verify that the SharePoint Web application used for Microsoft Dynamics AX Enterprise Search is configured for NTLM authentication. Also verify that the Web application is not configured for anonymous authentication.</p></td>
</tr>
<tr class="odd">
<td><p>Verify prerequisites</p></td>
<td><p>On the computer where you will install Enterprise Search, run the prerequisite validation utility to verify that system requirements have been met. For information about how to run the prerequisite validation utility, see <a href="check-prerequisites.md">Check prerequisites</a>.</p>
<p>For more information about the hardware and software requirements for Microsoft Dynamics AX, see the <a href="https://go.microsoft.com/fwlink/?linkid=165377">system requirements</a>.</p></td>
</tr>
<tr class="even">
<td><p>Stop BDC service in load balanced environments</p></td>
<td><p>If you are setting up Enterprise Search in a load-balanced SharePoint server farm, verify that the Business Data Connectivity service (BDC) is only running on the Enterprise Search server. You must stop this service an all Web front-end servers in the farm. If you do not stop the service on all Web front-end servers, the Enterprise Search Configuration Wizard returns errors.</p></td>
</tr>
<tr class="odd">
<td><p>Install hotfix</p></td>
<td><p>If you are installing Enterprise Search on Microsoft Search Server 2010 Express, you must install the SharePoint Server 2010 hotfix package dated August 31, 2010. If you do not install the hotfix, you receive the following error message when you install Enterprise Search: “The trial period for this product has expired.” For more information and to download the hotfix package, see Microsoft Knowledge Base article number <a href="https://support.microsoft.com/kb/2276336">2276336</a>.</p></td>
</tr>
</tbody>
</table>



> [!IMPORTANT]
> <P>Search is not supported in an environment with multiple AOS servers on the same server, unless all AOS servers point to the same database. Limitations in the Search server configuration (mssdmn.exe.config) and the Microsoft Dynamics AX client configuration prevent support for a topology with multiple AOS servers on the same server.</P>



## Install Enterprise Search

Use this procedure to install Enterprise Search. If you are installing other Microsoft Dynamics AX components at the same time, the installation pages vary, based on the components that you are installing.

1.  Start Microsoft Dynamics AX Setup. Under **Install**, select **Microsoft Dynamics AX components**.

2.  Advance through the first wizard pages.

3.  If the Setup Support files have not yet been installed on the computer, the **Select a file location** page is displayed. The Setup Support files are required for installation. Enter a file location or accept the default location, and then click **Next**. On the **Ready to install** page, click **Install**.

4.  If you are installing AX 2012 R3, in the **Select an installation option** page, click **Microsoft Dynamics AX**.

5.  On the **Select installation type** page, click **Custom installation**, and then click **Next**.

6.  On the **Select components** page, select **Enterprise Search**, and then click **Next**.

7.  On the **Prerequisite validation results** page, resolve any errors. For more information about how to resolve prerequisite errors, see [Check prerequisites](check-prerequisites.md). When no errors remain, click **Next**.

8.  On the **Select a file location** page, select the location where you want to install 32-bit versions of Microsoft Dynamics AX files, and then click **Next**.

9.  On the **Specify a location for configuration settings** page, specify whether you want Enterprise Search to access configuration information from the registry on the local computer or from a shared configuration file. If you select to use a shared configuration file, you must enter the network location of the file. Click **Next**.

10. On the **Connect to an AOS instance** page, enter the name of the computer that is running the Application Object Server (AOS) instance that you want to connect to. You can optionally specify the name of the AOS instance, the TCP/IP port number, and the WSDL port for services. Click **Next**.
    

    > [!NOTE]
    > <P>If you entered AOS connection information for other Microsoft Dynamics AX components that are installed on this computer, this screen is not displayed. Subsequent installations on this computer reuse the existing AOS connection.</P>



11. On the **Specify Business Connector proxy account information** page, enter the password for the proxy account that is used by the .NET Business Connector. Click **Next**.

12. On the **Specify the search crawler account** page, enter the account information, and then click **Next**.

13. On the **Configure a Web site for the search crawler** page, select a web site from the list. If the site is not already configured as a SharePoint Web application, then Setup configures it in SharePoint.

14. On the **Prerequisite validation results** page, resolve any errors. When no errors remain, click **Next**.

15. On the **Ready to install** page, click **Install**.

16. After the installation is complete, click **Finish** to close the wizard.

## Post-install configurations

If you installed Enterprise Search on a computer separate from the AOS, you must specify the **Search server url** in the **Enterprise Portal parameters** form. If you do not specify the URL, Search does not retrieve data.

1.  Click **System administration** \> **Setup** \> **Enterprise Portal** \> **Enterprise Portal parameters**.

2.  Click **Search**.

3.  In the **Search server url** field, enter the URL to the SharePoint Search service where you just installed Search. Replace *server\_name* with the name of the server where you installed Search: http:// *server\_name*/sites/DynamicsAXClientSearch/\_vti\_bin/search.asmx

4.  Click **Close** to save changes.

## Configure Business Connector Proxy membership in the SQL db\_owner role

After you install Enterprise Search by using Setup, use SQL Server Management Studio to add the Business Connector proxy account and the search service application pool account (if different from the Business Connector proxy account) as members of the **db\_owner** role for the following databases:

Search\_Service\_Application\_LinksStoreDB\_\<GUID\> (SharePoint 2013 only)

Search Service\_Application\_CrawlStoreDB\_\<GUID\>

Search\_Service\_Application\_DB\_\<GUID\>

Search\_Service\_Application\_PropertyStoreDB\_\<GUID\> (SharePoint 2010 only)


> [!IMPORTANT]
> <P>If you installed FAST Search Server 2010 for SharePoint each role is prefaced with the word FAST. For example, FAST_Search Service_Application_CrawlStoreDB_&lt;GUID&gt;</P>



## Configure queries for searchable data

Data, metadata, and documents can only be crawled and indexed for search if the database table is included in a Microsoft Dynamics AX AOT query. After the table is specified in a query, the query must be configured for Search. You configure a query for Search by setting the **Searchable** property to **True** in the AOT. By default, only the following queries are configured for Search. These queries are automatically published and indexed after you install Enterprise Search:

  - BdcDocuRef

  - CustTableListPage

  - EcoResProductPerCompanySearch

  - EngChgCaseAssociationInventTable

  - HcmWorkerListPage

  - HcmWorkerListPage\_NotAccounted

  - HcmWorkerListPage\_Present

  - ProjCategory

  - ProjGroupQuery

  - SecurityRoleAllTasks

  - smmBusinessRelations\_NoFilter

  - VendorEnterpriseSearch

For information about how to make data, metadata, and documents available in Search, see [Add AOT queries to the Search configuration](add-aot-queries-to-the-search-configuration.md). After you have specified which queries should be available in Search, you must publish the queries to SharePoint. For more information, see [Configure Enterprise Search by using the Search Configuration wizard](configure-enterprise-search-by-using-the-search-configuration-wizard.md).

## Configure SharePoint Farm Search Settings

Use SharePoint Central Administration to configure time-out settings and start a full crawl on the Microsoft Dynamics AX content sources.

1.  In SharePoint Central Administration, click **Manage service applications**, and then click **Search Service Application**.

2.  Click **Farm Search Administration**.

3.  In the **Time-out (seconds)** field, click the **60,60** link. Change the time-out to 600,600 and then click **OK**.

4.  In the **Search Service Applications** section, click the **Search Service Application** link.

5.  Click the **Content Sources** link.

6.  Right-click the **Microsoft Dynamics AX** and **Microsoft Dynamics AX Metadata** content sources and click **Start Full Crawl**.

7.  After the crawl completes, open an Microsoft Dynamics AX client and verify that the Search box appears in the upper-right corner. Also search on a term such as Sales and verify that the system returns results that are shown in both the middle pane (the data, metadata, and documents pane) and the **Help Topics** pane.

## Troubleshooting: SharePoint Search stops working after you install Enterprise Portal

If you install Enterprise Portal on a server that hosts a SharePoint Team site, the default Search settings for the team site can change. SharePoint Search returns errors. To restore Search for the SharePoint team site, reset the SharePoint Search settings to their default values.

1.  Open the **Search Settings** page. By default, the URL is: http://\< *server\_name*\>/\_layouts/enhancedSearch.aspx

2.  Under **Site Collection Search Center**, click **Do not use custom scopes**.

3.  Under **Site Collection Search Dropdown Mode**, click **Do not show scopes dropdown, and use contextual scope**.

4.  Under **Site Collection Search Results Page**, click **/\_layouts/OSSSearchResults.aspx**, and then click **OK**.

## See also

[Checklist: Deploy Microsoft Dynamics AX Enterprise Search](checklist-deploy-microsoft-dynamics-ax-enterprise-search.md)

  


