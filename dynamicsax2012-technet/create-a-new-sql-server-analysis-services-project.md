---
title: Create a New SQL Server Analysis Services Project
TOCTitle: Create a New SQL Server Analysis Services Project
ms:assetid: 134366bb-2430-4ebf-bacf-3aa2ee4ea0b9
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Cc583157(v=AX.60)
ms:contentKeyID: 28119313
ms.date: 08/27/2014
mtps_version: v=AX.60
---

# Create a New SQL Server Analysis Services Project [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

After you create perspectives that identify the tables and views that contain the measures and dimensions for your cubes, you can generate an Analysis Services project so that you can work with the cubes in SQL Server Business Intelligence Development Studio (BIDS).

The following procedure explains how to use the Analysis Services project wizard to generate a new Analysis Services project from one or more perspectives in Microsoft Dynamics AX.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><img src="images/Dd309683.TopicIcons_Task(AX.60).png" title="Tasks" alt="Tasks" />
<p>Create a project</p></td>
<td><img src="images/Dn507140.TopicIcons_Resources(AX.60).png" title="Resources" alt="Resources" />
<p></p>
<p><a href="http://www.youtube.com/watch?v=latzrx75_94">How to create a cube in Microsoft Dynamics AX 2012 (video)</a></p></td>
</tr>
</tbody>
</table>


## Create a project

1.  Click **Tools** \> **Business Intelligence (BI) tools** \> **SQL Server Analysis Services project wizard**. The **SQL Server Analysis Services Project wizard** form appears. Click **Next**.

2.  Select **Create**. In the **Project name** field, provide a name for the project. Click **Next**.

3.  Select the perspectives you want to use to create cubes. Move them from the **Available** list to the **Selected** list, and then click **Next**.
    

    > [!NOTE]
    > <P>The <STRONG>Usage</STRONG> property for a perspective determines whether the perspective can be used to generate an Analysis Services project. Only perspectives that have the <STRONG>Usage</STRONG> property set to <STRONG>OLAP</STRONG> appear in the list.</P>



4.  On the **Select Microsoft Dynamics AX dimensions** page, select Microsoft Dynamics AX dimensions to associate with the cubes, move them to the **Selected** list, and then click **Next**.

5.  Select calendars to use for date dimensions from the **Available** list, move them to the **Selected** list, and then click **Next**.

6.  Select label languages that you want to include as translations from the **Available** list, move them to the **Selected** list, and then click **Next**.

7.  Select **Add foreign currency support to the Analysis Services project** if you want to add the analysis currency dimension and convert measures to foreign currencies based on the accounting currency and exchange rates. You must have at least one date dimension in the Analysis Services project if you want to add foreign currency support. For more information about date dimensions, see [How to: Create a Date Dimension for a Cube](how-to-create-a-date-dimension-for-a-cube.md). Click **Next**.

8.  Select **Save to AOT** to save the project. To save the project to the hard disk, select **Save to disk** and type the location where you want to save the project. Click **Next**.

9.  On the **Deployment options** page, specify whether to deploy the project and whether to process the project. If you do not process the project, you will not be able to browse cube data. Click **Next**. Click **Finish**.
    

    > [!NOTE]
    > <P>Financial dimensions only work in the partition they are created in. Only deploy Analysis Services projects to the partition you are currently in.</P>



Information is logged in the global log file path that is specified in the [Analysis servers form](https://technet.microsoft.com/en-us/library/hh597195\(v=ax.60\)). Log files are not generated if you do not specify the global log file path.

Analysis Services projects are not supported for Microsoft Dynamics AX TFS source control. To put an Analysis Services project under TFS source control, set the source control provider in TFS to Visual Studio instead of Microsoft Dynamics AX. Add files to source control directly from the TFS source control explorer.

## See also

[Analytics in Microsoft Dynamics AX](analytics-in-microsoft-dynamics-ax.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

