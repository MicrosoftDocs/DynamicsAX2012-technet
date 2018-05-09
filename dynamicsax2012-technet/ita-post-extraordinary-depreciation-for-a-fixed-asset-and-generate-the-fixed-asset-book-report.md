---
title: (ITA) Post extraordinary depreciation for a fixed asset and generate the Fixed asset book report
TOCTitle: (ITA) Post extraordinary depreciation for a fixed asset and generate the Fixed asset book report
ms:assetid: 452eccac-aad5-4c1e-9227-4576e5b6854b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242380(v=AX.60)
ms:contentKeyID: 36056891
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Italy
- depreciation
- fixed asset book report
---

# (ITA) Post extraordinary depreciation for a fixed asset and generate the Fixed asset book report 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the Fixed asset journal to post extraordinary depreciation for eligible fixed assets. After posting the extraordinary depreciation, you can generate the Fixed asset book report to view the details.

Extraordinary depreciation functions in the same way as basic depreciation, but can be posted and reported independently. To maintain extraordinary depreciation as a separate transaction type, you must specify a ledger account when you credit the depreciation amount to the balance sheet. You must also charge the depreciation as expenditure to an offset account.

First, create an extraordinary depreciation profile to set up the extraordinary depreciation method. Next, set up the extraordinary depreciation book and ledger accounts.

## Create fixed asset groups

1.  Click **Fixed assets** \> **Setup** \> **Fixed asset groups**.

2.  Press CTRL+N to create a new line. For more information, see [Set up fixed asset groups](set-up-fixed-asset-groups.md) and [Fixed asset groups (form)](https://technet.microsoft.com/en-us/library/aa573347\(v=ax.60\)).

3.  In the **Fixed asset group** field, enter the unique code for the fixed asset group.

4.  In the **Name** field, enter the description of the fixed asset group.

5.  On the **General** tab, in the **Type** field, select the fixed asset type.

6.  Close the form to save your changes.

## Set up fixed asset posting profiles

1.  Click **Fixed assets** \> **Setup** \> **Fixed asset posting profiles**.

2.  Press CTRL+N to create a new line. For more information, see [Set up fixed asset posting profiles](set-up-fixed-asset-posting-profiles.md).

3.  In the **Posting profile** field, enter the posting profile that links a fixed asset transaction with a ledger account when you post the fixed asset transaction.

4.  In the **Description** field, enter the description of the posting profile.

5.  On the **Ledger accounts** tab, under the **Select** field group, select **Extraordinary depreciation**.

6.  Click the right pane and press CTRL+N to create a new line.

7.  In the **Value model** field, select a value model for posting fixed asset transactions.

8.  In the **Main account** field, select a ledger account number for posting the transactions.

9.  In the **Offset account** field, select an offset account for the transaction.

10. Close the form to save your changes.

## Create an extraordinary depreciation profile

1.  Click **Fixed assets** \> **Setup** \> **Depreciation** \> **Depreciation profiles**.

2.  Press CTRL+N to create a new line. For more information, see [About manual depreciation](about-manual-depreciation.md), [Create a depreciation profile](create-a-depreciation-profile.md), and [Depreciation profiles (form)](https://technet.microsoft.com/en-us/library/aa549887\(v=ax.60\)).

3.  In the **Depreciation profile** field, enter the unique code for the extraordinary depreciation profile.

4.  In the **Name** field, enter the description of the profile.

5.  In the **Method** field, select **Manual**.

6.  Click **Manual schedules** to open the **Fixed asset depreciation profile schedules** form.

7.  Press CTRL+N to create a new line.

8.  In the **Interval number** field, enter the number of the depreciation interval.
    

    > [!NOTE]
    > <P>The interval number refers to the individual depreciation period, which could be yearly, quarterly, monthly, or half-yearly. For example, if your depreciation period is quarterly, enter 1 to represent the first depreciation period, or quarter. Enter 4 for the fourth depreciation period, or fourth quarter.</P>



9.  In the **Percentage** field, enter the depreciation percentage to be applied for the selected depreciation period. The sum of the percentages entered in the **Percentage** field is displayed in the **Cumulative percentage** field.

10. Close the **Fixed asset depreciation profile schedules** form and the **Depreciation profiles** form to save your changes.

## Create an extraordinary depreciation book

1.  Click **Fixed assets** \> **Journals** \> **Depreciation book journal**.

2.  Press CTRL+N to create a new line. For more information, see [Depreciation books setup (form)](https://technet.microsoft.com/en-us/library/aa597721\(v=ax.60\)).

3.  In the **Depreciation book** field, enter the unique identification for the extraordinary depreciation book.

4.  In the **Description** field, enter the description of the book.

5.  On the **General** FastTab, select the **Depreciation** check box to indicate that the asset can be depreciated.

6.  In the **Depreciation profile** field, select the depreciation profile.

7.  In the **Extraordinary depreciation profile** field, select the extraordinary depreciation profile.

8.  In the **Calendar** field, select the fixed asset calendar for the depreciation book.

9.  Close the form to save your changes.

## Create a value model

1.  Click **Fixed assets** \> **Setup** \> **Value models**.

2.  Press CTRL+N to create a new line. For more information, see [Set up value models](set-up-value-models.md).

3.  In the **Value model** field, enter the unique code for the value model.

4.  In the **Description** field, enter the description of the value model.

5.  On the **General** FastTab, select the **Depreciation** check box to indicate that the asset can be depreciated.

6.  In the **Extraordinary depreciation profile** field, select an extraordinary depreciation profile.

7.  In the **Posting layer** field, select **Current**.

8.  Click **Fixed asset groups** to open the **Fixed asset group/value model** form.

9.  Press CTRL+N to create a new line.

10. In the **Fixed asset group** field, select the fixed asset group to be associated with the value model.

11. In the **Service life** field, enter the life of the fixed asset in years.

12. Close the **Fixed asset group/value model** form and the **Value models** form to save your changes.

## Create a new asset

1.  Click **Fixed assets** \> **Common** \> **Fixed assets** \> **Fixed assets**.

2.  In the **New** group, click **Fixed asset** to open the **Fixed assets** form. For more information, see [Fixed assets (form)](https://technet.microsoft.com/en-us/library/aa620341\(v=ax.60\)).

3.  Press CTRL+N to create a fixed asset.

4.  On the **General** FastTab, in the **Fixed asset group** field, select the group for the fixed asset.

5.  In the **Fixed asset number** field, enter the unique code for the fixed asset.

6.  In the **Name** field, enter the name of the fixed asset.

7.  In the **Type** field, select the fixed asset type.

8.  Close the form to save your changes.

## Acquire the asset

1.  Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice journal**.

2.  Press CTRL+N to create a new line.

3.  In the **Name** field, select the journal name. For more information, see [Journal header (form)](https://technet.microsoft.com/en-us/library/aa557917\(v=ax.60\)).

4.  Click **Lines** to open the **Journal voucher** form.

5.  In the **Date** field, enter the posting date.

6.  In the **Account type** field, select **Vendor**.

7.  In the **Account** field, select the account number of the vendor who supplied the fixed asset.

8.  In the **Invoice** field, enter the invoice number.

9.  In the **Credit** field, enter the acquisition cost.

10. In the **Offset account type** field, select **Fixed assets**.

11. In the **Offset account** field, select the number of the fixed asset.

12. Click **Validate** \> **Validate** to validate the journal.

13. Click **Post** \> **Post** to post the journal.

14. Close the **Journal voucher** form and the **Journal** form to save your changes.

## Post the extraordinary depreciation and generate the fixed asset book report

1.  Click **Fixed assets** \> **Journals** \> **Fixed assets**.

2.  Press CTRL+N to create a new line.

3.  In the **Name** field, select the journal name. For more information, see [Journal header (form)](https://technet.microsoft.com/en-us/library/aa557917\(v=ax.60\)).

4.  Click **Lines** to open the **Journal voucher** form.

5.  Click **Proposals** \> **Extraordinary depreciation proposal** to open the **Extraordinary depreciation proposal** form.

6.  In the **To date** field, enter the ending date of the depreciation period.

7.  Click **Select** to specify the fixed asset number, fixed asset group, and value model.

8.  Click **OK**. Extraordinary depreciation is calculated for the specified fixed asset number and displayed in the **Journal voucher** form.

9.  Click **Validate** \> **Validate** to validate the journal.

10. Click **Post** \> **Post** to post the journal.

11. Close the forms to save your changes.

12. Click **Fixed assets** \> **Reports** \> **Transactions** \> **Italian fixed asset book**. For more information, see [(ITA) Fixed asset book report (AssetDepreciationLedger\_IT)](ita-fixed-asset-book-report-assetdepreciationledger-it.md).

13. In the **Start date** and **End date** fields, select the starting and ending date of the transaction period.

14. Select the **Detailed print** check box to include detailed information about the asset books.

15. Click **OK** to generate the report. The percentage and amount of extraordinary depreciation for the previous year are displayed in the **Percent extraordinary depreciation** and **Accumulated Extraordinary Depreciation** columns of the report.

## See also

[About depreciation](about-depreciation.md)

[About manual depreciation](about-manual-depreciation.md)

[About reducing balance depreciation](about-reducing-balance-depreciation.md)

[About straight line service life depreciation](about-straight-line-service-life-depreciation.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

