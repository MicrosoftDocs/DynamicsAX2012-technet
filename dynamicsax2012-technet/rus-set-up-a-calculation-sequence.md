---
title: (RUS) Set up a calculation sequence
TOCTitle: (RUS) Set up a calculation sequence
ms:assetid: 4e128f6f-deda-424b-803f-cd7cb0ff6b6e
ms:mtpsurl: https://technet.microsoft.com/library/JJ665371(v=AX.60)
ms:contentKeyID: 49387459
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up a calculation sequence 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

A calculation sequence is a set of counters that performs a sequence of mathematical and logical operations on register lines of designated types for a specified period. Counters perform the calculation algorithms described in certain types of lines. The following table provides details that describe the counter lines.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Line type</p></th>
<th><p>Operand</p></th>
<th><p>Processing</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Register</p></td>
<td><p>Register</p></td>
<td><p>Selection of field from current register.</p></td>
</tr>
<tr class="even">
<td><p>Line</p></td>
<td><p>Number of lines of counter</p></td>
<td><p>Selection of a specified line of a counter.</p></td>
</tr>
<tr class="odd">
<td><p>Rate</p></td>
<td><p>Rate code</p></td>
<td><p>Select rates from a table of rates.</p></td>
</tr>
<tr class="even">
<td><p>Constant</p></td>
<td><p>Number</p></td>
<td><p>Entry of any number.</p></td>
</tr>
<tr class="odd">
<td><p>Price</p></td>
<td><p>No</p></td>
<td><p>Selection of the Price field from the source document that produced the transaction.</p></td>
</tr>
<tr class="even">
<td><p>Quantity</p></td>
<td><p>No</p></td>
<td><p>Selection of the Quantity field from the source document that produced the transaction.</p></td>
</tr>
<tr class="odd">
<td><p>Expense</p></td>
<td><p>Interval of expense/revenue IDs from directory (may consist of only one code).</p></td>
<td><p>Expense and income amount calculation for the period from which the register was obtained.</p></td>
</tr>
<tr class="even">
<td><p>Debit activity</p></td>
<td><p>Account Intervals (may consist of one account).</p></td>
<td><p>Debit turnovers calculation according to ledger accounts for the current interval period, defined by operands from the Period Type and Index counter lines.</p></td>
</tr>
<tr class="odd">
<td><p>Credit activity</p></td>
<td><p>Account Intervals (may consist of one account).</p></td>
<td><p>Credit turnovers calculation according to ledger accounts for the current interval period, defined by operands from the Period Type and Index counter lines.</p></td>
</tr>
<tr class="even">
<td><p>Debit balance</p></td>
<td><p>Account Intervals (may consist of one account).</p></td>
<td><p>Calculation of debit balance for accounts from the current interval to the start of the period, defined by operands from the Period Type and Index counter lines.</p></td>
</tr>
<tr class="odd">
<td><p>Credit balance</p></td>
<td><p>Account Intervals (may consist of one account).</p></td>
<td><p>Calculation of credit balance for accounts from the current interval to the start of the period, defined by operands from the Period Type and Index counter lines.</p></td>
</tr>
<tr class="even">
<td><p>Deferral write-off</p></td>
<td><p>Deferrals group</p></td>
<td><p>Calculation of upcoming deferral write-offs in the current reporting period.</p></td>
</tr>
</tbody>
</table>


1.  Click **General ledger** \> **Setup** \> **Profit tax** \> **Sequence of calculation**.

2.  Press CTRL+N to create a new line.

3.  In the **Sequence** field, enter the sequence number.

4.  In the **Description** field, enter a description of the calculation sequence.

5.  In the **Channel** field, select the output format for the calculation results from the following options:
    
      - **Register** – Calculation results are recorded in tax registers.
    
      - **Deferral** – Deferral cards are created from the calculation results.

6.  In the **Channel reference** field, select the register code or the deferrals group where you want to record the calculation results.

7.  Click **Counters** to open the **Counter setup** form, and then create counters for the calculation sequences.
    

    > [!NOTE]
    > <P>For each calculation sequence, you can define one or more counters. However, you can create only one counter for each expense code and calculation sequence.</P>



8.  Press CTRL+S or close the form.

## See also

[(RUS) Standard expenses sequence (form)](https://technet.microsoft.com/library/jj853198\(v=ax.60\))

  


