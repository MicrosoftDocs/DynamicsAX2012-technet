---
title: Create a product change case
TOCTitle: Create a product change case
ms:assetid: 2eec3012-309b-4c9b-872f-d2fbd28c41a7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn505746(v=AX.60)
ms:contentKeyID: 59604022
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create a product change case 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>



This topic describes how to use the product change case functionality in case management to document changes to a product or changes to the entities used in its production. The entities include the product and released product, bill of materials (BOM) or formula, and the production route.

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Prerequisite</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Case categories</strong></p></td>
<td><p>You must create a case category to use for product change cases. For more information, see the section in this topic titled “Create a case category for a product change.” For information about case categories, see <a href="https://technet.microsoft.com/en-us/library/hh209319(v=ax.60)">Case categories (form)</a>.</p></td>
</tr>
</tbody>
</table>


## Create a case category for a product change

Before you can create a product change case, you must create one or more case categories that you will assign to product change cases. When you create a case category and assign it to the product change category type, a **Validation rules** FastTab is available. This FastTab is not available for other category types. You can enable validation rules to make sure that the information in the case is complete and consistent. For each validation rule, you can specify whether a violation will cause an error message or a warning. An error message must be addressed before a user can close a case. Warning messages do not prevent a user from closing a case.

To create a case category for a product change case, follow these steps:

1.  Click **Organization administration** \> **Setup** \> **Cases** \> **Case categories**.

2.  Click **New**, and select **Case category**.

3.  In the **Case category** field, enter a name for the category.

4.  In the **Description** field, enter a description of the category.

5.  In the **Category type** field, select **Product change**.

6.  Click the **Validation rules** FastTab.

7.  For each validation rule that you want to use, do the following:
    
      - Select the **Enabled** check box.
    
      - In the **Error level** field, specify whether a violation will trigger an error or a warning.

8.  Optional: Enter information in the remaining fields.

## 1\. Create a product change case for an entity

The product change case is a central location for documenting one or more changes to a product. You can create a product change case and then associate entities, or create a product change case directly from the form for an entity. The entities that you associate with the case are either the cause of the change or the entities that are affected by the change.


> [!NOTE]
> <P>When you create a product change case from the form for an entity, the entity is automatically associated with the case. Additionally, when you create a product change case for a released product, the related product is automatically associated. If needed, you can remove the associations.</P>



To create a product change case for an entity, follow these steps:

1.  To create a case from the entity, use one of the following methods:
    
      - Click **Product information management** \> **Common** \> **Released products**. Select the released product. On the **Action Pane**, click the **Engineer** tab, and then click **Create case**.
    
      - Click **Inventory management** \> **Common** \> **Bills of materials**. Select the BOM, click **Product change**, and then select **Create case**.
    
      - Click **Production control** \> **Common** \> **Routes** \> **All routes**. Select the route, and then on the **Action Pane**, click **Create case**.

2.  In the **Name** field, select the person or organization that you are creating the case for.

3.  In the **Case category** field, expand the **Product change** node, and then select the case category that you created for product change cases.

4.  Optional: To add a note in the case log, click **Case log**, and then enter information in the **Description** and **Notes** fields.

5.  Optional: Enter information in the remaining fields.

## 2\. Associate entities with a product change case

There are several ways to associate the entities that are the cause of the change or are affected by the change with a product change case.

  - Make the association in the form for the entity by clicking **Associate with case** on the **Action Pane**.

  - Make the association in the **Case** form, on the **Associations** FastTab, by clicking **Add**, and then specifying the type of entity and its identifier.

  - Run the **Where-used analysis** for an item that is already associated with the case.

## 3\. Find related entities, and associate them with the product change case

After you associate the item that is the cause of the change, you can use the **Where-used analysis** feature to identify all of the related entities that may be affected by the change. After you run the analysis, you can associate all of the entities in the analysis results with the product change case. You cannot use the **Where-used analysis** feature to associate single entities.


> [!NOTE]
> <P>By default, the <STRONG>Planned effective date</STRONG> field displays today’s date. You can change the date in the <STRONG>Where-used analysis</STRONG> form, or later in the <STRONG>Approve and activate changes</STRONG> form. Changing the date has the following effect:</P>
> <UL>
> <LI>
> <P>The date is changed on the product change case.</P>
> <LI>
> <P>The route versions and formula versions may change in the analysis results.</P></LI></UL>



To run the analysis, follow these steps:

1.  Use one of the following methods to open the case that contains the entity to analyze:
    
      - Click **Product information management** \> **Common** \> **Released products**. Select the released product. On the **Action Pane**, click the **Engineer** tab, and then click **All cases**. Open the case that contains the entity to analyze.
    
      - Click **Home** \> **Common** \> **Cases** \> **All cases**. Open the case that contains the entity to analyze.

2.  On the **Associations** FastTab, select the entity, and then click **Where-used analysis**.

3.  On the **Include BOMs** and the **Routes** FastTabs, specify what to include in the analysis.

4.  Click **Run the analysis**.

5.  Optional: To add an entry in the case log, on the **Case log** FastTab, enter a note in the **Description** and **Notes** fields.

6.  Optional: To associate all of the entities in the analysis with the product change case, click **Associate all with the case**.
    

    > [!NOTE]
    > <P>When you associate all entities with the case, a message is displayed if one or more entities are already associated with the product change case. The associations are not duplicated for the entities.</P>



## 4\. Optional: Enter additional details in a product change case

You can enter additional information about the product changes in the case log. The process for entering information in the case log varies slightly depending on the form that you are working in. The following procedure describes where you can access the case log.


> [!NOTE]
> <P>If needed, you can also use the case management features to add information about the case. For more information, see <A href="add-details-to-a-case.md">Add details to a case</A>.</P>



To enter additional information in a product change case, follow these steps:

  - To add information to the case from the form for a specific entity, follow these steps:
    
      - **Released products** and **All routes** forms - On the **Action Pane**, click the **Engineer** tab, and then click **Add to case log**.
    
      - **Bills of materials** and **Formula** forms - Select the BOM or formula, click **Product change**, and then select **Add to case log**.

  - To add information directly in the case, follow these steps:
    
    1.  Click **Home** \> **Common** \> **Cases** \> **All cases**.
    
    2.  Enter the information on the appropriate FastTab:
        
          - **Case log** – Click **Add** to create a new case log information line where you can enter the information. Click **Details** to view the details form for the selected entity.
        
          - **Associations** – Click **Add** to create a new line and add information about an entity that is associated with the case that you are currently working on.

## 5\. Approve, activate, or expire entities in a product change case

You can approve, activate, and expire the entities that are associated with a case as follows:

  - You can approve BOMs, formulas, and routes.

  - You can approve, activate, and expire BOM versions, formula versions, and route versions. For example, if you are replacing a route, you can expire the replaced route version, approve, and then activate the new route version. You can also approve and activate formula versions where only co-products or bi-products are affected.

To approve, activate, or expire entities in a product change case, follow these steps:

1.  Click **Home** \> **Common** \> **Cases** \> **All cases**.

2.  Select the case, and then click **Approve and activate changes**.

3.  In the **Planned effective date** field, select the date when you want the change to take effect. By default, the current date is suggested.
    

    > [!NOTE]
    > <P>The planned effective date applies to the entities associated with the case. If needed, you can override the planned effective date for individual BOM versions, formula versions, and route versions.</P>



4.  Click **Validate** to check the completeness and consistency of the product change case.

5.  In the **Action** field for each entity, select the action that you want to apply, and then click **Apply actions**.
    

    > [!TIP]
    > <P>After you apply the action, one way to verify that all changes are made is to use the filters. For example, you can select a released product in the <STRONG>Component in BOMs or formulas</STRONG> filter to display only BOMs and routes that include that component.</P>



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
<td><p><strong>BOM versions</strong>, <strong>BOM approval</strong>, <strong>Allow cost breakdown activation</strong>, and <strong>Product change cases</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>The user must be assigned to the security role that grants permission to view the product change case category type. This is the same security role that is assigned to the <strong>Case category type security</strong> form.</p></td>
</tr>
</tbody>
</table>


## See also

[About product change cases](about-product-change-cases.md)

  


