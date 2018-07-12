---
title: Set up site and warehouse hierarchies
TOCTitle: Set up site and warehouse hierarchies
ms:assetid: 5881b5d1-eba5-48c8-bc48-107d0a162631
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg242481(v=AX.60)
ms:contentKeyID: 36870657
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- assign a warehouse to a site
- set up a warehouse system
- site and warehouse hierarchy
- warehouses at sites
- site and warehouse structure
- site infrastructure
audience: Application User
ms.search.region: Global
---

# Set up site and warehouse hierarchies 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To set up a warehouse system at a site, you can assign one or more warehouses to the site. A particular warehouse can only be assigned to one site. After a warehouse is assigned to a site, you cannot assign that warehouse to a different site.


> [!NOTE]
> <P>This task has the following prerequisites:</P>
> <UL>
> <LI>
> <P>A site must be created.</P>
> <LI>
> <P>One or more warehouses must be created.</P></LI></UL>



## Assign a warehouse to a site

1.  Click **Inventory management** \> **Setup** \> **Inventory breakdown** \> **Warehouses**.

2.  Select a warehouse in the list.

3.  On the **General** tab, in the **Site** field, select the site that you want to assign the warehouse to.

4.  On the **General** tab, in the **Quarantine warehouse** field, you can select a quarantine warehouse for the site. The quarantine warehouse cannot be a warehouse that is already assigned to another site.

5.  To view the hierarchy of sites and warehouses, click the **Hierarchy** tab. This tab displays the tree node that represents the selected warehouse and the site that the warehouse is assigned to. The tree node is expanded and displays all the warehouses that are assigned to the site. Any production units that are assigned to the site are also displayed.
    

    > [!NOTE]
    > <P>You can also view the hierarchy of sites and warehouses in the <STRONG>Sites</STRONG> form.</P>



After the hierarchy of sites and warehouses is created, you can modify it by performing the following tasks:

  - Add new warehouses.

  - Move inventory from a warehouse on one site to a warehouse on another site.

  - Delete old warehouses.

## Invalid combinations of warehouses and sites

If a warehouse is assigned to a site, and transactions are generated for that combination of a site and warehouse, the warehouse cannot be assigned to another site.

Additionally, if a warehouse is deleted and then recreated, you can only assign the new warehouse to the site that the deleted warehouse was assigned to.

The following table lists additional rules that apply when you enter combinations of site fields and warehouse fields in the **Warehouses** form. If you enter a combination that is not valid, the program displays an error message, and you cannot complete the action.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Current site ID</p></th>
<th><p>Current transit warehouse</p></th>
<th><p>Current quarantine warehouse</p></th>
<th><p>New site ID</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Blank</p></td>
<td><p>Blank</p></td>
<td><p>Blank</p></td>
<td><p>Any site</p></td>
</tr>
<tr class="even">
<td><p>Blank</p></td>
<td><p>A warehouse on site A</p></td>
<td><p>Blank</p></td>
<td><p>Any site</p></td>
</tr>
<tr class="odd">
<td><p>Blank</p></td>
<td><p>Blank</p></td>
<td><p>A warehouse on site A</p></td>
<td><p>Site A. The site must be the same site that the quarantine warehouse is assigned to.</p></td>
</tr>
<tr class="even">
<td><p>Blank</p></td>
<td><p>A warehouse on site A</p></td>
<td><p>A warehouse on site A</p></td>
<td><p>Site A. The site must be the same site that the quarantine warehouse is assigned to.</p></td>
</tr>
<tr class="odd">
<td><p>Blank</p></td>
<td><p>A warehouse on site A</p></td>
<td><p>A warehouse on site B</p></td>
<td><p>Site B. The site must be the same site that the quarantine warehouse is assigned to.</p></td>
</tr>
<tr class="even">
<td><p>Site A</p></td>
<td><p>Blank</p></td>
<td><p>Blank</p></td>
<td><p>Any site, provided that no transactions have been generated for this site/warehouse combination</p></td>
</tr>
<tr class="odd">
<td><p>Site A</p></td>
<td><p>A warehouse on site A</p></td>
<td><p>Blank</p></td>
<td><p>Any site, provided that no transactions have been generated for this site/warehouse combination</p></td>
</tr>
<tr class="even">
<td><p>Site A</p></td>
<td><p>Blank</p></td>
<td><p>A warehouse on site A</p></td>
<td><p>Site A. The site cannot be modified.</p></td>
</tr>
<tr class="odd">
<td><p>Site A</p></td>
<td><p>A warehouse on site A</p></td>
<td><p>A warehouse on site A</p></td>
<td><p>Site A. The site cannot be modified.</p></td>
</tr>
<tr class="even">
<td><p>Blank</p></td>
<td><p>Any warehouse</p></td>
<td><p>A warehouse is assigned as the quarantine warehouse for one or more warehouses on site A.</p></td>
<td><p>Site A. The site must be the same site that the quarantine warehouse is assigned to.</p></td>
</tr>
<tr class="odd">
<td><p>Site A</p></td>
<td><p>Any warehouse</p></td>
<td><p>A warehouse is assigned as the quarantine warehouse for one or more warehouses on site A.</p></td>
<td><p>Site A. The site cannot be modified.</p></td>
</tr>
</tbody>
</table>


## Default rules and validation rules for sites and warehouses

After you set up a hierarchy of sites and warehouses, the following rules apply when you work with journals and order transactions:

  - When you select a site from a site lookup form, the warehouse lookup form lists only warehouses that are assigned to the site that you selected. If you select a warehouse that is not assigned to the selected site, the program displays an error message, and you cannot complete the action.
    

    > [!NOTE]
    > <P>You can set a warehouse that is not assigned to the selected site by using X++ instead of the form. The <STRONG>Site</STRONG> field is then updated to match the site that is associated with the new warehouse.</P>



  - When you select a warehouse from a warehouse lookup form, the site that is associated with that warehouse is automatically entered in the **Site** field.

  - If you enter or select a site that is not associated with the selected warehouse, the program keeps the site that you entered and clears the **Warehouse** field.

  - You cannot specify a site on a transfer order line. Additionally, the site dimension cannot be enabled from the **Dimensions display** form that you open from a transfer order.

## See also

[Sites (form)](https://technet.microsoft.com/en-us/library/hh242661\(v=ax.60\))

[Warehouses (form)](https://technet.microsoft.com/en-us/library/aa620570\(v=ax.60\))

[Create sites](create-sites.md)

  


