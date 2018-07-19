---
title: Protest a bill of exchange
TOCTitle: Protest a bill of exchange
ms:assetid: b983dd16-a00d-427a-a40f-0c1c4045b8f6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa498849(v=AX.60)
ms:contentKeyID: 37822157
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Protest a bill of exchange 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If a customer does not accept a bill of exchange or does not pay it on time, you can use the **Protest bill of exchange journal** to change the status of the bill of exchange from **Drawn** to **Protested**. You can also include a reference to the drawn bill of exchange.

If a customer protests a bill of exchange that has already been settled with an invoice, you can change the status of the bill of exchange from **Honored** to **Protested**.

A bill of exchange that has been closed cannot be protested.

## Protest a bill of exchange

1.  Click **Accounts receivable** \> **Journals** \> **Bill of exchange** \> **Protest bill of exchange journal**.

2.  Create a journal, and then click **Lines**.

3.  Select the customer account for the invoice that corresponds to the bill of exchange that is being protested.

4.  Click the **Bill of exchange** tab.

5.  Verify that the **Remittance type** field is set to **None**, and that no bank account is selected.

6.  Click **Functions** \> **Settlement** to open the **Settle open transactions** form.

7.  On the **Overview** tab, select an open transaction from the invoice.

8.  Close the **Settle open transactions** form.

9.  In the **Journal voucher** form, click the **Bill of exchange** tab.

10. In the **Protest cause** field, select the reason that the bill of exchange is being protested.

11. Click **Post** \> **Post**.
    
    The protested bill of exchange is displayed in the **Bill of exchange journal** inquiry form, together with a related line. The line has a status of **Protested** and a sequence number of 1 or more. In the **Show document** inquiry form, the number in the **Protested bills** row is increased, and the number in the **Drawn bills** row is decreased.
    
    When you post the journal, the protest bill of exchange account is debited, and the bill of exchange summary account is credited.

## Protest a settled bill of exchange

1.  Click **Accounts receivable** \> **Journals** \> **Bill of exchange** \> **Protest bill of exchange journal**.

2.  Click **New** to create a journal.

3.  Click the **Bill of exchange** tab.

4.  Select either **Discount** or **Collection** in the **Remittance type** field, and then select the bank account that was used when the bill of exchange was settled.

5.  Select the **Protest settlements** check box to transfer settled bills of exchange to the journal lines. In the **Protest settled process** field, select whether to create the new lines as open payments or invoices.

6.  Click **Lines**.

7.  Select the customer account for the invoice that corresponds to the bill of exchange that is being protested.

8.  Click **Functions** \> **Select settled bills of exchange** to open the **Protest settled bills of exchange** form.

9.  On the **Overview** tab, select a transaction, and then close the form.

10. On the **Overview** tab in the **Journal voucher** form, enter an offset account.

11. Click the **Bill of exchange** tab.

12. In the **Protest cause** field, select the reason that the bill of exchange is being protested.

13. Click **Post** \> **Post**.
    
    The protested bill of exchange is displayed in the **Bill of exchange journal** inquiry form, together with a related line. The line has a status of **Protested** and a sequence number of 2 or more. In the **Show document** inquiry form, the number in the **Protested bills** row is increased, and the number in the **Honored bills** row is decreased.
    
    When you post the journal, the protest bill of exchange account is debited, and the ledger account for the bank is credited.
    

    > [!NOTE]
    > <P>If you receive a message that mentions posting restrictions, you might be set up to post only journals that you created. For more information, see <A href="https://technet.microsoft.com/en-us/library/hh227598(v=ax.60)">Posting restrictions (form)</A>.</P>



## See also

[Redraw a bill of exchange](redraw-a-bill-of-exchange.md)

[Remit a bill of exchange](remit-a-bill-of-exchange.md)

[Journal header (form)](https://technet.microsoft.com/en-us/library/aa557917\(v=ax.60\))

[Bills of exchange statistics (form)](https://technet.microsoft.com/en-us/library/aa572115\(v=ax.60\))

[Journal voucher - Bill of exchange journal (form)](https://technet.microsoft.com/en-us/library/aa553272\(v=ax.60\))

  


