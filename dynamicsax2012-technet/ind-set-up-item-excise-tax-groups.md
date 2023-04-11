---
title: (IND) Set up item excise tax groups
TOCTitle: (IND) Set up item excise tax groups
ms:assetid: 57395474-730d-4198-aef4-969c9c257c83
ms:mtpsurl: https://technet.microsoft.com/library/JJ677826(v=AX.60)
ms:contentKeyID: 49385790
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Set up item excise tax groups 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can attach a tax code that is created for excise to an item tax group. You also can indicate how the excise tax must be calculated for each item.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Item sales tax groups**..

2.  Type a short code or identification for the item tax group in the **Item sales tax group** field and the name of the item tax group in the **Description** field.

3.  Click the **Setup** tab and select the excise tax code in the **Sales tax code** field.

4.  Enter other required information, as needed.

5.  Select the **Load on inventory** check box to indicate that the excise tax amount must be loaded on inventory.

6.  Specify the percentage of tax amount that must be loaded on inventory in the **Load on inventory %** field.

7.  Click **Formula designer** to open the **Formula designer** form, where you can create or update the formulas for the calculation of excise.

Refer to the following examples for defining the calculation expression for excise components.

**Example 1**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Tax code field</p></th>
<th><p>Taxable basis field</p></th>
<th><p>Calculation expression field</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>BED</p></td>
<td><p>Line amount</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>AED</p></td>
<td><p>Excl. line amount</p></td>
<td><p>+[BED]</p></td>
</tr>
</tbody>
</table>


**Example 2**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Tax code field</p></th>
<th><p>Taxable basis field</p></th>
<th><p>Calculation expression field</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>BED</p></td>
<td><p>Max. retail price</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>AED</p></td>
<td><p>Max. retail price</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>SED</p></td>
<td><p>Max. retail price</p></td>
<td><p>+[BED]+ [AED]</p></td>
</tr>
<tr class="even">
<td><p>E-Cess</p></td>
<td><p>Excl. line amount</p></td>
<td><p>+[SED]</p></td>
</tr>
<tr class="odd">
<td><p>SHE cess</p></td>
<td><p>Excl. line amount</p></td>
<td><p>+[SED]</p></td>
</tr>
</tbody>
</table>


## See also

[(IND) Formula designer (form)](https://technet.microsoft.com/library/jj677983\(v=ax.60\))

[(IND) Item sales tax groups (modified form)](https://technet.microsoft.com/library/jj710918\(v=ax.60\))

[(IND) Setting up excise tax groups and item tax groups](ind-setting-up-excise-tax-groups-and-item-tax-groups.md)

  


