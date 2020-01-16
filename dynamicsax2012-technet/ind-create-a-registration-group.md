---
title: (IND) Create a registration group
TOCTitle: (IND) Create a registration group
ms:assetid: ce8bfaca-75f0-4e2d-90cb-1b64ad5c174b
ms:mtpsurl: https://technet.microsoft.com/library/JJ664925(v=AX.60)
ms:contentKeyID: 49386254
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Create a registration group 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

A tax registration group includes tax registration numbers for various tax types. The tax registration group is created to offset the tax amounts among the various tax types.

For example, you can create the following two tax registration groups.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Tax registration group</p></th>
<th><p>Tax type</p></th>
<th><p>Registration number</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>City one</p></td>
<td><p>Service tax</p></td>
<td><p>AAMES2696GST001</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p>Excise</p></td>
<td><p>AXRER8567NXM001</p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p>VAT</p></td>
<td><p>29390361850</p></td>
</tr>
<tr class="even">
<td><p>City two</p></td>
<td><p>Service tax</p></td>
<td><p>AAMES2696GST001</p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p>Excise</p></td>
<td><p>AXRER5987NXM001</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p>VAT</p></td>
<td><p>29390361870</p></td>
</tr>
</tbody>
</table>


You select a tax registration group in the **Sales tax payment** form. Click **General ledger** \> **Periodic** \> **Sales tax payments** \> **Sales tax payments**. The **In use** check box for that tax registration group is then selected automatically in the **Tax registration group** form. A selected check box indicates that the registration group is being used. Another user cannot select the tax registration group for tax settlement until the check box is cleared.


> [!NOTE]
> <P>When the <STRONG>Sales tax payment</STRONG> form is open, you cannot clear the <STRONG>In use</STRONG> check box for the selected tax registration group. However, you can clear the <STRONG>In use</STRONG> check box if the tax settlement process stops abruptly. For example, tax settlement stops if the system is shut down.</P>



1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **India** \> **Tax registration group**.

2.  Click **New** to create a new tax registration group.

3.  Enter the name and a description of the tax registration group.

4.  On the **Setup** tab, click **Add** to set up the tax registration numbers for the tax registration group.

5.  In the **Tax type** field, select the tax type. The following options are available:
    
      - **VAT**
    
      - **India sales tax**
    
      - **Excise**
    
      - **Service tax**

6.  Select the tax registration number and a description of the tax type.

## See also

[(IND) Sales tax payment (modified form)](https://technet.microsoft.com/library/jj664427\(v=ax.60\))

  


