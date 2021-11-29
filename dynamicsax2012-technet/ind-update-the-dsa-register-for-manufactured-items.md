---
title: (IND) Update the DSA register for manufactured items
TOCTitle: (IND) Update the DSA register for manufactured items
ms:assetid: 1d16de20-34e7-44a2-bf59-4538b6b77efc
ms:mtpsurl: https://technet.microsoft.com/library/JJ664535(v=AX.60)
ms:contentKeyID: 49385616
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- DSA
- (IND)
- India
- DSA register
- Update DSA register
audience: Application User
ms.search.region: India
---

# (IND) Update the DSA register for manufactured items 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this information to update the daily stock account (DSA) register for manufactured items.

In Microsoft Dynamics AX 2012, items and products are referred to interchangeably. A product name is always associated with an item ID. The main concepts that are associated with items are product, product master, and product variant. For more information, see [View items](view-items.md).

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Click **Sales order** to open the **Create sales order** form.

3.  In the **Customer account** field, select the customer account that the sales order was generated for.

4.  In the **Sales order** form, on the **Sales order lines** tab, in the **Item number** field, select an item.

5.  In the **Quantity**, **Unit**, and **Unit price** fields, enter the quantity ordered, the unit of measure for the item, and the purchase price per unit.

6.  Click the **Line details** tab, and then click the **Setup** tab.

7.  In the **TCS group** field, select the TCS group that is used to calculate withholding tax.

8.  Click the **Tax information** tab.

9.  In the **Excise type** field, select **Manufacturer**.

10. In the **Excise record type** field, select **None**.

11. Select the **DSA** check box.
    

    > [!NOTE]
    > <P>The <STRONG>DSA</STRONG> check box can be selected only for released products that have <STRONG>Production</STRONG> selected in the <STRONG>Default order type</STRONG> field on the <STRONG>Default order settings</STRONG>.</P>



12. On the **Sales order lines** tab, click **Product and supply** \> **Withholding tax** to open the **Temporary withholding tax transactions** form.

13. In the **Adjusted withholding tax amount in total** field, verify the calculated TCS amount and close the form.

14. In the **Sales order** form, click **Invoice** \> **Invoice** to open the **Posting invoice** form.

15. In the **Posting invoice** form, click **OK** to post the sales invoice.

## See also

[(IND) DSA details (form)](https://technet.microsoft.com/library/jj664573\(v=ax.60\))

  


