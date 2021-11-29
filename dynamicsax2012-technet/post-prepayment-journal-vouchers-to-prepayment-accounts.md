---
title: Post prepayment journal vouchers to prepayment accounts
TOCTitle: Post prepayment journal vouchers to prepayment accounts
ms:assetid: 90ea06d1-5fd5-4912-9a6d-5d8a483945df
ms:mtpsurl: https://technet.microsoft.com/library/Aa498371(v=AX.60)
ms:contentKeyID: 36993124
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Post prepayment journal vouchers to prepayment accounts 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Accounting practices in many countries/regions require that prepayment journal vouchers, or payments in advance, from a customer or to a vendor not be posted to the usual summary accounts for the customer or vendor. Instead, these prepayment journal vouchers must be posted to special ledger accounts for prepayment journal vouchers. When a sales order or purchase order is made, an invoice is issued to the customer or vendor. When the invoice is paid, the prepayment journal voucher and sales tax prepayment journal voucher on the ledger accounts for the prepayment journal vouchers are reversed. The invoice amounts are then automatically posted to the usual summary accounts.


> [!NOTE]
> <P>For more information about prepayments and prepayment journal vouchers, see <A href="about-prepayments-and-prepayment-journal-vouchers.md">About prepayments and prepayment journal vouchers</A>.</P>



## 1\. Set up prepayment journal vouchers for customers and vendors

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.
    
    –or–
    
    Click **Accounts payable** \> **Setup** \> **Accounts payable parameters**.

2.  Click **Ledger and sales tax**.

3.  If sales tax is calculated and posted when you post a prepayment journal voucher, select the **Sales tax on prepayment journal voucher** check box.

4.  In the **Posting profile with prepayment journal voucher** field, select a posting profile to indicate the accounts to which the prepayment journal voucher and sales tax prepayment journal vouchers are posted. The posting profile that you select in this field must include a summary account for prepayment journal vouchers. If the **Sales tax on prepayment journal voucher** check box is selected, the posting profile must also include a ledger account for sales tax prepayment journal vouchers.

## 2\. Create a prepayment journal voucher

1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.
    
    –or–
    
    Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Create a journal.

3.  On the **Setup** tab, select the **Amounts include sales tax** check box if you want to post the prepayment journal voucher together with sales tax amounts.

4.  Click **Lines**, and then create the payment line.

5.  On the **Payment** tab, select the **Prepayment journal voucher** check box. The posting profile changes automatically to the posting profile for the prepayment journal voucher.

6.  Post the prepayment journal voucher.

## 3\. Post an invoice to the customer or vendor

1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.
    
    –or–
    
    Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Click **Lines**, and then click **Functions** \> **Settlement**.

3.  In the **Settle open transactions** form, settle the invoice with the prepayment journal voucher.
    

    > [!NOTE]
    > <P>If you select a prepayment journal voucher for the invoice settlement, you receive a message that the marked payment transaction is a prepayment journal voucher.</P>



The settlement of the invoice reverses the transactions in the summary account and in the sales tax prepayment journal vouchers of the prepayment journal voucher posting profile. At the same time, a payment transaction settles the invoice and posts the amounts to the ledger accounts of the standard posting profile for the customer or vendor.

## Example

<table>
<colgroup>
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Date</p></th>
<th><p>Action</p></th>
<th><p>Sales account</p></th>
<th><p>Sales tax account</p></th>
<th><p>Customer account</p></th>
<th><p>Received prepayment journal voucher</p></th>
<th><p>Bank</p></th>
<th><p>Sales tax offset account of the prepayment journal voucher</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Not applicable</p></td>
<td><p>Prepayment journal voucher</p></td>
<td><p>Not applicable</p></td>
<td><p>-25</p></td>
<td><p>Not applicable</p></td>
<td><p>-125</p></td>
<td><p>125</p></td>
<td><p>25</p></td>
</tr>
<tr class="even">
<td><p>October 31, 2011</p></td>
<td><p>Invoice</p></td>
<td><p>-100</p></td>
<td><p>-25</p></td>
<td><p>125</p></td>
<td><p>Not applicable</p></td>
<td><p>Not applicable</p></td>
<td><p>Not applicable</p></td>
</tr>
<tr class="odd">
<td><p>October 31, 2011</p></td>
<td><p>Settle prepayment journal voucher</p></td>
<td><p>Not applicable</p></td>
<td><p>25</p></td>
<td><p>-125</p></td>
<td><p>125</p></td>
<td><p>Not applicable</p></td>
<td><p>-25</p></td>
</tr>
</tbody>
</table>


## See also

[Process customer prepayment journal vouchers](process-customer-prepayment-journal-vouchers.md)

  


