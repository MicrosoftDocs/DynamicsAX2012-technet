---
title: Set up containerization
TOCTitle: Set up containerization
ms:assetid: a8ece442-4456-45f1-972a-2e091f0c9240
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn553190(v=AX.60)
ms:contentKeyID: 62200134
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- container
- pack
- Forms.WHSContainerGroup
- Forms.WHSContainerizationTable
- Forms.WHSContainerType
- Forms.WHSContainerAttributes
- containerize
- containerization
- outbound
- container attribute
- container build template
- container group
- container type
audience: Application User
ms.search.region: Global
---

# Set up containerization 


_**Applies To:** Microsoft Dynamics AX 2012 R3_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Warehouse management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



This topic describes how to automate the containerization of loads in **Warehouse management**. Automated containerization creates containers and the picking work for shipments when a wave is processed.

To set up containerization, you must create the following:

  - **Container type** ─ Define the physical characteristics of the containers. Use container types to pack inventory items into a specific type and size of packaging, such as bins or pallets.

  - **Container groups** ─ Create groups of container types that are similar. For example, a container group can include container types that have similar size dimensions. A container group specifies the sequence in which containers are packed, and the fill percentage of each container.

  - **Container build template** ─ Create templates that define rules for containerization. For example, rules for mixing inventory and other packing strategies.

  - **Wave templates** – Set up one or more wave templates to create the picking work for containerization.

## 1\. Set up a wave template for containerization

You must set up one or more shipping wave templates for containerization. Wave templates include criteria that determine the following:

  - How to process waves. This can be either manual or automatic.

  - How to create picking work. This is determined by the wave methods. The wave template must include the **containerization** method.

  - How to match items or allocation lines with a wave.

For more information, see [Create a wave template](create-a-wave-template.md).

## 2\. Set up a container type

Use container types to create descriptions of containers, including maximum values for physical size dimensions and weight capacity. When a containerized wave is processed, the containers are created based on the container type information.

To set up a container type, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Containers** \> **Container type**.

2.  Click **New** to create a new container type.

3.  Enter a unique identifier (ID) and description for the container type.

4.  In the **Tare weight** field, enter the actual or estimated weight of the container.

5.  In the **Maximum weight** field, enter the maximum weight that the container can hold.

6.  In the **Containerization maximum volume**, **Containerization maximum length**, **Containerization maximum width**, and **Containerization maximum height** fields, specify the physical dimensions of the container.
    

    > [!NOTE]
    > <P>The values for length and width are interchangeable. This means that you can rotate items laterally, or on the x-axis, if needed. For example, if the length is 2 feet, and the width is 1 foot, you can change the length to 1 foot and the width to 2 feet. Note that this does not apply to the height dimension. You cannot change the height value to rotate an item vertically.</P>



7.  Optional: Select custom attribute values for the container in the fields for attributes. Attributes are custom values that are used to filter or sort items based on a value that is otherwise not available. For example, if you want to pack items for a particular customer, you can create an attribute for the customer name. You create attributes in the **Container attributes** form.

## 3\. Set up a container group

You can set up logical groups of container types. For each group, you can specify the sequence in which to pack the containers and the percentage of the containers to fill. Microsoft Dynamics AX uses the size dimensions of the item to determine whether it will fit in a container. The container that is closest to the size dimensions of the item is used. If you have multiple container types in a group, we recommend that you arrange the sequence by size, so that the largest container is first, number 1 in the sequence, and the smallest container is last.

To set up a container group, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Containers** \> **Container groups**.

2.  Click **New** to create a container group.

3.  Enter a unique ID and description for the container group.

4.  On the **Details** FastTab, click **New** to add a container type to the group.

5.  In the **Container type** field, select a container type.

6.  Click **Move up** or **Move down** to specify the sequence in which the container types are packed.

## 4\. Set up a container build template

You can set up rules for the containerization process, such as inventory mixing rules and other packing strategies. For example, you can set up a rule so that workers cannot pack allocation lines that represent sales orders from different customers in the same container.

To set up a container build template, follow these steps.

1.  Click **Warehouse management** \> **Setup** \> **Containers** \> **Container build template**.

2.  Create a new container build template.

3.  In the **Containerization name** and **Sequence number** fields, enter the name of the containerization template and the order that is matched to allocation lines.
    

    > [!NOTE]
    > <P>Microsoft Dynamics AX 2012 R3 will apply the first template that the allocation line meets the query criteria for. Therefore, put the template with the most specific criteria at the top of the list. The broader the criteria, the more likely that an allocation line will meet the criteria. This could lead to lines being assigned to the wrong container. If needed, you can click <STRONG>Move up</STRONG> or <STRONG>Move down</STRONG> to change the sequence of templates.</P>



4.  In the **Container group ID** field, select the container group from which to create containers.

5.  In the **Base query types** field, select the query type that will determine what to pack and what to base the filter query on. The following options are available:
    
      - **Sales allocation line** ─ Pack allocation lines that are created for sales orders.
    
      - **Transfer allocation line** ─ Pack allocation lines that are created for transfer orders.
    
      - **Container** ─ Pack a container that was already created by the containerization process. For example, this is used for nesting containers.
        

        > [!NOTE]
        > <P>To use nesting containers, you must make the containerization method repeatable. For more information, see <A href="create-a-wave-template.md">Create a wave template</A>.</P>



6.  On the **General** FastTab, in the **Wave step code** field, enter the unique identifier of the wave process method that links the container build template to steps in a wave template.

7.  Optional: Select the **Allow split picks** check box to allow workers to pack items from a work order in separate containers. This requires that the entire quantity fits in the container. The largest unit of measure in the allocation line is always used.

8.  Optional: In the **Pack by unit** field, select the unit of measure that will represent the container. For example, you can indicate that a case is a container. If you pack by the unit of measure, you cannot also specify a container group because the unit of measure is the container.

9.  In the **Container packing strategy** field, select the packing strategy to use. The following options are available:
    

    > [!NOTE]
    > <P>The strategy applies only to sales allocation lines and transfer allocation lines.</P>

    
      - **Pack into all open containers** – The system evaluates whether the allocation line will fit in any container that was created during the containerization cycle.
    
      - **Pack into current container only** – The system only evaluates whether the allocation line will fit in the most recently created container.

10. Optional: To set up rules for packing allocation lines in containers, click **Mixing Logic Breaks**. For example, you can create a rule that will allow workers to pack allocation lines for two different items in the same container.
    
    To define a mixing rule, follow these steps:
    
    1.  In the **Mixing Logic Breaks** form, click **New**.
    
    2.  In the **Table** field, select the table that contains the field to use as a criterion for the mixing logic break.
    
    3.  In the **Field Select** field, select the field to use as a criterion for the mixing logic break.
    
    4.  Repeat these steps until you have added all of the criteria for the mixing logic break.
    

    > [!NOTE]
    > <P>If you use mixing logic, we recommend that you sort by the same fields in the filter criteria query. This will reduce the number of containers that are created.</P>



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

  


