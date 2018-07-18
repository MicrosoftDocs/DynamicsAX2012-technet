---
title: Finalize a general budget reservation (Public sector)
TOCTitle: Finalize a general budget reservation (Public sector)
ms:assetid: 41bae344-b447-45cb-b07e-5301236929d3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn792455(v=AX.60)
ms:contentKeyID: 65205497
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- public sector
- Forms.LedgerFund
- year-end
- finalization
- budget reservation
- Forms.BudgetReservationYearEndClose_PSN
- budget reservations
- general budget reservation
- general budget reservations
- finalized budget reservations
- finalized general budget reservations
audience: Application User
ms.search.region: Denmark, France
---

# Finalize a general budget reservation (Public sector) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

You can close or finalize a completed or expired general budget reservation at the end of the year.


> [!NOTE]
> <P>General budget reservations are available only if the <STRONG>Public Sector</STRONG> configuration key is selected and if Microsoft Dynamics AX 2012 R3 Cumulative Update 8 is installed with the following hotfix: KB3047235</P>



## Finalize a general budget reservation

Use the following steps to finalize a general budget reservation that has a remaining balance at year-end. For example, if a general budget reservation is available only through the end of the fiscal year and should not get carried forward to the new fiscal year, you can finalize it at year-end and reduce the remaining balance to zero.

1.  Click **Budgeting \> Common \> General budget reservations \> All general budget reservations**.

2.  Open the reservation that you want to finalize.

3.  In the details form, do one of the following:
    
      - To finalize the whole budget reservation, on the **Action Pane**, click **Finalize**.
    
      - To finalize one line only, select it, and then, on the **General budget reservation lines** FastTab, on the Action strip, click **Finalize line**.
    
      - To finalize multiple lines, select them, and then, on the **General budget reservation lines** FastTab, on the Action strip, click **Finalize line**.

4.  Click **Close**. Accounting and budget-control entries are posted.

## Set fund-level overrides for general budget reservation year-end processing

The year-end processing option that you select in the **Year-end option** list (see the preceding procedure) is used for all of the general budget reservations that you select. However, you can override this selection and use a different year-end processing option for specific funds that you select in the **funds** form. For more information, see [Funds (form) (Public sector)](https://technet.microsoft.com/en-us/library/hh208514\(v=ax.60\)).

To override the default year-end process for general budget reservations, use the following steps.

1.  Click **General ledger** \> **Setup** \> **Fund** \> **Funds**.

2.  In the **Fund** form, select the fund number or name that you want.

3.  Under **Purchase order year-end process**, select the **Override selected year-end option** check box. This setting is shared between purchase orders and general budget reservations.

4.  Under **Purchase order year-end process**, in the **Year-end option** list, select the process you want.

## See also

[Set up General ledger year-end processes (Public sector)](set-up-general-ledger-year-end-processes-public-sector.md)

[Carry forward general budget reservation information to a new fiscal year (Public sector)](carry-forward-general-budget-reservation-information-to-a-new-fiscal-year-public-sector.md)

[About general budget reservations (Public sector)](about-general-budget-reservations-public-sector.md)

  


