---
title: Set up store locator groups in Retail
TOCTitle: Set up store locator groups in Retail
ms:assetid: e3f49c05-3374-428b-87cd-dc5a2a8dd296
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ728715(v=AX.60)
ms:contentKeyID: 49556620
ms.date: 08/15/2014
mtps_version: v=AX.60
---

# Set up store locator groups in Retail 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes how to set up and use store locator groups to control which brick-and-mortar stores are included in a search when a customer in an online store searches for a product. You use store locator groups to define groups of stores, based on location or other criteria, and then assign those groups to your online stores. When a customer in an online store searches to see whether a product is available at nearby stores, the search results include only the stores that are included in the store locator groups that are assigned to that online store.


> [!NOTE]
> <P>In Microsoft Dynamics AX 2012 R3, you can’t add online stores to a store locator group. You can add only brick-and-mortar stores.</P>



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


Next, you assign the store locator groups to your online stores as described in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Online store A</p></th>
<th><p>Online store B</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Assigned store locator group:</p>
<ul>
<li><p>Group 3: All stores</p></li>
</ul></td>
<td><p>Assigned store locator groups:</p>
<ul>
<li><p>Group 1: Mall stores</p></li>
<li><p>Group 2: Flagship stores</p></li>
</ul></td>
</tr>
</tbody>
</table>


A customer who is shopping in online store A then searches to see whether a product is available at a local store. In this case, all stores are included in the inventory search results, because group 3, which is assigned to online store A, includes all stores.

However, a customer who is shopping in online store B also searches for product availability at a local store. In this case, only stores 1, 3, and 5 are included in the search results, because groups 1 and 2, which are assigned to online store B, include only these three stores.


> [!IMPORTANT]
> <P>The store locator feature uses the address of the default warehouse that is assigned to the customer, product, or store to determine the shipping information that is used when product orders are shipped. If no address is defined for the default warehouse, an error can occur.</P>
> <P>For more information about how to set up a default warehouse for Microsoft Dynamics AX 2012 for Retail, see <A href="set-up-a-retail-store.md">Set up a retail store</A>.</P>



## Set up store locator groups

1.  Click **Retail** \> **Setup** \> **Store locator groups**.

2.  In the **Store locator groups** form, click **New**, and then enter a name and description for the store locator group.

3.  On the **Setup** FastTab, click **Add**, and then, in the **Store** field, select a store to add to the new store locator group. Add a new line for each store that you want to add to the group.

## Assign store locator groups to an online store

1.  Click **Retail** \> **Common** \> **Retail channels** \> **Online stores**. In the **Online stores** list, double-click a store.

2.  In the **Online store** form, on the **Action Pane**, on the **Set up** tab, in the **Setup** group, click **Store locator group assignment**.

3.  In the **Store locator group assignment** form, in the **Locator group** field, select the store locator group to assign to the store. Add a new line for each store locator group that you want to add to the store.

4.  Click **Retail store locator groups** to view the stores that are included in a selected store locator group. To add stores to a store locator group, click **Add**. To remove stores from a store locator group, click **Remove**.

## See also

[Store locator group assignment (form)](https://technet.microsoft.com/en-us/library/jj728726\(v=ax.60\))

[Store locator groups (form)](https://technet.microsoft.com/en-us/library/jj728728\(v=ax.60\))

[Set up a retail store](set-up-a-retail-store.md)

[Set up an online store](set-up-an-online-store.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

