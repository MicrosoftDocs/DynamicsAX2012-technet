---
title: Settle a promissory note
TOCTitle: Settle a promissory note
ms:assetid: e0b507d0-f4c1-4880-b987-ea9f29ecafce
ms:mtpsurl: https://technet.microsoft.com/library/Aa551320(v=AX.60)
ms:contentKeyID: 36059705
author: Khairunj
ms.date: 06/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Settle a promissory note 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can settle a remitted promissory note when it is due.

## Settle a promissory note in a journal

1.  Click **Accounts payable** \> **Journals** \> **Promissory notes** \> **Settle promissory note journal**.

2.  Press CTRL+N to create a journal, or select a journal.

3.  On the **Promissory note** tab, select the bank account that was used when the promissory note was remitted.

4.  Click **Lines**.

5.  In the **Journal voucher** form, select the vendor account for the invoice, and then click **Functions** \> **Settlement**.

6.  In the **Settle open transactions** form, select the check box in the **Mark** field for the remitted transaction from the invoice. Close the form to transfer the transaction to the journal line.

7.  In the **Journal voucher** form, click **Post** \> **Post**.

A new line with a status of **Honored** and a sequence number of 1 or higher is created for the remitted promissory note and is shown in the **Promissory note journal** form. In the **Promissory note statistics** form, the number in the **Honored documents** row is increased, and the number in the **Remitted and remitted-confirmed documents** row is decreased.

When you settle a remitted promissory note, the remitted promissory notes summary account is debited and the bank summary account is credited. When you settle an invoice-remitted invoice, the invoice-remitted summary account is debited and the vendor summary account is credited.

(ESP) Conditional sales tax is posted when you settle a promissory note that is drawn for a customer invoice on which conditional sales tax is applied. You can view the conditional sales tax that is posted for the payment in the **Voucher transactions** form.


> [!NOTE]
> <P>If you cannot post and you receive a message that mentions posting restrictions, you might be able to post only the journals that you created. For more information, see <A href="https://technet.microsoft.com/library/hh227598(v=ax.60)">Posting restrictions (form)</A>.</P>



## Close settled promissory note documents

Use the **Remittance files for vendors** form to change the status of promissory note documents from **Honored** to **Closed**. You can see the number of honored documents and closed documents in the **Promissory note statistics** form.

1.  Click **Cash and bank management** \> **Common** \> **Bank accounts**.

2.  Select a bank account. On the Action Pane, click the **Manage payments** tab, and then click **Vendor remittances**.
    

    > [!NOTE]
    > <P>You can also open the form from the <STRONG>Methods of payment</STRONG> form.</P>



3.  Select a remittance file, and then click the **Status** tab.

4.  Select the **Closed** check box.

## See also

[Redraw a promissory note](redraw-a-promissory-note.md)

[Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md)

[Journal header (form)](https://technet.microsoft.com/library/aa557917\(v=ax.60\))

[Promissory note statistics (form)](https://technet.microsoft.com/library/aa550186\(v=ax.60\))

[Remittance files for vendors (form)](https://technet.microsoft.com/library/aa585800\(v=ax.60\))

[About payment types](about-payment-types.md)

[View payments made to a vendor](view-payments-made-to-a-vendor.md)

[Specify when a vendor bank account is active](specify-when-a-vendor-bank-account-is-active.md)

  


