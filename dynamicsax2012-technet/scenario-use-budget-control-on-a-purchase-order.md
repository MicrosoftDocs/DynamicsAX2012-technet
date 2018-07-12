---
title: 'Scenario: Use budget control on a purchase order'
TOCTitle: 'Scenario: Use budget control on a purchase order'
ms:assetid: add8a26f-13ed-4d4f-92e4-9a5d093cfb02
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242700(v=AX.60)
ms:contentKeyID: 36058931
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- budget control statistics
- budget control and purchase orders
- purchase orders and budget control
audience: Application User
ms.search.region: Global
---

# Scenario: Use budget control on a purchase order 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This scenario explains how to use budget control when you create a purchase order. In this scenario, the Department and Cost center dimensions were defined for budget control and purchase orders were enabled for budget control. The budget control configuration has been activated and turned on. For more information, see [Set up budget control](set-up-budget-control.md).

You could start a similar scenario by creating a purchase requisition and converting it to a purchase order. For more information, see [Create and maintain purchase orders](create-and-maintain-purchase-orders.md).

A budget register entry was submitted to establish a budget amount for Department 010 and Cost center 0101. For more information, see [Create budget register entries](create-budget-register-entries.md). You can view the budget balances for the department and cost center before you create the purchase order. In the **Budget control statistics** form, you would select the budget cycle and financial dimension values for the department and cost center. For more information, see [View the status and history of budget registry entries](view-the-status-and-history-of-budget-registry-entries.md).

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  On the **Action Pane**, click **Purchase order** to create a purchase order.

3.  Select a vendor account.

4.  On the **General** FastTab, verify the accounting date. The account date determines the fiscal period for the budget check. The current date is the default date, but you can change this.
    
    In the budget control configuration, the budget control interval was set to **Fiscal year** so that the budget amounts for the fiscal year aggregate for the budget check.

5.  Add a line to the purchase order and enter information in the required fields, such as **Procurement category**, **Quantity**, and **Unit price**.

6.  Click **Financials** \> **Distribute amounts** and enter the accounting distributions in the **Ledger account** field. For example, you might enter 606300-010-0101.

7.  Close the **Accounting distributions** form.
    
    If the **Enable budget control for line item on entry** check box was selected in the **Select source documents** area of the **Budget control configuration** form, a budget check icon is displayed on the purchase order line. If the **Enable budget control for line item on entry** check box was not selected, you can click **Financials** \> **Perform budget checking** to perform a budget check on the whole purchase order.
    

    > [!NOTE]
    > <P>Budget checking is performed on all lines when the purchase order is confirmed and when the purchase order is submitted to a workflow, and then again when the purchase order is approved in a workflow.</P>



8.  Click **Budgeting** \> **Inquiries** \> **Budget control statistics**. Select the budget cycle and the financial dimension values for the inquiry. For this example, you would select 010-0101 as the dimension values.
    
    The amount of the purchase order line is displayed in the **Budget reservations for encumbrances** field in the grid.

9.  Click **Encumbrances**.
    
    The **Budget reservations for encumbrances** form shows detailed information about the purchase order transaction. This includes the status, which is **Draft**. After the purchase order is confirmed, the status changes to **Confirmed**.
    
    When the invoice is received and entered, the fields in the **Relieved amounts this period** grid in the **Budget reservations for encumbrances** form are updated with information from the invoice. A budget reservation for the actual expenditure is also created.

  


