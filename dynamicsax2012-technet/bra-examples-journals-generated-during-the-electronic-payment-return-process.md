---
title: '(BRA) Examples: Journals generated during the electronic payment return process'
TOCTitle: '(BRA) Examples: Journals generated during the electronic payment return process'
ms:assetid: 1498434d-1540-4e1b-bcbd-d1319f8af656
ms:mtpsurl: https://technet.microsoft.com/library/JJ730964(v=AX.60)
ms:contentKeyID: 49675194
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- payment journal
- electronic payment
- return file
audience: Application User
ms.search.region: Brazil
---

# (BRA) Examples: Journals generated during the electronic payment return process 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can make electronic payments by transferring files between a legal entity and a bank. You can generate and send electronic remittance files to a bank. After the bank processes the exported files, you can import a return file from the bank. The return file contains information about the acceptance of an invoice together with the payment number that is provided by the bank, or information about the payments that are received from a customer or paid to a vendor. When you import a return file, the status of the payments is updated in the **Payment status** field in the **Payment transfers** form, based on the relationship between the bank return occurrence codes in the return file and the return occurrence codes in Microsoft Dynamics AX. For more information, see [(BRA) Return occurrence codes (form)](https://technet.microsoft.com/library/jj730966\(v=ax.60\)). When you post the payments that the return file is imported for, only the payments that have a status of **Approved** are posted to a payment journal or multiple payment journals.

## Approved payment lines posted to the same payment journal

You can post all approved payment lines that belong to the same journal name to a payment journal. For example, you import a return file that contains six payment lines. Of the six payment lines, three payments lines have a status of **Approved**, and three have a status of **Rejected**. Two of the approved payment lines, for journal numbers 001 and 002, belong to the same journal name, DP. The third approved payment line, for journal number 100, belongs to the journal name Test. The following table contains information about the payment lines in the return file.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Name of journal</p></th>
<th><p>Journal number</p></th>
<th><p>Payment line</p></th>
<th><p>Status</p></th>
<th><p>Amount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>DP</p></td>
<td><p>001</p></td>
<td><p>1</p></td>
<td><p>Received</p></td>
<td><p>1000</p></td>
</tr>
<tr class="even">
<td><p>DP</p></td>
<td><p>001</p></td>
<td><p>2</p></td>
<td><p>Approved</p></td>
<td><p>2000</p></td>
</tr>
<tr class="odd">
<td><p>Test</p></td>
<td><p>100</p></td>
<td><p>1</p></td>
<td><p>Approved</p></td>
<td><p>3000</p></td>
</tr>
<tr class="even">
<td><p>Test</p></td>
<td><p>100</p></td>
<td><p>2</p></td>
<td><p>Rejected</p></td>
<td><p>4000</p></td>
</tr>
<tr class="odd">
<td><p>DP</p></td>
<td><p>002</p></td>
<td><p>1</p></td>
<td><p>Approved</p></td>
<td><p>5000</p></td>
</tr>
<tr class="even">
<td><p>DP</p></td>
<td><p>002</p></td>
<td><p>2</p></td>
<td><p>Sent</p></td>
<td><p>6000</p></td>
</tr>
</tbody>
</table>


When you post the payment lines, the two approved payment lines for journal numbers 001 and 002 that belong to the DP journal are posted to the same payment journal, 003. However, the approved payment line for journal number 100 that belongs to the Test journal is posted to a different payment journal, 101.The following table contains information about the payment journals that are created when you post the approved payment lines.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>New journal number</p></th>
<th><p>From journal number</p></th>
<th><p>Payment line</p></th>
<th><p>Status</p></th>
<th><p>Amount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>003</p></td>
<td><p>001</p></td>
<td><p>2</p></td>
<td><p>Approved</p></td>
<td><p>2000</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p>002</p></td>
<td><p>1</p></td>
<td><p>Approved</p></td>
<td><p>5000</p></td>
</tr>
<tr class="odd">
<td><p>101</p></td>
<td><p>100</p></td>
<td><p>1</p></td>
<td><p>Approved</p></td>
<td><p>3000</p></td>
</tr>
</tbody>
</table>


## Approved payment lines posted to multiple payment journals

If the transaction date that is updated for the approved payment line is different for each payment line in a return file, the payment lines are posted to different payment journals. For example, you import a return file that contains approved payment files that have three different transaction dates. The following table contains information about the three approved payment lines that have different transaction dates.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Journal number</p></th>
<th><p>Payment line</p></th>
<th><p>Transaction date</p></th>
<th><p>Status</p></th>
<th><p>Amount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>001</p></td>
<td><p>1</p></td>
<td><p>January 5, 2013</p></td>
<td><p>Approved</p></td>
<td><p>1000</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p>2</p></td>
<td><p>January 2, 2013</p></td>
<td><p>Received</p></td>
<td><p>2000</p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p>3</p></td>
<td><p>January 1, 2013</p></td>
<td><p>Approved</p></td>
<td><p>3000</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p>4</p></td>
<td><p>January 3, 2013</p></td>
<td><p>Approved</p></td>
<td><p>4000</p></td>
</tr>
</tbody>
</table>


When you post the approved payment lines, the three payment lines are posted to three different journals. The following table contains information about the payment journals created when you post the approved payment lines.

<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Journal number</p></th>
<th><p>Payment line</p></th>
<th><p>Transaction date</p></th>
<th><p>Status</p></th>
<th><p>Amount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>002</p></td>
<td><p>1</p></td>
<td><p>January 5, 2013</p></td>
<td><p>Approved</p></td>
<td><p>1000</p></td>
</tr>
<tr class="even">
<td><p>003</p></td>
<td><p>1</p></td>
<td><p>January 1, 2013</p></td>
<td><p>Approved</p></td>
<td><p>3000</p></td>
</tr>
<tr class="odd">
<td><p>004</p></td>
<td><p>1</p></td>
<td><p>January 3, 2013</p></td>
<td><p>Approved</p></td>
<td><p>4000</p></td>
</tr>
</tbody>
</table>


## See also

[(BRA) Process electronic payment remittances](bra-process-electronic-payment-remittances.md)

[(BRA) Process electronic payment returns](bra-process-electronic-payment-returns.md)

[(BRA) Return occurrence codes (form)](https://technet.microsoft.com/library/jj730966\(v=ax.60\))

  


