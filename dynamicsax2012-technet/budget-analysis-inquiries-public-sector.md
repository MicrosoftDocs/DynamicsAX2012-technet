---
title: Budget analysis inquiries (Public sector)
TOCTitle: Budget analysis inquiries (Public sector)
ms:assetid: a8102d21-014b-437f-a6d5-efb8b1fc7d85
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn715993(v=AX.60)
ms:contentKeyID: 62200218
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- analysis
- Public sector
- budget
- budget analysis
audience: Application User
ms.search.region: Denmark, France
---

# Budget analysis inquiries (Public sector) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic explains how you can use the **Budget analysis** form to view revenues and expenditures by financial dimension, by using a combination of general ledger and budget control data. You can view summarized amounts and transaction details for revised budgets, actual expenditures, encumbrances, and pre-encumbrances.


> [!NOTE]
> <P>This feature is available only if Microsoft Dynamics AX 2012 R3 Cumulative Update 8 is installed, and if the <STRONG>Public Sector</STRONG> configuration key is selected.</P>



## Should I use the Budget control statistics form or the Budget analysis form?

The **Budget control statistics** form is the tool to use when you want to analyze a single budget account, or a combination or group of accounts. (Click **Budgeting** \> **Inquiries** \> **Budget control statistics**.) The **Budget analysis** form is more flexible. (Click **Budgeting** \> **Inquiries** \> **Budget analysis**.) You can use it to query in any dimension order across the chart of accounts or to query a subset of an account. For example, you could view a list of year-to-date fund totals, drill down to a specific fund to view department totals, and then drill down to a specific department to view account totals.

The following table explains the differences between these forms.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Budget control statistics form</p></th>
<th><p>Budget analysis form</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Allows you to view the budget balances for a budget cycle and a budget model for a single financial dimension value or budget group.</p></td>
<td><p>Allows you to view the combined budget amounts for multiple financial dimension values at the same time.</p></td>
</tr>
<tr class="even">
<td><p>Includes data from both confirmed and unconfirmed encumbrances.</p></td>
<td><p>Includes data from confirmed encumbrances only.</p></td>
</tr>
<tr class="odd">
<td><p>Includes data from expense accounts only.</p></td>
<td><p>Includes data from both revenue and expense accounts.</p></td>
</tr>
<tr class="even">
<td><p>Does not require a configuration key.</p></td>
<td><p>Requires the <strong>Public Sector</strong> configuration key.</p></td>
</tr>
</tbody>
</table>



> [!NOTE]
> <P>If you want the available or remaining budget amounts to include draft transactions, use the <STRONG>Budget control statistics</STRONG> form. The <STRONG>Budget analysis</STRONG> form displays only posted transactions.</P>



## Can I export the results on the Budget analysis form to Microsoft Excel?

Yes, you can export budget analysis results. On the **Budget analysis** form, press **Ctrl+T**.

## How do I display information for a specific closing period?

To view balances and information for a specific closing period, use the **Trial balance** list page. The **Budget analysis** form does not distinguish between operating periods and closing periods.

## How do I analyze the budget in a dimension order that’s different from the expense account structure? For example, what if I want to view certain Main accounts across programs or other dimensions?

You can create financial dimension sets that reflect the way that you want to analyze your data. To do this, use the **Financial dimension sets** form in the **General ledger** module. (Click **General ledger** \> **Setup** \> **Financial dimensions** \> **Financial dimension sets**.) To view Main accounts across programs, for example, create a Programs dimension set, and then add dimensions by using **MainAccount**. When you return to the **Budget analysis** form and select that dimension set, the budget appears as a list of Main accounts. You can then drill down in any Main account to include the program level of the dimension set, which breaks down all the totals by program within that Main account.

For more information, see [Create a financial dimension set](create-a-financial-dimension-set.md).

## What if the financial dimension set that I want to use isn’t included on the Budget analysis form?

All existing financial dimensions sets are displayed on the **Budget analysis** form. If you don’t see the one that you want, you can create it in the **General ledger** module.

For more information, see [Create a financial dimension set](create-a-financial-dimension-set.md).

## What is the Carry forwards column set used for?

Use the **Expense budget with carry-forwards** column set if you carry forward the budget for purchase orders that are open at year-end. This column set shows separate totals both for transactions that use active prior-year budget and transactions that use the new year’s budget. This makes it easy for you to monitor the budgeted, encumbered, and expended amounts that are related to transactions from the prior year.

For more information about column sets, see [Budget analysis (form) (Public sector)](https://technet.microsoft.com/en-us/library/jj710370\(v=ax.60\)).

## What should I do if the grids are empty even when I’ve selected all the values at the top of the form?

If the grids are empty in the **Budget analysis** form, try the following actions to resolve the issue:

  - Click **Update totals** after you set the values at the top of the form.

  - Verify that the selected dimension set includes the dimension value that you’re looking for.

  - Verify that the posting layer and the dates are correct for the values that you’re looking for.

  - Verify that the transaction document that you’re looking for has been posted or confirmed. Only posted transactions are displayed in the **Budget analysis** form.

## How can I see updated numbers in the columns when I change the dimension set, dates, posting layers, and other settings?

After you change the settings at the top of the form, click **Update totals** to see the results of your query.

## Why can’t I adjust the size of the Total area at the bottom of the form?

Because the **Total** grid only displays a single row, it is not useful to adjust the size vertically. However, you can adjust the column widths.

## How can I change the column widths in the Totals area at the bottom of the form to match the columns at the top?

The columns in the primary grid and summary grid are separate controls, and are sized independently.

## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

## See also

[Budget analysis (form) (Public sector)](https://technet.microsoft.com/en-us/library/jj710370\(v=ax.60\))

[Budget analysis for revised budgets (form) (Public sector)](https://technet.microsoft.com/en-us/library/jj710369\(v=ax.60\))

[Budget analysis for pre-encumbrances (form) (Public sector)](https://technet.microsoft.com/en-us/library/jj710368\(v=ax.60\))

[Budget analysis for actual expenditures (form) (Public sector)](https://technet.microsoft.com/en-us/library/jj710367\(v=ax.60\))

[Budget analysis for encumbrances (form) (Public sector)](https://technet.microsoft.com/en-us/library/jj710366\(v=ax.60\))

  


