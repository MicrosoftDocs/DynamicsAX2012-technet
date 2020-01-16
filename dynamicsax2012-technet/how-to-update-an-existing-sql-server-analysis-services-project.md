---
title: 'How to: Update an Existing SQL Server Analysis Services Project'
TOCTitle: 'How to: Update an Existing SQL Server Analysis Services Project'
ms:assetid: bb15b5df-7080-432f-bef9-bdd8f1a233a0
ms:mtpsurl: https://technet.microsoft.com/library/Cc618242(v=AX.60)
ms:contentKeyID: 28119577
author: Khairunj
ms.date: 11/14/2012
mtps_version: v=AX.60
---

# How to: Update an Existing SQL Server Analysis Services Project 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can incrementally update the objects for an existing SQL Server Analysis Services project that is based on metadata defined in Microsoft Dynamics AX. This topic describes how to use the Analysis Services project wizard to update Analysis Services projects.

You can update an Analysis Services project without overwriting the core dimensional model object definitions, such as dimensions, dimension attributes, measure groups, measures, and cubes. For example, you can update an Analysis Services project to add new language translations for tables and fields that are referenced by a deployed cube or to update the cube enumeration list. You can also add new attributes and measures to a perspective and then update a deployed cube by using the Analysis Services project wizard.

You can create Key Performance Indicators (KPIs) in SQL Server Business Intelligence Development Studio (BIDS) after you create an Analysis Services project. KPIs are also included with the default cubes. When you configure or update the Analysis Services project, the KPIs will be updated based on the following:

  - If the KPI is in both the source and the target Analysis Services projects, the KPI from the source will override the KPI from the target.

  - If the KPI is in the source only, the KPI from the source will be added to the updated Analysis Services project.

  - If the KPI is in the target only, the KPI from the target will remain unchanged in the Analysis Services project. In this case, the KPI may become invalid if it uses data that has been removed from the Analysis Services project. You must validate your KPIs in this scenario.


> [!NOTE]
> <P>When you update an Analysis Services project by using the wizard, the old project is overwritten by a new Analysis Services project. A backup copy of the project folder is available in your temp directory. For example, the project folder may be located in C:\Users\User1\AppData\Local\Temp\1.</P>



### To update a SQL Server Analysis Services project

1.  Click **Tools** \> **Business Intelligence (BI) tools** \> **SQL Server Analysis Services project wizard**. The **SQL Server Analysis Services Project wizard** form is displayed. Click **Next**.

2.  Select **Update**. Click **Next**.

3.  Select the Analysis Services project to update. You can select a project that is already deployed in the AOT or open a project from a file. Click **Next**. If the project builds, click **Next** again.

4.  Select the perspectives that correspond with the cubes you want included in the project. Move the perspectives you want to include in the project to the **Selected** list. Move the perspectives you want to remove from the project to the **Available** list. Click **Next**.

5.  On the **Select Microsoft Dynamics AX dimensions** page, select Microsoft Dynamics AX dimensions to associate with the cubes and then click **Next**.
    

    > [!NOTE]
    > <P>Dimensions in the <STRONG>Selected</STRONG> list will be included in the project. Dimensions in the <STRONG>Available</STRONG> list will not be added to the project, and will be removed if they were in the project before.</P>



6.  Select calendars to use for date dimensions and then click next.
    

    > [!NOTE]
    > <P>Calendars in the <STRONG>Selected</STRONG> list will be included in the project. Calendars in the <STRONG>Available</STRONG> list will not be added to the project, and will be removed if they were in the project before.</P>



7.  Select label languages that you want to include as translations and then click **Next**.
    

    > [!NOTE]
    > <P>Languages in the <STRONG>Selected</STRONG> list will be included in the project. Languages in the <STRONG>Available</STRONG> list will not be added to the project, and will be removed if they were in the project before. If values in your cubes display in English even after you specify a different language, you can open the Analysis Services project in BIDS and modify the translations. For more information, see the <A href="http://technet.microsoft.com/en-us/library/ms166708.aspx">SQL Server documentation</A>.</P>
    > <P>Label translations are global and incremental. You cannot update the labels for a subset of elements.</P>
    > <P>Language translations are supported if you use Microsoft SQL Server 2008 Enterprise Edition or Microsoft SQL Server 2008 R2 or later for your Analysis Services server. Do not include translations in the project if you are using a Microsoft SQL Server 2008 Standard Edition Analysis Services server. If you do and you get an error, you can delete the Analysis Services project in the AOT and then redeploy the Analysis Services project by using the SQL Server Analysis Services project update wizard. Alternatively, you can edit the Analysis Services project in BIDS to remove the translations. To do this, open the Analysis Services project in BIDS. Open each cube and dimension, and then click the <STRONG>Translations</STRONG> tab. Right-click the column for each translation that is not a Default translation, and then click Delete translation. After you have removed the translations, import the project into the AOT.</P>



8.  Select to add foreign currency support to the Analysis Services project. Click **Next**.

9.  Specify deployment options. Click **Next** and complete the wizard.
    

    > [!NOTE]
    > <P>Financial dimensions only work in the partition they are created in. Only deploy Analysis Services projects to the partition you are currently in.</P>



Log files are generated in two locations. Information is logged in the global log file path that is specified in the [Analysis servers form](https://technet.microsoft.com/library/hh597195\(v=ax.60\)). This log file is not generated if you do not specify the global log file path. When the Analysis Services project is updated, the information about the changes to the project is logged in the UpdateProjectActions.log file in the project folder.

## See also

[Working with Analysis Services Projects](working-with-analysis-services-projects.md)

