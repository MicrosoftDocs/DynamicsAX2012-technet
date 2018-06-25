---
title: Carry forward general budget reservation information to a new fiscal year (Public sector)
TOCTitle: Carry forward general budget reservation information to a new fiscal year (Public sector)
ms:assetid: 571e4b1e-3063-445c-843d-49e0047328a0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn762312(v=AX.60)
ms:contentKeyID: 65205499
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- public sector
- year end
- year-end
- budget reservation
- Forms.BudgetReservationYearEndClose_PSN
- budget reservations
- general budget reservation
- general budget reservations
---

# Carry forward general budget reservation information to a new fiscal year (Public sector) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

For any general budget reservation that has not expired at the fiscal year-end, you can carry forward (roll over) the document to the new year. The carry-forward process creates all the accounting and budgeting entries to close the document in the current year and open the document in the new year.


> [!NOTE]
> <P>General budget reservations are available only if the <STRONG>Public Sector</STRONG> configuration key is selected and if Microsoft Dynamics AX 2012 R3 Cumulative Update 8 is installed with the following hotfix: KB3047235</P>



## Carry forward a general budget reservation to a new fiscal year

To process general budget reservations at year-end, use the following steps.

1.  Click **General ledger \> Periodic \> Fiscal Year close \> General budget reservation year-end process**.

2.  In the **General budget reservation year-end process** form, in the **Year-end option** list, select whether to carry forward budget for the reservation.

3.  Select the fiscal years for the **Closing parameters** and **Opening parameters**.

4.  Click the **Retrieve documents** button.

5.  In the query form that appears, enter the criteria to find the reservations you want to process and carry forward to the new year.

6.  Click **OK** to display the reservations in the **General budget reservation year-end process** form.

7.  To process the selected reservations, click **Process**. You can clear a reservation’s check box if you don’t want to process it.

8.  If you selected **Process and carry forward budget** in the **Year-end option** list, an InfoLog provides messages that list all the budget entries that were created and all the general budget reservations that were processed. Any document not processed because of an error is also listed.

## Reduce carry-forward budget in a new fiscal year

If you have enabled budget control, you can reduce carry-forward budget for any carry-forward general budget reservations that are finalized with a remaining balance. This ensures that prior-year funds are not spent on new-year purchases. If the **Reduce carry-forward budget** check box for your reservation type is enabled in the **General budget reservation type** form, then finalizing the document in the new fiscal year reduces the remaining document balance to zero and reduces any remaining carry-forward budget to zero.

## See also

[Finalize a general budget reservation (Public sector)](finalize-a-general-budget-reservation-public-sector.md)

[Set up General ledger year-end processes (Public sector)](set-up-general-ledger-year-end-processes-public-sector.md)

[About general budget reservations (Public sector)](about-general-budget-reservations-public-sector.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

