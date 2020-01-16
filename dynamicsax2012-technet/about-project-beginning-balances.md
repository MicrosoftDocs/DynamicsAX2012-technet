---
title: About project beginning balances
TOCTitle: About project beginning balances
ms:assetid: 2e859c6c-17d0-4d4b-8ea3-2baa69bcf1e0
ms:mtpsurl: https://technet.microsoft.com/library/Hh208530(v=AX.60)
ms:contentKeyID: 36056279
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About project beginning balances 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

By entering beginning balance transactions, you can transfer projects to Microsoft Dynamics AX without affecting the general ledger. For example, if you have been tracking a project offline or in another program, you can migrate the project to Microsoft Dynamics AX, specify a beginning balance, and then continue to track the project information. You can also use a beginning balance journal if you have been recording project costs and revenues in Microsoft Dynamics AX, but have not recorded details in **Project management and accounting** and now want to track project details.

**Example**

In Microsoft Dynamics AX, in the **Sales price (hour)** form, you create sales prices for project 9012 as described in the following table.

<table style="width:100%;">
<colgroup>
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
<col style="width: 14%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Effective date</strong></p></th>
<th><p><strong>Category</strong></p></th>
<th><p><strong>Worker</strong></p></th>
<th><p><strong>Project</strong></p></th>
<th><p><strong>Currency</strong></p></th>
<th><p><strong>Sales price model</strong></p></th>
<th><p><strong>Pricing</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>June 10, 2011</p></td>
<td><p>Service</p></td>
<td><p>AWA</p></td>
<td><p>9012</p></td>
<td><p>EUR</p></td>
<td><p>Quantity</p></td>
<td><p>10.00</p></td>
</tr>
<tr class="even">
<td><p>June 10, 2011</p></td>
<td><p>Service</p></td>
<td><p>AMO</p></td>
<td><p>9012</p></td>
<td><p>EUR</p></td>
<td><p>Quantity</p></td>
<td><p>15.00</p></td>
</tr>
<tr class="odd">
<td><p>June 12, 2011</p></td>
<td><p>Service</p></td>
<td><p>AMO</p></td>
<td><p>9012</p></td>
<td><p>EUR</p></td>
<td><p>Quantity</p></td>
<td><p>20.00</p></td>
</tr>
</tbody>
</table>


In Microsoft Dynamics AX, in the **Hour** journal, enter a line for worker AWA for project 9012. The effective date is June 11, 2011, and the category is **Service**. EUR 10.00 is automatically inserted as the sales price in the journal line. Now enter a line for worker AMO for the same effective date and category. EUR 15.00 is inserted into the hour journal line.

On June 15, 2011, add another line for AMO. The new price EUR 20.00 is inserted because effective June 12, 2011, this is the valid price. However, when you perform the same action for worker AWA, the sales price remains at EUR 10.00 because no sales prices with more recent effective dates have been created for worker AWA.


> [!NOTE]
> <P>A beginning balance transaction cannot be adjusted in the way other transaction types are. Beginning balance transactions do not need to be adjusted because they do not have an impact on the general ledger. Instead, to change the beginning balance in a project, you can enter another beginning balance journal that has a negative amount. This adjusts the overall beginning balance.</P>



## See also

[Create a project beginning balance](create-a-project-beginning-balance.md)

[Beginning balance journal (form)](https://technet.microsoft.com/library/hh209585\(v=ax.60\))

[Journal lines for beginning balances (form)](https://technet.microsoft.com/library/hh227479\(v=ax.60\))

  


