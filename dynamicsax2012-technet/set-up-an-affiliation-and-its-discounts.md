---
title: Set up an affiliation and its discounts
TOCTitle: Set up an affiliation and its discounts
ms:assetid: f34e5dfc-eff4-43ef-b262-51d0241cadc0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn497852(v=AX.60)
ms:contentKeyID: 62200186
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.RetailAffiliations
- Forms.RetailAffiliationPriceGroup
---

# Set up an affiliation and its discounts [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up affiliations and their discounts. This is useful if your retail stores give discounts to customers who are students or seniors, or customers who are affiliated with organizations that your company gives discounts to.

To set up price affiliations and their discounts, follow these steps:

1.  Click **Retail** \> **Setup** \> **Pricing and discounts** \> **Price groups**.

2.  In the **Price groups** form, click **New** to create a new price group.

3.  Enter a unique identification (ID) number and a descriptive name for the price group.

4.  Select the **Retail** check box if the price group is exclusively a retail price group. These price groups are only available for retail-specific discounts.

5.  Close the **Price groups** form.

6.  Click **Retail** \> **Setup** \> **Pricing and discounts** \> **Affiliations**.

7.  In the **Affiliations** form, click **New**.

8.  Enter a name and a description for the affiliation.

9.  Click **Price groups**.

10. In the **Affiliation price groups** form, click **Add**, and then in the **Price group** column, select the price group that you created in steps 1 through 5.

11. Close the **Affiliation price groups** form, and then close the **Affiliations** form.

12. Create a discount for the affiliation. In the discount form, on the Action Strip, click **Price groups**.
    
    For information about how to create discounts, see [Setting up price adjustments and discounts](setting-up-price-adjustments-and-discounts.md).

13. In the **Price groups** form, click **Add**, and then in the **Price group** column, select the price group that you created in steps 1 through 5.

14. Close the **Price groups** form.
    
    The discount is now linked to the affiliation through the price group.

## See also

[Setting up price adjustments and discounts](setting-up-price-adjustments-and-discounts.md)

[Setting up prices using price groups](setting-up-prices-using-price-groups.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

