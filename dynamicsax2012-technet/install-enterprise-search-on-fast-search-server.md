---
title: Install Enterprise Search on FAST Search Server
TOCTitle: Install Enterprise Search on FAST Search Server
ms:assetid: 50945280-0565-4786-b0c9-f26d0f947f27
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh575214(v=AX.60)
ms:contentKeyID: 39555353
ms.date: 04/18/2014
mtps_version: v=AX.60
dev_langs:
- powershell
---

# Install Enterprise Search on FAST Search Server 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to deploy Microsoft Dynamics AX Enterprise Search on FAST Search Server 2010 for SharePoint.

## Prerequisites

The following list includes links to documents that describe how to configure the prerequisites for Microsoft Dynamics AX Enterprise Search. The list also includes links to documents that describe how to install and configure FAST Search Server 2010 for SharePoint. You must complete all of the tasks in order before you install Microsoft Dynamics AX Enterprise Search on FAST Search Server 2010. If you do not complete every task, Enterprise Search on FAST Search Server 2010 is not installed correctly.

1.  [Configure the Search Crawler account](configure-the-search-crawler-account.md)

2.  [Add AOT queries to the Search configuration](add-aot-queries-to-the-search-configuration.md)

3.  [Install SharePoint 2012 Products and Technologies](http://go.microsoft.com/fwlink/?linkid=241980)

4.  [Install FAST Search Server 2010 for SharePoint](http://go.microsoft.com/fwlink/?linkid=241974)

5.  [Configure a stand-alone deployment or a multiple server deployment (FAST Search Server 2010 for SharePoint)](http://go.microsoft.com/fwlink/?linkid=241975)

6.  [Create and set up the Content Search Service Application (FAST Search Server 2010 for SharePoint)](http://go.microsoft.com/fwlink/?linkid=241976)

7.  [Create and set up the Query Search Service Application (FAST Search Server 2010 for SharePoint)](http://go.microsoft.com/fwlink/?linkid=241977)

8.  [Enable queries from Microsoft SharePoint Server (FAST Search Server 2010 for SharePoint)](http://go.microsoft.com/fwlink/?linkid=241978)

9.  [Install Hotfix 2276339 on the SharePoint server](http://go.microsoft.com/fwlink/?linkid=241979)

## Configure the Business Connector proxy account for membership in the db\_owner role

The Business Connector proxy account must be a member of the **db\_owner** role for each FAST Search database. Use Microsoft SQL Server Management Studio to verify that the Business Connector proxy account is listed as a user for each database, and that the user account is a member of the **db\_owner** role.

## Increase the time-out for Farm Search Administration

After you install Microsoft Dynamics AX Enterprise Search as described later in this topic, Setup starts a full crawl of the content sources for Microsoft Dynamics AX and Microsoft Dynamics AX metadata. The crawl must be completed without errors before you can configure managed properties as described later in this topic. By default, the time-out for the filter daemon in SharePoint is too short. Therefore, you receive the following error message when the content source for Microsoft Dynamics AX metadata is crawled: *The filter daemon did not respond within the time-out limit.* Use the following procedure to increase the Farm Search Administration timeout.

1.  In SharePoint Central Administration, click **Manage Service Applications**.

2.  Select the search service application for the FAST Search connector.

3.  In the left navigation pane, click **Farm Search Administration**.

4.  Under **Farm-Level Search Settings**, change the default value of **Time-out (seconds)**, 60,60, to larger numbers, such as 120,120.

5.  Click **OK** to save your changes.

## Install Enterprise Search

If FAST Search is present on the server when you install Enterprise Search by using Microsoft Dynamics AX Setup, the system configures only the default FAST Search Server application, as specified in SharePoint. All other search service applications are ignored. After the installation is completed, the system performs a full crawl of the Microsoft Dynamics AX content sources. The full crawl of the content sources must be completed without errors before you can continue with the remaining procedures in this topic.

After the full crawl of the content sources is completed without errors, install Microsoft Dynamics AX Enterprise Search on the server. For more information, see [Install Microsoft Dynamics AX Enterprise Search](install-microsoft-dynamics-ax-enterprise-search.md).

## Create managed properties

FAST Search Server 2010 creates properties for crawled data. Microsoft Dynamics AX Enterprise Search enables a rich advanced search experience if these properties are mapped to Microsoft Dynamics AX managed properties. The following Windows PowerShell script creates managed properties for Microsoft Dynamics AX Enterprise Search and registers these properties so that they can be used by FAST Search Server 2010 at crawl time. The script also maps the crawled properties to managed properties to enable a rich advanced search experience.

1.  On the FAST Search Server, create a new \*.ps1 file. Copy and paste the following code into the \*.ps1 file.
    
    ``` powershell
    function MapManagedPropertyToCrawledProperty()
    {
      Param 
      (  
        [string]$managedProperty = $null,
        [string]$crawledProperty = $null,
        [int32]$managedPropertyType = 1
      )
    
      $EntityManagedProperty = New-FASTSearchMetadataManagedProperty -Name $managedProperty -Type $managedPropertyType
      $EntityCrawledProperty = Get-FASTSearchMetadataCrawledProperty -Name $crawledProperty
      $FullTextIndex = Get-FASTSearchMetadataFullTextIndex -Name Content
      $PropertyMapping = New-FASTSearchMetadataCrawledPropertyMapping -CrawledProperty $EntityCrawledProperty -ManagedProperty $EntityManagedProperty
      if ($managedPropertyType -eq 1)
      {
        New-FASTSearchMetadataFullTextIndexMapping -ManagedProperty $EntityManagedProperty -FullTextIndex $FullTextIndex -Level 1
      }
    
      Write-Host $managedProperty " mapped to " $crawledProperty
    }
    
    function MapManagedPropertyToCrawledProperties()
    {
      Param 
      (  
        [string]$managedProperty = $null,
        [string]$crawledProperties = $null,
        [int32]$managedPropertyType = 2
      )
    
      $EntityManagedProperty = New-FASTSearchMetadataManagedProperty -Name $managedProperty -Type $managedPropertyType
    
      $crawledProperties.split(",") | ForEach-Object
      {
        $crawledProperty = $_;
        $EntityCrawledProperty = Get-FASTSearchMetadataCrawledProperty -Name $crawledProperty    
        $PropertyMapping = New-FASTSearchMetadataCrawledPropertyMapping -CrawledProperty $EntityCrawledProperty -ManagedProperty $EntityManagedProperty
      }
    
      $FullTextIndex = Get-FASTSearchMetadataFullTextIndex -Name Content
      if ($managedPropertyType -eq 1)
      {
        New-FASTSearchMetadataFullTextIndexMapping -ManagedProperty $EntityManagedProperty -FullTextIndex $FullTextIndex -Level 1
      }
    
      Write-Host $managedProperty " mapped to " $crawledProperty
    }
    
    # Map predefined values
    MapManagedPropertyToCrawledProperty -managedProperty Entity -crawledProperty EntityName -managedPropertyType 1
    MapManagedPropertyToCrawledProperty -managedProperty EntityPath -crawledProperty EntityKey.Path -managedPropertyType 1
    MapManagedPropertyToCrawledProperty -managedProperty EntityHelpText -crawledProperty EntityKey.HelpText -managedPropertyType 1
    MapManagedPropertyToCrawledProperty -managedProperty EntityType -crawledProperty EntityKey.Type -managedPropertyType 2
    MapManagedPropertyToCrawledProperties -managedProperty PartitionKey -crawledProperty "CustTable,DocuRef,InventTable,EmployeeTable,HcmWorker,smmBusRelTable,VendTable" -managedPropertyType 2
    
    # Create empty properties required by client search query
    New-FASTSearchMetadataManagedProperty -Name Title1 -Type 1
    New-FASTSearchMetadataManagedProperty -Name Title2 -Type 1
    ```

2.  Run the \*.ps1 file from the FAST Search Server 2010 PowerShell command window. Figure 1 shows the results of the command.
    
    ![Output of FastSearch PowerShell command for EP](images/Hh575214.FastSearch1(AX.60).gif "Output of FastSearch PowerShell command for EP")
    
    *Figure 1: Output of the FAST Search Server 2010 PowerShell command for managed properties*
    
    The following list describes the actions of the script and the corresponding results in the output:
    
    1.  MapManagedPropertyToCrawledProperty -managedProperty Entity -crawledProperty EntityName -managedPropertyType 1
        
        The crawled property Entity was mapped to the managed property EntityName. The managed property is of type 1. Full-text index mapping was added to the property.
    
    2.  MapManagedPropertyToCrawledProperty -managedProperty EntityPath -crawledProperty EntityKey.Path -managedPropertyType 1
        
        The crawled property EntityPath was mapped to the managed property EntityKey.Path. The managed property is of type 1. Full-text index mapping was added to the property.
    
    3.  MapManagedPropertyToCrawledProperty -managedProperty EntityHelpText -crawledProperty EntityKey.HelpText -managedPropertyType 1
        
        The crawled property EntityHelpText was mapped to the managed property EntityKey.HelpText. The managed property is of type 1. Full-text index mapping was added to the property.
    
    4.  MapManagedPropertyToCrawledProperty -managedProperty EntityType -crawledProperty EntityKey.Type -managedPropertyType 2
        
        The crawled property EntityType was mapped to the managed property EntityKey.Type.
    
    5.  New-FASTSearchMetadataManagedProperty -Name Title1 -Type 1
        
        The managed property Title1 was registered.
    
    6.  New-FASTSearchMetadataManagedProperty -Name Title2 -Type 1
        
        The managed property Title2 was registered.

3.  After the managed properties are created, use SharePoint Central Administration to start a full crawl of the Microsoft Dynamics AX and Microsoft Dynamics AX metadata content sources.

## See also

[Checklist: Deploy Microsoft Dynamics AX Enterprise Search](checklist-deploy-microsoft-dynamics-ax-enterprise-search.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

