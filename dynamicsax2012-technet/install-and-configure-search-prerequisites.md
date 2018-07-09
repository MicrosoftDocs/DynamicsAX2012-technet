---
title: Install and configure Search prerequisites
TOCTitle: Install and configure Search prerequisites
ms:assetid: f4c8a8af-43a1-4203-9d32-196ebf050bb3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ133958(v=AX.60)
ms:contentKeyID: 47290825
ms.date: 05/19/2014
mtps_version: v=AX.60
---

# Install and configure Search prerequisites [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes how to configure prerequisite software and services for Microsoft Dynamics AX Enterprise Search. If the Microsoft Dynamics AX Prerequisite Checker displayed an error when you tried to install Enterprise Search, then this topic might help you troubleshoot the error.

## Services required for Search

Microsoft Dynamics AX Enterprise Search uses the following services.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Service</p></th>
<th><p>Details</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Microsoft Search Server service</p></td>
<td><p>The Microsoft Search Server service crawls, indexes, and retrieves Microsoft Dynamics AX data and metadata for Enterprise Search. This service is available in the following products.</p>
<ul>
<li><p>SharePoint Server 2010</p></li>
<li><p>Microsoft Search Server 2010</p></li>
<li><p>Microsoft Search Server Express 2010, which is a free <a href="http://go.microsoft.com/fwlink/?linkid=180385">download</a></p></li>
<li><p>Microsoft FAST Search Server 2010</p></li>
<li><p>Microsoft SharePoint Foundation 2013 or Microsoft SharePoint Server 2013</p></li>
</ul>
<p>One of these products must be available in the computing environment before you can install Enterprise Search.</p>
<div class="alert">

> [!WARNING]
> <P>If you intend to deploy Microsoft Dynamics AX Enterprise Search on Microsoft Fast Search Server 2010 know that FAST Search Server requires additional configurations beyond what is described in this topic. For more information, see <A href="install-enterprise-search-on-fast-search-server.md">Install Enterprise Search on FAST Search Server</A>.</P>


</div></td>
</tr>
<tr class="even">
<td><p>Business Data Connectivity (BDC) service</p></td>
<td><p>SharePoint uses the BDC service to display business data from back-end server applications, web services, and databases. Verify that the BDC service application is deployed by using the <strong>Manage Service Applications</strong> page in SharePoint Central Administration. Click <strong>Start</strong> &gt; <strong>All Programs</strong> &gt; <strong>Microsoft SharePoint Products</strong>, and then click <strong>SharePoint Central Administration</strong>. For more information about the BDC service, see the SharePoint documentation.</p></td>
</tr>
<tr class="odd">
<td><p>Search Host Controller Service (SharePoint Server 2013)</p></td>
<td><p>This service manages the search topology components. The service is automatically started on all servers that run search topology components.</p></td>
</tr>
<tr class="even">
<td><p>SharePoint Server Search service</p></td>
<td><p>The SharePoint Server Search service crawls and indexes content for a SharePoint system. This service also provides a user interface for running queries against the catalog of crawled content. SharePoint Search is installed with Microsoft SharePoint Server and all Microsoft Search Server products.</p>
<p>Verify that the SharePoint Server Search service is available in the <strong>Services</strong> Control Panel. Click <strong>Start</strong> &gt; <strong>Administrative Tools</strong>, and then click <strong>Services</strong>. If the service is not listed, install a supported version of Microsoft SharePoint Server or Microsoft Search Server. If the service exists, but is disabled then you must setup and configured the Search service in SharePoint Central Administration. Verify that the BDC service application is deployed by using the <strong>Manage Service Applications</strong> page in SharePoint Central Administration. Click <strong>Start</strong> &gt; <strong>All Programs</strong> &gt; <strong>Microsoft SharePoint Products</strong>, and then click <strong>SharePoint Central Administration</strong>.</p></td>
</tr>
</tbody>
</table>


## Verify SharePoint components before you install Enterprise Search

Use the following procedure to verify that SharePoint Search is configured correctly. We recommend that you perform these checks before you attempt to install Microsoft Dynamics AX Enterprise Search.

1.  Click **Start** \> **All Programs** \> **Microsoft SharePoint Products**, and then click **SharePoint Central Administration**.

2.  Click **System Settings**, and then click **Manage Services on Server**.

3.  Verify that the **SharePoint Server Search** service is running. Also verify that the **SharePoint Foundation Search** service is stopped. SharePoint Foundation Search is not required for Enterprise Search.
    

    > [!WARNING]
    > <P>If SharePoint Server Search does not appear in the list, you might be using SharePoint Foundation, which requires additional configuration. See the section titled “SharePoint Search or SharePoint Server Search 14 service does not pass the prerequisite check” in <A href="troubleshoot-installation-issues-with-enterprise-search.md">Troubleshoot installation issues with Enterprise Search</A>.</P>



4.  From SharePoint Central Administration, click **Manage Service Applications**.

5.  Click the **Business Data Connectivity Service** link and verify that the page loads without errors.

6.  On the **Manage Service Applications** page, click the **Search Service Application** link and verify that the page loads without errors.

7.  On the **Search Administration** page, click the **Content Sources** link and verify that the page loads without errors.

If all pages loaded without errors, you can install Microsoft Dynamics AX Enterprise Search in the environment. For more information, see [Install Microsoft Dynamics AX Enterprise Search](install-microsoft-dynamics-ax-enterprise-search.md).

## Verify the Business Connector Proxy Account for Search Services

The SharePoint Server Search service and the Search Host Controller service must run as the Microsoft Dynamics AX Business Connector Proxy (BC proxy) account to access Microsoft Dynamics AX data. If these services are not configured to run as the BC proxy, Search returns no results.

Use the following procedure to specify the BC proxy for the SharePoint Server Search service and the Search Host Controller service.

1.  Locate the alias and domain for BC proxy in the Microsoft Dynamics AX client. Click **System administration** \> **Setup** \> **System** \> **System service accounts**.

2.  In SharePoint Central Administration, click **Security**, and then click **Configure Service Accounts**.

3.  In the **Credential Management** list, click **Windows Service - Search Host Controller Service**.

4.  In the **Select an account for this component** list, verify that the BC proxy is selected. If you do not see the BC proxy as an option, click the **Register new managed account** link and create an account that uses the alias and domain of the BC proxy. Click **OK** to save your changes.

5.  Repeat steps 3 and 4 for the **Windows Service - SharePoint Server Search** service.

6.  In SharePoint Central Administration, click **System Settings**, and then click **Manage services on server**.

7.  Locate **Search Host Controller Service** in the list. Stop and restart this service.

8.  In Windows, type services.msc in the **Run** dialog box and press Enter.

9.  Locate **SharePoint Server Search** in the list of services. Stop and restart this service.

## See also

[Checklist: Deploy Microsoft Dynamics AX Enterprise Search](checklist-deploy-microsoft-dynamics-ax-enterprise-search.md)

[Troubleshoot installation issues with Enterprise Search](troubleshoot-installation-issues-with-enterprise-search.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

