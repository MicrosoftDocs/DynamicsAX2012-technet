---
title: (CHN) Validate the closing or stopping of a fiscal period
TOCTitle: (CHN) Validate the closing or stopping of a fiscal period
ms:assetid: be9959cf-7804-4349-b7be-264c08df7743
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664105(v=AX.60)
ms:contentKeyID: 49384691
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- China
- CHN
- Validity check
- Validity check to end or close an accounting period
- CN - 00013
---

# (CHN) Validate the closing or stopping of a fiscal period 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can close, stop, or open fiscal periods that are included in a fiscal calendar. When you modify the calendar status for a selected fiscal period, a validity check is run, based on the conditions that are specified in the **Validation checklist** form. After successful validation, the fiscal period statuses are updated to **Closed** or **On hold** in the **Ledger calendar** form.

The following buttons are available in the **Ledger calendar** form only when the **Extended monthly closing check** check box is selected in the **General ledger parameters** form.

  - **Close period**

  - **Stop period**

  - **Open fiscal period**

## Close a fiscal period

You must run a validity check for fiscal periods that you close. You can set up the validation checklist with checklist items in the **Validation checklist** form. When validity checks are run, only the checklist items that have a status of **Warning** or **Stop** are validated. You cannot post transactions to a fiscal period that has a status of **Closed**.

1.  Click **General ledger** \> **Setup** \> **Ledger**. Click **Ledger calendar**.

2.  In the left pane, expand a fiscal year to select a fiscal period to close.

3.  On the **Periods** FastTab, select a fiscal period with a status of **On hold** or **Open**, and then click **Close period** to open the **Period closing checklist** wizard.

4.  The **Period closing checklist** wizard displays nodes that contain checklist links. To run a validity check, expand the nodes, and click the links in the order in which they appear.

The status of the fiscal period changes to **Closed** in the **Ledger calendar** form after successful validation.

## Stop a fiscal period

When you set up the monthly stop for a fiscal period, you can choose whether to run the validity check. If you set up a validity check, only checklist items with a status of **Warning** or **Stop** in the **Validation checklist** form are validated. To stop a fiscal period without running a validity check, you must select **No validation** for all of the checklist items in the **Validation checklist** form. You cannot create a journal for a period that has a status of **On hold**, but you can post during the stopped period.

1.  Click **General ledger** \> **Setup** \> **Ledger**. Click **Ledger calendar**.

2.  In the left pane, expand a fiscal year to select a fiscal period to stop or put on hold.

3.  On the **Periods** FastTab, select a fiscal period with a status of **Open**, and then click **Stop period** to open the **Stop period checklist** wizard.

4.  The **Stop period checklist** wizard displays nodes that contain checklist links. Expand the nodes, and click the links in the order in which they appear to run a validity check.

After the validation process is completed for all of the checklist items, the status of the selected fiscal period changes to **On hold** in the **Ledger calendar** form.

## Reopen a stopped fiscal period

Only a stopped fiscal period can be opened. You cannot reopen a fiscal period that has a status of **Closed**. There is no validity check when you open fiscal periods that have a status of **On hold**.

1.  Click **General ledger** \> **Setup** \> **Ledger**. Click **Ledger calendar**.

2.  In the left pane, expand a fiscal year to select the fiscal period to open.

3.  Select a fiscal period with a status of **On hold**, and then click **Open fiscal period** to open the **Open fiscal period** form.

4.  Click **OK** to reopen the fiscal period. The status of the fiscal period changes to **Open** in the **Ledger calendar** form.

## See also

[(CHN) Ledger calendar (modified form)](https://technet.microsoft.com/en-us/library/jj664094\(v=ax.60\))

[(CHN) Validation checklist (form)](https://technet.microsoft.com/en-us/library/jj664060\(v=ax.60\))

[Key tasks: Fiscal calendars, fiscal years, and periods](key-tasks-fiscal-calendars-fiscal-years-and-periods.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

