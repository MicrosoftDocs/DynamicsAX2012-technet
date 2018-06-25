---
title: Inventory dimension group upgrade
TOCTitle: Inventory dimension group upgrade
ms:assetid: a5527e0c-dce8-414f-b0cd-4a3084a8a837
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg731885(v=AX.60)
ms:contentKeyID: 35132795
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Inventory dimension group upgrade [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Preprocess inventory dimension groups** form to define how company-specific inventory dimension groups are consolidated into a set of inventory dimension groups that are shared between companies.

If you are upgrading to Microsoft Dynamics AX 2012 R2 or AX 2012 R3, you must identify a data partition when performing this task. If you have configured multiple partitions, the procedure must be repeated for each partition. For more information about data partitions and upgrade, see [Configure partitions](configure-partitions.md).

## The inventory dimension grouping is new

In Microsoft Dynamics AX 2012, the inventory dimension groups are split into three groups: product, storage, and tracking. The groups contain the following dimensions.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Group</p></th>
<th><p>Dimensions</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Product</p></td>
<td><p><strong>Color</strong>, <strong>Size</strong>, <strong>Configuration</strong></p></td>
</tr>
<tr class="even">
<td><p>Storage</p></td>
<td><p><strong>Site</strong>, <strong>Warehouse</strong>, <strong>Location</strong>, <strong>Pallet ID</strong></p></td>
</tr>
<tr class="odd">
<td><p>Tracking</p></td>
<td><p><strong>Batch number</strong>, <strong>Serial number</strong></p></td>
</tr>
</tbody>
</table>


The **Color**, **Size**, and **Configuration** dimensions, which were previously called item dimensions, are now found in the product dimension group. Furthermore, the storage dimensions are now divided between a storage dimension group and a tracking dimension group.

Each inventory dimension group that already exists must be mapped to one of the new product, storage, or tracking dimension groups.


> [!NOTE]
> <P>If an inventory dimension group has no active item dimensions, the mapping methods do not create a product dimension group. A product dimension group cannot be created if there are no active dimensions.</P>



## Map preexisting company-specific inventory dimension groups to the new dimension groups

When you start preprocessing inventory dimension groups, the **Preprocess inventory dimension groups** form contains a list of all preexisting inventory dimension groups from all companies. You must map the company-specific inventory groups to the new product, storage, and tracking dimension groups.

1.  Click **Inventory dimension group upgrade** to open the **Preprocess inventory dimension groups** form.

2.  In the **Partition key** field, select a partition for preprocessing.

3.  Click **Dimension group mapping**, and then select a method of mapping. The following options are available:
    
      - **Map dimension groups 1:1** – For each preexisting inventory dimension group, create three dimension groups: a product dimension group, a storage dimension group, and a tracking dimension group. The active dimension in each new dimension group corresponds to one type of active dimensions in the original, company-specific inventory dimension group. The names of the new dimension groups consist of consecutive numbers prefixed by PDG\_, SDG\_, or TDG\_.
        

        > [!NOTE]
        > <P>You can change this naming convention in the <STRONG>Map dimension groups 1:1</STRONG> form.</P>

    
      - **Map dimension groups ID** – For each preexisting inventory dimension group, create product, storage, and tracking dimension groups, just as when you use the **Map dimension groups 1:1** method. The difference between this method and the 1:1 mapping method is the naming convention. When you use this method, the names of the new dimension groups are copied from the original, company-specific inventory dimension groups.
        

        > [!NOTE]
        > <P>Consolidating inventory dimension groups from different companies that use identical naming conventions for dimension groups can cause validation errors. For example, if both company 1 and company 2 have an inventory dimension group that is named DimGroup1, the identical names can cause a validation error. The active dimensions and the setup of the active dimensions must be identical. Otherwise, the upgrade consolidation is not successful.</P>

    
      - **Map dimension groups by setup** – Map dimension groups according to the setup of the active dimensions and settings of the inventory dimension groups. For more information, see the next section.

4.  Click **Dimension groups** to view and change the names and descriptions of the new dimension groups.
    
    1.  To change the name of a new dimension group, you must first change the name of the original inventory dimension group in the **Preprocess product dimension groups**, **Preprocess storage dimension groups**, or **Preprocess tracking dimension groups** form.
    
    2.  Then select the new name for the product, storage, and tracking dimension groups in the **Preprocess inventory dimension groups** form.

5.  Click **Validation report** to check for validation errors before you set the dimension groups to ready for upgrade.

6.  After you resolve all validation errors, click **Set to ready for upgrade**.

## Mapping according to the setup of the inventory dimension groups

You can map the new, shared product, storage, and tracking dimension groups according to the active item and storage dimension setup in the original inventory dimension groups. For each preexisting inventory dimension group, the program proposes a product dimension group, a storage dimension group, and a tracking dimension group. When new groups are created, the configurations in all the existing inventory groups is considered. The new product, storage, and tracking groups are based on information that is merged from all the existing inventory groups.

When you map inventory dimension groups by setup, the program may propose the same product, storage, or tracking dimension group for more than one inventory dimension group. This is because the existing inventory dimension groups have the same setup of active product, storage or tracking dimensions.

## Example: Map inventory dimension groups by setup

In the following example, three company-specific inventory dimension groups, InvGroup1, InvGroup2, and InvGroup3, are consolidated into product, storage, and tracking dimension groups.


> [!TIP]
> <P>The three inventory groups can come from three different companies, or they can all come from the same company.</P>



The following table shows the setup of the active dimensions in the three inventory dimension groups.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>InvGroup1</p></th>
<th><p>InvGroup2</p></th>
<th><p>InvGroup3</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p></p></td>
<td><p>Color</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Size</p></td>
<td><p></p></td>
<td><p>Size</p></td>
</tr>
<tr class="odd">
<td><p>Configuration</p></td>
<td><p></p></td>
<td><p>Configuration</p></td>
</tr>
<tr class="even">
<td><p>Site</p></td>
<td><p>Site</p></td>
<td><p>Site</p></td>
</tr>
<tr class="odd">
<td><p>Warehouse</p></td>
<td><p>Warehouse</p></td>
<td><p>Warehouse</p></td>
</tr>
<tr class="even">
<td><p>Serial number</p></td>
<td><p></p></td>
<td><p>Serial number</p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p>Batch number</p></td>
<td><p>Batch number</p></td>
</tr>
</tbody>
</table>


The following table shows the dimension groups that Microsoft Dynamics AX proposes, based on the setup of the preexisting company-specific inventory dimension groups.

  - For the item dimensions, **Color**, **Size**, and **Configuration**, the setup of active dimensions in InvGroup2 differs from the setup in InvGroup1 and InvGroup3. Therefore, two product dimension groups are created.

  - For the storage dimensions, **Site** and **Warehouse**, the setup of active dimensions is identical in InvGroup1, InvGroup2, and InvGroup3. Therefore, one storage dimension group is created.

  - For the **Batch number** and **Serial number** dimensions, the setup of active dimensions is different in InvGroup1, InvGroup2, and InvGroup3. Therefore, three tracking dimension groups are created.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Product dimension groups</p></th>
<th><p>Storage dimension groups</p></th>
<th><p>Tracking dimension groups</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>PDG_1</p></td>
<td><p>SDG_1</p></td>
<td><p>TDG_1</p></td>
</tr>
<tr class="even">
<td><p>- Size</p></td>
<td><p>- Site</p></td>
<td><p>- Serial number</p></td>
</tr>
<tr class="odd">
<td><p>- Configuration</p></td>
<td><p>- Warehouse</p></td>
<td><p>- Batch number</p></td>
</tr>
<tr class="even">
<td><p>PDG_2</p></td>
<td><p></p></td>
<td><p>TDG_2</p></td>
</tr>
<tr class="odd">
<td><p>- Color</p></td>
<td><p></p></td>
<td><p>- Serial number</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p></p></td>
<td><p>TDG_3</p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p></p></td>
<td><p>- Batch number</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

