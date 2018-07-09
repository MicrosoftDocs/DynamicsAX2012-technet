---
title: (RUS) Create and post deferrals by using the Proportional VAT refund method
TOCTitle: (RUS) Create and post deferrals by using the Proportional VAT refund method
ms:assetid: 58043f5c-74a6-497e-8fde-4e0a38b0b926
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ665401(v=AX.60)
ms:contentKeyID: 49387489
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Create and post deferrals by using the Proportional VAT refund method [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the following procedures to create and post deferrals by using the proportional VAT refund method.

## Prerequisites

Complete the following tasks before you process the incoming VAT for deferrals: 

  - Create transactions for write-off and disposal of deferrals. For more information, see [(RUS) Generate a deferrals write-off voucher for one deferral](rus-generate-a-deferrals-write-off-voucher-for-one-deferral.md).

  - Create and update a purchase book.

## Create and post a purchase order

Use the **Purchase order** form to create and post a purchase order for the purchase of items. For more information, see [Purchase order (form)](https://technet.microsoft.com/en-us/library/aa557983\(v=ax.60\)) and [(RUS) Purchase orders (modified form)](https://technet.microsoft.com/en-us/library/jj733294\(v=ax.60\)).

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Press CTRL+N to open the **Create purchase order** form. For more information, see [Create a purchase order](create-a-purchase-order.md) and [(RUS) Generate a facture for a purchase order](rus-generate-a-facture-for-a-purchase-order.md).

3.  In the **Vendor account** field, select the vendor from whom you are purchasing the items.

4.  Click **OK** to open the **Purchase order** form.

5.  On the **Purchase order lines** FastTab, in the **Item number** field, select the item to be purchased.

6.  Click the **Setup** tab, and in the **Sales tax group** and **Item sales tax group** fields, select the required sales tax group and item sales tax group.

7.  Click the **Financial dimensions** tab, and in the **ProfitTax** field, select the expense code. This field must be the same as the expense code set up in the **Counter setup** form.
    

    > [!NOTE]
    > <P>When you create an expense code, you can select the relevant main accounts and financial dimensions to calculate the tax, and to accumulate the correspondence accounts for the transaction.</P>



8.  Click the **Purchase** tab, and on the **Generate** action group, click **Confirm** to confirm the purchase order.

9.  On the **Invoice** tab, in the **Generate** action group, click **Facture**.

10. In the **Update facture** form, click **Facture** \> **Post** to post the facture.

## Create a deferral

Use the **Counter setup** form to create a deferral using the periodic procedure.

1.  Click **General ledger** \> **Periodic** \> **Deferrals** \> **Deferrals creating**.

2.  Select the created sequence, and then click **Calculate marked**.

3.  In the **Start date** and **End date** fields, enter the starting and ending dates for the deferral calculation.

4.  Click **OK**.


> [!NOTE]
> <P>Use the <STRONG>Deferrals</STRONG> form to view the new deferrals. You can also verify the proportional VAT deduction method for the deferral, and view the link to the source invoice for the deferral.</P>



## Create and post a deferral journal

You must create and post a journal for deferrals that are created using the periodic process.

1.  Click **General ledger** \> **Journals** \> **Deferrals journal**.

2.  Press CTRL+N to create a new deferrals journal.

3.  In the **Name** field, select the journal name. Enter a description for the journal in the **Description** field.

4.  Click **Lines** to open the **Journal voucher** form.

5.  Press CTRL+N to open the **Create new line** form.

6.  In the **Transaction date** field, select the transaction date, and in the **Transaction type** field, indicate whether the transaction is a write-off or disposal transaction.

7.  In the **Deferral ID** field, select the identification for the deferral.

8.  In the **Model number** field, select the model number for the deferral.

9.  Click **OK**. The details of the deferral are copied into the voucher lines.

10. Click **Post** \> **Post** to post the journal.


> [!NOTE]
> <P>You can also reverse transactions to write off or dispose of deferrals. The transactions can be reversed only if the purchase book for the relevant period is open. When you reverse the transactions, a line is created for each reversal transaction when you process the incoming VAT for that period. The reversed amount corresponds with the posted incoming VAT amount of the reversed transaction.</P>


  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

