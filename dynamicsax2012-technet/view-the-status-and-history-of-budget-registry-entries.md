---
title: View the status and history of budget registry entries
TOCTitle: View the status and history of budget registry entries
ms:assetid: 5795c149-a2a0-4ff9-bba7-9e5c68615745
ms:mtpsurl: https://technet.microsoft.com/library/Hh208970(v=AX.60)
ms:contentKeyID: 36057333
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- actual versus budget inquiry
- budget control statistics
- budget register entry status
- statistics for budget control
- status of budget register entries
audience: Application User
ms.search.region: Global
---

# View the status and history of budget registry entries 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Budget register entries let you track and audit budget activities, and can be used with workflow and with budget control. You can view budget register entries, budget control statistics, and actual versus budget totals from the following list pages and forms:

  - **Budget register entries** (Click **Budgeting** \> **Common** \> **Budget register entries** \> **All budget register entries**.)

  - **Budget control statistics** (Click **Budgeting** \> **Inquiries** \> **Budget control statistics**.)

  - **Ledger - actual vs. budget inquiry** (Click **Budgeting** \> **Inquiries** \> **Actual vs. budget**.)

## View the status of budget register entries

You can view all of the budget register entries on the **Budget register entries** list page. You can select multiple **Draft** budget register entries and update the budget balances at the same time. You can also work with budget register entries that are submitted to workflow.

If you select or open a budget register entry that was submitted to workflow, a yellow information bar appears at the top of the **Budget register entries** list page and the **Budget register entry** form. This bar includes status information and options. Near the right side of the workflow status bar, you can click the **View workflow instructions** icon for any instructions that were included when the workflow was set up. For more information, see [Submit a document](submit-a-document.md) and [Workflow actions](workflow-actions.md).

The **Budget register entry status** field displays either **Draft** or **Completed**. The **Source document** field displays the identifier of the source document that a budget register entry originated from. For example, a **Transfer** budget register entry could have originated from a purchase order.

If budget control is turned on, view the icons that identify the result of budget checking. A red X indicates that the budget check failed, a yellow triangle indicates that the budget check passed with warnings, and a green check mark indicates that the budget check passed.

For more information, see [Create budget register entries](create-budget-register-entries.md) and [Budget registry entry (form)](https://technet.microsoft.com/library/hh227354\(v=ax.60\)).

## View budget control statistics

You can view the budget balances for a budget cycle and budget model from the **Budget control statistics** form.

1.  Click **Budgeting** \> **Inquiries** \> **Budget control statistics**.

2.  Select a budget cycle and enter other information for the inquiry.

3.  For additional details, select a line in the grid and then click one of the following buttons: **Actual expenditures**, **Revised budget**, **Encumbrances**, or **Pre-encumbrances**.

For more information, see [Budget control statistics (form)](https://technet.microsoft.com/library/hh242457\(v=ax.60\)).

## View actual versus budget amounts in an inquiry

The budget amounts that are displayed in the **Ledger - actual vs. budget inquiry** form are the sum of expense and revenue budget amounts for the financial dimension value that you select. The actual amounts are a sum of the debits and credits that were processed for the financial dimension value.

1.  Click **Budgeting** \> **Inquiries** \> **Actual vs. budget**.

2.  Select a budget model.

3.  Click **Select** to open a query form where you can enter criteria to specify a financial dimension value. Click **OK**.

4.  Enter information in the **Fiscal year** fields.

5.  Click **Update totals**.

For more information, see [Ledger - Actual vs. budgeted inquiry (form)](https://technet.microsoft.com/library/hh209598\(v=ax.60\)).


> [!NOTE]
> <P>If the <STRONG>Public Sector</STRONG> configuration key is selected and budget register entries for <STRONG>Preliminary budget</STRONG> or <STRONG>Apportionments</STRONG> are used, the processed budget amounts on these inquiries could include preliminary or apportioned budget amounts.</P>


  


