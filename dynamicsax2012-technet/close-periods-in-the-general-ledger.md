---
title: Close periods in the general ledger
TOCTitle: Close periods in the general ledger
ms:assetid: a361185b-dafe-493b-ba42-47a027dc68e7
ms:mtpsurl: https://technet.microsoft.com/library/Aa571842(v=AX.60)
ms:contentKeyID: 36058807
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Close periods in the general ledger 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The following information describes how to complete closing procedures at the end of a period. You are not required to complete all of the following steps. The modules that your legal entity uses and the options that are selected in the **License configuration** and **Security privileges** forms might prevent you from completing some steps.

To close one or more modules, use the **Ledger calendar** form. Click **General ledger** \> **Setup** \> **Ledger**. Click **Ledger calendar**. In the left pane, select a fiscal year and period. On the **Module access level** FastTab, select the module to close. In the **Access level** field, select **None**.


> [!NOTE]
> <P>Complete General ledger month-end procedures after you have completed other procedures that might generate ledger transactions. Also, you cannot close a fiscal period until all invoices for the period are posted and the <STRONG>Journalize finalized product receipt</STRONG> batch job in the <STRONG>Batch job</STRONG> form is run. For more information, see <A href="set-up-parameters-for-the-journalized-finalized-product-receipt-batch-job.md">Set up parameters for the Journalized finalized product receipt batch job</A>.</P>



1.  Post all open journal vouchers for the month in all relevant modules.

2.  Complete any batch posting routines in Accounts receivable and Accounts payable.

3.  Complete the following processes:
    
    1.  Calculate interest. See [Interest calculation (class form)](https://technet.microsoft.com/library/aa600712\(v=ax.60\)).
    
    2.  Create collection letters. See [Creation of collection letter (class form)](https://technet.microsoft.com/library/aa616523\(v=ax.60\)).
    
    3.  Process foreign currency revaluations in the **Foreign currency revaluation** form. See [Perform a foreign currency revaluation](perform-a-foreign-currency-revaluation.md).
    
    4.  Process payment jobs in Accounts receivable and Accounts payable.

4.  Complete closing and adjustment processes in Inventory management. See [Closing and adjustment (form)](https://technet.microsoft.com/library/aa553192\(v=ax.60\)).

5.  Post and adjust project transactions. See [Adjust transactions](adjust-transactions.md).

6.  Complete monthly General ledger procedures. See [Close the general ledger at month end](close-the-general-ledger-at-month-end.md).

You can also print reports, such as account statements and aging reports.

## See also

[Close the general ledger at month end](close-the-general-ledger-at-month-end.md)

  


