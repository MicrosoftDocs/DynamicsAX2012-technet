---
title: 'How to: Deploy an Existing SQL Server Analysis Services Project'
TOCTitle: 'How to: Deploy an Existing SQL Server Analysis Services Project'
ms:assetid: 55ee3a4b-5889-418a-9a02-756b65f5f00f
ms:mtpsurl: https://technet.microsoft.com/library/Cc590284(v=AX.60)
ms:contentKeyID: 28119357
author: Khairunj
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# How to: Deploy an Existing SQL Server Analysis Services Project 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can deploy and process Analysis cubes by using the Analysis Services project wizard in Microsoft Dynamics AX) or by using SQL Server Business Intelligence Development Studio (BIDS).

Deploying an Analysis Services project creates the defined objects in an instance of Analysis Services. Processing the objects in an instance of Analysis Services extracts and then maps data from the data sources defined in the project into the cube objects. After the cube and dimensions are processed, you can view the data for the objects in the project.

### To deploy an Analysis Services project by using the Analysis Services project wizard

1.  Click **Tools** \> **Business Intelligence (BI) tools** \> **SQL Server Analysis Services project wizard**. The **SQL Server Analysis Services Project wizard** form appears. Click **Next**.

2.  Click **Deploy** and then click **Next**.

3.  Select the Analysis Services project to deploy. You can select a project that is already in the AOT or open a project from disk. Click **Next**.

4.  Select **Deploy the project**.
    

    > [!NOTE]
    > <P>If you are using Microsoft Dynamics AX 2012 R2, select the database to deploy, and then select <STRONG>Deploy</STRONG>. Specify whether to process the project, and then click <STRONG>Next</STRONG>.</P>



5.  Specify the following options:
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Option</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Analysis Services server</p></td>
    <td><p>Specify the Analysis Services server to which to deploy the project.</p></td>
    </tr>
    <tr class="even">
    <td><p>Analysis Services database</p></td>
    <td><p>Specify the existing Analysis Services database where you want to deploy the project.</p>
    <p>-OR-</p>
    <p>Specify to create a new Analysis Services database.</p></td>
    </tr>
    </tbody>
    </table>
    

    > [!NOTE]
    > <P>If you are using Microsoft Dynamics AX 2012 R2, skip this step.</P>



6.  Specify whether to process the project after it is deployed. If you do not process the cubes, you will not be able to browse cube data. Click **Next**.

After the project is deployed and processed, you can view the data in the project.

Information is logged in the global log file path that is specified in the [Analysis servers form](https://technet.microsoft.com/library/hh597195\(v=ax.60\)). Log files are not generated if you do not specify the global log file path.

### To deploy an Analysis Services project by using BIDS

1.  In the AOT in Microsoft Dynamics AX, right-click Analysis Services project that you want to deploy and then click **Edit**. Analysis Services projects are located under **Visual Studio Projects** \> **Analysis Services Projects**.
    

    > [!NOTE]
    > <P>If you have already deployed an Analysis Services project and you need to deploy it again, you must open it from the AOT. Otherwise, a duplicate WHERE clause will be added to the data source view.</P>



2.  In Solution Explorer, right-click the Analysis Services project, and then click **Properties**. The project **Property Pages** window opens. In the left pane, click **Deployment**, and then in the right pane, enter the deployment target group settings.

3.  Click **OK** to save the property changes.

4.  In Solution Explorer, right-click the Analysis Services project, and then click **Deploy**.

BIDS builds and then deploys the Analysis Services project to the specified instance of Analysis Services by using a deployment script. The progress of the deployment is displayed in two windows: the **Output** window and the **Deployment Progress** window. The **Output** window displays the overall progress of the deployment. The **Deployment Progress** window displays the detail about each step taken during deployment.

After the project is deployed and processed, you can view the data in the project.


> [!NOTE]
> <P>You might have to update the connection string of the project database file.</P>



## See also

[How to: Create a New SQL Server Analysis Services Project](create-a-new-sql-server-analysis-services-project.md)

[Working with Analysis Services Projects](working-with-analysis-services-projects.md)

