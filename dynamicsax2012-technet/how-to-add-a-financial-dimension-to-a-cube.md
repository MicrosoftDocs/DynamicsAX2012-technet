---
title: 'How to: Add a Financial Dimension to a Cube'
TOCTitle: 'How to: Add a Financial Dimension to a Cube'
ms:assetid: 507d6dab-53bb-4116-971b-f834bb3192c8
ms:mtpsurl: https://technet.microsoft.com/library/Hh128830(v=AX.60)
ms:contentKeyID: 35588429
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# How to: Add a Financial Dimension to a Cube 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Financial dimensions in Microsoft Dynamics AX help you analyze finance data. You can add financial dimensions to an Analysis Services project. The MainAccount financial dimension is included with Microsoft Dynamics AX, but you can include other financial dimensions in your Analysis Services project if you define additional financial dimensions.

## Adding Financial Dimensions to an Analysis Services Project

To add a financial dimension, run the Analysis Services project wizard and select the **Update** option. On the Add Microsoft Dynamics AX dimensions screen, select financial dimensions you want to include in your Analysis Services project.

### To add a financial dimension

1.  Click **Tools** \> **Business Intelligence (BI) tools** \> **SQL ServerAnalysis Services project wizard**. Click **Next**.

2.  Select **Update** and then click **Next**.

3.  Select an Analysis Services project to add the financial dimension to, and then click **Next**. After the project builds, click **Next** again.

4.  On the **Select perspectives** screen, click **Next**.

5.  On the Select Microsoft Dynamics AX dimensions screen, select financial dimensions you want to include in your Analysis Services project.

6.  Complete the wizard.
    

    > [!NOTE]
    > <P>Financial dimensions only work in the partition they are created in. Only deploy Analysis Services projects to the partition you are currently in.</P>



## See also

[Financial dimensions (form)](https://technet.microsoft.com/library/hh209534\(v=ax.60\))

  


