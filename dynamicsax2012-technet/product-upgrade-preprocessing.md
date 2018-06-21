---
title: Product upgrade (preprocessing)
TOCTitle: Product upgrade (preprocessing)
ms:assetid: 7e2e587a-bb29-4197-8ca8-fb22f6381d03
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg731843(v=AX.60)
ms:contentKeyID: 35132696
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Product upgrade (preprocessing) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX 2012, there are new processes for handling items. A new structure requires any item that is configured in a company to be based on a product definition. Therefore, any item that is handled in inventory, or during the purchase or sales process, must be associated with a product definition. Product definitions reside at the shared level.

You use the **Product upgrade** form to define how existing, company-specific items are mapped to products.


> [!NOTE]
> <P>Before you can start mapping items to products, you must set the company's priority and complete the preprocessing of inventory dimensions.</P>



If you are upgrading to Microsoft Dynamics AX 2012 R2 or AX 2012 R3, you must identify a data partition when performing this task. If you have configured multiple partitions, the procedure must be repeated for each partition. For more information about data partitions and upgrade, see [Configure partitions](configure-partitions.md).

## New product concepts

To understand how items are mapped to products, you must be familiar with the following new concepts that are introduced in Microsoft Dynamics AX:

  - Product master – A standard or functional representation of a product that is the basis for configuring product variants.

  - Product variant – A configuration of a product master.

  - Distinct product – A uniquely identifiable product.

## Items are upgraded to product masters and distinct products

Existing items that have active item dimensions are created as product masters. Items that do not have active item dimensions are created as distinct products.

## Combinations of item dimensions are created as variants

When you map items to products, combinations of item dimensions are created as product variants. Therefore, product variants are created for product masters, and product masters are based on items that have active item dimensions.


> [!TIP]
> <UL>
> <LI>
> <P>In the <STRONG>Product upgrade</STRONG> form, click <STRONG>View</STRONG> &gt; <STRONG>All item dimension combinations</STRONG> to view the combinations of item dimensions for items that have active item dimensions.</P>
> <LI>
> <P>In the <STRONG>Product preview</STRONG> form, click <STRONG>Variants</STRONG> to view product variants.</P></LI></UL>



## The mapping process

There are two mapping methods. The method that you choose determines the level of manual work that you must do to map items. Your choice depends on factors such as the number of items and the number of different companies for which items must be merged. For example, if you upgrade two lists of items, and each list contains identical items, you may want to map by item number. If you map by item number, items that have identical item numbers are merged. You can complete a clean-up of the data after the mapping instead of after the upgrade. However, when you map by item number instead of using the 1:1 method, there is a higher risk of validation errors. There is also a greater likelihood that you must perform manual work later.

## Synchronize

When you synchronize items, you synchronize the data in the upgrade environment with the existing data in the system.


> [!NOTE]
> <P>The first time that you open the <STRONG>Product upgrade</STRONG> form, the fields are empty. The fields are not populated until you synchronize items.</P>



### Synchronize items

1.  Click **Product upgrade** to open the **Product upgrade** form.

2.  Click **Synchronize items** to synchronize the items in the upgrade environment.
    

    > [!NOTE]
    > <P>You cannot continue the mapping process until the synchronization is completed.</P>
    > <P>If item data is changed during the upgrade process, you can synchronize items at any time to make sure that the upgrade environment includes the most recent data.</P>



## Map items

You can choose between the following two mapping methods:

  - **Map all items 1:1** – Each item is mapped to a unique product of the Product master or Distinct product subtype. The item number is replicated in the new product number. The name and search name of the product are identical to the name and search name of the item.

  - **Map all items by item number** – All items that have identical item numbers are mapped to the same product. For example, if you map items from two different companies, items that have the same item number can be mapped to one product.
    

    > [!NOTE]
    > <P>If two items that have identical item numbers have different names or different setups for their item dimensions, for example, you receive a validation error. The solution depends on the problem. If the names of the two items are different, you can change the text in the <STRONG>Product name</STRONG> fields in the <STRONG>Product preview</STRONG> form. If the dimensions are different, you must change the original data in the system. However, you may not be able to make the changes if transactions exist in the system.</P>



### Map items 1:1

1.  In the **Product upgrade** form, click **Product mapping**, and then select **Map all items 1:1**.

2.  In the **Map all items 1:1** form, enter a prefix in the **Product number prefix** field, and then enter an initial number in the **Initial number** field.
    

    > [!NOTE]
    > <P>The numbering convention that you define in the <STRONG>Product number prefix</STRONG> and <STRONG>Initial number</STRONG> fields is only applied if you map items that have identical numbers but come from different companies. For these items, the product numbers are replaced with numbers based on this convention.</P>

    
    The sequence of product numbers is based on the company's priority. To view or change the priority of companies, click **View** \> **Company priority setup**.
    
    **Example**
    
    Three items from three different companies have the item number XL-1000. For the numbering convention, the product number prefix is PXL, and the initial number is 99.
    
    The three item numbers come from three companies, C1, C2, and C3. The priority of C1 is 1, the priority of C2 is 2, and the priority of C3 is 3.
    
    The following product numbers are generated:
    
      - Item XL-1000 from company C1 – Product number: XL-1000
    
      - Item XL-1000 from company C2 – Product number: PXL99
    
      - Item XL-1000 from company C3 – Product number: PXL100

### Map items by item number

1.  In the **Product upgrade** form, click **Product mapping**, and then select **Map all items by item number**.

2.  Click **OK** to continue.

## Approve the mapping

Product mappings must be approved before you can set the items to ready for upgrade. You can approve all mappings, or reverse the approval of all mappings, from either the **Product upgrade** form or the **Product preview** form. You can approve or reverse the approval of selected items only from the **Product preview** form.

### Approve or reverse all mappings from Product upgrade

1.  In the **Product upgrade** form, click **Product mapping approval**.

2.  Select **Approve all mappings** to approve all mappings. Select **Reverse all mapping approvals** to reverse the approval of all mappings.

### Approve or reverse all or selected mappings from Product preview

1.  In the **Product upgrade** form, click **View** \> **Product preview** to open the **Product preview** form.

2.  Click **Product mapping approval** and select one of the following submenu commands:
    
      - Select **Approve all mappings** to approve all mappings.
    
      - Select **Reverse all mapping approvals** to reverse the approval of all mappings.
    
      - Select **Approve selected mappings** to approve mappings of the products that you have selected in the **Product preview** form.
    
      - Select **Reverse selected mapping approvals** to reverse the approval of mappings for the products that you have selected in the **Product preview** form.

## Clear all product numbers

  - In the **Product upgrade** form, click **Clear all product numbers** to remove all product numbers from a previous mapping.

## Validate mappings

After you map items and approve the mappings, you can request a validation report. The validation report shows the validation errors that are caused by inconsistencies or data violations, such as when two items that have identical names are mapped to the same product. If you mapped all items by item number, you may have to repeat the mapping process and the validation several times to resolve all of the validation errors. You must repeat the mapping process and the validation until all errors are resolved.


> [!NOTE]
> <P>You cannot complete the upgrade until all validation errors are resolved. In addition to validation errors, you may receive validation warnings. Validation warnings are just warnings about inconsistent data. The upgrade can be completed if there are validation warnings.</P>



### Validate all product mappings

1.  In the **Product upgrade** form, click **View** \> **All validation results**.

2.  In the **Product validation** form, click **Validate all** to update the view.
    

    > [!NOTE]
    > <P>You must click <STRONG>Validate all</STRONG> to update this form, even if you are opening the form for first time, or if you previously validated the mappings.</P>



## Set to ready for upgrade

  - In the **Product upgrade** form, click **Set to ready for upgrade** to indicate that the products are ready to be upgraded.
    

    > [!NOTE]
    > <P>You must approve all product mappings before you set products to ready for upgrade. If validation errors exist, you must resolve the errors before you can continue.</P>



## Troubleshoot product variants with no association to a product master

On rare occasions, the preexisting data set can include item dimension combinations where one or more of the corresponding item dimensions are inactive on the associated dimension group.

If this applies to your data set, we recommend that before you start to preprocess your data, you consider how you want to handle these item dimension combinations.

In the upgrade process, all item dimension combinations are created as product variants. Product variants depend on an association with a product master. If the potential product masters for the product variants are based on items with inactive item dimensions, these items are mapped to distinct products rather than to product masters. Product variants that lack an association with a product master prevent the data from being properly upgraded.

To resolve this issue we recommend the following:

  - If possible, on the dimension groups, activate any item dimensions that are associated with item dimension combinations.

  - If you cannot activate the dimensions, you can try to delete the item dimension combinations. Before you delete, make sure that you back up your data.

## Product preview

Use the **Product preview** form to view products, and to perform tasks on all products or selected products. From this form, you can see how items are mapped to products of the Distinct product or Product master subtype. You can also lock products, approve the mapping of products, and view product details.


> [!TIP]
> <P>Some tasks, such as product mapping and product approval, can be completed in both the <STRONG>Product upgrade</STRONG> form and the <STRONG>Product preview</STRONG> form. However, the two forms are not identical. For example, the perspective in the forms is different. In the <STRONG>Product preview</STRONG> form, you view data from the product's perspective. However, in the <STRONG>Product upgrade</STRONG> form, you view data from the item's perspective. In addition, you can use the <STRONG>Product preview</STRONG> form to approve the mapping of selected products. However, you approve product mappings from the <STRONG>Product upgrade</STRONG> form, the approval applies to all items in the form.</P>



### View mappings and perform tasks on products

1.  In the **Product upgrade** form, click **View** \> **Product preview** to open the **Product preview** form.

2.  Click the buttons to complete the following tasks:

<!-- end list -->

  - **Product mapping** – Map all items, either by item number or by using the 1:1 method.

  - **Product locking** – Lock all products or selected products. Locked products are disregarded during the mapping process. When you consider the mapping of a set of products final, you can lock the products. The locked products are not affected if you later repeat the mapping process.

  - **Product mapping approval**: – Approve or reverse the approval of the mappings for all items or selected items.

  - **Validation** – Validate all mappings or selected mappings.
    

    > [!TIP]
    > <P>You can validate mappings at any time. When you validate a mapping, you receive a list of validation errors and guidelines to help you resolve the errors.</P>



  - **Variants** – View the product variants that were created for products of the Product master subtype.
    

    > [!TIP]
    > <P>The variants of a product correspond to the combinations of item dimensions for an item.</P>



  - **Configurations**, **Sizes**, and **Colors** – View the setups for configuration, size, and color that are inherited from the items.

  - **Translations** – View any text translations in different languages that were set up for the items.

## See also

[Company priority setup](company-priority-setup.md)

[Inventory dimension group upgrade](inventory-dimension-group-upgrade.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

