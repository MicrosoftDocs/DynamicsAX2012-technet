---
title: Set up packing and container closing profiles for manual pack process
TOCTitle: Set up packing and container closing profiles for manual pack process
ms:assetid: a41ab053-2635-4323-91ad-f2c8c94303bc
ms:mtpsurl: https://technet.microsoft.com/library/Dn553187(v=AX.60)
ms:contentKeyID: 62200127
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.WHSPackProfile
- Forms.WHSCloseContainerProfile
- closing profiles
- container closing profiles
- packing profiles
audience: Application User
ms.search.region: Global
---

# Set up packing and container closing profiles for manual pack process 


_**Applies To:** Microsoft Dynamics AX 2012 R3_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Warehouse management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



This topic describes how to set up the profiles that are used during the manual packing and close container processes. These profiles control the validation and packing of inventory items into outbound shipping containers. Before packing, you must set up a container and determine the item that is being shipped in the container. After the container is packed, you use a container closing profile to close the container and indicate that the container is ready for shipping.

## 1\. Set up a packing profile

Use the **Packing profiles** form to define the default values that can be selected in the **Select a packing profile.** window during the manual packing process. You can create several packing profiles for different packing operations.

1.  Click **Warehouse management** \> **Setup** \> **Packing** \> **Packing profiles**.

2.  Enter an ID and description for the packing profile.

3.  In the **Container closing profile ID** field, select the default container closing profile for the specified packing profile.

4.  In the **Container ID mode** field, select either **Manual** or **Auto** to indicate if the container ID is entered manually or generated automatically when the container is created.

5.  Optional: Select the **Autocreate container at container close** check box to automatically create a container in Microsoft Dynamics AX when you close the previously packed container.

## 2\. Set up a container closing profile

The container closing profile defines the default values that are used during the container closing process.

1.  Click **Warehouse management** \> **Setup** \> **Containers** \> **Container closing profiles**.

2.  Enter a description and ID for the container closing profile.

3.  In the **Manifest at** field, select either **Container close** or **Shipment close** to specify when the manifest should happen. For example, when you select **Container close**, the rating process and the verification of the shipping carrier for the container is initiated.

4.  In the **Warehouse** field, select the warehouse that the container closing profile will be associated with.

5.  Select the default location for final shipment, and the unit of weight for the container.

6.  In the **Printer path** field, enter the network path for a printer to print the shipping label.

7.  Optional: Select the **Print shipping label** check box to print the shipping label when the container is closed.

8.  Optional: Select the **Print container contents** check box to print a report of the contents of the container.

9.  Optional: Select the **Print packing slip** check box to print the packing slip for the container.

## Related tasks

[Set up containerization](set-up-containerization.md)

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

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
<td><p><strong>Configuration keys</strong></p></td>
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>. Expand the <strong>Trade</strong> license key, and select the <strong>Warehouse and Transportation management</strong> configuration key.</p></td>
</tr>
</tbody>
</table>

  


