---
title: (IND) About transactions that include excise duty
TOCTitle: (IND) About transactions that include excise duty
ms:assetid: 69669b37-11f1-46bf-8dca-cc45fee218ec
ms:mtpsurl: https://technet.microsoft.com/library/JJ677892(v=AX.60)
ms:contentKeyID: 49385855
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) About transactions that include excise duty 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use the **Purchase order** form to record or invoice the following transaction types in an excise register:

  - Purchase orders

  - Packing slips

  - Product receipts

  - Invoices

  - Credit notes

## Recording a purchase order transaction that includes excise duty

When you invoice a purchase order that includes excise duty, the excise amounts that are calculated for the purchase order lines are debited to the recoverable accounts. The recoverable accounts are defined in the **Tax ledger posting groups** form for the excise control code (ECC) number.

The excise register, either RG23A (Parts I and II), RG23C (Parts I and Part II), or RG23D, is updated when you record the purchase order line. You can verify or update which register is updated with excise duty information in the **Purchase order** form, on the **Tax information** tab, in the **Excise record type** field. If you selected RG23A or RG23C, Part I is updated with the purchase order item quantity and Part II is updated with the excise duty amount.

The excise registers are updated based on the selections that you make in the **General ledger parameters** form.

  - If you select **Delivery date** or **Document date** in the **Vendor calculation date type** field in the **Sales tax** area, the excise register is updated on the date when the product receipt is generated.

  - If you select **Invoice date** in the **Vendor calculation date type** field in the **Sales tax** area, the excise register is updated on the date when the invoice is posted.

After you record a purchase order transaction that includes excise duty, the following information is updated in the **Purchase order** form:

  - The **Assessable value** field displays the total of the net amount and the charges for the order line. For example, if the net amount of the purchase order line is 1,000.00, and charges for the order line equal freight (200.00) plus insurance (300.00), the value that is displayed in the **Assessable value** field is 1,500.00. This is the net amount plus the charges (1,000.00 + 200.00 + 300.00).
    
    If you define the taxable basis of a tax code as an assessable value in the **Formula designer** form, the tax for a purchase order line is calculated based on the amount in the **Assessable value** field. If you enter **0.00** in this field, the taxable basis for the tax code is **0.00**. You can modify the value in the **Assessable value** field as necessary.

  - The **Direct settlement** field contains the excise record that is used to offset the reversed excise tax amounts against the balance amount in the excise tax recoverable accounts or the personal ledger accounts (PLA). The excise amount is credited to these accounts depending on the register that is selected in the **Direct settlement** field. If the excise type for the organization address is **Trader**, the **Direct settlement** field displays the value **None**, and cannot be changed. The PLA and the excise registers RG23A and RG23C must contain sufficient funds to offset the excise amount of the record that is selected in the **Direct settlement** field.
    

    > [!NOTE]
    > <P>The <STRONG>Direct settlement</STRONG> field is available only when the purchase order quantity is a negative value.</P>



## Generating packing slip transactions for a purchase order that includes excise duty

When you are updating the packing slip information for a purchase order that includes excise duty, in the **Purchase order** form, do the following:

1.  On the **Action Pane**, on the **Receive** tab, in the **Journals** group, click **Product receipt**.

2.  In the **Product receipt journal** form, on the **Lines** tab, in the **Received** field, enter the quantity of items received.

## See also

[(IND) Tax ledger posting groups (form)](https://technet.microsoft.com/library/jj664546\(v=ax.60\))

[(IND) Goods receipt note (form)](https://technet.microsoft.com/library/jj664834\(v=ax.60\))

[(IND) Purchase orders (modified form)](https://technet.microsoft.com/library/jj664798\(v=ax.60\))

  


