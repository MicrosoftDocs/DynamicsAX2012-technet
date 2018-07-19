---
title: Fiscal year closing checklist
TOCTitle: Fiscal year closing checklist
ms:assetid: fd2f412e-d2e5-4fda-b4ee-b1cacaf0bd95
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa500109(v=AX.60)
ms:contentKeyID: 36931889
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Fiscal year closing checklist 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

At the end of a fiscal year, you must prepare your accounts for the next fiscal year and close the current fiscal year. Requirements for this process differ, based on the laws and accounting practices of the country/region where your organization is located.

Use the following information to prepare for a new fiscal year and close the current fiscal year.


> [!NOTE]
> <P>We recommend that you contact your accountants or auditors to make sure that the accounts fulfill all legal requirements.</P>



1.  Verify the closing options that you have selected in the **General ledger parameters** form.

2.  If you are using Inventory management, complete the inventory closing process. For more information, see [Inventory close](inventory-close.md).

3.  Complete month-end and other period closings in all modules other than General ledger. These include foreign currency revaluations on unrealized transactions. For more information, see [Close periods in the general ledger](close-periods-in-the-general-ledger.md).

4.  Complete month-end and other period closings in General ledger and print financial reports for the month and quarter. For more information, see [Close the general ledger at month end](close-the-general-ledger-at-month-end.md).

5.  If your legal entity is a consolidation legal entity, complete steps 1 through 4 for each subsidiary, and set up the subsidiary accounts to consolidate data. If the data for the subsidiary legal entities is in a separate database, export the subsidiary data to use in a trial consolidation.
    
    To close the fiscal year for a subsidiary legal entity, see [Prepare a legal entity for use in the consolidation process](prepare-a-legal-entity-for-use-in-the-consolidation-process.md) and [Perform an online consolidation](perform-an-online-consolidation.md).

6.  In all modules other than General ledger, complete year-end closing activities that might create ledger postings. For example, process year-end depreciations in Fixed assets.

7.  Create the new fiscal year. For more information, see [Key tasks: Fiscal calendars, fiscal years, and periods](key-tasks-fiscal-calendars-fiscal-years-and-periods.md).

8.  In the **Ledger calendar** form, set the appropriate period status to **On hold** for the current fiscal year. For more information, see [Ledger calendar (form)](https://technet.microsoft.com/en-us/library/hh242506\(v=ax.60\)).

9.  Back up your legal entity’s data.

10. Make adjusting entries. Use the **Closing sheet** form to create and post all necessary adjustments. (Click **General ledger** \> **Periodic** \> **Fiscal year close** \> **Closing sheet**.) These include adjustments to taxes and write-offs.
    

    > [!NOTE]
    > <P>You can also post adjustments in the <STRONG>General journal</STRONG> form.</P>



11. Print final financial statements. For more information, see [Generate, print, and export a traditional financial statement](generate-print-and-export-a-traditional-financial-statement.md).

12. Print 1099 statements for vendors who require the statements. For more information, see [(USA) About United States tax 1099](usa-about-united-states-tax-1099.md).

13. Transfer opening balances for ledger accounts to a new fiscal year. For more information, see [Transfer opening balances to a new fiscal year](transfer-opening-balances-to-a-new-fiscal-year.md).

14. You can reset number sequences. (Click **Organization administration** \> **Common** \> **Number sequences** \> **Number sequences**.)

15. Print the final reports for the fiscal year. These include financial statements such as the operating statement and the balance sheet. Publish the statements as required by law. For more information, see [About traditional financial statements](about-traditional-financial-statements.md).

  


