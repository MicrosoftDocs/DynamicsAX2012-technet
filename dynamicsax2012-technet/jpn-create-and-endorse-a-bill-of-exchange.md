---
title: (JPN) Create and endorse a bill of exchange
TOCTitle: (JPN) Create and endorse a bill of exchange
ms:assetid: c1c22cfc-9812-4f64-af12-b905eb9df72a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ911062(v=AX.60)
ms:contentKeyID: 52075312
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- JP - 00008
---

# (JPN) Create and endorse a bill of exchange 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can accept a bill of exchange (BOE) by drawing a bill of exchange, and you can endorse the BOE to a vendor for a partial or full payment by using Japan endorsement bills of exchange. You can endorse any BOE that is not matured, and that has a status of **Drawn** or **Redrawn**. Also you can settle the open vendor invoices with the endorsed BOE after you perform the endorsement.After the endorsed BOE is matured, you can settle the endorsed BOE if you have not received a non-acceptance message from the vendor. Additionally, if the endorsed BOE itself has not been settled, you can reverse the BOE endorsement at any time. However, if you have settled the BOE with a specific vendor invoice, you must first reverse the settlement with the vendor invoice.


> [!NOTE]
> <P>Select the posting profile to use for endorsed BOEs in the <STRONG>Ledger and sales tax</STRONG> area of the <STRONG>Accounts receivable parameters</STRONG> form.</P>



## Create a bill of exchange

1.  Click **Accounts receivable** \> **Common** \> **Bill of exchange** \> **Endorse bills of exchange**.

2.  On the **Endorse bills of exchange** list page, on the **Bill of exchanges list** tab, click **Draw bill of exchange journal** to create a new BOE journal.

3.  Click **Lines** to create a new line, and then, in the **Account** field, select the customer account number. For more information, see [Draw a bill of exchange](draw-a-bill-of-exchange.md).

4.  In the **Description** field, select invoice.

5.  In the **Credit** field, enter the credit amount.

6.  Click **Functions** \> **Settlement** to open the **Settle open transactions** form.

7.  Select the customer invoice line, and then select the **Mark** check box to settle the open transactions. For more information, see [Settle a bill of exchange](settle-a-bill-of-exchange.md).

8.  Close the form, and then, in the **Transfer** message that is displayed, click **No**.

9.  In the **Due date** field, modify the due date to settle the payment.

10. Click **Post** to post the BOE.

## Endorse a bill of exchange

1.  Click **Accounts receivable** \> **Common** \> **Bill of exchange** \> **Endorse bills of exchange**.

2.  Select a customer account with a status of **Drawn**.

3.  On the **Bill of exchanges list** tab, click **Endorse to vendor** to enter the information about BOE endorsement to the vendor.

4.  In the **Date of endorsement** field, select the date for the endorsement.

5.  In the **Vendor account** and **Description** fields, select the vendor account.

6.  Click **Endorse to vendor** to endorse the BOEs for the customer. The status changes to **Endorsed**.

## Settle a vendor invoice

1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.

2.  Select a vendor transaction.

3.  On the **Invoice** tab, click **Settle open transactions in several currencies** to open the **Settle open transactions** form.

4.  Select the vendor invoice lines for BOE endorsement.

5.  Select the **Mark** check box, and then click **Update** to settle the vendor invoice. For more information, see [Settle a bill of exchange](settle-a-bill-of-exchange.md).

## Settle endorsed bills of exchange

1.  Click **Accounts receivable** \> **Common** \> **Bill of exchange** \> **Endorse bills of exchange**. Select the endorsed BOE transaction line that is overdue.

2.  Click **Settle endorsed bill of exchange** to settle the endorsed BOE and update the status to **Endorsement settled**.

3.  Click **Inquiries** \> **Voucher** to view the voucher transactions with settled endorsed bills of exchange details.

## See also

[(JPN) Accounts receivable parameters (modified form)](https://technet.microsoft.com/en-us/library/jj664964\(v=ax.60\))

[Remit a bill of exchange](remit-a-bill-of-exchange.md)

[Protest a bill of exchange](protest-a-bill-of-exchange.md)

[Redraw a bill of exchange](redraw-a-bill-of-exchange.md)

[(JPN) Endorse bill of exchange (list page)](https://technet.microsoft.com/en-us/library/jj911067\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

