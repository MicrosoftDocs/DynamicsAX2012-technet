---
title: 'Key tasks: Create retail product catalogs'
TOCTitle: 'Key tasks: Create retail product catalogs'
ms:assetid: e0af4c3e-0908-4bf9-8193-522a102bb772
ms:mtpsurl: https://technet.microsoft.com/library/JJ728712(v=AX.60)
ms:contentKeyID: 49556617
author: tonyafehr
ms.date: 04/25/2014
mtps_version: v=AX.60
f1_keywords:
- product catalog
- retail
- product catalogs
audience: Application User
ms.search.region: Global
---

# Key tasks: Create retail product catalogs 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In Retail, you can use product catalogs to identify the products that you want to offer in your stores. When you create a catalog, you add the stores that the catalog is being created for. The products in the catalog are selected from the product assortments that are assigned to the stores.

After you add the products to the catalog, you can enhance the product offerings by adding attribute data such as HTML rich text, images, and videos. After you complete the catalog, you validate it to verify the required data and then submit the catalog for review and approval. After the catalog is approved, it can be published.

When the catalog is published, the product listings are generated and the products are made available in the store.

You can use product catalogs for online stores. If Microsoft Dynamics AX 2012 R3 is installed, you can also use catalogs to add product attributes for products that are offered in retail brick-and-mortar stores and call centers. For information about how to create a product catalog for call centers, see [Create call center catalogs](create-call-center-catalogs.md). For information about how to create a catalog for brick-and-mortar stores, complete the tasks in this topic.

**Prerequisites**

Before you create a catalog, you must set up the retail channel that the catalog is assigned to. For online stores, you must also publish the store to a Microsoft SharePoint site. For more information about how to set up a retail channel, see [Set up a retail store](set-up-a-retail-store.md) or [Set up an online store](set-up-an-online-store.md).

## What do you want to do?

Learn more about...

Create a catalog

Validate a catalog

Submit a catalog for review and approval

Publish a catalog

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About retail product catalogs](about-retail-product-catalogs.md)

## Create a catalog

Create a catalog for one or more online stores. Add the products that you want to include in the catalog, and then review and update the attributes for the products.

1.  Click **Retail** \> **Common** \> **Catalogs** \> **Catalogs**. On the **Action Pane**, in the **New** group, click **Catalog** to create a new catalog.
    
    You can also create a new catalog by copying an existing catalog. To copy a catalog, on the **Catalogs** list page, select a catalog, and then, on the **Action Pane**, in the **Maintain** group, click **Copy**.

2.  In the **Create new catalog** dialog box, enter a name and description for the catalog.

3.  In the **Catalogs** form, on the **General** FastTab, select the catalog owner and enter an effective date and expiration date for the catalog.
    
    When the catalog is published, the effective date and expiration date are used to determine when to make the products available in the online store. The **Expiration date** is optional. Leave this field blank if the catalog does not expire.

4.  On the **Retail channels** FastTab, click **Add**.

5.  In the **Choose organization nodes** form, select the online stores that the catalog applies to, and then click **Add \>\>**. In AX 2012 R3, for a brick-and-mortar store catalog, select the brick-and-mortar store.
    
    Close the form.

6.  On the **Action Pane**, in the **Products** group, click **Add products**.
    
    To add products to a specific category, select a category in the category navigation pane, and then, on the **Products** FastTab, click **Add**.

7.  In the **Add products** form, select the check box next to the products that you want to add, click **Add**, and then click **OK**. The product list is filtered by the assortments that are assigned to the online stores that you selected on the **Retail channels** FastTab.
    

    > [!NOTE]
    > <P>If you add a product master to the catalog, any variants that are defined for the product master are also automatically added to the catalog. When the catalog is published, the product master and all of its variants are made available in the online store.</P>

    
    Products that are assigned to a category are automatically added to that category in the catalog. Products that are not assigned to a category are added to the **Uncategorized** category in the catalog. Products in the **Uncategorized** category must be manually assigned to the appropriate category in the catalog.

8.  To assign any uncategorized products to the appropriate category in the catalog, follow these steps:
    
    1.  In the category navigation pane, select the **Uncategorized** category.
    
    2.  On the **Products** FastTab, select the products that you want to categorize.
    
    3.  Click **Categorize products**.
    
    4.  Select the categories to move the products to.
        
        You can select one or more products to move to single category at the same time. To move products to different categories, you must select them and move them one at a time.

9.  In the category navigation pane, select each category in the catalog and do one or more of the following:
    
      - On the **Products** FastTab, review the list of products.
    
      - Click **Add** to add products to the selected category.
    
      - Click **Remove** to remove any products from the selected category. If the catalog has not been published, you can delete the products from the catalog category. If the catalog has been published, you can remove products from the catalog category, but the catalog must be republished for the product listings to be removed from the online store.
        

        > [!NOTE]
        > <P>To remove products from the whole catalog, on the <STRONG>Action Pane</STRONG>, click <STRONG>Remove products</STRONG>, and then in the <STRONG>Remove products</STRONG> dialog box, select the products that you want to remove.</P>

    
      - Click **Related products** to open the **Related products** form and view the list of products that are associated with the product. You can select whether to include or exclude the related products in the catalog.

10. Click **Attributes** to view the attributes that are assigned to the products and to add or modify attribute values. If HTML rich text attributes, image attributes, or video attributes are assigned to the product, in the **Product attribute values** form, click **Edit** to add the HTML rich text or the URLs for the images or video files.

Back to top

## Validate a catalog

After you finish setting up the catalog, you must run the validation process to verify that the required data is complete and that the catalog can be published. This process verifies that required data for channel attributes and product attributes is complete and valid. The process also verifies that the online stores that are assigned to the catalog are complete and valid, and have a status of **Published**.

1.  Click **Retail** \> **Common** \> **Catalogs** \> **Catalogs**. On the **Catalogs** list page, select a catalog, and then, on the **Action Pane**, in the **Maintain** group, click **Edit**.

2.  In the **Catalogs** form, on the **Action Pane**, in the **Publish** group, click **Validate catalog**.

3.  In the **Validate catalog** form, click **Validate catalog**. Then, in the **Validate catalog** dialog, leave the fields as they appear by default, or select the **Batch processing** check box to run the process as a batch job, and click **OK** to run the validation process.
    
    If the validation process has never been run for the catalog, the fields in the form are blank. If the validation process has previously been run for the catalog, the results from the last validation are displayed in the form. You can run the validation process as many times as you have to.

4.  In the **Channel summary** section, review any errors or warnings for the online store.

5.  In the **Product summary** section, in the **Channel** field, select the online stores that are assigned to the catalog, and then review any errors or warnings for the products.

6.  Correct any errors that are found by the validation process. Then, repeat steps 2 through 5 until the catalog is valid and ready to be submitted for review.

Back to top

## Submit a catalog for review and approval

After a catalog is validated, you can submit the catalog for review and approval. A catalog must be approved before it can be published. You can configure workflow so that catalogs are either automatically approved or require manual approval.

For information about how to configure workflow for retail product catalogs, see [Set up workflow for retail catalogs](set-up-workflow-for-retail-catalogs.md).

1.  Click **Retail** \> **Common** \> **Catalogs** \> **Catalogs**. On the **Catalogs** list page, select a catalog, and then, on the **Action Pane**, in the **Maintain** group, click **Edit**.

2.  In the **Catalogs** form, in the workflow message bar, click **Submit**.
    
    The catalog status is changed from **Draft** to **Submitted for approval**. When the catalog is approved, the catalog status is changed to **Approved**.

3.  If you are an approver, in the **Catalogs** form, in the workflow message bar, click **Approve**.
    
    When the catalog is approved, the catalog status is changed to **Approved**.

Back to top

## Publish a catalog

Publishing a catalog makes products and product information available in a specific online store. You can publish your catalogs manually, or you can use a batch process to publish based on a schedule. Before you can publish a catalog, the catalog must be validated and approved. To change the catalog after it is published, you can retract the catalog, and then republish it to push those changes to the online store.


> [!NOTE]
> <P>If you change a category in a navigation category hierarchy that is assigned to an online store or a retail product catalog, you must republish the channel or catalog as follows:</P>
> <UL>
> <LI>
> <P>If you add or delete a category node, republish the channel and the catalog that use the category hierarchy.</P>
> <LI>
> <P>If you activate or inactivate a category, assign any products to active categories, and then republish the channel and the catalog that use the category hierarchy.</P>
> <LI>
> <P>If you change the name of a category, republish the channel that uses the category hierarchy.</P></LI></UL>



1.  Click **Retail** \> **Common** \> **Catalogs** \> **Catalogs**. On the **Catalogs** list page, select a catalog, and then, on the **Action Pane**, in the **Maintain** group, click **Edit**.

2.  In the **Catalogs** form, on the **Action Pane**, in the **Publish** group, click **Publish**.

3.  In the **Publish catalog** form, in the **Publish** field, select one of the following options:
    
      - **Only products that have changed** – Select this option to publish only the changes that were made to a catalog since it was last published.
    
      - **All products** – Select this option if this is the first time the catalog is being published, or if you want to republish the whole catalog.

4.  In the **Product totals by channel** grid, review the total number of product listings to be created, updated, or deleted when the publishing process is completed.

5.  Click **OK** to start the publishing process.

6.  In the **Catalogs** form, on the **Retail channels** FastTab, select an online store, and then click **Listings**.
    
    Alternatively, on the **Products** FastTab, click **Listings** to review the product listings for a specific category.

7.  In the **Listings** form, review the product listings that the publishing process is creating, updating, or deleting for the selected online store. You can also review the listing status that is updated by Microsoft Dynamics AX Commerce Runtime. The following statuses are displayed:
    
      - **In progress** – The catalog is being published, republished, or retracted.
    
      - **Success** – The publishing process is completed and the product listings have been updated in the online store.
    
      - **Error** – An error occurred, and the product listing could not be processed.

8.  In AX 2012 R3: For catalogs that are set up for brick-and-mortar stores, run the catalog scheduler job to send the updated data to the Retail stores.
    
    1.  Click **Retail** \> **Periodic** \> **Data distribution** \> **Distribution schedule**.
    
    2.  In the **Distribution schedule** form, in the left pane, in the **Name** column, select the **1150** (Catalog) scheduler job.
    
    3.  To run the job manually or in batch mode, do one of the following:
        
          - To manually run the scheduler job, on the menu bar at the top of the form, click **Run now**.
        
          - To run the scheduler job in batch mode, on the **Scheduler jobs** FastTab, verify that the **Enabled** check box is selected for the job, and then click **Create batch job**. In the form that is displayed, enter information about the batch job. For more information about the options in the form, see [Submit a batch processing job from a form](submit-a-batch-processing-job-from-a-form.md).

Back to top

## Find form help

[Catalogs (list page) (Retail)](https://technet.microsoft.com/library/jj728733\(v=ax.60\))

[Catalogs (form) (Retail)](https://technet.microsoft.com/library/jj728723\(v=ax.60\))

[Listings (form)](https://technet.microsoft.com/library/jj728734\(v=ax.60\))

[Validate catalog (form)](https://technet.microsoft.com/library/jj728739\(v=ax.60\))

[Publish catalog (form)](https://technet.microsoft.com/library/jj728730\(v=ax.60\))

## Find related tasks

[Set up an online store](set-up-an-online-store.md)

  


