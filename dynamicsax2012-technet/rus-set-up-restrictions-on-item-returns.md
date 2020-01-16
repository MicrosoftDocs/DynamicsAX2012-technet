---
title: (RUS) Set up restrictions on item returns
TOCTitle: (RUS) Set up restrictions on item returns
ms:assetid: 129de8fa-74d3-4287-8085-48df3ce6ad07
ms:mtpsurl: https://technet.microsoft.com/library/Dn530769(v=AX.60)
ms:contentKeyID: 59683047
author: Khairunj
ms.date: 04/28/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.RetailCategory
- Forms.RetailPosPermissionGroup
- nonreturnable items
- product hierarchy
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up restrictions on item returns 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use the **Released product details**, **Retail product hierarchy**, and **Permission groups** forms to set up parameters that determine whether to reject the return of nonreturnable items for Retail and point of sale (POS). These items can belong to specific categories of items such as medicinal drugs or undergarments.

You can also update the restrictions on products using the **Update products** and **Mass update worksheet** forms.


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


## Set up restrictions on item returns in the Retail product hierarchies form

1.  Click **Retail** \> **Setup** \> **Category hierarchies** \> **Retail product hierarchy**.

2.  In the left pane, select the category of the nonreturnable item.

3.  On the **Retail product properties** FastTab, select the **Disallow item return** check box, and then close the form.
    

    > [!NOTE]
    > <P>You must deselect the <STRONG>Disallow item return</STRONG> check box before you update retail products by using the <STRONG>Update products</STRONG> form.</P>



4.  Click **Retail** \> **Setup** \> **POS** \> **Permission groups**.

5.  Select the permission group that is associated with the nonreturnable item. The permission group can be the role of the person who is responsible for registering Retail and POS sales.

6.  On the **Permissions** FastTab, select the **Allow return of non-returnable items** check box. A worker, such as a cashier, who is assigned to this permission group, can view the items that are marked as nonreturnable during return processing.
    

    > [!NOTE]
    > <P>This check box is also available on the <STRONG>POS position permissions</STRONG> form.</P>



## Update item return restrictions using the Update products and Mass update worksheet forms

1.  Click **Retail** \> **Setup** \> **Category hierarchies** \> **Retail product hierarchy**.

2.  In the left pane, select a category for the nonreturnable item.

3.  Click **Update products**.

4.  Select or clear the **Disallow item return** check box.

5.  Click **Update** to update all of the products in the selected category.

6.  Click **Retail** \> **Periodic** \> **Mass update worksheet**.

7.  Press CTRL+N to create a worksheet.

8.  Add products to the worksheet, and then click **OK**. For more information, see [Mass update worksheet (form)](https://technet.microsoft.com/library/hh597155\(v=ax.60\)).

9.  Select a product that you want to update, and then select the **Disallow item return** check box.

## Set up restrictions on item returns in the Released product details form

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  Double-click a released product, and then click the **Retail** FastTab.

3.  Select the **Disallow item return** check box to indicate that the product is nonreturnable.

## See also

[Set up retail products](set-up-retail-products.md)

[Set up a retail hierarchy](set-up-a-retail-hierarchy.md)

[View retail sales](view-retail-sales.md)

[POS position permissions (form)](https://technet.microsoft.com/library/hh597327\(v=ax.60\))

  


