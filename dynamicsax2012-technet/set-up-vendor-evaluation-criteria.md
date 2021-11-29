---
title: Set up vendor evaluation criteria
TOCTitle: Set up vendor evaluation criteria
ms:assetid: 69415ee9-c809-4145-94bd-2d19678e2a73
ms:mtpsurl: https://technet.microsoft.com/library/Dn765128(v=AX.60)
ms:contentKeyID: 63008007
author: Khairunj
ms.date: 02/06/2015
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up vendor evaluation criteria 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


In your role as a purchasing agent or purchasing manager, you can set up vendor evaluation criteria to evaluate vendor performance. This is useful if you want to see how a vendor is rated, either by an overall rating or by a specific criterion. When you rate a vendor, the rating appears as the **Specialist rating** on the **Employee services** page of the Enterprise Portal for Microsoft Dynamics AX. After you’ve created vendor evaluation criteria, procurement professionals can rate vendors on the **Vendors** FastTab in the **Procurement categories: %1** form. If you evaluate a vendor in a procurement category, your evaluation will appear as a **Specialist rating** on the **Employee services** page of the Enterprise Portal.

This topic describes how to do the following:

  - Set up vendor evaluation criteria, such as quality or price.

  - Create a vendor criterion group, where specific criteria can be grouped together.

  - Assign an evaluation criterion group to one or more procurement categories.

## Workflow for setting up vendor evaluation criteria

The following illustration shows the order in which the tasks covered in this topic should be performed. The numbers correspond to the procedures later in this topic.

![Set up vendor evaluation criteria in this order](images/Dn765128.SetUpVendorEvaluationCriteriaWorkflow(AX.60).png "Set up vendor evaluation criteria in this order")

## This task is part of a bigger process

The following illustration shows where setting up vendor evaluation criteria fits into the overall procurement and sourcing process. You must set up vendor evaluation criteria to see how a vendor is rated according to predefined categories when you search for products. This process relates to maintaining vendor category assignments and profiles, searching for a vendor, and identifying potential sources and supply. For more information about how to search for a vendor, see section “4. Check your set up: evaluate a vendor, and search for a vendor” later in this topic.

For an overview of the process, see [Procurement and sourcing](procurement-and-sourcing.md).

![Set up vendor evaluation criteria process overview](images/Dn765128.SetUpVendorEvaluationCriteriaOverview(AX.60).png "Set up vendor evaluation criteria process overview")

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
<td><p>Assign vendors to categories</p></td>
<td><p>Set up procurement categories</p></td>
</tr>
</tbody>
</table>


## 1\. Create a vendor evaluation criterion group to evaluate vendors

Some vendors might provide similar services, such as computer supplies. By grouping criteria and applying it to your vendors, you can quickly compare each vendor according to how they are rated for a specific category. A vendor evaluation criterion group makes it easier to decide on a product or service. You can determine how well a vendor provides a service by reviewing the ratings of vendors who supply similar products against a group of evaluation criteria.

For example, for computer supplies, a vendor evaluation criterion group could be called “Ordering process”, and the vendor evaluation criteria for this group might include the following:

  - Is the vendor certified?

  - Does the vendor provide good customer service?

  - What is the ordering experience like?

  - Is the vendor good at collaborating with other suppliers and couriers?

In this example, organizing an executive event becomes easier because you can see at a glance which vendors are preferred, according to the ratings for their services.


> [!IMPORTANT]
> <P>You must set up a vendor evaluation criterion group before you can create vendor evaluation criteria; this is because you can’t create criteria without assigning them to at least one group.</P>



To create a vendor evaluation criterion group, follow these steps:

1.  Click **Procurement and sourcing** \> **Setup** \> **Vendors** \> **Vendor evaluation criterion groups**.

2.  Click **New** and enter a name for the group

3.  Optional: Enter a detailed description of the group.

4.  Optional: To translate the description into another language, on the **Action Pane**, click **Translations**.

5.  To add vendor evaluation criteria to the group or to create new criteria and then assign them to the group, on the **Action Pane**, click **Vendor evaluation criteria**.

## 2\. Create vendor evaluation criteria for a group

Creating vendor evaluation criteria lets you determine whether you want to use particular a vendor. You must set up vendor evaluation criteria groups before you can create evaluation criteria.

To create vendor evaluation criteria, follow these steps:

1.  Click **Procurement and sourcing** \> **Setup** \> **Vendors** \> **Vendor evaluation criteria**.

2.  Click **New** and enter a unique name for the criterion.

3.  Optional: Enter a detailed description of the criterion.

4.  Optional: To translate the description into another language, on the **Action Pane**, click **Translations**.

5.  Select a vendor evaluation criterion group.

## 3\. Assign an evaluation criterion group to one or more procurement categories

If you want to assign different vendor evaluation criteria to different categories in the procurement hierarchy, you can assign an evaluation criterion group to one or more procurement categories. For example, assign the vendor evaluation criterion group “Custom installation” to the procurement category “Computer systems”, if the vendor evaluation criteria includes Device installation and Operating system installation. More than one vendor evaluation criterion group can be assigned to a particular procurement category and vice versa.

To assign an evaluation criterion group, follow these steps:

1.  Click **Procurement and sourcing** \> **Setup** \> **Categories** \> **Procurement categories**.

2.  Select a procurement category from the procurement hierarchy.

3.  In the rightmost pane, scroll down to the **Vendor evaluation criterion groups** FastTab, click **Add**.

4.  In the **Add vendor evaluation criterion groups** form, in the leftmost pane, click a vendor evaluation criterion group, to view the individual evaluation criteria assigned to the group.

5.  Click **Select -\>** to assign a group to the procurement category. Click **OK** to close the form.
    

    > [!TIP]
    > <P>You can select more than one group to assign to a category. You can also assign the same group to multiple categories by repeating the process and assigning the same group to a different category. The vendor rating for the criteria will also appear as a specialist rating for that category.</P>



6.  To remove a group, click **Remove**.
    
    Alternatively, on the **Vendor evaluation criterion groups** FastTab, select the **Inherit vendor evaluation criterion groups from parent category:** check box to assign the same vendor evaluation criterion groups to the selected category that is also assigned to the parent of the same category.

## 4\. Check your set up: evaluate a vendor and search for a vendor

Now that you have created a vendor evaluation criterion group, created criteria for that group, and assigned an evaluation criterion group to a procurement category, it’s a good idea to assess how this will work for the procurement professional who will use it.

Before you evaluate a vendor, you must already have assigned vendor evaluation criterion groups and rating criteria to a procurement category.

To evaluate a vendor, follow these steps:

1.  Click **Procurement and sourcing** \> **Setup** \> **Categories** \> **Procurement categories**.

2.  In the leftmost pane of the **Procurement categories: %1** form, select a category in which you want to evaluate a vendor.

3.  On the **Vendors** FastTab, select a vendor from the list of vendors assigned to the category.

4.  Click **Evaluation** to open the **Rating on vendor evaluation criteria** form.

5.  In the rightmost pane, select a rating for the vendor for each evaluation criterion, and then close the form to save your ratings.


> [!NOTE]
> <P>If you have assigned the same evaluation criterion group to multiple procurement categories and a vendor is scored using the criteria in the group, then that score will apply to all the categories that the group is assigned to and that the vendor is approved for.</P>



After you’ve evaluated a vendor, try searching for a vendor. You can search for a vendor based on criteria or groups of criteria.

To search for a vendor, follow these steps:

1.  Click **Procurement and sourcing** \> **Common** \> **Vendors** \> **All vendors**.

2.  On the **Action Pane**, click **Vendor search**.

3.  In the **Vendor search criteria** form, on the **Common criteria** FastTab, click the **+** button to add specific procurement categories.

4.  On the **Vendor specific criteria** FastTab, you can search for vendors by adding to the **Vendor evaluation criterion group** field, or by adding to the **Vendor evaluation criteria** field.

## Related tasks

[Vendor evaluation criterion group (form)](https://technet.microsoft.com/library/hh242894.aspx)

[Vendor evaluation criteria (form)](https://technet.microsoft.com/library/hh209715.aspx)

## See also

[Key tasks: Set up and maintain procurement category hierarchies](key-tasks-set-up-and-maintain-procurement-category-hierarchies.md)

  


