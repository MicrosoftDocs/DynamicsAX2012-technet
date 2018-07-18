---
title: Set up affiliations (Retail essentials)
TOCTitle: Set up affiliations (Retail essentials)
ms:assetid: e5fc333c-7654-4afa-a3e7-cc23c17227aa
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn859570(v=AX.60)
ms:contentKeyID: 63820145
ms.date: 12/17/2014
mtps_version: v=AX.60
---

# Set up affiliations (Retail essentials) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up price discounts and affiliations and how to add an affiliation to a customer record. An affiliation identifies customers who are members of or associated with a group, for example, seniors or students, or customers who are affiliated with organizations that your company provides discounts to. When a customer who has an affiliation added to their record is making a purchase, the affiliation and its discount are automatically added to the transaction when the cashier adds the customer to the transaction.

## Set up price discounts

This section explains how to set up affiliations and price discounts. You must complete this section before you can add an affiliation to a customer record.

1.  Click **Retail essentials** \> **Merchandising** \> **Setup** \> **Price and discount setup** \> **Price groups**.

2.  In the **Price groups** form, click **New** to create a new price group.

3.  Enter a unique identification (ID) number and a descriptive name for the price group.

4.  Select the **Retail** check box if the price group is exclusively a retail price group. These price groups are only available for retail-specific discounts.

5.  Close the **Price groups** form.

6.  Click **Retail essentials** \> **Merchandising** \> **Setup** \> **Price and discount setup** \> **Affiliations**.

7.  In the **Affiliations** form, click **New**.

8.  Enter a name and a description for the affiliation.

9.  Click **Price groups**.

10. In the **Affiliation price groups** form, click **Add**, and then in the **Price group** column, select the price group that you created in steps 1 through 5.

11. Close the **Affiliation price groups** form, and then close the **Affiliations** form.

12. Click **Retail essentials** \> **Merchandising** \> **Pricing and discounts** \> **Discounts**.

13. Click **Price groups**.
    
    For information about how to create discounts, see [Setting up prices, price adjustments, and discounts (Retail essentials)](setting-up-prices-price-adjustments-and-discounts-retail-essentials.md).

14. In the **Price groups** form, click **Add**, and then in the **Price group** column, select the price group that you created in steps 1 through 5.

15. Close the **Price groups** form.
    
    The discount is now linked to the affiliation through the price group.

## Add an affiliation to a customer record

After you have set up affiliations and price discounts, use this procedure to add an affiliation to a customer record.

1.  Click **Retail essentials** \> **Customers** \> **All customers**.

2.  On the **All customers** list page, double-click a customer.

3.  In the **Customers** form, on the **Action Pane**, on the **Retail** tab, in the **Related information** group, click **Affiliations**.

4.  In the **Affiliations** form, in the **Name** column, select an affiliation.

5.  If the customer has more than one affiliation, click **New**, and then, in the **Name** column, select another affiliation.

## See also

[Set up a price adjustment or discount (Retail essentials)](set-up-a-price-adjustment-or-discount-retail-essentials.md)

[Set up price groups (Retail essentials)](set-up-price-groups-retail-essentials.md)

Set up price point groups

  


