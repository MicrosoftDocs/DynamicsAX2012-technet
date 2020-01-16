---
title: (IND) Reverse fixed asset transactions
TOCTitle: (IND) Reverse fixed asset transactions
ms:assetid: db45e7ac-8388-4bb1-adc6-aea4baae9e44
ms:mtpsurl: https://technet.microsoft.com/library/JJ710876(v=AX.60)
ms:contentKeyID: 49386289
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Reverse fixed asset transactions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can reverse a fixed asset transaction, reverse direct and indirect taxes for the transaction, and update general ledger accounts. Information about the updated asset is displayed in the **Asset group balances** form for the selected tax layer value model and depreciation.

You can reverse fixed asset acquisitions or acquisition adjustment transactions on which VAT were calculated. The posted VAT tax codes should also be reversed along with the fixed asset transaction entries. If the settlement process is already run for the original transaction period, the tax amounts which were posted to the VAT recoverable account at the time of posting the original transaction should be reversed to the VAT payable account. All the indirect taxes for India, other than the VAT tax type, that is calculated and posted to the fixed asset at the time of posting the acquisition or acquisition adjustment transaction, are reversed as is when a fixed asset acquisition or acquisition adjustment transaction is reversed.


> [!NOTE]
> <P>The <STRONG>Companies Act depreciation</STRONG> and the <STRONG>Income tax Act depreciation</STRONG> check boxes must be selected in the <STRONG>General ledger parameters</STRONG> form.</P>




> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Fixed assets** \> **Common** \> **Fixed assets** \> **Fixed assets**. Select a fixed asset line, and click **Books** \> **Value models**.

2.  Select the value model with a tax layer in the **Value model** field.

3.  Click **Transactions** to open the **Fixed asset transactions** form.

4.  Select the transaction posted for acquisition to activate the **Reverse transaction**.

5.  Click **Reverse transaction** to open the **Transaction reversal** form.

6.  Enter the **Reversal posting date**.

7.  Click **OK** to reverse the transactions.

8.  Click **Fixed assets** \> **Setup** \> **Value models**.

**Example 1**

You can post multiple journals to account for the acquisition of fixed assets.

<table style="width:100%;">
<colgroup>
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Journal</p></th>
<th><p>Value model</p></th>
<th><p>Fixed asset group</p></th>
<th><p>Fixed asset number</p></th>
<th><p>Amount</p></th>
<th><p>Date of acquisition</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>0001_FA</p></td>
<td><p>VM1</p></td>
<td><p>FAG1</p></td>
<td><p>FA-001</p></td>
<td><p>75,000.00</p></td>
<td><p>01/01/2009</p></td>
</tr>
<tr class="even">
<td><p>0002_FA</p></td>
<td><p>VM1</p></td>
<td><p>FAG2</p></td>
<td><p>FA-002</p></td>
<td><p>65,000.00</p></td>
<td><p>01/01/2009</p></td>
</tr>
<tr class="odd">
<td><p>0003_FA</p></td>
<td><p>VM1</p></td>
<td><p>FAG3</p></td>
<td><p>FA-003</p></td>
<td><p>35,000.00</p></td>
<td><p>01/01/2009</p></td>
</tr>
</tbody>
</table>


When you post the journals for value model 1 (VM1), the **Asset group balances** form displays the following details:

  - The amount INR 175,000.00 (75,000.00 + 65,000.00 + 35,000.00) is displayed in the **Acquisition** field.

  - If you reverse the fixed asset FA-002 using the transaction reversal functionality, the **Acquisition** field in the **Asset group balances** form must display the amount as INR 110,000.00 (75,000.00 + 35,000.00).

  - The value of the reversed transaction must not be displayed in the **Asset group balances** form.

**Example 2**

When the acquisition transaction that was reversed earlier is revoked, the revoked transaction appears again in the **Asset group balances** form.

With reference to Example 1, if you revoke the reversal of fixed asset FA-002 using transaction reversal, the **Acquisition** field in the **Asset group balances** form displays the amount as INR 175,000.00 (75,000.00 + 65,000.00 + 35,000.00)

  - The revoked transaction is updated back in the **Asset group balances** form.

  


