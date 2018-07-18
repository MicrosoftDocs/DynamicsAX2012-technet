---
title: Troubleshoot installation issues with Enterprise Search
TOCTitle: Troubleshoot installation issues with Enterprise Search
ms:assetid: 7d38c40f-3ae5-4a10-b159-9519c6ed9150
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh575226(v=AX.60)
ms:contentKeyID: 39555372
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Troubleshoot installation issues with Enterprise Search 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic includes information to help you troubleshoot issues you might encounter when you install Microsoft Dynamics AX Enterprise Search.

## Search prerequisite errors

This section includes error messages you might experience when you run the Microsoft Dynamics AX Prerequisite Validation utility from Setup. Each error includes recommended actions for resolving the problem. For more information about Search prerequisites, see [Install and configure Search prerequisites](install-and-configure-search-prerequisites.md)

**Business Data connectivity (BDC) service application is not deployed**

The Business Data Connectivity (BDC) service is installed with SharePoint. To pass the prerequisite check, you must configure the service application in SharePoint Central Administration. If you configure the service application by using the SharePoint configuration wizard you might create other issues because the wizard creates a SharePoint application that runs on Port 80. This port 80 application can conflict with other IIS Web applications and could cause them to stop working.

Use the following procedure to manually configure the BDC service.


> [!NOTE]
> <P>Completing the steps in this procedure creates a BDC service database in SQL Server.</P>



1.  In **SharePoint Central Administration**, click **Application Management**, and then click **Manage Service Applications**.

2.  Click **New** \> **Business Data Connectivity** service.

3.  Enter a name for the BDC service and the application pool, and then click **OK**. SharePoint displays a message that the Business Data Connectivity Service application was created.

4.  Click **System Settings**, and then click **Manage Services on Server**. If the BDC service is in a status of **Stopped**, click the start link to start the service. Once the service is started, use Microsoft Dynamics AX Setup to run the Prerequisite validation utility.

**SharePoint Search or SharePoint Server Search 14 service does not pass the prerequisite check**

By default, the SharePoint Search service is not installed on SharePoint Foundation. If you are running SharePoint Foundation you must install Microsoft Search Server Express 2010, which is a free [download](http://go.microsoft.com/fwlink/?linkid=180385).

After you installed Search Server Express 2010, use the Services Control Panel to verify that the SharePoint Server Search 14 service is running. If the service is listed but **Disabled**, then you must configure it in SharePoint Central Administration.


> [!NOTE]
> <P>Completing the steps in this procedure creates Search services databases in SQL server.</P>



1.  In **SharePoint Central Administration**, click **Application Management**, and then click **Manage Service Applications**.

2.  Click **New** \> **Search Service Application**.

3.  Enter a name for the service and the application pool, and then click **OK**. SharePoint displays a message that the Search Service application was created.

4.  Click **System Settings**, and then click **Manage Services on Server**. If the Search service is in a status of **Stopped**, click the **Start** link to start the service. Once the service is started, use Microsoft Dynamics AX Setup to run the Prerequisite validation utility.

## The trial period for this product has expired

If you are using Microsoft Search Server 2010 Express, and you receive the error message “The trial period for this product has expired,” you may have to install the SharePoint Server 2010 hotfix package dated August 31, 2010.

For more information and to download the hotfix package, see Microsoft Knowledge Base article number [2276336](http://support.microsoft.com/kb/2276336).

## The Business Connector proxy account does not have permission to perform the operation

The Business Connector (BC) proxy account and the account that is used for the SharePoint Search service application pool must be a member of the db\_owner role for the following databases in SQL Server. If you receiver this error, use SQL Server Management Studio to verify permissions for the following databases.

1.  Search Service\_Application\_CrawlStoreDB\_\<guid\>

2.  Search\_Service\_Application\_DB\_\<guid\>

3.  Search\_Service\_Application\_PropertyStoreDB\_\<guid\>

## See also

[Install Microsoft Dynamics AX Enterprise Search](install-microsoft-dynamics-ax-enterprise-search.md)

  


