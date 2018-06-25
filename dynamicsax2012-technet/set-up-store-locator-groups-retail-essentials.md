---
title: Set up store locator groups (Retail essentials)
TOCTitle: Set up store locator groups (Retail essentials)
ms:assetid: f3f710cf-d996-4d16-b647-fb79b26eefb9
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn736975(v=AX.60)
ms:contentKeyID: 62200452
ms.date: 08/15/2014
mtps_version: v=AX.60
---

# Set up store locator groups (Retail essentials) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up and use store locator groups to control which stores are included in a search when an employee searches for a product. Use store locator groups to define groups of stores based on location or other criteria, and then assign them to your stores. When an employee searches to see if a product is available at nearby stores, the search results include only the stores that are included in the store locator groups that are assigned to that store.


> [!IMPORTANT]
> <P>The store locator feature uses the address for the default warehouse that is assigned to the customer, product, or store to determine the shipping information to use when product orders are shipped. If no address is defined for the default warehouse, an error can occur.</P>
> <P>For more information about how to set up a default warehouse for Retail, see <A href="set-up-a-retail-store-retail-essentials.md">Set up a retail store (Retail essentials)</A>.</P>



**Example: Store locator groups and store locator group assignments**

In this example, you set up the store locator groups as described in the following table.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Group 1: Mall stores</p></th>
<th><p>Group 2: Flagship stores</p></th>
<th><p>Group 3: All stores</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><ul>
<li><p>Store 3</p></li>
<li><p>Store 5</p></li>
</ul></td>
<td><ul>
<li><p>Store 1</p></li>
<li><p>Store 3</p></li>
</ul></td>
<td><ul>
<li><p>Store 1</p></li>
<li><p>Store 2</p></li>
<li><p>Store 3</p></li>
<li><p>Store 4</p></li>
<li><p>Store 5</p></li>
<li><p>Store 6</p></li>
</ul></td>
</tr>
</tbody>
</table>


If an employee in store 1 searches to see whether a product is available at a local store, all stores are included in the inventory search results. This is because group 3, which is assigned to store 1, includes all stores. However, if an employee is searching in group 2, only stores 1 and 3 are included in the inventory search results. These are the only stores that are included in the store locator group that is assigned to group 2.

## Set up store locator groups

1.  Click **Retail essentials** \> **Channels** \> **Retail stores**.

2.  On the **Retail stores** list page, select a store, and then, on the **Action Pane**, on the **Set up** tab, in the **Set up** group, click **Store locator group assignment**.

3.  In the **Store locator group assignment** form, click **Store locator groups**.

4.  In the **Store locator groups** form, click **New**, and then enter a name and description for the store locator group.

5.  On the **Setup** FastTab, click **Add**, and then, in the **Store** field, select a store to add to the new store locator group. Add a new line for each store that you want to add to the group.


> [!NOTE]
> <P>In Retail essentials, the form that you use to complete this task includes a subset of the controls that are available for other configurations of Retail. If a topic about this form describes controls that you don't see, it may be because you’re using Retail essentials.</P>



## See also

[Set up a retail store (Retail essentials)](set-up-a-retail-store-retail-essentials.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

