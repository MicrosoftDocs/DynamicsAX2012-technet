---
title: 'How to: Upgrade Microsoft Dynamics AX cubes'
TOCTitle: 'How to: Upgrade cubes'
ms:assetid: 4cd62ae4-dc8c-4de0-8a1f-4ee49e6e6a8b
ms:mtpsurl: https://technet.microsoft.com/library/Gg731924(v=AX.60)
ms:contentKeyID: 35132852
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# How to: Upgrade Microsoft Dynamics AX cubes 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you upgrade to a new version of Microsoft Dynamics AX from Microsoft Dynamics AX 2009, you must create new cubes to display the information your old cubes displayed. When you upgrade from Microsoft Dynamics AX 2012 to Microsoft Dynamics AX 2012 R2, you can upgrade the cubes by using the SQL Server Analysis Services project wizard. The cubes can be categorized as follows:

  - Default cubes

  - Customized default cubes

  - Custom cubes

## Default Cubes

Default cubes are included with Microsoft Dynamics AX. If you upgrade from Microsoft Dynamics AX 2012 to Microsoft Dynamics AX 2012 R2, you can upgrade the cubes by using the SQL Server Analysis Services project wizard. If you upgrade to a new version of Microsoft Dynamics AX from Microsoft Dynamics AX 2009, you can use new default cubes to replace your existing default cubes.

### To upgrade default cubes

1.  Click **Tools** \> **Business Intelligence (BI) tools** \> **Analysis Services project wizard**.

2.  If you upgrade from Microsoft Dynamics AX 2012 to Microsoft Dynamics AX 2012 R2, follow the steps in the wizard to **update** an Analysis Services project that contains the default cubes you want to use. If you upgrade to a new version of Microsoft Dynamics AX from Microsoft Dynamics AX 2009, follow the steps in the wizard to **create** an Analysis Services project that contains the default cubes you want to use.

3.  Manually delete the legacy cubes from your Analysis Services database.

## Customized Default Cubes

Customized default cubes are default cubes that you modify. If you upgrade from Microsoft Dynamics AX 2012 to Microsoft Dynamics AX 2012 R2, you can upgrade customized default cubes by using the SQL Server Analysis Services project wizard. If you upgrade to a new version of Microsoft Dynamics AX from Microsoft Dynamics AX 2009, you must apply the same customizations to the default cubes in the new version. Either modify the corresponding perspective and then create an Analysis Services project that contains the customized default cube, or perform customizations in Microsoft SQL Server Business Intelligence Development Studio (BIDS) or SQL Server Data Tools.

### To upgrade a customized default cube

1.  In the AOT, expand **Data Dictionary** \> **Perspectives**.

2.  Optionally modify the perspective that corresponds to the default cube you want to customize. For example, you can specify dimension attributes and measures in the perspective.

3.  Click **Tools** \> **Business Intelligence (BI) tools** \> **Analysis Services project wizard**. If you upgrade from Microsoft Dynamics AX 2012 to Microsoft Dynamics AX 2012 R2, follow the steps in the wizard to **update** an Analysis Services project that contains the customized default cubes you want to use. If you upgrade to a new version of Microsoft Dynamics AX from Microsoft Dynamics AX 2009, follow the steps in the wizard to **create** an Analysis Services project that contains the default cubes you want to use.

4.  Optionally customize your cube in SQL Server Business Intelligence Development Studio or SQL Server Data Tools.

5.  Manually delete the old cube from your Analysis Services database.

## Custom Cubes

Custom cubes are cubes that you create from scratch. If you upgrade from Microsoft Dynamics AX 2012 to Microsoft Dynamics AX 2012 R2, you can upgrade custom cubes by using the **Update** path in the SQL Server Analysis Services project wizard. If you upgrade to a new version of Microsoft Dynamics AX from Microsoft Dynamics AX 2009, you must recreate the custom cube manually. To create a custom cube, create a perspective that defines the data that will be included in the cube, and then run the Analysis Services project wizard.


> [!NOTE]
> <P>If you use a perspective from your last version of Microsoft Dynamics AX instead of creating a new one, you must manually set the <STRONG>Usage</STRONG> property for the perspective to <STRONG>OLAP</STRONG>.</P>



### To create a custom cube

  - For information about how to create a custom cube, see [Defining Cubes in Microsoft Dynamics AX](defining-cubes-in-microsoft-dynamics-ax.md).
    

    > [!NOTE]
    > <P>Manually delete old custom cubes from your Analysis Services database.</P>



## See also

[Working with Analysis Services Projects](working-with-analysis-services-projects.md)

  


