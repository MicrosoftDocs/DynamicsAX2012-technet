---
title: Update the Publishing Job Configuration
TOCTitle: Update the Publishing Job Configuration
ms:assetid: 14539c45-0e22-4d10-9940-809e3748affb
ms:mtpsurl: https://technet.microsoft.com/library/Dn168132(v=AX.60)
ms:contentKeyID: 53257401
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Update the Publishing Job Configuration 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

The Microsoft Dynamics AX for Retail publishing job has parameters that are stored in a .NET application configuration file. The file is loaded at runtime each time the job is started. Before the file is called by the publishing job code, it must be extracted from your SharePoint configuration database, where it is persisted in serialized form.

You can update the configuration file before Microsoft Dynamics AX is installed by opening the RetailPublishingJob.App.config file and modifying its contents. After you deploy Microsoft Dynamics AX, the configuration file will be persisted in the configuration database and will be used each time the publishing job runs.


> [!NOTE]
> <P>Microsoft Dynamics AX 2012 R3 has a tool in the Retail SDK that you can use to update the publishing job configuration. For more information, see <A href="microsoft-dynamics-ax-for-retail-online-channel-tools.md">Microsoft Dynamics AX for Retail online channel tools</A>.</P>



If you update the configuration file after Microsoft Dynamics AX is installed, you must read the configuration file from the configuration database, update it, and then save it.


> [!NOTE]
> <P>The maximum number of listings that the publishing job can retrieve in one page while querying the database (one trip to the database) is 2,100. If you modify your settings to retrieve more listings than the maximum, the job will fail.</P>



## Settings of the Publishing Job

The following example shows XML that contains the settings of the publishing job:

    <jobConfiguration CategoriesPageSize="200"
                        ProductAttributesPageSize="200"
                        CRTListingPageSize="2000"
                        ChannelListingPageSize="500"
                        ListingMapPageSize="10000"
                        ForceTimingInfoLogging ="false"
                        DefaultUncategorizedListName ="UncategorizedList"
                        MaxListLengthForInitialPublishing ="20000"
                        MaxListLengthForIncrementalPublishing ="0"
                        MaxListFieldCount ="200"
                        ListingTitleAttributeKey="Productname"
                        MaxCatalogSizePerPublishingIteration="0"
                        MaxActiveCrawlerWaitTime="0">
        <TypeMappings>
          <add Name="Specification" Value="Note"/>
          <add Name="Features" Value="Note" />
        </TypeMappings>
        <PartitioningSchema>
        </PartitioningSchema>
      </jobConfiguration>

## Reading the Publishing Job Configuration

The job configuration is persisted in the configuration database with the ID 920EEF5F-8BB4-4855-AB4A-7D3C28919F13.

The following code demonstrates how to read the configuration file.

    Guid JobSettingsId = new Guid("920EEF5F-8BB4-4855-AB4A-7D3C28919F13");
    RetailPublishingJobSettings currentSettings = (RetailPublishingJobSettings)SPFarm.Local.GetObject(JobSettingsId);

This code returns an instance of the RetailPublishingJobSettings class, which is defined in the Microsoft.Dynamics.Retail.SP.PublishingConnector.dll assembly and has two public fields:

  - AppConfigString

  - CommerceRuntimeConfigString

The AppConfigString field is the Commerce Runtime (CRT) configuration that you might want to update if you are customizing the CRT. The CommerceRuntimeConfigString field contains the XML configuration file that is described above.

## Updating the Publishing Job Configuration

The following code demonstrates how to read, modify, and save the configuration file.

``` 
        RetailPublishingJobSettings settings = (RetailPublishingJobSettings)SPFarm.Local.GetObject(JobSettingsId);
        // Delete old settings.
        settings.Delete();

        // Modify original settings.
        settings = new RetailPublishingJobSettings(SPFarm.Local.TimerService, JobSettingsId)
        {
            // Typically you would use XML parsing to find and modify correct attribute.
            AppConfigString = settings.AppConfigString.Replace(@"""UncategorizedList""", @"""CustomList"""),
            CommerceRuntimeConfigString = settings.CommerceRuntimeConfigString
        };

        settings.Update();
```

The configuration file that contains the jobSettings section also contains a section called connectionStrings. The connectionStrings section contains a connection string called CommerceRuntimeConnectionString that points to the CRT database. You can use the same procedure of reading, modifying, and saving the configuration to update the connection string.

  


