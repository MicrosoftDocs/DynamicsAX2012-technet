---
title: (IND) Attach an EPCG incentive scheme to an import order
TOCTitle: (IND) Attach an EPCG incentive scheme to an import order
ms:assetid: a533d482-4c3f-4741-a6ba-db7ca61b196d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664737(v=AX.60)
ms:contentKeyID: 49386069
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (IND)
- india
- import order
- EPCG incentive scheme
- Attach EPCG incentive scheme
audience: Application User
ms.search.region: India
---

# (IND) Attach an EPCG incentive scheme to an import order 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When you create a new purchase order to import products that meet the requirements for the Export Promotion Capital Goods (EPCG) incentive scheme, you can assign an EPCG incentive scheme to the purchase order.

**Prerequisites**

  - Create and approve an EPCG incentive scheme. Importable items and approved vendors for the importable items are assigned to the EPCG incentive scheme during the approval process. For more information, see [(IND) Approval EPCG schemes (form)](https://technet.microsoft.com/en-us/library/jj710885\(v=ax.60\)).

  - Set up import and export taxes. For more information, see [(IND) Tax codes for incentive schemes (form)](https://technet.microsoft.com/en-us/library/jj664578\(v=ax.60\)).

  - Define currency exchange rates for vendor currencies. For more information, see [Currency exchange rates (form)](https://technet.microsoft.com/en-us/library/hh209477\(v=ax.60\)).

<!-- end list -->

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  On the **Action Pane**, on the **Purchase order** tab, in the **New** group, click **Purchase order**.

3.  In the **Create purchase order** form, select a vendor for the import order. The vendor must be listed as an approved vendor of importable items in the EPCG incentive scheme.

4.  Select the **Import order** check box.

5.  On the **General** FastTab, select the vendor’s currency.

6.  Enter the remaining purchase order details, and then click **OK**.

7.  In the **Purchase order** form, on the **Purchase order lines** FastTab, select an item, and then enter line item details. The item must be listed as an importable item in the EPCG incentive scheme.

8.  On the **Line details** FastTab, on the **Setup** tab, in the **Sales tax** group, select an item sales tax group.

9.  On the **Tax information** tab, in the **Customs tariff code** field, select a tariff for the item.

10. In the **EXIM incentive scheme** section, select an EPCG incentive scheme group. The **Port ID** and **Product group** fields are automatically added from the approved EPCG incentive scheme.

11. Optional: Before you post the import order, you can verify the import details. Click **General ledger** \> **Common** \> **EXIM Authorization schemes**. Select the EPCG incentive scheme, and then, on the **Action Pane**, in the **Inquiry** group, click **Import details**.

12. Complete and post the purchase order.

## See also

[Purchase order (form)](https://technet.microsoft.com/en-us/library/aa557983\(v=ax.60\))

[Create a purchase order](create-a-purchase-order.md)

[(IND) Import details - EPCG (form)](https://technet.microsoft.com/en-us/library/jj664479\(v=ax.60\))

[(IND) Create a primary EPCG license](ind-create-a-primary-epcg-license.md)

[(IND) Verify import information for an EPCG license](ind-verify-import-information-for-an-epcg-license.md)

  


