---
title: Remit a bill of exchange
TOCTitle: Remit a bill of exchange
ms:assetid: d0a6553f-9413-46f4-b963-14e8016ddc94
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa551009(v=AX.60)
ms:contentKeyID: 36966740
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Remit a bill of exchange [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use a remittance journal to generate a bill of exchange remittance file to send to your bank. The information in the file is based on bill of exchange journal lines that have been posted but not remitted.

If the **Automatic settlement** check box in the **Accounts receivable parameters** form is selected, a remittance file is automatically generated when you post sales invoices or free text invoices, if the method of payment is set up to draw a bill of exchange. If this is the case, you do not have to complete either of the following procedures.


> [!NOTE]
> <P>When you transfer transactions to the remittance journal, the way that due dates are handled depends on how you select the transactions. If you click <STRONG>Payment proposal</STRONG> &gt; <STRONG>Payment proposal</STRONG> to select transactions by using a query that is set up to select the total number of payments that are due as of a specific date, the date that you enter in the <STRONG>Total payment date</STRONG> field is used for all transferred transactions. If you select transactions manually in the <STRONG>Settle open transactions</STRONG> form, the latest due date of the selected transactions is used.</P>



## Remit for discount

Use this procedure to generate a remittance file that includes discount amounts.

1.  Click **Accounts receivable** \> **Journals** \> **Bill of exchange** \> **Remittance journal**.

2.  Create a journal.

3.  Click the **Bill of exchange** tab.

4.  In the **Remittance type** field, select **Discount**.

5.  In the **Bank account** field, select the bank account that is affected by the bill of exchange. The bank account must use a standard bank account number.

6.  Click **Lines**.

7.  On the **Overview** tab, select the customer account for the invoice that corresponds to the bill of exchange.

8.  Click **Functions** \> **Settlement** to open the **Settle open transactions** form.

9.  On the **Overview** tab, select an open transaction from the invoice, and then close the form.
    

    > [!NOTE]
    > <P>Alternatively, in the <STRONG>Journal voucher</STRONG> form, you can select <STRONG>Payment proposal</STRONG> &gt; <STRONG>Proposal by due date</STRONG> to select the transactions by using a query, instead of following steps 8 and 9.</P>



10. If the remittance in the **Journal voucher** form includes a payment fee that is paid to you by your customer, click the **Payment fee** tab, click **Add**, select a fee ID, and enter information about the fee.

11. Click **Functions** \> **Generate remittance**, and then click **Dialog**.

12. In the dialog box, enter a file name, and then click **OK**. Click **OK** in the **Generate remittance** form to generate and print the remittance file for the bank.
    

    > [!NOTE]
    > <P>Some countries/regions have specific guidelines and formats for remitting bills of exchange.</P>

    
    For each journal line, the payment status is changed to **Sent**.

13. Click **Post** \> **Post**.
    
    A new line that has a **Remitted** status and a **Remitted** remittance type that corresponds to the bill of exchange is shown in the **Bill of exchange journal** inquiry form. In the **Bills of exchange statistics** inquiry form, the number in the **Remitted bills** field is increased, and the number in the **Bills in remittance** field is decreased.
    
    When the journal is posted, the remit for discount account is debited, and the bill of exchange account is credited. Also, the ledger account for the bank is debited for the discount amount, and the liabilities for discount account is credited for the discount amount.

## Remit for collection

Use this procedure to generate a remittance file to collect the amount that is due on the due date.

1.  Click **Accounts receivable** \> **Journals** \> **Bill of exchange** \> **Remittance journal**.

2.  Create a journal.

3.  Click the **Bill of exchange** tab.

4.  In the **Remittance type** field, select **Collection**.

5.  In the **Bank account** field, select the bank account that is affected by the bill of exchange. The bank account must use a standard bank account number.

6.  Click **Lines**.

7.  On the **Overview** tab, select the customer account for the invoice that corresponds to the bill of exchange.

8.  Click **Functions** \> **Settlement** to open the **Settle open transactions** form.

9.  On the **Overview** tab, select an open transaction from the invoice, and then close the form.
    

    > [!NOTE]
    > <P>Alternatively, in the <STRONG>Journal voucher</STRONG> form, you can select <STRONG>Payment proposal</STRONG> &gt; <STRONG>Proposal by due date</STRONG> to select the transactions by using a query, instead of following steps 8 and 9.</P>



10. If the remittance includes a payment fee that is paid to you by your customer, in the **Journal voucher** form, click the **Payment fee** tab, click **Add**, select a fee ID, and enter information about the fee.

11. Click **Functions** \> **Generate remittance**, and then click **Dialog**.

12. In the dialog box, enter a file name, and then click **OK**. Click **OK** in the **Generate remittance** form to generate and print the remittance file for the bank.
    

    > [!NOTE]
    > <P>Some countries/regions have specific guidelines and formats for remitting bills of exchange.</P>

    
    For each journal line, the payment status is changed to **Sent**.

13. Click **Post** \> **Post**.
    
    A new line that has a **Remitted** status and a **Remitted** remittance type that corresponds to the bill of exchange is shown in the **Bill of exchange journal** inquiry form. In the **Bills of exchange statistics** inquiry form, the number in the **Remitted bills** row is increased, and the number in the **Bills in remittance** row is decreased.
    
    When the journal is posted, the remit for collection account is debited, and the bill of exchange account is credited.
    

    > [!NOTE]
    > <P>If you receive a message that mentions posting restrictions, you might be set up to post only journals that you created. For more information, see <A href="https://technet.microsoft.com/en-us/library/hh227598(v=ax.60)">Posting restrictions (form)</A>.</P>



## See also

[Settle a bill of exchange](settle-a-bill-of-exchange.md)

[Protest a bill of exchange](protest-a-bill-of-exchange.md)

[Redraw a bill of exchange](redraw-a-bill-of-exchange.md)

[Journal header (form)](https://technet.microsoft.com/en-us/library/aa557917\(v=ax.60\))

[Bill of exchange journal (form)](https://technet.microsoft.com/en-us/library/aa582684\(v=ax.60\))

[Bills of exchange statistics (form)](https://technet.microsoft.com/en-us/library/aa572115\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

