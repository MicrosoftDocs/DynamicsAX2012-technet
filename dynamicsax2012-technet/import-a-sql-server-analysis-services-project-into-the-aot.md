---
title: Import a SQL Server Analysis Services Project into the AOT
TOCTitle: Import a SQL Server Analysis Services Project into the AOT
ms:assetid: ee6b90ca-d735-4670-9504-26f4b54466b9
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn754850(v=AX.60)
ms:contentKeyID: 62504010
ms.date: 06/11/2014
mtps_version: v=AX.60
---

# Import a SQL Server Analysis Services Project into the AOT [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

If you have multiple partitions in Microsoft Dynamics AX, you may want to use Power View to analyze cube data in multiple partitions. Because financial dimensions and calendars may vary between different partitions, in each partition you must provide cubes that contain financial dimensions that are specific to that partition. You can then modify and deploy each partition-specific Analysis Services project. This topic explains how to deploy Analysis Services projects for each partition and then save the projects to the AOT so that you can maintain them separately.

### Deploy cubes to each partition

1.  Update the default Analysis Services project that is included with Microsoft Dynamics AX to add financial dimensions and calendars that are relevant to the current partition. For more information, see [Update an Existing SQL Server Analysis Services Project](how-to-update-an-existing-sql-server-analysis-services-project.md).

2.  Deploy the Analysis Services project to the partition you want the custom dimensions and calendars in. For more information, see [Deploy an Existing SQL Server Analysis Services Project](how-to-deploy-an-existing-sql-server-analysis-services-project.md).

3.  Repeat steps 1 and 2 for each partition-specific Analysis Services project you want to deploy.
    

    > [!NOTE]
    > <P>Data that is shown in the Microsoft Dynamics AX client is filtered by partition. For example, a list of available financial dimensions that you see when you add financial dimensions in the Analysis Services project wizard shows only the dimensions that are in your current partition. When you deploy a partition-specific project to another partition, these dimensions will contain empty data. Or if the target partition coincidentally has a financial dimension with the same name but different data values, you may see unexpected values in the dimension. To avoid this scenario, you can save the original Analysis Services project to disk, update that local copy of the project, and then deploy it. Then you can switch to another partition and repeat. To save an Analysis Services project to disk, right-click the project in the AOT and then click <STRONG>Edit</STRONG>.</P>



### Import projects into the AOT

1.  In the AOT, under the **Visual Studio Projects** node, right-click **Analysis Services Projects** and then click **Import**.
    

    > [!NOTE]
    > <P>Before you import a project, you must create a partition-specific project that uses the deployed Analysis Services database for each partition, as demonstrated in the previous procedure. We recommend that you rename the project so that it reflects the partition.</P>



2.  In **Choose Analysis Services project**, select the project to import. Click **Open**.

3.  Repeat for each partition-specific Analysis Services project you want to maintain.
    

    > [!NOTE]
    > <P>When you deploy the project by using the Analysis Services project wizard, the system will apply appropriate partition filters based on the partitions that are deployed.</P>


  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

