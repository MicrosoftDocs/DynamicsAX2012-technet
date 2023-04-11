---
title: Set up a call center
TOCTitle: Set up a call center
ms:assetid: 1bf8c330-eaff-4d39-80a4-8e6ecb07d92b
ms:mtpsurl: https://technet.microsoft.com/library/Dn497725(v=AX.60)
ms:contentKeyID: 62200039
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.RetailMCRChannelListPage
- Forms.MCRChannelUser
- MsDynAx060.Forms.RetailMCRChannelDetailPage
- MsDynAx060.Forms.MCRChannelUser
- MsDynAx060.Forms.RetailMCRChannelListPage
- Forms.RetailMCRChannelDetailPage
- call center
- call center setup
- set up call center
- call center channel
- create call center
audience: Application User
ms.search.region: Global
---

# Set up a call center 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Microsoft Dynamics AX 2012 for Retail supports multiple retail channels, such as online stores, online marketplaces, brick-and-mortar stores, and call centers. In call centers, workers take customer orders over the phone and create sales orders. This topic describes how to create a call center and configure call center options.

Each call center can have its own users, payment methods, price groups, financial dimensions, and modes of delivery. You can configure these options when you create the call center.

The **Call center** form can also be used to enable or disable groups of features that are unique to call centers. The following three groups of features can be enabled:

  - Order completion – This group includes features that are related to payments and order completion in the **Sales order** form.

  - Directed selling – This group includes features that are related to source codes, scripts, and catalog requests.

  - Price control – This group includes features that are related to pricing options in the **Sales order** form.

When you enable these features in the call center settings, they are available in the **Sales order** form for users who are associated with the call center. Most of these features require additional setup before they can be used. For more information about each feature, see the relevant topic in [Setting up and maintaining Call center](setting-up-and-maintaining-call-center.md) and [Working with Call center](working-with-call-center.md).

After you create a call center, you can configure call center parameters and set up a catalog. For information about these setup tasks, see the links at the end of this topic.

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
<td><p>Required setup tasks</p></td>
<td><p>Create an organizational hierarchy. For more information, see <a href="create-or-modify-an-organization-hierarchy.md">Create or modify an organization hierarchy</a>. The call center is added to this hierarchy during the call center setup process.</p>
<p>Set up reason codes. For more information, see <a href="set-up-info-codes.md">Set up info codes</a>.</p>
<p>Set up price groups. For more information, see <a href="about-setting-prices-by-using-price-groups.md">About setting prices by using price groups</a>.</p></td>
</tr>
</tbody>
</table>


## 1\. Create a new call center

To create a new call center, follow these steps.

1.  Click **Retail** \> **Common** \> **Retail channels** \> **Call centers**.

2.  On the **Action Pane**, in the **New** group, click **Call center**.

3.  On the **General** FastTab, enter a name for the call center.

4.  Set the following additional fields on the **General** FastTab.
    
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
    <td><p><strong>Warehouse</strong></p></td>
    <td><p>The warehouse to use for the call center.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Email notification profile</strong></p></td>
    <td><p>The profile that contains the email templates that are used by the call center.</p>
    <p>You can set up email notification profiles in Retail. Click <strong>Retail</strong> &gt; <strong>Setup</strong> &gt; <strong>Parameters</strong> &gt; <strong>Retail Email notification profile</strong>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Enable order completion</strong></p></td>
    <td><p>Select this check box to enable the following features for call center users in the <strong>Sales order</strong> form:</p>
    <ul>
    <li><p>The payment process – Multiple payment buttons in the <strong>Sales order</strong> form are enabled when the <strong>Enable order completion</strong> check box is selected.</p></li>
    <li><p>The <strong>Complete</strong> button – This button controls access to the <strong>Sales order summary</strong> form, where the user can enter payment and submit the order. If the <strong>Enable order completion</strong> check box is not selected, users can create and save orders, but cannot complete them.</p></li>
    <li><p>The <strong>Recap</strong> button – This button controls access to the <strong>Sales order summary</strong> form, where the user can review the order, and optionally enter payment and submit the order.</p></li>
    <li><p>The <strong>Coupons</strong> button – Coupon calculation requires that the order be completed.</p></li>
    </ul></td>
    </tr>
    <tr class="even">
    <td><p><strong>Enable directed selling</strong></p></td>
    <td><p>Select this check box to enable the following directed selling options for call center users in the <strong>Sales order</strong> form:</p>
    <ul>
    <li><p>Source codes</p></li>
    <li><p>Scripts</p></li>
    <li><p>Additional item information</p></li>
    <li><p>Catalog requests</p></li>
    </ul></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Enable order price control</strong></p></td>
    <td><p>Select this check box to enable the following price control options for call center users in the <strong>Sales order</strong> form:</p>
    <ul>
    <li><p>Price matching</p></li>
    <li><p>Price details</p></li>
    <li><p>Price overrides</p></li>
    <li><p>Margin alerts</p></li>
    </ul></td>
    </tr>
    <tr class="even">
    <td><p><strong>Reason codes</strong></p></td>
    <td><p>The reason codes that are available in the <strong>Sales order</strong> form. Choose reason codes for price overrides, holds, and credits.</p>
    <p>You can set up reason codes in Retail. Click <strong>Retail</strong> &gt; <strong>Setup</strong> &gt; <strong>Info codes</strong>.</p></td>
    </tr>
    </tbody>
    </table>


5.  On the **Financial dimensions** FastTab, enter any financial dimensions to use for the call center.

6.  On the **Action Pane**, in the **Pricing** group, click **Price groups**.

7.  Click **New**, and then select a price group to use for the call center. Close the form.
    

    > [!NOTE]
    > <P>A retail price group is a list of products that have specific prices for specific customers. For more information about how to create price groups, see <A href="setting-up-prices-using-price-groups.md">Setting up prices using price groups</A>.</P>



8.  On the **Action Pane**, in the **Users** group, click **Channel users**.

9.  Click **New**, and then select the user ID and name of a user who has to perform tasks in the call center. Repeat this step to add as many users as you require, and then close the form.
    

    > [!IMPORTANT]
    > <P>Only users who have been added to the call center channel have access to the call center options in the <STRONG>Sales order</STRONG> form, such as the <STRONG>Sales order summary</STRONG> form, directed selling options, and pricing options.</P>



## 2\. Add the call center to an organization hierarchy

Next, add the call center to an organization hierarchy. The organization hierarchy is required for product assortments and delivery modes to function correctly. The organization hierarchy can also be used for reporting.

To add the call center to an organization hierarchy, follow the steps in [Create or modify an organization hierarchy](create-or-modify-an-organization-hierarchy.md).

## 3\. Add modes of delivery to the call center

You can specify which modes of delivery are available to customers in the call center. You can also specify different modes of delivery for specific combinations of products and addresses.


> [!NOTE]
> <P>Before you can add modes of delivery to a call center, you must create modes of delivery. For more information, see <A href="https://technet.microsoft.com/library/aa619881(v=ax.60)">Modes of delivery (form)</A>.</P>



To specify modes of delivery for a call center, follow these steps.

1.  Click **Retail** \> **Common** \> **Retail channels** \> **Call centers**.

2.  In the **Call center** form, on the **Set up** tab, on the **Action Pane**, click **Modes of delivery**, and then click **Manage modes of delivery**.

3.  In the list on the left, select a mode of delivery.

4.  On the **Retail channels** FastTab, click **Add line**.

5.  In the **Choose organization nodes** form, select an organization hierarchy.

6.  Expand the **Available organization nodes:** list, select the call center, and then click **Add \>\>**.

7.  Close the form.

8.  If you want to include one or more products in the mode of delivery, or exclude one or more products, on the **Products** FastTab, click **Add line**. Then specify the product, and also specify whether to include or exclude it.
    
    To add more than one product, click **Add products**.

9.  If you want to include one or more addresses in the mode of delivery, or exclude one or more addresses, on the **Addresses** FastTab, click **Add line** for each address. Then specify the address, and also specify whether to include or exclude it.

After you specify delivery modes for a call center, you must set up a batch job to complete the process of associating channels and products with delivery modes. To set up the batch job, follow these steps.

1.  Click **Retail** \> **Periodic** \> **Process delivery modes**.

2.  Enter the parameters for the batch job, and then click **OK**.

## 4\. Add payment methods to the call center

You can specify which payment methods customers can use in the call center. For more information, see [Set up payment methods (Call center)](set-up-payment-methods-call-center.md).

## 5\. Add attributes to the call center

You can use attributes to add descriptive characteristics to the products that the call center offers. After you complete the setup for attributes and attribute groups as described in [Set up attributes and attribute types](set-up-attributes-and-attribute-types.md) and [Set up retail attribute groups](set-up-retail-attribute-groups.md), you can assign attributes and attribute groups to the call center.

When you assign channel product attributes to the call center, you can select a channel hierarchy to associate with the call center. The channel hierarchy is a component of the process that you use to add products to the catalogs that you create for the call center.

To add attributes to a call center, follow these steps.

1.  Click **Retail** \> **Common** \> **Retail channels** \> **Call centers**.

2.  In the **Call center** form, on the **Set up** tab, on the **Action Pane**, click **Channel attributes** to add the attribute groups that apply to the whole call center.

3.  Click **Sales order attributes** to add attributes that are specific to sales orders. Sales order attributes are applied to sales orders that are generated from the call center. For example, you can add a sales order attribute for a gift box.

4.  Click **Channel product attributes** to add attributes that apply to all products in the call center, such as a Universal Products Code (UPC). Channel product attributes are applied to the products in the catalog when the catalog is published.

5.  To set a category hierarchy for the channel, follow these steps.
    
    1.  In the **Channel product attributes** form, in the **Category hierarchy** field, select a hierarchy to use for the channel.
    
    2.  On the **Action Pane**, click **Publish channel updates**.
    

    > [!NOTE]
    > <P>Before you can add channel product attributes to a call center, a default hierarchy must be assigned to the retail assortment in the <STRONG>Organization hierarchy purposes</STRONG> form. For more information, see <A href="https://technet.microsoft.com/library/hh208614(v=ax.60)">Organization hierarchy purposes (form)</A>.</P>



## Next step

After the call center is set up, perform these additional tasks.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Topic</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Configure call center parameters.</p></td>
<td><p><a href="configuring-parameters-and-initial-settings-call-center.md">Configuring parameters and initial settings (Call center)</a></p></td>
</tr>
<tr class="even">
<td><p>Set up the products that you want the call center to offer.</p></td>
<td><p><a href="setting-up-retail-products.md">Setting up retail products</a></p></td>
</tr>
<tr class="odd">
<td><p>Set up a product assortment.</p></td>
<td><p><a href="set-up-an-assortment.md">Set up an assortment</a></p></td>
</tr>
<tr class="even">
<td><p>Create a call center catalog.</p></td>
<td><p><a href="create-call-center-catalogs.md">Create call center catalogs</a></p></td>
</tr>
</tbody>
</table>


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
<p><strong>Call center</strong> configuration key</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>Retail catalog manager</p>
<p>Retail operations manager</p></td>
</tr>
</tbody>
</table>


## See also

[Call center](call-center.md)

[Setting up and maintaining Call center](setting-up-and-maintaining-call-center.md)

[Working with Call center](working-with-call-center.md)

  


