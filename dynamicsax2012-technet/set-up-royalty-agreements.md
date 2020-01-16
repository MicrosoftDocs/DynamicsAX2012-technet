---
title: Set up royalty agreements
TOCTitle: Set up royalty agreements
ms:assetid: f1c78500-9640-4e23-b136-13513454d4a0
ms:mtpsurl: https://technet.microsoft.com/library/Dn497851(v=AX.60)
ms:contentKeyID: 62286787
author: Khairunj
ms.date: 05/09/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.TAMPromotionParameters
audience: Application User
ms.search.region: Global
---

# Set up royalty agreements 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to define and set up royalty agreements. A royalty is a fee that one party (the licensee) pays to another party (the licensor) for the use of intellectual property, including logos or copyrights. For example, Fabrikam sells t-shirts that have a small logo on the sleeve. The logo is owned by Contoso. This means that Fabrikam, the licensee, must pay Contoso, the licensor, a royalty for use of the logo.

## Prerequisite: Set up options for royalty payments

Before you set up royalty agreements, you must select options for how your company handles royalty payments. Use the following procedure to set up royalty options.

1.  Click **Accounts payable** \> **Setup** \> **Accounts payable parameters**.

2.  In the **Accounts payable parameters** form, in the left pane, click **Broker and royalty**.

3.  If you calculate royalties on a weekly basis, in the **Royalties** field group, in the **Starting day of week** field, select the day of the week on which to calculate royalties.

4.  In the **Accrual journal name** field, select the journal to which to post royalty accrual amounts when the royalty is approved.

5.  In the **Accrual account** field, select the account to which to post interim royalty liabilities.

6.  In the **Expense account** field, select the account to which to post interim royalty expenses.

7.  In the **Procurement category** field, select the category for line items that include the processed royalty claims on vendor invoices.

## Set up a royalty agreement

Use the following procedure to set up a royalty agreement.

1.  Click **Accounts payable** \> **Common** \> **Royalties** \> **Royalty agreements**.

2.  In the **Royalty agreements** form, click **Create a new record**, and in the upper pane, on the **Overview** tab, enter the vendor and unit information for the royalty agreement.

3.  Enter the following information for this agreement:
    
    1.  In the **Cumulate sales by** field, select whether to cumulate royalties by invoice or by a time period, such as weekly or monthly.
    
    2.  In the **Taken from** field, select whether the royalty value is taken from the net price, or gross price of the item.
    
    3.  In the **Accrual account** and **Expense account** fields, select the accounts used for interim liability postings and interim expense postings, respectively.
    
    4.  Verify that the correct currency is selected and then, if a royalty must be approved before accrual or payment, select the **Approval required** check box.
    
    5.  In the **Calculate by** field, select whether the royalty break is based on the item quantity on the line item or the amount of the line item.

4.  In the upper pane, on the **Selection** tab, click **Add**.

5.  In the **Item number** field, select an item to add to the royalty agreement.
    
    Add more items as necessary.

6.  In the lower pane, on the **Lines** tab, click **Add line**. The values that you entered on the **Selection** tab are shown.

7.  In the lower pane, on the **Royalty amounts** tab, click **Add line**.

8.  In the **From value** and **To value** fields, enter the lowest and highest price of the royalty item.

9.  In the **Value** field, enter the royalty amount that your organization must pay for the item.

## Validate a royalty agreement

A royalty agreement must be validated before it can be applied to a sales order. Use this procedure to validate a royalty agreement.

1.  Click **Accounts payable** \> **Common** \> **Royalties** \> **Royalty agreements**.

2.  In the **Royalty agreements** form, select the agreement to validate, and then click **Validation**.

3.  In the **Validate royalty contract** dialog box, in the **Validated by** field, select your worker identification number, and then click **OK**.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Configuration keys</strong></p></td>
<td><p><strong>Call center</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>System administrator</p></td>
</tr>
</tbody>
</table>

  


