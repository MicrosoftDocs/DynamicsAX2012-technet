---
title: (ITA) Generate the Italian fixed asset book report after disposal of a fixed asset
TOCTitle: (ITA) Generate the Italian fixed asset book report after disposal of a fixed asset
ms:assetid: ceff3382-7b0d-496b-9f16-1b2fe1e0436a
ms:mtpsurl: https://technet.microsoft.com/library/Hh242912(v=AX.60)
ms:contentKeyID: 36059473
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- report
- Italy
- fixed assets
- disposal
- fixed asset book
audience: Application User
ms.search.region: Italy
---

# (ITA) Generate the Italian fixed asset book report after disposal of a fixed asset 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In accordance with Italian law, when an asset is sold or scrapped, the value of the asset is printed in the **Disposal in period** column of the Italian fixed asset book report. After disposal, the asset is no longer included in the report.

To print the Italian fixed asset book report, complete the following tasks:

  - Acquire an asset.

  - Depreciate the asset.

  - Dispose of or scrap the asset.

## Prerequisites

Before acquiring an asset, set up the following information:

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p><strong>Task</strong></p></td>
<td><p><strong>Condition</strong></p></td>
<td><p><strong>Cross-reference</strong></p></td>
</tr>
<tr class="even">
<td><p>Set up a depreciation profile</p></td>
<td><p>Create a manual method of depreciation, using two manual schedules, each with depreciation of 50%.</p></td>
<td><ul>
<li><p><a href="create-a-depreciation-profile.md">Create a depreciation profile</a></p></li>
<li><p><a href="https://technet.microsoft.com/library/aa549887(v=ax.60)">Depreciation profiles (form)</a></p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Set up value models</p></td>
<td><ul>
<li><p>Select the posting layer as <strong>Current</strong>.</p></li>
<li><p>Select the depreciation profile.</p></li>
</ul></td>
<td><p><a href="set-up-value-models.md">Set up value models</a></p></td>
</tr>
<tr class="even">
<td><p>Set up fixed asset groups</p></td>
<td><ul>
<li><p>Select the value model.</p></li>
<li><p>Specify the service life as two years.</p></li>
</ul></td>
<td><p><a href="set-up-fixed-asset-groups.md">Set up fixed asset groups</a></p></td>
</tr>
<tr class="odd">
<td><p>Create a fixed asset</p></td>
<td><p>Select the fixed asset group.</p></td>
<td><p><a href="https://technet.microsoft.com/library/aa620341(v=ax.60)">Fixed assets (form)</a></p></td>
</tr>
</tbody>
</table>


## Acquire a fixed asset

When you acquire an asset, you must create and post an invoice journal for depreciation. For more information, see [About options for entering fixed asset transactions](about-options-for-entering-fixed-asset-transactions.md) and [About assets acquired through procurement](about-assets-acquired-through-procurement.md).

Click **General ledger** \> **Setup** \> **Journals** \> **Journal names**. Use this form to create a journal name before you acquire an asset and specify the **Journal type** as **Vendor invoice recording**. For more information, see [Journal names setup (form)](https://technet.microsoft.com/library/aa552517\(v=ax.60\)).

1.  Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice journal**.

2.  Press CTRL+N to create a new journal line. For more information, see [Journal header (form)](https://technet.microsoft.com/library/aa557917\(v=ax.60\)).

3.  In the **Name** field, select the acquisition journal name and then click **Lines** to open the **Journal voucher** form. For more information, see [Journal voucher - Invoice journal (form)](https://technet.microsoft.com/library/aa616218\(v=ax.60\)).

4.  In the **Date** field, enter the posting date. The voucher number is generated and displayed in the **Voucher** field.

5.  In the **Account type** and **Account** fields, select **Vendor**, and then select the account of the vendor you purchased the fixed asset from.

6.  In the **Invoice** and **Credit** fields, enter the invoice number and the purchase amount.

7.  In the **Offset account type** and **Offset account** fields, select **Fixed assets**, and then enter the number of the fixed asset.

8.  Click **Validate** \> **Validate** to validate the journal.

9.  Click **Post** \> **Post** to post the journal.

10. Close the forms to save your changes.

## Depreciate a fixed asset

1.  Click **Fixed assets** \> **Journals** \> **Depreciation book journal**.

2.  Press CTRL+N to create a new line. For more details, see [Depreciation book journal (form)](https://technet.microsoft.com/library/aa634765\(v=ax.60\)).

3.  In the **Name** field, select the relevant journal name and then click **Lines** to open the **Journal line** form. For more information, see [Journal line (form)](https://technet.microsoft.com/library/hh209722\(v=ax.60\)).

4.  Click **Proposals** \> **Depreciation proposal** to open the **Depreciation proposal** form.

5.  In the **To date** field, enter the ending date for calculating depreciation for the fixed asset.

6.  Click **Select** to filter the information based on the fixed asset number, fixed asset group, depreciation book, or depreciation, and then click **OK**.

7.  In the **Depreciation proposal** form, click **OK**. The depreciation details are displayed in the journal.

8.  Click **Validate** to validate the journal.

9.  Click **Post** \> **Post** to post the depreciation transactions.

10. Close the forms to save your changes.

## Dispose of a fixed asset

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  Press CTRL+N to create a new line. For more information, see [Key tasks: Free text invoices](key-tasks-free-text-invoices.md).

3.  In the **Customer account** field, select the account number of the customer you sold the asset to.

4.  In the **Invoice account** field, select the account number of the customer to be invoiced.

5.  In the **Date** field, select the invoice date.

6.  Click the **Line details** tab, and in the **Invoice text** field, enter a description for the invoice.

7.  In the **Fixed asset number** field, select the fixed asset to be sold.

8.  Click **Post** to open the **Post free text invoice** form.

9.  Select the **Posting** check box, and then click **OK** to post the free text invoice.

10. Close the form to save your changes.

## Scrap a fixed asset

1.  Click **Fixed assets** \> **Journals** \> **Depreciation book journal**.

2.  Press CTRL+N to create a new line. For more information, see [Create depreciation book journals](create-depreciation-book-journals.md).

3.  In the **Name** field, select the relevant journal name and then click **Lines** to open the **Journal line** form.

4.  In the **Date** field, enter the transaction date.

5.  In the **Transaction type** field, select **Disposal - scrap**.

6.  In the **Fixed asset number** field, select the asset number of the fixed asset to be scrapped.

7.  In the **Depreciation book** field, select the depreciation book for the fixed asset.

8.  In the **Debit** field, enter the scrap amount.

9.  Click **Validate** to validate the journal.

10. Click **Post** \> **Post** to post the transactions for scrapping the asset.

11. Close the form to save your changes.

12. Click **Fixed assets** \> **Reports** \> **Transactions** \> **Italian fixed asset book**. For more information, see [(ITA) Fixed asset book report (AssetDepreciationLedger\_IT)](ita-fixed-asset-book-report-assetdepreciationledger-it.md).

13. In the **Closing date prior year** and **Closing date this year** fields, select the ending date of the previous fiscal year and the ending date of the current fiscal year to generate the **Italian fixed asset book** report.

14. Select the **Detailed print** check box to include detailed information about the asset books.

15. Click **OK** to generate the report.
    

    > [!NOTE]
    > <P>The value of the sold or scrapped fixed asset is displayed in the <STRONG>Disposal in period</STRONG> column of the report. Generate the report for the subsequent year to verify that the asset is no longer included in the report.</P>


  


