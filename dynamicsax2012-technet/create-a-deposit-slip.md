---
title: Create a deposit slip
TOCTitle: Create a deposit slip
ms:assetid: 05b7745d-61cb-492d-858f-f9b273e11077
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa569716(v=AX.60)
ms:contentKeyID: 36055956
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- deposit slip
- generating deposit slip
audience: Application User
ms.search.region: Global
---

# Create a deposit slip 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use deposit slips to deposit payments that were made in a journal into bank accounts. The transactions for which the **Use a deposit slip** check box is selected in the **Journal voucher** form are displayed on a separate deposit slip for each bank account.

1.  Click **General ledger** \> **Journals** \> **General journal**. Create or select a journal and then click **Lines**.
    
    –or–
    
    Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**. Create or select a journal and then click **Lines**.

2.  Create payment lines that include information about the customer accounts and the amounts. Enter, as the offset account on each line, the correct bank account for the deposit of the payment. For information about how to enter journal lines or payment lines, see [Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md) or [Key tasks: Customer payments and settlements](key-tasks-customer-payments-and-settlements.md).

3.  On the **Overview** tab, select the **Use a deposit slip** check box for all the payment lines to be included on a bank deposit slip.

4.  Click the **Payment** tab in the **Journal voucher** form.

5.  Select the bank transaction type that is set up for bank deposits. For more information, see [Bank transaction type (form)](https://technet.microsoft.com/en-us/library/aa619635\(v=ax.60\)).

6.  In the **Payment reference** field, enter a reference that pertains to the payment line.

7.  Repeat steps 4 through 6 for all the payment lines for which the **Use a deposit slip** check box is selected.
    

    > [!NOTE]
    > <P>Some organizations set up payment control parameters on methods of payment to make sure that all payment lines are entered on a deposit slip. For more information, see <A href="https://technet.microsoft.com/en-us/library/aa499398(v=ax.60)">Methods of payment - customers (form)</A>.</P>



8.  Click **Validate** \> **Validate**, and then click **Post** \> **Post**.

9.  To prepare a printout of the deposit slips, click **Functions** \> **Deposit slip**. Select the date to display on the deposit slips, and then click **OK**.

10. A dialog box is displayed for each bank account that is listed as an offset account on the journal lines for which the **Use a deposit slip** check box is displayed. In each dialog box, click **OK** to print a copy of the deposit slip for the specific bank account.
    
    When the deposit slips are printed, the deposit slip number is entered in the **Deposit slip** field on the **Payment** tab in the **Journal voucher** form for the lines that are included on a deposit slip.
    

    > [!NOTE]
    > <P>Use the <STRONG>Deposit slip</STRONG> form to view deposit slips for a bank account. (Click <STRONG>Cash and bank management</STRONG> &gt; <STRONG>Common</STRONG> &gt; <STRONG>Bank accounts</STRONG>. Select a bank account. On the <STRONG>Action Pane</STRONG>, click the <STRONG>Manage payments</STRONG> tab, and then click <STRONG>Deposit slips</STRONG>.) In this form, you can cancel a payment transaction on a deposit slip. For example, you might cancel a payment transaction if a check from a customer does not clear.</P>


  


