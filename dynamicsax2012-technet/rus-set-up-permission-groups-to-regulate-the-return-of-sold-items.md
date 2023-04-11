---
title: (RUS) Set up permission groups to regulate the return of sold items
TOCTitle: (RUS) Set up permission groups to regulate the return of sold items
ms:assetid: 61010684-1800-46e5-9b23-73618850e86e
ms:mtpsurl: https://technet.microsoft.com/library/Dn530768(v=AX.60)
ms:contentKeyID: 59683048
author: tonyafehr
ms.date: 04/28/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.RetailPosPermissionGroup
- Forms.RetailPositionPosPermission
- POS
- disallow return
- permission group
- nonreturnable item
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up permission groups to regulate the return of sold items 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use the **Permission groups** form to set up parameters that determine whether to allow or reject the return of sales items that are not returned during the shift in which they are sold. You can assign the created permission group to a worker in the **Workers** form.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>



## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Version</strong></p></td>
<td><p>Microsoft Dynamics AX 2012 R2 with cumulative update 7 or later</p></td>
</tr>
<tr class="even">
<td><p><strong>Country/region</strong></p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: Russia</p></td>
</tr>
</tbody>
</table>


1.  Click **Retail** \> **Setup** \> **POS** \> **Permission groups**.

2.  Click **New** to create a permission group, and then enter the required details. For more information, see [Permission groups (form)](https://technet.microsoft.com/library/hh597270\(v=ax.60\)).

3.  In the **POS permission group ID** and **Description** fields, enter a name and a description for the permission group.

4.  On the **Permissions** FastTab, in the **Return during a different shift** field, select one of the following to regulate the item that is not returned during the shift during which it is sold.
    
      - **Disallow return** – Disallow the return of the item
    
      - **Warn for return** – Display a warning message when the item is returned
    
      - **Allow return** – Allow the return of the item
    

    > [!NOTE]
    > <P>If you select <STRONG>Warn for return</STRONG>, Microsoft Dynamics AX displays a form, where you can specify whether to allow the return of the item.</P>



5.  Close the **Permission groups** form.

6.  Click **Retail** \> **Common** \> **Workers**. Select a worker, and then on the **Action Pane**, click the **Retail** tab.

7.  In the **Set up** group, click **POS permissions**.

8.  Select the **Override permissions** check box to override the permissions for the worker.

9.  In the **POS permission group** field, select the permission group for the worker.

## See also

[Set up retail products](set-up-retail-products.md)

[Set up a retail hierarchy](set-up-a-retail-hierarchy.md)

[View retail sales](view-retail-sales.md)

  


