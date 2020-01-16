---
title: Prepare a legal entity for a currency conversion
TOCTitle: Prepare a legal entity for a currency conversion
ms:assetid: 22570bdf-7798-43ed-bb91-7fc7b13b2790
ms:mtpsurl: https://technet.microsoft.com/library/Aa496797(v=AX.60)
ms:contentKeyID: 36941285
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Prepare a legal entity for a currency conversion 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you can convert your legal entity’s currency, you must revert any foreign currency revaluation amounts for customer and vendor accounts, and close the previous fiscal years. You must also complete tasks that prepare the database for the conversion, and then make the required changes to the legal entity’s account that is undergoing the currency conversion.

## Revert foreign currency revaluation amounts for customer and vendor accounts

If you performed foreign currency revaluations to revalue amounts with regard to the legal entity’s currency, you must revert the amounts to the original currency amounts before you change the currency for the legal entity. For more information, see [Revalue foreign currency amounts for customers or vendors](revalue-foreign-currency-amounts-for-customers-or-vendors.md). To revert amounts to the original currency amounts, select **Invoice date** in the **Method** field for the revaluation.

1.  Click **Accounts receivable** \> **Periodic** \> **Foreign currency revaluation**.

2.  Click **Foreign currency revaluation**.

3.  In the **Method** field, select **Invoice date**.

4.  In the **Considered date** field, select the date to use for the currency conversion.

5.  Enter values in the other fields, as necessary.

6.  Click **OK** to revalue the foreign currency amounts for customers.

7.  Click **Accounts payable** \> **Periodic** \> **Foreign currency revaluation**.

8.  Click **Foreign currency revaluation**.

9.  In the **Method** field, select **Invoice date**.

10. In the **Considered date** field, select the date to use for the currency conversion.

11. Enter values in the other fields, as necessary.

12. Click **OK** to revalue the foreign currency amounts for vendors.

## Close previous fiscal years

1.  Click **Inventory management** \> **Periodic** \> **Closing and adjustment**. Close the inventory the day before the opening date of the current fiscal year.

2.  Click **General ledger** \> **Periodic** \> **Fiscal year close** \> **Opening transactions**. Create opening transactions for the current fiscal year.

3.  Click **General ledger** \> **Setup** \> **Ledger**. Click **Ledger calendar**. Select **Closed** in the **Period status** field for all periods of the previous fiscal years.

## Prepare the database for currency conversion

1.  Click **General ledger** \> **Setup** \> **Currency** \> **Currencies**.

2.  Select the **Reference currency for triangulation** check box.

3.  Select the **Conversion** check box, and enter a prefix and a suffix.

4.  Create a backup of the database. For more information, see ![technet logo](images/Aa556994.technet_thumbnail(AX.60).jpg "technet logo") [Database administration for Microsoft Dynamics AX](database-administration-for-microsoft-dynamics-ax.md).

5.  Click **General ledger** \> **Periodic** \> **Currency conversions** \> **Check ledger transactions**. Print the **Check ledger transactions** report to verify amounts before the conversion.
    
    Any errors are displayed on the report. If there are no errors, the report is blank.
    

    > [!NOTE]
    > <P>If there are errors, you must correct the incorrect data before you continue the conversion.</P>



## Make required changes to the legal entity account undergoing currency conversion

1.  Click **System administration** \> **Setup** \> **Licensing** \> **License configuration**. Verify that the **Euro** and **Reporting currency** configuration keys are selected under the **Currency** license code.

2.  Click **General ledger** \> **Setup** \> **Currency** \> **Currencies**. Verify that there is a currency code for the legal entity’s new currency. If a new legal entity currency code does not exist, create one.

3.  Click **General ledger** \> **Setup** \> **Chart of accounts** \> **Chart of accounts**. Select the chart of accounts, and then click **Edit** on the **Main accounts** FastTab. Verify that main accounts that have the following posting types have been created:
    
      - **Accounting currency conversion gain**
    
      - **Accounting currency conversion loss**
    
    If the main accounts do not exist, create them.

4.  Click **General ledger** \> **Setup** \> **Posting** \> **Accounts for automatic transactions**. Verify that main accounts are assigned to the following posting types:
    
      - **Accounting currency conversion gain**
    
      - **Accounting currency conversion loss**
    
      - **Penny difference in accounting currency**
    
      - **Penny difference in reporting currency**
    
      - **Year-end result**
    
    If a posting type does not have a main account assigned to it, assign a main account.

## See also

[Accounts for automatic transactions (form)](https://technet.microsoft.com/library/aa548973\(v=ax.60\))

[Chart of accounts (form)](https://technet.microsoft.com/library/aa618234\(v=ax.60\))

[Check ledger transactions report (LedgerCheckTrans)](check-ledger-transactions-report-ledgerchecktrans.md)

[Closing and adjustment (form)](https://technet.microsoft.com/library/aa553192\(v=ax.60\))

[Currencies (form)](https://technet.microsoft.com/library/aa582902\(v=ax.60\))

[Key tasks: Fiscal calendars, fiscal years, and periods](key-tasks-fiscal-calendars-fiscal-years-and-periods.md)

[Ledger (form)](https://technet.microsoft.com/library/hh209331\(v=ax.60\))

[Main accounts - chart of accounts (form)](https://technet.microsoft.com/library/hh209695\(v=ax.60\))

[Opening transactions (form)](https://technet.microsoft.com/library/aa572506\(v=ax.60\))

  


