---
title: (IND) Calculate and post depreciation for a fixed asset group using depreciation books
TOCTitle: (IND) Calculate and post depreciation for a fixed asset group using depreciation books
ms:assetid: 0cdee331-7c29-473e-8e05-f4e5bdd0207d
ms:mtpsurl: https://technet.microsoft.com/library/JJ664481(v=AX.60)
ms:contentKeyID: 49385560
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Calculate and post depreciation for a fixed asset group using depreciation books 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



You can calculate depreciation for a fixed asset group based on the number of days defined in the **Asset group depreciation threshold** field in the **General ledger parameters** form. The following table shows the various formulas that are used to calculate asset group depreciation.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Type of proposal</p></th>
<th><p>Number of days the asset is used</p></th>
<th><p>Formula</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Depreciation</p></td>
<td><p>Equal to or more than the number of days defined in the <strong>Asset group depreciation threshold</strong> field</p></td>
<td><p>(Net book value of the fixed asset group on the date of depreciation) * (Rate of depreciation defined for the depreciation profile)</p></td>
</tr>
<tr class="even">
<td><p>Depreciation</p></td>
<td><p>Fewer than the number of days defined in the <strong>Asset group depreciation threshold</strong> field</p></td>
<td><p>(Net book value of the fixed asset) * (Depreciation threshold percentage defined in parameters) * (Rate of depreciation defined for the depreciation profile)</p></td>
</tr>
<tr class="odd">
<td><p>Bonus depreciation</p></td>
<td><p>Equal to or more than the number of days defined in the <strong>Asset group depreciation threshold</strong> field</p></td>
<td><p>(Cost of acquisition) * (Rate of depreciation defined in the depreciation profile)</p></td>
</tr>
<tr class="even">
<td><p>Bonus depreciation</p></td>
<td><p>Fewer than the number of days defined in the <strong>Asset group depreciation threshold</strong> field</p></td>
<td><p>(Cost of acquisition) * (Depreciation threshold percentage defined in the <strong>General ledger parameters</strong> form) * (Rate of depreciation defined in the depreciation profile)</p></td>
</tr>
</tbody>
</table>


**Example**

You own Machinery A, B, and C on April 1, 2008. The written-down value of machinery A is INR 70,000, Machinery B is INR 1,64,000, and Machinery C is INR 84,000. The rate of depreciation is 15 percent. You purchased Machinery D for INR 60,000 on November 2, 2008. On March 15, 2009, Machinery B is sold for INR 1,80,000 and Machinery C is sold for INR 40,000.

The calculated written-down value of the group of assets on March 31, 2009 = INR 1,58,000 (INR 3,18,000 + INR 60,000 – INR 2,20,000). This is calculated by adding the amount of the new machinery to the sum of the written-down value of Machinery A, B, and C and then deducting the sale proceeds of Machinery B and C.

You must calculate depreciation on the asset that is used for fewer than 180 days at the rate of 7.5 percent, which in this case is INR 4,500 (INR 60,000 \* 7.5%). The depreciation on the remaining amount of the written-down value of the group of assets is calculated at the rate of 15 percent, which is INR 14,700.

On March 31, 2009, you must deduct the amount of depreciation from the written-down value of the group of assets (INR 1,58,000 – INR 60,000 = INR 98,000) to calculate the written-down value of the group of assets on April 1, 2008, which is INR 1,58,000 – INR 19,200 = INR 1,38,800.


> [!NOTE]
> <P>Depreciation is not calculated for the asset group that has a zero written-down value. If the sale amount of all assets or some assets in a fixed asset group is greater than the net book value of the group during a year, it is considered a short-term capital gain, so it will have a zero written-down value. If the sale amount of all assets in a fixed asset group is less than the net book value of the fixed asset group, it is considered a short-term capital loss, so it will have a zero written-down value.</P>



If the positive or negative amount is entered in the **Debit** field of a journal line, the same amount is updated in the **Fixed asset balances** form. However, if a positive amount is entered in the **Credit** field, the amount is updated as negative and the negative amount in the **Credit** field is updated as a positive amount in the **Fixed asset balances** form.

1.  Click **Fixed assets** \> **Journals** \> **Depreciation book journal**.

2.  Create a new depreciation book journal.

3.  Select a depreciation book journal name in the **Name** field.

4.  Click **Lines**.

5.  Select a transaction type in the **Transaction type** field.

6.  Select a fixed asset number in the **Fixed asset number** field.
    

    > [!NOTE]
    > <P>The <STRONG>Fixed asset number</STRONG> field is not available in the journal line when a fixed asset group and depreciation book is selected with the <STRONG>Depreciation</STRONG> or <STRONG>Depreciation adjustment</STRONG> transaction type, and the <STRONG>Asset group depreciation</STRONG> check box is selected.</P>



7.  Select a fixed asset group in the **Fixed asset group** field.

8.  Enter an amount in the **Debit** field or the **Credit** field.

9.  Click **Proposals** to generate different types of proposals for fixed asset groups for which the **Asset group depreciation** check box has been selected, and then click **OK**.
    

    > [!NOTE]
    > <P>You can create an acquisition, depreciation, revaluation, or bonus depreciation proposal.</P>



10. Click **Post** to post the journal, or post lines with no errors and transfer the lines with errors to a new journal.
    

    > [!NOTE]
    > <P>The totals of the amounts that are entered for the fixed asset numbers with the same fixed asset group and transaction type are updated in the <STRONG>Fixed asset balances</STRONG> form (Click <STRONG>Fixed assets</STRONG> &gt; <STRONG>Common</STRONG> &gt; <STRONG>Fixed assets</STRONG> &gt; <STRONG>Fixed assets</STRONG>. Select a fixed asset. On the <STRONG>Action Pane</STRONG>, click <STRONG>Depreciation books</STRONG>. Select a depreciation book and then click <STRONG>Inquiry</STRONG> &gt; <STRONG>Balance</STRONG>.).</P>

    
    For example, you post an acquisition type of journal voucher for fixed asset numbers Book 1 and Book 2 in a fixed asset group. You enter INR 20,000.00 for Book 1 and INR 30,000.00 for Book 2. The total amount of INR 50,000.00 is displayed in the **Acquisition** field of the **Fixed asset balances** form.
    
    A new journal line is created for the proposal type, and the amount that is entered in the **Debit** field or the **Credit** field is updated in the **Fixed asset balances** form (Click **Fixed assets** \> **Common** \> **Fixed assets** \> **Fixed assets**. Select a fixed asset. On the **Action Pane**, click **Depreciation books**. Select a depreciation book and then click **Inquiry** \> **Balance**.).
    

    > [!NOTE]
    > <P>Asset group depreciation is not applicable for <STRONG>Consumption depreciation</STRONG>, <STRONG>Revenue recognition of reserves</STRONG>, and <STRONG>Extraordinary depreciation</STRONG> types of proposals.</P>


  


