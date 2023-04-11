---
title: (IND) Verify the import details for an import purchase order
TOCTitle: (IND) Verify the import details for an import purchase order
ms:assetid: 53eaa34f-769e-4d33-8d3a-4b76756bbe1e
ms:mtpsurl: https://technet.microsoft.com/library/JJ677821(v=AX.60)
ms:contentKeyID: 49385784
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- purchase order
- import
- (IND)
- india
- import details
- import purchase order
audience: Application User
ms.search.region: India
---

# (IND) Verify the import details for an import purchase order 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

To apply for advance authorization (AA) incentive schemes, you must attach the authorization scheme to an import purchase order. You can use the **Purchase order** form to create an import purchase order and then verify the import details.

For information about how to create an import purchase order and attach an AA incentive scheme to it, see [(IND) Create an import order and apply the AA incentive scheme to the import order](ind-create-an-import-order-and-apply-the-aa-incentive-scheme-to-the-import-order.md).

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  On the **All purchase orders** list page, select the import order to verify the details for.

3.  In the **Purchase order** form, click the **Purchase order lines** FastTab.

4.  On the **Action Pane**, on the **Purchase** tab, click **Sales tax**.

5.  In the **Sales tax transactions** form, on the **General** tab, view the customs fields in the **Customs currency** and **Adjustment in customs currency** field groups. Close the form.

6.  Click **General ledger** \> **Common** \> **EXIM Authorization schemes**. Select an authorization scheme, and then, on the **Action Pane**, in the **Inquiry** group, click **Import details**.

7.  In the **Import details** form, view the value in the **Utilized** field. This field is updated to include the quantity in the posted import order. The **Balance** field is updated based on the quantity in the **Allowed** field and the value in the **Utilized** field.

## See also

[(IND) Create an import order and apply the AA incentive scheme to the import order](ind-create-an-import-order-and-apply-the-aa-incentive-scheme-to-the-import-order.md)

[(IND) Import details - AA/DFIA (form)](https://technet.microsoft.com/library/jj664632\(v=ax.60\))

[(IND) Temporary sales tax transactions (modified form)](https://technet.microsoft.com/library/jj664487\(v=ax.60\))

  


