---
title: Create call center catalogs
TOCTitle: Create call center catalogs
ms:assetid: bf42fea1-696e-4183-be39-05b1e67b69c0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn497822(v=AX.60)
ms:contentKeyID: 62200149
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.RetailCatalogDetails
- Forms.RetailCatalogListPage
- MsDynAx060.Forms.RetailCatalogDetails
- Forms.MCRCatalogFreeProduct
- MsDynAx060.Forms.MCRCatalogFreeProduct
- MsDynAx060.Forms.RetailCatalogListPage
- call center catalog
- catalog setup
- set up catalog
- create catalog
- print catalog
---

# Create call center catalogs [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

In a call center, you can use product catalogs to identify the products that you want to offer to customers. Call centers typically use printed catalogs. The design and production of a printed catalog is handled outside Microsoft Dynamics AX, but you can create and store a digital form of a catalog in Microsoft Dynamics AX 2012 for Retail by using the same forms that you use to set up online Retail catalogs.

Before you can create a catalog, you must set up product assortments and assign the assortments to a call center. You then add products to the catalog by selecting products from these assortments. After products have been added to the catalog, and the catalog is complete, you must validate the catalog to verify the data. You must then submit the catalog for review and approval. After the catalog is approved, it can be published.

When a call center catalog is created, you can take a snapshot of the catalog data at the time that the catalog is published. This snapshot functionality lets you access a particular version of the catalog even if the catalog is later changed and updated.

Call center catalogs can also be set up to include the following optional features:

  - Source codes – Codes that are used to track the customer response to particular catalog mailings.

  - Free products – Products that are included in a customer's order at no additional charge. These products are added to the order automatically when the source code for the catalog is entered into the order.

  - Scripts – Texts that a call center worker reads to a customer when a sales order is being created. Scripts can include greetings or purchase suggestions.

These options can be set up after the catalog is validated and approved, but before it is published.

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
<td><p>Related setup tasks</p></td>
<td><p>Set up products and product assortments:</p>
<p><a href="setting-up-retail-products.md">Setting up retail products</a></p>
<p><a href="set-up-an-assortment.md">Set up an assortment</a></p>
<p>Create a call center:</p>
<p><a href="set-up-a-call-center.md">Set up a call center</a></p>
<p>Add the call center to an organization hierarchy:</p>
<p><a href="create-or-modify-an-organization-hierarchy.md">Create or modify an organization hierarchy</a></p></td>
</tr>
</tbody>
</table>


## 1\. Create a catalog

You must first create a catalog, add products to the catalog, and then review and update the attributes for the products.

To create a catalog, follow these steps.

1.  Click **Retail** \> **Common** \> **Catalogs** \> **Catalogs**.

2.  On the **Action Pane**, in the **New** group, click **Catalog** to create a new catalog.
    
    You can also create a new catalog by copying an existing catalog. To copy a catalog, on the **Catalogs** list page, select a catalog. Then, on the **Action Pane**, in the **Maintain** group, click **Copy**.

3.  In the **Create new catalog** dialog box, enter a name and a description for the catalog.

4.  In the **Catalogs** form, on the **General** FastTab, select the catalog owner. Enter an effective date and expiration date for the catalog.
    
    The **Expiration date** field is optional. Leave this field blank if the catalog does not expire.

5.  Optional: If you want to save a version of the catalog as it exists at the time that it is published, select the **Take snapshot** check box.
    
    The snapshot captures information about products that are included in the catalog, and also about the price groups that are associated with the catalog.

6.  On the **Retail channels** FastTab, click **Add**.

7.  In the **Choose organization nodes** form, select the call centers that the catalog applies to, and then click **Add \>\>**. Close the form.
    

    > [!NOTE]
    > <P>Before you can associate the catalog with a call center, the call center must be set up and added to an organization hierarchy. For information about how to set up a call center, see <A href="set-up-a-call-center.md">Set up a call center</A>. For information about how to add a retail channel to an organization hierarchy, see <A href="create-or-modify-an-organization-hierarchy.md">Create or modify an organization hierarchy</A>.</P>



8.  On the **Action Pane**, click **Price groups**, and then click **Add** to add a price group to the catalog. For more information about price groups, see [Setting up prices using price groups](setting-up-prices-using-price-groups.md).
    

    > [!NOTE]
    > <P>After a snapshot is created for a catalog, you must retract and republish the catalog if you change any of the price group information, such as trade agreement prices or retail discounts.</P>



9.  Below the **Action Pane**, in the **Category hierarchy** field, select a category hierarchy that you want to use to organize products in the catalog. Then, on the **Action Pane**, in the **Products** group, click **Add products**.
    

    > [!NOTE]
    > <P>To add products to a specific category, in the category navigation pane, select a category, and then, on the <STRONG>Products</STRONG> FastTab, click <STRONG>Add</STRONG>.</P>

    

    > [!NOTE]
    > <P>Product assortments must be set up before you can use the <STRONG>Add products</STRONG> form. This setup is part of the setup for retail products. For more information, see <A href="assortments.md">Assortments</A>.</P>



10. In the **Add products** form, select the products to add to the catalog, and then click **OK**.
    

    > [!NOTE]
    > <P>If you add a product master to the catalog, any variants that are defined for the product master are also automatically added. When the catalog is published, the product master and all its variants are made available to the call center.</P>

    
    Products that are assigned to a category are automatically added to that category in the catalog. Products that are not assigned to a category are added to the **Uncategorized** category in the catalog. Products in the **Uncategorized** category must be manually assigned to the appropriate category in the catalog.

11. To assign uncategorized products to an appropriate category in the catalog, follow these steps:
    
    1.  In the category navigation pane, select the **Uncategorized** category.
    
    2.  On the **Products** FastTab, select the products to categorize.
    
    3.  Click **Categorize products**.
    
    4.  Select the category to move the products to.
        
        You can select one or more products to move to single category at the same time. To move products to different categories, you must select them and move them one at a time.

12. In the category navigation pane, select each category in the catalog, and then follow one or more of these steps:
    
      - To review the list of products, click the **Products** FastTab.
    
      - To add products to the selected category, click **Add**.
    
      - To remove products from the selected category, click **Remove**. You can delete products from a catalog category only if the catalog has not been published. If the catalog has been published, you can remove products from the catalog category, but the catalog must be republished before the change takes effect.
        

        > [!NOTE]
        > <P>To remove products from the whole catalog, on the <STRONG>Action Pane</STRONG>, click <STRONG>Remove products</STRONG>, and then, in the <STRONG>Remove products</STRONG> dialog box, select the products to remove.</P>

    
      - To open the **Related products** form, where you can view the list of products that are associated with the products, click **Related products**. You can select whether the catalog includes or excludes the related products.

13. Click **Attributes** to view the attributes that are assigned to the products, and add or modify attribute values if changes are required.
    

    > [!NOTE]
    > <P>You can update product attributes in bulk. For more information, see <A href="bulk-edit-product-attributes-by-using-excel.md">Bulk edit product attributes by using Excel</A>.</P>



## 2\. Validate a catalog

After you have finished setting up the catalog, you must run the validation process. This process verifies that the data that is required for channel attributes and product attributes is complete and valid, and that the catalog can be published.

To validate a catalog, follow these steps.

1.  Click **Retail** \> **Common** \> **Catalogs** \> **Catalogs**. On the **Catalogs** list page, select a catalog, and then, on the **Action Pane**, in the **Maintain** group, click **Edit**.

2.  In the **Catalogs** form, on the **Action Pane**, in the **Publish** group, click **Validate catalog**.

3.  In the **Validate catalog** form, on the **Action Pane**, click **Validate catalog** to run the validation process.
    
    If the validation process has never been run for the catalog, the fields in the form are blank. If the validation process has previously been run for the catalog, the results from the last validation are displayed in the form. You can run the validation process as many times as you require.

4.  In the **Channel summary** section, review any errors or warnings for the call center.

5.  In the **Product summary** section, in the **Channel** field, select the call centers that are assigned to the catalog, and then review any errors or warnings for the products.

6.  Correct any errors that are found by the validation process. Then repeat steps 2 through 5 until the catalog is valid and ready to be submitted for review.

## 3\. Submit a catalog for review and approval

After a catalog is validated, you can submit the catalog for review and approval. A catalog must be approved before it can be published. You can configure workflow so that catalogs either are automatically approved or require manual approval.

For information about how to configure workflow for retail product catalogs, see [Set up workflow for retail catalogs](set-up-workflow-for-retail-catalogs.md).

To submit a catalog for review and approval, follow these steps.

1.  Click **Retail** \> **Common** \> **Catalogs** \> **Catalogs**. On the **Catalogs** list page, select a catalog, and then, on the **Action Pane**, in the **Maintain** group, click **Edit**.

2.  In the **Catalogs** form, in the workflow message bar, click **Submit**.
    
    The catalog status is changed from **Draft** to **Submitted for approval**. When the catalog is approved, the catalog status is changed to **Approved**.

3.  If you are an approver, in the **Catalogs** form, in the workflow message bar, click **Approve**.
    
    When the catalog is approved, the catalog status is changed to **Approved**.

## 4\. Optional: Add source codes, free products, and scripts

Catalog source codes, free products, and scripts can be added to a call center catalog at any time before publication. These options don't have to be validated and approved.

To add source codes, follow the procedures in [Set up catalog source codes](set-up-catalog-source-codes.md).

After you have a source code set up, you can add free products to the catalog. To add free products, follow these steps.

1.  Click **Retail** \> **Common** \> **Catalogs** \> **Catalogs**. On the **Catalogs** list page, select a catalog, and then, on the **Action Pane**, click **Edit**.

2.  On the **Action Pane**, in the **Call center** group, click **Free products**.

3.  Click **New**, select the product to add, and then click **Add**. Repeat this step to add more free products, and then click **OK**.

To add scripts, follow these steps.

1.  Click **Retail** \> **Common** \> **Catalogs** \> **Catalogs**. On the **Catalogs** list page, select a catalog, and then, on the **Action Pane**, click **Edit**.

2.  Click the **Scripts** FastTab.

3.  Click **Add** to add a new line.

4.  In the **Script name** field, select a script. Set the other fields in the list to the values that you require.

5.  If you want the script to be displayed at order time, select the **Active** check box.

## 5\. Publish a catalog

By publishing a catalog for a call center, you finalize the product information in the catalog. Publication also indicates that the catalog is ready for additional actions that you want to perform, such as creating a printed catalog. You can publish your catalogs manually, or you can use a batch process to publish according to a schedule. Before you can publish a catalog, the catalog must be validated and approved. To change the catalog after it is published, you can retract the catalog and then republish it.

To publish a catalog, follow these steps.

1.  Click **Retail** \> **Common** \> **Catalogs** \> **Catalogs**. On the **Catalogs** list page, select a catalog, and then, on the **Action Pane**, in the **Maintain** group, click **Edit**.

2.  In the **Catalogs** form, on the **Action Pane**, in the **Publish** group, click **Publish**.

3.  In the **Publish catalog** form, in the **Publish** field, select one of the following options:
    
      - **Only products that have changed** – Select this option to publish only the changes that have been made to the catalog since it was last published.
    
      - **All products** – Select this option if the catalog is being published for the first time, or if you want to republish the whole catalog.

4.  Click **OK** to start the publication process.

## Related tasks

[Set up catalog source codes](set-up-catalog-source-codes.md)

[Working with call center catalogs](working-with-call-center-catalogs.md)

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
<td><p><strong>Retail Headquarters</strong> configuration key</p>
<p><strong>Call center</strong> configuration key</p>
<p><strong>Source code</strong> configuration key (if you set up source codes and free products)</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>Retail catalog manager</p></td>
</tr>
</tbody>
</table>


## See also

[About retail product catalogs](about-retail-product-catalogs.md)

[Setting up retail products](setting-up-retail-products.md)

[Setting up prices using price groups](setting-up-prices-using-price-groups.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

