---
title: Configure an Existing SQL Server Analysis Services Project
TOCTitle: Configure an Existing SQL Server Analysis Services Project
ms:assetid: ee0aa94f-28f9-4427-82c6-51a18e0939be
ms:mtpsurl: https://technet.microsoft.com/library/Gg724140(v=AX.60)
ms:contentKeyID: 35133500
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Configure an Existing SQL Server Analysis Services Project 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX includes several default cubes. If you deploy these cubes before you modify your license configuration, you must update the cubes that you deployed by using the Analysis Services project wizard.

## Deploying the Default Cubes

You can use SQL Server Business Intelligence Development Studio (BIDS) or the Analysis Services project wizard to deploy the default cubes.

### To deploy the default cubes

  - Follow the steps in [Deploy the default cubes](deploy-the-default-cubes.md).

## Changing the Configuration

During implementation, it is common to change configuration keys. You should update the default cubes after the configuration phase is completed. You configure Microsoft Dynamics AX by entering license codes in the **License information** form, and by enabling or disabling configuration keys in the **License configuration** form.


> [!NOTE]
> <P>If you change your Microsoft Dynamics AX configuration more than one time, you can use the <STRONG>Configure</STRONG> option in the Analysis Services project wizard the first time, but you should use the <STRONG>Update</STRONG> option to update your Analysis Services project to reflect any subsequent configuration changes.</P>



### To configure Microsoft Dynamics AX

  - Follow the steps in [Configure application functionality](configure-application-functionality.md).

## Configuring Analysis Cubes

After you configure Microsoft Dynamics AX, you must configure any analysis cubes that were already deployed based on the original configuration. Use the Analysis Services project wizard to remove measures, dimensions, and all dependent objects that are not available due to the Microsoft Dynamics AX configuration change.

You can create Key Performance Indicators (KPIs) in SQL Server Business Intelligence Development Studio (BIDS) after you create an Analysis Services project. KPIs are also included with the default cubes. When you configure or update the Analysis Services project, the KPIs will be updated based on the following:

  - If the KPI is in both the source and the target Analysis Services projects, the KPI from the source will override the KPI in the target.

  - If the KPI is in the source only, the KPI from the source will be added to the updated Analysis Services project.

  - If the KPI is in the target only, the KPI from the target will remain unchanged in the Analysis Services project. In this case, the KPI may become invalid if it uses data that has been removed from the Analysis Services project. You must validate your KPIs in this scenario.


> [!NOTE]
> <P>When you configure an Analysis Services project by using the wizard, the old project is overwritten by a new Analysis Services project. A backup copy of the project folder is available in your temp directory. For example, the project folder may be located in C:\Users\User1\AppData\Local\Temp\1.</P>



### To configure analysis cubes

1.  Click **Tools** \> **Business Intelligence (BI) tools** \> **SQL Server Analysis Services project wizard**. Click **Next**.

2.  On the **Select an option** page, select **Configure**. Click **Next**.

3.  On the **Select an existing Analysis Services project** page, select the project to update. You can select a project from the AOT or from disk. Click **Next** After the project builds, click **Next** again.

4.  Select the **Apply the Microsoft Dynamics AX configuration to the Analysis Services project** check box. Click **Next**.

5.  Select additional languages for which to provide label translations and then click **Next**.
    

    > [!NOTE]
    > <P>Language translations are supported if you use Microsoft SQL Server 2008 Enterprise Edition or Microsoft SQL Server 2008 R2 or later for your Analysis Services server. Do not include translations in the project if you are using a Microsoft SQL Server 2008 Standard Edition Analysis Services server. If you do and you get an error, you can delete the Analysis Services project in the AOT and then redeploy the Analysis Services project by using the SQL Server Analysis Services project update wizard. Alternatively, you can edit the Analysis Services project in BIDS to remove the translations. To do this, open the Analysis Services project in BIDS. Open each cube and dimension, and then click the <STRONG>Translations</STRONG> tab. Right-click the column for each translation that is not a Default translation, and then click Delete translation. After you have removed the translations, import the project into the AOT.</P>



6.  After the project is generated, click **Next**.

7.  On the **Deployment options** page, specify whether to deploy the project and whether to process the project. If you do not process the project, you will not be able to browse cube data. Click **Next** until you reach the end of the wizard.


> [!NOTE]
> <P>The fixed database schema that Microsoft Dynamics AX uses means that related data is not removed from the database when a configuration key is disabled. When you disable a license or configuration key, some data and functionality in Microsoft Dynamics AX is removed from cubes. You must remove all reports and KPIs that rely on the data that is unavailable.</P>



Information is logged in the global log file path that is specified in the [Analysis servers form](https://technet.microsoft.com/library/hh597195\(v=ax.60\)). Log files are not generated if you do not specify the global log file path.

## See also

[How to: Create and Apply a Configuration Key](https://technet.microsoft.com/library/aa893167\(v=ax.60\))

[About license codes and configuration keys](https://technet.microsoft.com/library/aa548653\(v=ax.60\))

[Configure application functionality](configure-application-functionality.md)

  


