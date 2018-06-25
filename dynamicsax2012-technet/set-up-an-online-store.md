---
title: Set up an online store
TOCTitle: Set up an online store
ms:assetid: 7150615f-3c60-498c-be76-40e07d0c0ce6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ682095(v=AX.60)
ms:contentKeyID: 49655582
ms.date: 11/19/2014
mtps_version: v=AX.60
f1_keywords:
- publish
- online store
- online storefront
- online stores
- webstore
---

# Set up an online store [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic explains how to set up an online store, which is a type of retail channel that customers can access on the web. An online store gives a retailer an online presence so that their customers can purchase products from their online store in addition to their brick-and-mortar store. Customers who purchase products from the online store can have the products shipped to them, or they can pick up the products from a local store.


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed for <STRONG>Retail</STRONG> in Microsoft Dynamics AX 2012 R3.</P>



The process of setting up an online store includes the following overall tasks:

1.  Create the online store.

2.  Add the store to the appropriate organization hierarchies.

3.  Configure the store details.

4.  Publish the store to a Microsoft SharePoint site.

After you publish the store, you can create retail product catalogs that you can publish to the store. The retail product catalogs contain the products that you offer through the online store. For information about how to create retail product catalogs, see [Key tasks: Create retail product catalogs](key-tasks-create-retail-product-catalogs.md).

## Prerequisites

You create an online store in Microsoft Dynamics AX and then publish it to a SharePoint site. Before you can publish an online store, you must do the following:

  - In AX 2012 R2 and AX 2012 Feature Pack, set up a distribution location for the online store. For more information, see [Create distribution locations for retail databases](create-distribution-locations-for-retail-databases.md).

  - In AX 2012 R3, set up a channel database profile instead of a distribution location. The channel database profile sets up the links between the online store in Microsoft Dynamics AX and the database that you use to publish the online store. For more information about how to set up a channel database profile, see [Set up a channel database profile](set-up-a-channel-database-profile.md).

  - Configure the appropriate publishing and product catalog site collections for the SharePoint site. For information about how to configure the site collections for a SharePoint site, see [Deploy a Microsoft Dynamics AX online store](http://go.microsoft.com/fwlink/?linkid=263679).

## Create an online store

Use this procedure to create the basic structure for the online store. The details that you define for the online store in Microsoft Dynamics AX control the behavior of the online store after it is published. For more information, see [About online stores](about-online-stores.md).

1.  Click **Retail** \> **Common** \> **Retail channels** \> **Online stores**. On the **Online stores** list page, on the **Action Pane**, on the **Channel** tab, click **Online store**.

2.  In the **Online store** form, on the **General** FastTab, enter information in the following fields:
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Name</strong></p></td>
    <td><p>Enter a name for the new online store.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Company</strong></p>
    <p>In AX 2012 R3, this field is called <strong>Legal entity</strong>.</p></td>
    <td><p>Select the legal entity that the online store belongs to.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Warehouse</strong></p></td>
    <td><p>Select the warehouse that products are shipped or sourced from. This warehouse is used by default.</p>
    <div class="alert">

    > [!NOTE]
    > <P>In AX 2012 R3, you can only configure a Microsoft Dynamics AX Retail store to use a warehouse that is managed in <STRONG>Inventory management</STRONG>. You can’t configure a Retail store to use a warehouse that is managed in <STRONG>Warehouse management</STRONG>.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Search name</strong></p></td>
    <td><p>Enter the store name that is displayed when a shopper searches for the store online.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Category hierarchy</strong></p></td>
    <td><p>Select the navigation category hierarchy for the online store. Online stores must be assigned to a category hierarchy that is assigned to the <strong>Retail channel navigation hierarchy</strong> category hierarchy type.</p>
    <div class="alert">

    > [!IMPORTANT]
    > <P>In AX 2012 R3, this field is located in the <STRONG>Channel product attributes</STRONG> form, on the <STRONG>General</STRONG> FastTab. To open the <STRONG>Channel product attributes</STRONG> form, in the <STRONG>Online store</STRONG> form, on the <STRONG>Set up</STRONG> tab, click <STRONG>Store product attributes</STRONG>.</P>


    </div>
    <p>For information about how to set up a retail channel navigation hierarchy, see <a href="set-up-a-retail-hierarchy.md">Set up a retail hierarchy</a>.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Currency</strong></p></td>
    <td><p>Select the currency that is accepted by default for the online store.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Default customer</strong></p></td>
    <td><p>Select the default customer for the online store. You can use the default customer as a template for entering the shipping address and other transaction information when a customer is added to an online transaction but is not yet registered in the store.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Customer address book</strong></p></td>
    <td><p>Select the address book to which to add customer records that are created in the online store.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Real-time Service profile</strong></p></td>
    <td><p>Select the service profile. The online store uses the profile data to access Microsoft Dynamics AX Application Object Server (AOS) to retrieve or update information in real time.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Channel profile</strong> (optional)</p></td>
    <td><p>Select the channel profile for the online store. The channel profile contains the URLs for the publishing site collection and the catalog site collection for the online store.</p>
    <p>This control is available only if Microsoft Dynamics AX 2012 R3 is installed.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Live channel database</strong> (optional)</p></td>
    <td><p>Select the database for the channel that is currently active.</p>
    <p>This control is available only if Microsoft Dynamics AX 2012 R3 is installed.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Prices include sales tax</strong></p></td>
    <td><p>Select this check box to indicate that the online store's prices include sales tax or value added-tax (VAT).</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Email notification profile</strong></p></td>
    <td><p>Select the profile that contains the email message templates to use to communicate with customers at different points in the sales process for the online store.</p></td>
    </tr>
    </tbody>
    </table>


3.  On the **Payment accounts** FastTab, in the **Connectors** field, select the payment connector that is used to connect to the payment provider. Then enter the configuration data to enable payment processing for transactions that are received through the online store.

4.  On the **Languages** FastTab, click **Add** to add the languages that can be displayed in the online store. Select the **Default** check box to specify the language that appears by default.

## Assign an online store to an organization hierarchy

Before you can assign product assortments, fulfill orders for the online store that you created, or generate reports that include information from it, you must assign the store to one or more organization hierarchies. At a minimum, you must assign the online store to an organization hierarchy that includes product assortments. For more information about how to create and modify organization hierarchies, see [Create or modify an organization hierarchy](create-or-modify-an-organization-hierarchy.md).

1.  Click **Organization administration** \> **Setup** \> **Organization** \> **Organization hierarchies**.

2.  In the **Organization hierarchies** form, select the hierarchy to add the online store to, and then click **View**.

3.  In the **Hierarchy designer -** form, on the **Action Pane**, click **Edit**.

4.  Click **Insert**, and then click **Retail channel**. In the **Retail channel** form, select an organization to add the online store to, and then click **OK**.

5.  After you finish making changes, follow one of these steps:
    
      - To save a draft, on the **Action Pane**, click **Save as draft**. Your changes are saved, but the hierarchy does not become active.
    
      - If you have finished making changes to the hierarchy, click **Publish and close**. When you publish a hierarchy, you must specify an effective date. The effective date indicates when the hierarchy becomes active.
    

    > [!NOTE]
    > <P>If you close the <STRONG>Hierarchy designer -</STRONG> form without saving changes, a message appears asking you to save the hierarchy as a draft or discard your changes. If you close the message without making a selection, your changes are discarded.</P>



6.  Repeat steps 2 through 5 to add the online store to additional organization hierarchies.

## Configure an online store

After you set up the basic information for an online store and add it to the appropriate organization hierarchies, you can add more configuration data for the store, such as assortments, delivery modes, and attributes. Then, publish the online store to create the basic store structure for the SharePoint site. After the online store is published, you can assign product catalogs to it and publish your retail products to the online store to make the products available to your customers.

Depending on the version of AX 2012 you’re using, use one of the following procedures to configure an online store.

## Configure an online store in AX 2012 R2 and AX 2012 Feature Pack

To configure an online store in AX 2012 R2 and AX 2012 Feature Pack, follow these steps:

1.  Click **Retail** \> **Common** \> **Retail channels** \> **Online stores**. In the **Online stores** list, double-click a store.

2.  In the **Online store** form, on the **Action Pane**, on the **Channel** tab, in the **Inventory** group, click **View assortments**.

3.  In the **View assortments** list, double-click an assortment. Alternatively, on the **Action Pane**, in the **New** group, click **Assortment** to add a new assortment.

4.  In the **Assortments** form, on the **Retail channels** FastTab, add the online store. If you are adding a new assortment, enter any additional details for the assortment. When you are finished, close the form.

5.  In the **Online store** form, on the **Action Pane**, on the **Channel** tab, in the **Pricing** group, click **Price groups**.

6.  In the **Retail channel price groups** form, add the price groups for the online store, and then close the form. Price groups define the trade agreements and promotions that apply to the online store.
    
    To view the prices, price adjustments, and discounts of all the products that are assigned to the online store, on the **Action Pane**, in the **Pricing** group, click **Price list**.

7.  On the **Action Pane**, on the **Set up** tab, follow these steps:
    
    1.  Click **Channel attributes** to add the attribute groups that apply to the entire store. For example, a channel attribute might include a PayPal address or an IP address for the online store. Channel attributes are applied when the online store is published.
    
    2.  Click **Channel product attributes** to add attributes that apply to all products in the online store, such as a Universal Products Code (UPC). Channel product attributes are applied to the product listings when the retail product catalog is published.
    
    3.  Click **Sales order attributes** to add attributes that are specific to sales orders. Sales-order attributes are applied to sales orders that are generated from the online store. For example, you can add a sales order attribute for a gift box.
    
    4.  Click **Map attributes**. In the **Map attributes** form, for each category in the online store, select the options that indicate how the attributes for each category or channel product should behave in the online store on the SharePoint site. For example, you can select whether attributes are required, whether they can be used for search, and whether they can be used as a filter in the navigation pane in the online store.
        
        For more information about how to map attributes, see [Manage the search schema in SharePoint 2013 Preview](http://go.microsoft.com/fwlink/?linkid=265297).
    
    5.  Click **Modes of delivery** to select the delivery methods that are offered by the online store.
    
    6.  Click **Payment methods** to select the payment methods that are accepted by the online store, such as credit cards and PayPal.
    
    7.  Click **Store locator group assignment** to assign the online store to a store locator group. When you assign stores to store locator groups, customers can be directed to locations where products are available, based on the retail store or online store where a product inquiry is made.
    
    8.  Click **Distribution locations** to set up the links between the online store in Microsoft Dynamics AX and the database that you use to publish the online store.

## Configure an online store in AX 2012 R3

To configure an online store in AX 2012 R3, follow these steps:

1.  Click **Retail** \> **Common** \> **Retail channels** \> **Online stores**. In the **Online stores** list, double-click a store.

2.  In the **Online store** form, on the **Action Pane**, on the **Channel** tab, in the **Inventory** group, click **View assortments**.

3.  In the **View assortments** list, double-click an assortment. Alternatively, on the **Action Pane**, in the **New** group, click **Assortment** to add a new assortment.

4.  In the **Assortments** form, on the **Retail channels** FastTab, add the online store. If you are adding a new assortment, enter any additional details for the assortment. When you’re finished, close the form.

5.  In the **Online store** form, on the **Action Pane**, on the **Channel** tab, in the **Pricing** group, click **Price groups**.

6.  In the **Retail channel price groups** form, add the price groups for the online store, and then close the form. Price groups define the trade agreements and promotions that apply to the online store.
    
    To view the prices, price adjustments, and discounts of all the products that are assigned to the online store, on the **Action Pane**, in the **Pricing** group, click **Pricing**.

7.  On the **Action Pane**, on the **Set up** tab, follow these steps:
    
    1.  Click **Channel attributes** to add the attribute groups that apply to the entire store. For example, a channel attribute might include a PayPal address or an IP address for the online store. Channel attributes are applied when the online store is published.
    
    2.  Click **Store product attributes** to add, modify, or remove product attributes, attribute values, and attribute metadata for any product or product category in the retail product hierarchy that is assigned to the online store. You can maintain attributes for individual products or product categories or you can maintain product attributes in bulk by using Microsoft Excel.
        
        To map product attributes to attribute metadata, in the **Channel product attributes** form, on the **Setup** tab, click **Set attribute metadata**.
        
        For more information about how to map attributes, see [Manage the search schema in SharePoint 2013 Preview](http://go.microsoft.com/fwlink/?linkid=265297). For more information about maintaining product attributes for a retail channel, see [Add and update product attributes for retail channels](add-and-update-product-attributes-for-retail-channels.md).
    
    3.  Click **Sales order attributes** to add attributes that are specific to sales orders. Sales-order attributes are applied to sales orders that are generated from the online store. For example, you can add a sales order attribute for a gift box.
    
    4.  Click **Modes of delivery** to select the delivery methods that are offered by the online store.
    
    5.  Click **Payment methods** to select the payment methods that are accepted by the online store, such as credit cards and PayPal.
    
    6.  Click **Store locator group assignment** to assign the online store to a store locator group. When you assign stores to store locator groups, customers can be directed to locations where products are available, based on the retail store or online store where a product inquiry is made.
    
    7.  Click **Channel database** to set up the links between the online store in Microsoft Dynamics AX and the database that you use to publish the online store.

## Publish an online store

After you configure an online store, you can publish it. How you publish the online store depends on what version of AX 2012 you’re using and whether you are publishing the online store for the first time or republishing an existing online store.


> [!NOTE]
> <P>If you change a category in a navigation category hierarchy that is assigned to an online store or a retail product catalog, you must republish the online store or catalog as follows:</P>
> <UL>
> <LI>
> <P>If you add or delete a category node, republish the online store and the catalog that use the category hierarchy.</P>
> <LI>
> <P>If you activate or inactivate a category, republish the online store and the catalog that use the category hierarchy.</P>
> <LI>
> <P>If you change the name of a category, republish the online store that uses the category hierarchy.</P></LI></UL>



Depending on the version of AX 2012 you’re using, use one of the following procedures to publish an online store.

## Publish an online store in AX 2012 R2 and AX 2012 Feature Pack

Use one of the following procedures to publish an online store depending on your circumstances.

**If you are publishing the online store for the first time**

1.  Click **Retail** \> **Common** \> **Retail channels** \> **Online stores**. In the **Online stores** list, double-click a store.

2.  In the **Online store** form, on the **Action Pane**, on the **Channel** tab, click **Publish** to publish the channel to a SharePoint site. When you click the **Publish** button, the **Publishing status** is set to **In progress**.

3.  On the **Action Pane**, on the **Set up** tab, click **Distribution locations**.

4.  In the **Distribution locations** form, click **Functions**, and then click **Deploy initial dataset**.

5.  In the **Select distribution schedule** dialog box, select the **A-1075\_OC** job, and then click **OK**.

6.  In the **Job for initial replication of data to an environment** form, leave all fields as they appear by default, and then click **OK**.

7.  After the scheduler job is complete, one of the following publishing statuses is displayed for the online store:
    
      - **Published** – The online store has been published to the SharePoint site. The category navigation has been created in the online store, and retail product catalogs can be published to the online store.
    
      - **Failed** – An error has occurred and the publishing process could not be completed.

**If you are republishing an existing online store**

1.  Click **Retail** \> **Common** \> **Retail channels** \> **Online stores**. In the **Online stores** list, double-click a store.

2.  In the **Online store** form, on the **Action Pane**, on the **Channel** tab, click **Publish** to publish the channel to a SharePoint site. When you click the **Publish** button, the **Publishing status** is set to **In progress**.

3.  Click **Retail** \> **Periodic** \> **Data distribution** \> **Create actions**. Leave all fields as they appear by default, and then click **OK** to run the **Create actions** job.

4.  Click **Retail** \> **Periodic** \> **Data distribution** \> **Distribution schedule**. In the **Distribution schedule** form, follow these steps:
    
    1.  In the left pane, select the distribution schedule **A-1075\_OC**.
    
    2.  On the **Scheduler jobs** FastTab, verify that the job number **A-1075\_OC** is displayed in the list.
    
    3.  Run the scheduler job. To manually run the scheduler job, on the menu bar at the top of the form, click **Run now**. To run the scheduler job in batch mode, on the **Scheduler jobs** FastTab, verify that the **Enabled** check box is selected for the job, and then click **Create batch job**. In the form that opens, enter information about the batch job. For more information about the options in the form, see [Submit a batch processing job from a form](submit-a-batch-processing-job-from-a-form.md).

5.  After the scheduler job is complete, one of the following publishing statuses is displayed for the online store:
    
      - **Published** – The online store has been published to the SharePoint site. The category navigation has been updated in the online store, and retail product catalogs can be published to the online store.
    
      - **Failed** – An error has occurred and the publishing process could not be completed.


> [!NOTE]
> <P>An online store must be set to a status of <STRONG>Published</STRONG> before a retail product catalog can be published to the online store. For information about how to create retail product catalogs, see <A href="key-tasks-create-retail-product-catalogs.md">Key tasks: Create retail product catalogs</A>.</P>



## Publish an online store in AX 2012 R3

Use one of the following procedures to publish an online store depending on your circumstances.

**If you are publishing the online store for the first time**

1.  Click **Retail** \> **Common** \> **Retail channels** \> **Online stores**. In the **Online stores** list, double-click a store.

2.  In the **Online store** form, on the **Action Pane**, on the **Channel** tab, click **Publish** to publish the channel to a SharePoint site. When you click the **Publish** button, the **Publishing status** is set to **In progress**.

3.  Click **Retail** \> **Periodic** \> **Data distribution** \> **Distribution schedule**. Select the distribution schedule **1070**, and then click **OK**.

4.  In the **Job for initial replication of data to an environment** form, leave all fields as they appear by default, and then click **OK**.

5.  After the scheduler job is complete, one of the following publishing statuses is displayed for the online store:
    
      - **Published** – The online store has been published to the SharePoint site. The category navigation has been created in the online store, and retail product catalogs can be published to the online store.
    
      - **Failed** – An error has occurred and the publishing process could not be completed.

**If you are republishing an existing online store**

1.  Click **Retail** \> **Common** \> **Retail channels** \> **Online stores**. In the **Online stores** list, double-click a store.

2.  In the **Online store** form, on the **Action Pane**, on the **Channel** tab, click **Publish** to publish the channel to a SharePoint site. When you click the **Publish** button, the **Publishing status** is set to **In progress**.

3.  Click **Retail** \> **Periodic** \> **Data distribution** \> **Distribution schedule**. In the **Distribution schedule** form, follow these steps:
    
    1.  In the left pane, select the distribution schedule **1070**.
    
    2.  Run the scheduler job. To manually run the scheduler job, on the menu bar at the top of the form, click **Run now**. To run the scheduler job in batch mode, on the **Scheduler jobs** FastTab, verify that the **Enabled** check box is selected for the job, and then click **Create batch job**. In the form that opens, enter information about the batch job. For more information about the options in the form, see [Submit a batch processing job from a form](submit-a-batch-processing-job-from-a-form.md).

4.  After the scheduler job is complete, one of the following publishing statuses is displayed for the online store:
    
      - **Published** – The online store has been published to the SharePoint site. The category navigation has been updated in the online store, and retail product catalogs can be published to the online store.
    
      - **Failed** – An error has occurred and the publishing process could not be completed.
    
    If a retail catalog is set up for the online store, also run the **1150** (Catalog) job to publish the catalog data by following the instructions in step 3.


> [!NOTE]
> <P>An online store must be set to a status of <STRONG>Published</STRONG> before a retail product catalog can be published to the online store. For information about how to create retail product catalogs, see <A href="key-tasks-create-retail-product-catalogs.md">Key tasks: Create retail product catalogs</A>.</P>



## (IND) Set up tax parameters for an online store

Use the **Online stores** form to set up the parameters that determine how taxes are displayed for online stores in India and to verify tax registration numbers for the legal entity. The tax registration numbers of the legal entity are displayed on the **Tax information** FastTab based on the warehouse selection that you make in the **Online stores** form.


> [!NOTE]
> <P>(IND) This procedure applies only if your company's primary address is in India and the following hotfix is installed:</P>
> <P><STRONG>2973603</STRONG></P>



To perform this task, follow these steps:

1.  Click **Retail** \> **Common** \> **Retail channels** \> **Online stores**. In the **Online stores** list, double-click a store.

2.  On the **General** FastTab, clear the **Prices include sales tax** check box.

3.  In the **Sales tax group for inter-state transactions** field, specify the sales tax group that is used for transactions for which the origin and delivery addresses are in two different states.

4.  Select the **Display tax amount per tax component** check box to display the tax amount for each tax component. When you check out an item from an online store, the tax amount that is calculated for each tax component is displayed along with the total tax amount.

## See also

[Online stores (list page)](https://technet.microsoft.com/en-us/library/jj730401\(v=ax.60\))

[Online store (form)](https://technet.microsoft.com/en-us/library/jj713630\(v=ax.60\))

[About online stores](about-online-stores.md)

[Set up an assortment](set-up-an-assortment.md)

[Set up a retail hierarchy](set-up-a-retail-hierarchy.md)

[Set up store payment methods](set-up-store-payment-methods.md)

[Add and update product attributes for retail channels](add-and-update-product-attributes-for-retail-channels.md)

[Troubleshoot installation issues for a Retail online store](troubleshoot-installation-issues-for-a-retail-online-store.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

