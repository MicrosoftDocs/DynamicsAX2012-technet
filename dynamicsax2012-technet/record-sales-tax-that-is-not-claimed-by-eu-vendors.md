---
title: Record sales tax that is not claimed by EU vendors
TOCTitle: Record sales tax that is not claimed by EU vendors
ms:assetid: 8e06bc57-37d9-420c-ae99-d61a1f36f92c
ms:mtpsurl: https://technet.microsoft.com/library/Aa498354(v=AX.60)
ms:contentKeyID: 44081006
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Record sales tax that is not claimed by EU vendors 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If your legal entity is located in a country/region in the European Union (EU), and you buy items from a vendor in another country/region in the EU, your legal entity must account for purchases that are not subject to sales tax.

If the vendor invoice does not include the value-added tax (VAT) that current tax regulations require, you must record the sales tax.

You must first create a sales tax code to record the sales tax. Then create a ledger posting group for the EU purchases that are not subject to sales tax, and assign the ledger posting group to a sales tax group. You must also assign an item sales tax group to a sales tax code.

## Create a ledger posting group for EU purchases that are not subject to sales tax

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Ledger posting groups**.

2.  Click **New**.

3.  In the **Ledger posting group** field, enter an identifier for the ledger posting group.

4.  In the **Use tax expense** field, select a main account for the ledger posting group. You can select the main account that is used for incoming VAT, or you can create a separate main account that is used for reporting.

5.  In the **Use tax payable** field, select a main account for the ledger posting group.

6.  Close the form.

## Create a sales tax group, and assign the ledger posting group to the sales tax group

Before you can complete this procedure, you must create a sales tax code that is used to record sales tax that is not claimed.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax groups**.

2.  Select a sales tax group.

3.  On the **Setup** FastTab, add the sales tax code that you created for sales tax that is not claimed.

4.  Select the **Use tax** check box for the sales tax code.

5.  Close the form.

6.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.
    
    –or–
    
    Click **Procurement and sourcing** \> **Common** \> **Vendors** \> **All vendors**.

7.  Double-click the EU vendor account.

8.  On the **Action Pane**, click **Edit**.

9.  On the **Invoice and delivery** FastTab, select the sales tax group to assign to the vendor.

10. Close the form.

## Create an item sales tax group, and assign a sales tax code to the item sales tax group

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Item sales tax groups**.

2.  Click **New**, enter an identifier in the **Item sales tax group** field, and select a reporting type.

3.  On the **Setup** FastTab, click **Add**, and then select the sales tax code to assign to the item sales tax group.

4.  Close the form.

5.  Click **Product information management** \> **Common** \> **Released products**.

6.  Double-click the item that you are purchasing from the EU vendor.

7.  In the **Item sales tax group** field, select the item sales tax group that you created.
    

    > [!NOTE]
    > <P>If you also purchase the item from non-EU vendors, and you do not want to change the default item sales tax group for the item, you can change the item sales tax group on the purchase order line or invoice line for the EU vendor.</P>



8.  Close the form.

## Additional tasks and information

1.  Create and post the purchase order or vendor invoice that includes the item that you are purchasing from the EU vendor. For more information, see [Create a purchase order](create-a-purchase-order.md).

2.  When you receive the goods and post the vendor invoice, the sales tax appears to be calculated and posted as if it is being paid to the vendor. However, the following transactions occur instead:
    
      - The sales tax is debited to the account that you selected in the **Use tax payable** field for the ledger posting group.
    
      - An equal transaction is credited to the account that you selected in the **Use tax payable** field for the ledger posting group. However, you have not actually paid the sales tax amount to the vendor. Therefore, nothing is settled with the tax authorities.
    

    > [!NOTE]
    > <P>If the vendor charges VAT on the invoice, and you accept the invoice, you cannot deduct the VAT amount from the VAT calculation that you prepare for the necessary tax authority. Instead, you must post the VAT amount that you paid to the vendor as part of the purchase cost. To post the VAT amount as part of the purchase cost, select an appropriate sales tax group and item sales tax group for each line before you post.</P>



3.  Click **General ledger** \> **Periodic** \> **Sales tax payments** \> **Sales tax payments**. Complete the periodic job. The transactions in step 2 offset each other, and sales tax is not paid for the transaction with the EU vendor.

## See also

[Set up and use sales tax codes](set-up-and-use-sales-tax-codes.md)

[Set up and use a sales tax group](set-up-and-use-a-sales-tax-group.md)

[Create item sales tax groups](create-item-sales-tax-groups.md)

[Ledger posting groups (form)](https://technet.microsoft.com/library/aa598801\(v=ax.60\))

  


