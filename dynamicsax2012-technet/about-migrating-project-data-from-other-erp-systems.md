---
title: About migrating project data from other ERP systems
TOCTitle: About migrating project data from other ERP systems
ms:assetid: 253c025d-7c4d-4351-9b02-d207eb068244
ms:mtpsurl: https://technet.microsoft.com/library/Hh208482(v=AX.60)
ms:contentKeyID: 36056190
author: Khairunj
ms.author: daxcpft
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- fixed-price
- migrate project
audience: Application User
ms.search.region: Global
---

# About migrating project data from other ERP systems 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The process of migrating project data from another Enterprise Resource Planning system into Microsoft Dynamics AX consists of two major tasks:

  - Create a General ledger journal to record the account balances from another system

  - Create a Beginning balance project journal to specify project balances

When you migrate project data to Microsoft Dynamics AX from offline records or another Enterprise Resource Planning (ERP) system, the project details must be retained. Additionally, the accumulated milestone or progress invoices, from the start of the project to the date of the migration, must be recorded during the migration. If you want to migrate project details that were previously tracked, but you do not want to affect the General ledger, use the **Beginning balance journal** form to post the project's beginning balance detail. Then run the Microsoft Dynamics AX Estimate process, which is used to recognize the revenues of fixed-price projects. When the migration process is completed correctly, the posted values in **Project management and accounting** equal the account values in the General ledger, and the General ledger does not contain a double entry or inflated balances.

You can migrate project details to Microsoft Dynamics AX for the following types of projects:

  - Fixed-price

  - Time and material

  - Investment

  - Internal

  - Time

  - Cost

## Migrating a fixed-price project

As part of the process of migrating a fixed-price project to Microsoft Dynamics AX, you must run the Estimate process. Microsoft Dynamics AX can then calculate the percentage of the project that is completed as of the migration date. Because fixed-price projects accrue revenue, it is assumed that invoice transactions have been recorded but not invoiced.

Based on the cost estimates and previous sales billings, you can enter the work in progress (WIP) detail from your previous tracking method in the **Beginning balance journal** form. The detail is then posted to Microsoft Dynamics AX Project management and accounting. The WIP detail can consist of hour, expense, and item transactions, and it is recorded on the balance sheet as gross WIP.

WIP can be based on either of the two accepted accounting revenue recognition rules, completed contract or percentage of completion. WIP can be valued at the cost price, the sales price, or production plus profit.

  - Percentage of completion – This method recognizes the revenues, costs, and gross margin for each period, based on the progress of a long-term project. For example, if 25 percent of a building project was completed during the year, the builder can recognize 25 percent of the total profit that is expected on the contract. This method is usually preferred, because it matches the revenues and expenses in a fiscal period better than the completed contract method. Because of principles for conservatism, expected loss is usually fully recognized in the current fiscal year.

  - Completed contract – This method only recognizes the revenue and profit when a long-term project is completed.

If you are using the percentage of completion method, net WIP is calculated by subtracting on-account invoices that are posted from the gross WIP. Gross WIP is the work that is performed. The net WIP represents the investment that the company has made in the project.

You must complete the following tasks when you migrate project details:


> [!NOTE]
> <P>It is assumed that you have created a fixed-price project, and that you configured the project to track transactions according to your business requirements as the project progresses.</P>



1.  Create a beginning balance journal by using the **Beginning balance journal** form. Then enter the transaction detail for the projects that you are migrating to Microsoft Dynamics AX, at the level that you require. Consider the project's category, worker, and item details that you want to migrate to Microsoft Dynamics AX for reporting purposes. Additionally, consider the detail that is necessary to calculate revenue recognition.

2.  Create and run a beginning balance estimate.

Based on the actual and forecast information, the Estimate process calculates the percentage of the project that is completed, and uses the value to record accrued revenue.

## Migrating at the end of the fiscal year vs. migrating at midyear

If you migrate the project details at the beginning of your fiscal year, the following events are recorded for both the percentage of completion method and the completed contract method:

1.  A general journal for assets and liabilities is posted to the balance sheet in the General ledger. This journal includes a debit amount for the gross WIP that was posted, and a credit amount for invoiced WIP. No entries are recorded for profit and loss.

2.  A detailed beginning balance journal is posted in Project management and accounting. This journal includes costs and invoices that were recorded in the previous system until the end of the fiscal year.

3.  A beginning balance estimate is posted at the end of the fiscal year. This estimate includes both costs and revenues.

## Migrating during the fiscal year

If you migrate project details in the middle of your fiscal year, a second estimate is posted. This estimate covers the end of the last fiscal year up to the migration date.

Additionally, the events that are described in the following table can occur, depending on the method that you use for valuation.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Method</p></th>
<th><p>Entries</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Percentage of completion</p></td>
<td><ul>
<li><p>In addition to the entry for the balance sheet journal, entries for profit and loss are recorded for the current fiscal year to the migration date.</p></li>
<li><p>In addition to the beginning balance journal that is posted, an additional set of entries is recorded for transactions as of the migration date.</p></li>
<li><p>Two beginning balance estimates are posted instead one. One posting is for the end of the previous fiscal year and is for WIP only. The other posting is as of the migration date and is for both WIP and profit and loss.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Completed contract</p></td>
<td><ul>
<li><p>In addition to the beginning balance journal that is posted, an additional set of entries is recorded for transactions as of the migration date.</p></li>
<li><p>Two beginning balance estimates are posted. One estimate is posted for the end of the previous fiscal year, and the other is posted for transactions occurring after the end of the year and up to the migration date. Both estimates are for WIP only.</p>
<div class="alert">

> [!NOTE]
> <P>The two beginning balance estimates do not affect the General ledger, either at the end of the previous fiscal year or on the migration date.</P>


</div></li>
</ul></td>
</tr>
</tbody>
</table>


## Reconciliation

After you migrate the project details, reconcile the WIP balances on the balance sheet with the details that are posted in Project management and accounting. You can view detailed information about transactions in the following reports:

  - Ledger reconciliation – WIP (report)

  - Projects – WIP (report)

## Migrating time and material projects

You can also migrate the beginning balances for time and material projects, so that transactions that were posted in the previous ERP system can be tracked and invoiced in Microsoft Dynamics AX.

If you are migrating project details for time and material projects, consider the following questions:

  - Do you record costs to WIP and accrue revenues, or do you record costs to profit and loss?

  - Has invoicing been run in the previous system?
    

    > [!NOTE]
    > <P>If the previous transactions have been invoiced, you must set the <STRONG>Transaction status</STRONG> field in the <STRONG>Journal lines for beginning balances</STRONG> form to <STRONG>Invoiced</STRONG>.</P>



  - Has revenue been posted in the previous system, and was the revenue recorded in the General ledger as a lump sum?

You do not have to run the Estimate process on the project details for time and material projects. You must only enter details in the **Beginning balance journal** form.


> [!TIP]
> <P>Transactions from the beginning balance journal are excluded from the adjustment function. Therefore, you must correct beginning balances manually in the <STRONG>Beginning balance journal</STRONG> form. To correct beginning balances, use reversing journal transactions and new journal transactions.</P>



## Migrating investment projects

When you track investment projects, you record expenses on the balance sheet. To migrate the cost detail, enter the recorded costs from the previous system in the **Beginning balance journal** form. However, you must still run the Estimate process in Microsoft Dynamics AX after the WIP is posted. Microsoft Dynamics AX can then calculate the percentage of the project that is completed, and record the transaction as processed.

## Migrating other projects: cost, internal, and time

If you are migrating details for internal project expenses, or if you have projects for which you are only tracking hours, consider the following questions:

  - Are you posting expenses to profit and loss or to the balance sheet? The method that you use to book expenses for each project determines how you migrate the expenses to Microsoft Dynamics AX.

  - What type of project do you have, and what are the posting options? The type of project and the posting options determine how you manage and track these projects.

## Rules for posting costs in beginning balance journals

For fixed-price projects and investment projects, the revenue recognition accounting rule for the associated project group controls the locations to which costs are posted. The ledger to which a transaction is posted depends on the project group's settings for posting to the balance sheet or profit and loss. The project group's setting for posting to the balance sheet or profit and loss can be overridden only if the **Capitalize cost** check box has been selected for the associated line property on the **Line properties** form. (Click **Project management and accounting** \> **Setup** \> **Line properties** \> **Line properties**.) If the **Capitalize cost** check box is not selected, the transaction is posted to profit and loss, regardless of the project group's setting.


> [!NOTE]
> <P>If the default cost status is changed on lines in the beginning balance journal, the Estimate process may post additional cost transactions. The General ledger is not updated.</P>



The following table describes the rules for posting costs in beginning balance journals.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Revenue recognition type</p></th>
<th><p>Condition</p></th>
<th><p>Posted cost status</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Percentage of completion</p>
<p>–or–</p>
<p>Completed contract</p></td>
<td><p>The transaction type is <strong>Hour</strong>, and the cost status for hours in the Project group ledger setting is <strong>Never ledger</strong>.</p>
<div class="alert">

> [!NOTE]
> <P>If the status is <STRONG>Never ledger</STRONG>, costs are posted only to the project's subledger, not to the General ledger.</P>


</div></td>
<td><p>Never ledger</p></td>
</tr>
<tr class="even">
<td><p>Completed contract</p></td>
<td><p>The <em>Capitalize</em> line property is set to <em>True</em>.</p></td>
<td><p>Balance sheet</p></td>
</tr>
<tr class="odd">
<td><p>Completed percentage</p></td>
<td><p>The <em>Capitalize</em> line property is set to <em>True</em>.</p></td>
<td><p>Profit and loss</p></td>
</tr>
<tr class="even">
<td><p>Percentage-of-completion</p>
<p>–or–</p>
<p>Completed contract</p></td>
<td><p>The <em>Capitalize</em> line property is set to <em>False</em>.</p></td>
<td><p>Profit and loss</p></td>
</tr>
</tbody>
</table>


## Using the forecast reduction feature

When you enter your forecast for projects that are in process, the amounts that you enter include any forecast amounts that were not previously spent. However, if you use the forecast reduction feature, the forecast that you enter includes the amounts that were previously spent. Then, when you enter the beginning balance journals for the amounts that were previously spent, the forecast amounts are reduced to the current balance.


> [!IMPORTANT]
> <P>If you posted the beginning balance journals before you posted the forecasts, you can still use the forecast reduction feature. We recommend that you enter the total forecasts, enable forecast reduction, and then post the beginning balance journals.</P>



The following topics provide information about migrating project data from other ERP system and creating beginning balance journal entries:

[Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md)

[Create a project beginning balance](create-a-project-beginning-balance.md)

[Beginning balance journal (form)](https://technet.microsoft.com/library/hh209585\(v=ax.60\))

[Journal lines for beginning balances (form)](https://technet.microsoft.com/library/hh227479\(v=ax.60\))

[Journal voucher - General journal (form)](https://technet.microsoft.com/library/aa591466\(v=ax.60\))

[Journal header (form)](https://technet.microsoft.com/library/aa557917\(v=ax.60\))

  


