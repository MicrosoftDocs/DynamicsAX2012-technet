---
title: Settle a bill of exchange
TOCTitle: Settle a bill of exchange
ms:assetid: c9f2e52d-bd35-420c-8ab4-d836a9cccf53
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa499074(v=AX.60)
ms:contentKeyID: 36059328
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Settle a bill of exchange [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can settle the bill of exchange when the invoice is due.

1.  Click **Accounts receivable** \> **Journals** \> **Bill of exchange** \> **Settle bill of exchange journal**.

2.  Press CTRL+N to create a journal.

3.  Click the **Bill of exchange** tab. In the **Remittance type** and **Bank account** fields, select the remittance type and the bank account that was used when the bill of exchange was remitted.

4.  Click **Lines**.

5.  In the **Journal voucher** form, select the customer account for the invoice, and then click **Functions** \> **Settlement**.

6.  In the **Settle open transactions** form, select the check box in the **Mark** column for the remitted transaction from the invoice.

7.  Close the form to transfer the transaction to a journal line. If the remittance type is **Discount**, the default entry in the **Offset account** field is the same as the account in the **Liabilities for discount account** field for the remittance for discount posting profile.

8.  In the **Journal voucher** form, click **Post** \> **Post**.
    

    > [!NOTE]
    > <P>If you receive a message that mentions posting restrictions, you can post only the journals that you created. For more information, see <A href="https://technet.microsoft.com/en-us/library/hh227598(v=ax.60)">Posting restrictions (form)</A>.</P>



A new line with a status of **Honored** and a sequence number of 1 or higher is created for the remitted bill of exchange and is shown in the **Bill of exchange journal** inquiry form. In the **Bills of exchange statistics** inquiry form, the number in the **Honored bills** row is increased, and the number in the **Remitted bills** row is decreased.

When you settle a bill of exchange that is remitted for discount, the liabilities for discount account is debited and the remit for discount account is credited. When you settle a bill of exchange that is remitted for collection, the ledger account for the bank that is used is debited, and the remit for collection account is credited.

## Close settled bills of exchange

Use the **Remittance files for customers** form to change the status of a bill of exchange from **Honored** to **Closed**. You can see the number of honored bills and closed bills in the **Bills of exchange statistics** form.

1.  Click **Cash and bank management** \> **Common** \> **Bank accounts**.

2.  Double-click a bank account. On the Action Pane, click the **Manage payments** tab, and then click **Customer remittances**.
    

    > [!NOTE]
    > <P>You can also open the <STRONG>Remittance files for customers</STRONG> form from the <STRONG>Methods of payment</STRONG> form.</P>



3.  In the **Remittance files for customers** form, select a remittance file, and then click the **Status** tab.

4.  Select the **Closed** check box.

## See also

[Protest a bill of exchange](protest-a-bill-of-exchange.md)

[Set up bills of exchange](set-up-bills-of-exchange.md)

[Journal header (form)](https://technet.microsoft.com/en-us/library/aa557917\(v=ax.60\))

[Remittance files for customers (form)](https://technet.microsoft.com/en-us/library/aa596345\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

