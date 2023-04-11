---
title: Set up lines for a cost template
TOCTitle: Set up lines for a cost template
ms:assetid: 50e95c3e-8664-4e7e-832e-534a9cc9274d
ms:mtpsurl: https://technet.microsoft.com/library/Aa548909(v=AX.60)
ms:contentKeyID: 36057247
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- estimate templates
- cost template
- cost estimates
- cost line
audience: Application User
ms.search.region: Global
---

# Set up lines for a cost template 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you create a cost template in the **Cost template** form, you define the names of the cost lines and assign all categories to the three system cost lines: items, hours, and expenses. If the cost template is applied in its default state, the percentage of completion is calculated based on the consumption in all categories for the three system cost lines.

You can modify this setup by adding cost lines in the **Estimate template** form or including an optional number of additional categories in the calculation of a percentage of completion.


> [!TIP]
> <P>In the cost template system, every category must reference a cost line, and each category can reference only one cost line. To remove a category reference from one cost line, you must move the category reference to another cost line in the form.</P>



1.  Click **Project management and accounting** \> **Setup** \> **Estimates** \> **Cost template**.

2.  In the **Cost template** form, create a new cost template or select the cost template that you want to modify, and then click **Cost lines**.

3.  In the **Estimate template** form, click **New** to create a new cost line, or select an existing line.

4.  On the **Categories** tab, in the **Remaining categories** list, select the category that you want to move from another cost line, and click the arrow to add it to the current line.

5.  Select the **Percentage of completion** check box to include a cost line in the calculation of a percentage completion. If the check box is cleared, the cost line will be excluded from the calculation.
    

    > [!NOTE]
    > <P>The check boxes for the three system-created cost lines are selected by default.</P>


  


