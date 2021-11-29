---
title: About cash flow in Project control
TOCTitle: About cash flow in Project control
ms:assetid: 097329d0-1a29-45b9-adb9-bc7f72f73deb
ms:mtpsurl: https://technet.microsoft.com/library/Gg230696(v=AX.60)
ms:contentKeyID: 42517316
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- cash flow
- project control
- cash in flow actuals
- cash in flow forecasting
audience: Application User
ms.search.region: Global
---

# About cash flow in Project control 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use cash flow monitoring to review both the forecasted cash flows and actual cash flows of a project. You can review cash flows while a project is in progress or you can view the cash flows of a completed project.

By monitoring cash flows, you can evaluate a single project, use the reports to view multiple projects, and transfer project cash flows to the cash flow forecasts in the general ledger.

This topic contains examples that describe setting up forecasted and actual cash inflows and outflows.

## Cash inflow forecasting

Based on what you define in the **Project management and accounting parameters** form and the **Project contracts** form, you can forecast the cash inflows of a selected project. For example, if the project date is March 5, 2012, and you invoice on March 31, 2012, you can forecast the due date and the expected sales-payment date.

The following assumptions apply to this example:

  - **Project date** – March 5, 2012.

  - **Invoice date** – March 31, 2012. This date is determined when you set up invoice frequency in the **Project contracts** form. In this example, you set the invoice frequency to the current month. This means that all transactions that are posted in the month of March are invoiced on the last day of the month.

  - **Due date** – April 14, 2012. This date is determined by the terms of payment that you selected in the **Project contracts** form for this project. For example, you selected payment terms of 14 days. The 14 days are added to the invoice date. This results in a due date of April 14, 2012.

  - **Expected sales payment date** – April 27, 2012. This date is determined by adding the number of days you enter in the **General buffer days** field in the **Project management and accounting parameters** form to the number of days in the **Individual buffer days** field in the **Project contracts** form, and then adding the total to the number of days in the **Due date** field. For example, you select three days in the **General buffer days** field and 10 days in the **Individual buffer days** field. A total of 13 days is added to the due date to determine the expected sales payment date.

The general buffer days can either replace the individual buffer days or be added to the individual buffer days. If you are using the general buffer days as a replacement, enter the average number of days between the due date and the actual payment date for customers.

If you want to add the general buffer days to the individual buffer days, in the **General buffer days** field, enter your estimate of the number of days between when the payment is sent from the customer and when the payment is received by your organization.

Set up individual buffer days in the **Project contracts** form. The days are calculated based on both the sales invoice due date and your organization’s experience with a customer's payment pattern.

## Cash inflow actual

Actual cash inflow is like forecasting except that you can begin your calculations from the first invoice date. For example:

  - **Invoice date** – March 2, 2012.

  - **Due date** – March 16, 2012. The terms of payment are set to 14 days.

  - **Expected sales payment date** – March 29, 2012. This includes three general buffer days and 10 individual buffer days.

## Cost forecasting

Based on the days that you define in the **Project management and accounting parameters** form, the cost payment date can differ from the project date. When this is the case, the cost payment date is calculated by adding the number of days from the project date to the number of days in the terms of payment that you selected in the **Project management and accounting parameters** form.

For example, the project date of the transaction is March 5, 2012, and you set the following terms of payment:

  - Hours - Current month (M)

  - Expenses - 14 days (D14)

  - Items - 30 days (D30)

Based on these settings, the cost payment date is as follows for each transaction type:

  - Hours - March 31, 2012, which is the last day of the selected month.

  - Expenses - March 19, 2012, which is 14 days after the date of the transaction.

  - Items - April 4, 2012, which is 30 days after the date of the transaction.


> [!NOTE]
> <P>The due date for a purchase order is not determined by the setup in the <STRONG>Project management and accounting parameters</STRONG> form. Instead, the due date is based on the vendor transaction when the project purchase order is created.</P>



The cost payment date is not calculated based on buffer days. When a project is finished and all costing and invoicing is complete, both the cost and the sales are posted to the profit and loss accounts.

When all sales and vendor invoices are completed, you can view the relationship between the **Cash flow** form and the **Project statements** form.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Cash flow</strong> form</p></th>
<th><p><strong>Project statements</strong> form</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Cash inflows</strong></p></td>
<td><p><strong>Revenue</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Cash outflows</strong></p></td>
<td><p><strong>Total cost</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Net cash flows</strong></p></td>
<td><p><strong>Gross margin</strong></p></td>
</tr>
</tbody>
</table>


## See also

[Project management and accounting parameters (form)](https://technet.microsoft.com/library/aa599440\(v=ax.60\))

[Project contracts (form)](https://technet.microsoft.com/library/aa586038\(v=ax.60\))

[Project statements (form)](https://technet.microsoft.com/library/aa552521\(v=ax.60\))

  


