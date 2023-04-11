---
title: Waive, reinstate, or reverse interest or fees
TOCTitle: Waive, reinstate, or reverse interest or fees
ms:assetid: c5534372-f34f-417f-8b32-d33e4d382341
ms:mtpsurl: https://technet.microsoft.com/library/Hh242842(v=AX.60)
ms:contentKeyID: 36059299
author: tonyafehr
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.CustInterestJourList
- adjustment credit note, waive, reinstate, reverse, interest note, adjustment history
- MsDynAx060.Forms.CustInterestJourList
audience: Application User
ms.search.region: Global
---

# Waive, reinstate, or reverse interest or fees 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When interest notes are created, you sometimes must make adjustments to the interest and fees that they include. You can use the buttons on the **Collect** tab of the **All customers** list page to waive, reverse, or reinstate charges:

  - Waived charges are forgiven. You might waive a charge if, for example, a customer disputes the charge, and you want to maintain a good business relationship with the customer.

  - Reinstated charges become due again. You can reinstate charges that were previously waived. This is sometimes necessary if you decide that charges should not have been waived.

  - Reversed charges are removed from a customer’s account, and are no longer due. You might reverse charges if, for example, the wrong interest rate was selected to calculate the amount that a customer owes. You can use a separate process to recalculate interest and create an interest note with new charges for the customer.

All of these actions change an interest note, which is the business document that informs a customer when interest or fees have been charged to their account. When you waive or reverse interest or fees, a credit note or adjustment invoice is automatically created to settle the charges. If you reinstate waived charges, an invoice with a debit amount is automatically created to reinstate the charges that the customer owes. The following information describes the results of each action.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Action</p></th>
<th><p>Result for the customer</p></th>
<th><p>Process</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Waive complete interest notes with all of the interest and fees that they include.</p>
<p>–or–</p>
<p>Select and waive fees or interest transactions that are part of interest notes.</p></td>
<td><p>The charges are forgiven.</p></td>
<td><p>A credit note, or adjustment invoice, is created for the customer, and is used to automatically settle the interest note, or the interest transactions or fees that you selected. The settled amount is equal to the total amount of the charges, minus any previous payments by the customer, and minus any amounts that were previously waived or written off.</p>
<p>If the amount of the credit note exceeds what the customer owes, you can convert the credit note to a vendor invoice. You can then give a refund to the customer. For more information, see <a href="reimburse-customers.md">Reimburse customers</a>.</p></td>
</tr>
<tr class="even">
<td><p>Reinstate complete interest notes with all of the interest and fees that they include.</p>
<p>–or–</p>
<p>Select and reinstate fees or interest transactions that are part of interest notes.</p></td>
<td><p>The waived amount is due again.</p></td>
<td><p>An invoice with a debit amount is created, and the amount is automatically settled against the charges that were previously waived. The actual interest notes are not reinstated. Instead, an invoice is created that shows the amount that is due from the customer.</p>
<p>The credit notes, or adjustment invoices, that were created to settle waived interest notes can still exist if they were not used to settle the interest notes. When this occurs, the outstanding credit notes are canceled. Outstanding credit notes are usually automatically settled when interest notes are waived. However, an outstanding credit note might exist if a customer paid an interest note, even though the customer disputed the charges.</p></td>
</tr>
<tr class="odd">
<td><p>Reverse complete interest notes.</p>
<p>–or–</p>
<p>Reverse selected interest transactions that are part of interest notes.</p>
<div class="alert">

> [!NOTE]
> <P>You cannot reverse a fee, but you can reverse a complete interest note that includes a fee.</P>


</div></td>
<td><p>The charges are no longer due from the customer. However, the charges become due again if you recalculate interest.</p></td>
<td><p>The process is the same as for waiving interest notes or selected interest transactions. A credit note, or adjustment invoice, is created for the customer. This is used to automatically settle the interest note.</p>
<p>You can use a separate process to recalculate interest and create a new interest note. For more information, see <a href="https://technet.microsoft.com/library/aa600712(v=ax.60)">Interest calculation (class form)</a>.</p></td>
</tr>
</tbody>
</table>



> [!NOTE]
> <P>You can also use a separate process to write off bad debts, which marks all customer transactions for settlement instead of waiving only the charges that are part of interest notes. For more information, see <A href="collections-and-credit-in-accounts-receivable.md">Collections and credit in Accounts receivable</A> and <A href="key-tasks-collections.md">Key tasks: Collections</A>.</P>



## Adjust interest for invoices

In addition to adjusting interest notes, you can also remove interest charges on invoices using one of the following processes. Both processes also make adjustments to the related interest notes:

## Correct an invoice with associated interest

You can use this process to correct a posted invoice that is included in an interest note. The invoice is canceled and a new one is created. Interest on the transaction is also reversed on the interest note, if the interest note was posted. For more information, see [Correct a posted free text invoice](correct-a-posted-free-text-invoice.md).


> [!TIP]
> <P>This process copies the details from the existing invoice to a new one to make only the corrections you want.</P>



1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  Select the invoice to correct.

3.  On the Action Pane, click **Correct invoice**.
    

    > [!NOTE]
    > <P>This button is available only if the <STRONG>Free text invoice correction</STRONG> configuration key is selected.</P>



4.  Select a reason code and enter the canceled date for the invoice.

5.  Click **Create corrected invoice**. The **Free text invoice** form is displayed.

6.  Make any changes to the invoice.

7.  On the Action Pane, click **Post**.

8.  Click **OK** to post the invoice.

9.  Click **Continue**.

## Reverse a customer transaction with associated interest

You can use this process to reverse a customer transaction on an invoice, when an invoice was created incorrectly. If the reversed customer transaction has interest included on an interest note, and the interest note was posted, interest on the transaction is also reversed on the interest note. The interest note is canceled if it has not been posted. For more information, see [Reverse a transaction](reverse-a-transaction.md).


> [!TIP]
> <P>After using this process, you can review the original and corrected invoices on the <STRONG>Overview</STRONG> tab of the <STRONG>Customer transactions</STRONG> form.</P>



1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Select a customer account.

3.  On the Action Pane, on the **Customer** tab, click **Transactions**.

4.  Select the invoice to reverse.

5.  Click **Reverse transaction**.

6.  Select a reason code and enter the posting date for the reversal.

7.  Click **OK**.

## Waive or reinstate interest notes

You can waive or reinstate all of the charges on the interest notes that you select. When you waive charges, the total amount to be waived cannot exceed any amount limits that have been set. For more information, see [Manage customer waive limits (form)](https://technet.microsoft.com/library/hh209728\(v=ax.60\)). You can reinstate an interest note only if it was previously waived.

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Select a customer account.

3.  On the Action Pane, on the **Collect** tab, click **Interest note**, and then click one of the following actions:
    
      - Click **Waive** to waive interest notes.
    
      - Click **Reinstate** to reinstate interest notes that were previously waived.

4.  Select the **Waive** or **Reinstate** check boxes for the interest notes that you want to waive or reinstate.
    

    > [!TIP]
    > <P>To view the details for an interest note, click <STRONG>View interest note</STRONG>.</P>



5.  Click **Waive** to waive the selected interest notes, or click **Reinstate** to reinstate interest notes that were previously waived. You will receive a message to confirm that the action was completed.

## Waive or reinstate interest transactions

You can waive or reinstate specific interest transactions on an interest note instead of adjusting all of the charges on an interest note. When you waive charges, the total amount to be waived cannot exceed any amount limits that have been set. For more information, see [Manage customer waive limits (form)](https://technet.microsoft.com/library/hh209728\(v=ax.60\)). You can reinstate an interest transaction only if it was previously waived.

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Select a customer account.

3.  On the Action Pane, on the **Collect** tab, click **Transaction interest**, and then click one of the following options:
    
      - Click **Waive** to waive the interest transactions.
    
      - Click **Reinstate** to reinstate interest transactions that were previously waived.

4.  Select the **Waive** or **Reinstate** check boxes for the interest transactions that you want to waive or reinstate.
    

    > [!TIP]
    > <P>To view the details for the interest note that includes the interest transaction, click <STRONG>View interest note</STRONG>.</P>



5.  Click **Waive** to waive the selected interest transactions, or click **Reinstate** to reinstate interest transactions that were previously waived. You will receive a message to confirm that the action was completed.

## Waive or reinstate fees

You can waive or reinstate specific fees on an interest note instead of adjusting all of the charges on an interest note. When you waive charges, the total amount to be waived cannot exceed any amount limits that have been set. For more information, see [Manage customer waive limits (form)](https://technet.microsoft.com/library/hh209728\(v=ax.60\)). You can reinstate a fee only if it was previously waived.

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Select a customer account.

3.  On the Action Pane, on the **Collect** tab, click **Fee**, and then click one of the following options:
    
      - Click **Waive** to waive fees.
    
      - Click **Reinstate** to reinstate fees that were previously waived.

4.  Select the **Waive** or **Reinstate** check boxes for the fees that you want to waive or reinstate.
    

    > [!TIP]
    > <P>To view the details for the interest note that includes the fee, click <STRONG>View interest note</STRONG>.</P>



5.  Click **Waive** to waive the selected fees, or click **Reinstate** to reinstate fees that were previously waived. You will receive a message to confirm that the action was completed.

## Reverse interest notes

You can reverse all of the charges on the interest notes that you select. Reversed charges are removed from a customer’s account, and are no longer due. After the interest note is reversed, you can recalculate interest and create a new interest note. For more information, see [Interest calculation (class form)](https://technet.microsoft.com/library/aa600712\(v=ax.60\)).

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Select a customer account.

3.  On the Action Pane, on the **Collect** tab, click **Interest note**, and then click **Reverse**.

4.  Select the **Reverse** check box for the first interest note that you want to reverse. You can reverse only one interest note at a time. If you have to reverse multiple interest notes, start with the most recent interest note.
    

    > [!TIP]
    > <P>To view the details for the interest note, click <STRONG>View interest note</STRONG>.</P>



5.  Click **Reverse**. You will receive a message to confirm that the action was completed.

## Reverse interest transactions

You can reverse all of the interest transactions that you select. Reversed charges are removed from a customer’s account, and are no longer due. After the transactions are reversed, you can recalculate interest and create a new interest note. For more information, see [Interest calculation (class form)](https://technet.microsoft.com/library/aa600712\(v=ax.60\)).

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Select a customer account.

3.  On the Action Pane, on the **Collect** tab, click **Transaction interest**, and then click **Reverse**.

4.  Select the **Reverse** check box for the first interest transaction that you want to reverse. You can reverse only one transaction at a time. If you have to reverse multiple interest transactions, start with the most recent interest transaction.
    

    > [!TIP]
    > <P>To view the details for the interest note that includes the interest transaction, click <STRONG>View interest note</STRONG>.</P>



5.  Click **Reverse**. You will receive a message to confirm that the action was completed.

## View the history of adjustments for charges that were waived, reinstated, or reversed

You can view the detailed history of adjustments that were made for interest notes, such as the user who entered the adjustment, the type of adjustment, the amount, and when the adjustment was entered. For example, you might want to view the previous adjustments that were entered for an interest note before you create a new interest note. For more information, see [Interest note adjustment history (form)](https://technet.microsoft.com/library/hh208580\(v=ax.60\)).

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Select a customer account.

3.  On the Action Pane, on the **Collect** tab, click **History**.

4.  The interest notes adjustments for the selected customer are displayed. You can view additional details by clicking the following buttons:
    
      - **Open interest note** – Open the **Interest note** form, where you can view the complete details for an interest note.
    
      - **Open adjustment invoice** – Open the **Free text invoice** form, where you can view details of the adjustment invoice. You can also convert the adjustment invoice to a vendor payment and give a refund to the customer.
    
      - **View user** – Open the **User** form, where you can view details about the permissions and status of the user who entered the adjustment. For more information, see [User (form)](https://technet.microsoft.com/library/aa554087\(v=ax.60\)).

## See also

[Interest note adjustment history (form)](https://technet.microsoft.com/library/hh208580\(v=ax.60\))

[Manage customer waive limits (form)](https://technet.microsoft.com/library/hh209728\(v=ax.60\))

[Reinstate waived fees (form)](https://technet.microsoft.com/library/hh209559\(v=ax.60\))

[Reinstate waived interest notes (form)](https://technet.microsoft.com/library/hh227615\(v=ax.60\))

[Reinstate waived interest on customer transactions (form)](https://technet.microsoft.com/library/hh242540\(v=ax.60\))

[Reverse interest notes (form)](https://technet.microsoft.com/library/hh208621\(v=ax.60\))

[Reverse interest on customer transactions (form)](https://technet.microsoft.com/library/hh209602\(v=ax.60\))

[Waive interest on customer transactions (form)](https://technet.microsoft.com/library/hh209483\(v=ax.60\))

[Waive interest notes (form)](https://technet.microsoft.com/library/hh209719\(v=ax.60\))

  


