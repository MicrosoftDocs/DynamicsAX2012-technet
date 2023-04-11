---
title: About array variable group
TOCTitle: About array variable group
ms:assetid: c325e7cc-476b-43cf-84fa-9743339bd00e
ms:mtpsurl: https://technet.microsoft.com/library/Aa550711(v=AX.60)
ms:contentKeyID: 36676411
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About array variable group 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use variable groups of the array type be to present a product model’s modeling variables in a grid, similar to the grids found elsewhere in Microsoft Dynamics AX 2012. Each modeling variable in the group will then be shown as a separate column in the grid.


> [!NOTE]
> <P>This information applies only to Product builder.</P>



If you want to make the current variable group into an array, select the **Array** check box in the **Variable group** form that opens when you click **Grouping** in the **Product model** form. The **Max.** field is used to specify the number of rows in this table, that is, the number of array elements for each modeling variable in the variable group. Whenever you refer to one of the modeling variables from an array variable group, you must specify not only the name of the variable, but also the number, that is the index, of the specific array element.

When you change the values of the **Array** or **Max.** fields for a variable group, the values, you enter are automatically transferred to the corresponding fields for each modeling variable in the group. You cannot change these values separately for one modeling variable. You have to change them in the **Variable group** form.

  


