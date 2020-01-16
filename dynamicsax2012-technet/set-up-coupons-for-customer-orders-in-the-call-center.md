---
title: Set up coupons for customer orders in the call center
TOCTitle: Set up coupons for customer orders in the call center
ms:assetid: f4155152-096c-4c36-a7d1-54f2436d23d8
ms:mtpsurl: https://technet.microsoft.com/library/Dn497853(v=AX.60)
ms:contentKeyID: 62224166
author: Khairunj
ms.date: 05/01/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.MCRCoupon
- Forms.MCRCouponImportDialog
- Forms.MCRCouponCatalog
- Forms.MCRCouponCopy
- Forms.MCRCouponCustomer
- Forms.MCRCouponSalesTable
- Forms.MCRCouponItem
- Forms.MCRPMCouponListPage
audience: Application User
ms.search.region: Global
---

# Set up coupons for customer orders in the call center 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

You can set up coupons to offer discounts to customers when they place an order with your organization’s call center. Coupons can be either a fixed amount discount or a percentage of an item price or order total. This topic explains how to create different types of coupons, how to set up parent-child coupons, and how to copy or void a coupon.

## Create a coupon

You can create coupons that offer customers a discount on their order. For example, an amount coupon might offer customers a 75.00 discount when the customer spends 750.00 or more. Use this procedure to create coupons.

1.  Click **Call center** \> **Setup** \> **Coupons** \> **Coupons**.

2.  In the **Coupons** form, click **New**. If a coupon ID is not automatically created, enter the information in the appropriate fields.

3.  Enter a name and description for the coupon.

4.  On the **Overview** FastTab, add or select information in the field groups that are described in the following table.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field group</p></th>
    <th><p>Information</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Attribute</strong></p></td>
    <td><p>In the <strong>Redemption rate</strong> field, enter the value of the expected redemption rate for the coupon as a percentage, and then select whether the coupon is a one-time use coupon, will be automatically reissued, or is specific to a customer.</p>
    <p>If the coupon is specific to a customer, click <strong>Set up</strong> &gt; <strong>Customer reference</strong>, and then, in the <strong>Customer reference</strong> form, add or import customers who are eligible for the coupon.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Valid</strong></p></td>
    <td><p>In the <strong>Start date</strong> and <strong>End date</strong> fields, enter the dates for the first and last days that the coupon is valid.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Include/exclude rules</strong></p></td>
    <td><p>In the <strong>Catalogs</strong> and <strong>Items</strong> fields, select whether any catalogs or items are included or excluded in the coupon. If you select <strong>Include</strong> or <strong>Exclude</strong>, click <strong>Set up</strong>, and then select <strong>Include/exclude catalogs</strong> or <strong>Include/exclude products</strong> and enter information about the catalog or item.</p>
    <p>If you select <strong>None</strong> in these fields, all catalogs or items are included in the coupon.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Miscellaneous</strong></p></td>
    <td><p>If this coupon can’t be used with other discounts, select the <strong>Exclusive</strong> check box, and in the <strong>Origin</strong> field, select where the coupon can be used.</p>
    <p>If this is a manufacturer’s coupon, select the <strong>Manufacturer coupon</strong> check box.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Future coupon</strong></p></td>
    <td><p>If this coupon will be associated as a parent to other coupons, select the <strong>Parent coupon</strong> check box. If this coupon should be associated as a child coupon with an existing coupon, select the parent coupon in the <strong>Parent coupon ID</strong> field.</p>
    <p>For example, you might create a coupon for the upcoming spring catalog. All other coupons that you create for the spring catalog would be child coupons of the spring catalog coupon. Child coupons might include a 20 percent discount for new customer orders, a 10 percent discount on a newly released item, or 95.00 off orders of 1,000.00 or more.</p></td>
    </tr>
    </tbody>
    </table>


5.  On the **Discounts** FastTab, click **New**, and then, in the **Amount** field, enter the minimum amount required on an order before the coupon can be applied.

6.  In the **Value** field, enter the amount or percentage value of the coupon.

7.  In the **Value attributes** field, select whether the coupon applies to a percentage of the order, the amount of the order, or the amount per unit of an order.

8.  Click **Activate** to activate the coupon.
    

    > [!IMPORTANT]
    > <P>You can’t modify a coupon after you have activated it.</P>



## Copy a coupon

You can create a copy of an existing coupon and use as much information from the original coupon as needed. Use this procedure to copy a coupon.

1.  Click **Call center** \> **Setup** \> **Coupons** \> **Coupons**.

2.  In the **Coupons** form, select the coupon that you want to copy, and then click **Copy**.

3.  In the **Copy** form, click **New**, and then, in the **Description** field, enter a description of the new coupon.

4.  Select the check boxes to copy the appropriate information to the new coupon:
    
      - **Coupon attributes** – Copy the attributes from the original coupon. These attributes include the information included on the **Overview** and **Discounts** FastTabs in the **Coupons** form.
    
      - **Item rules** – Copy item rules, if they are included in the original coupon.
    
      - **Catalog rules** – Copy catalog rules, if they are included in the original coupon.
    
      - **Customers** – Copy customer information, if the original coupon is marked as **Customer specific** .

5.  Click **Copy**.
    
    The new coupon will appear in the list of coupons in the **Coupons** form.

## Void a coupon

Use this procedure to void a coupon.

1.  Click **Call center** \> **Setup** \> **Coupons** \> **Coupons**.

2.  In the **Coupons** form, select a coupon in the list, and then click **Void**.

## See also

Create a sales order in Call center

  


