---
title: (RUS) Cash flow management
TOCTitle: (RUS) Cash flow management
ms:assetid: ef8cce87-635c-477b-b744-e29c16745f39
ms:mtpsurl: https://technet.microsoft.com/library/Mt282498(v=AX.60)
ms:contentKeyID: 67234753
author: tonyafehr
ms.date: 07/27/2015
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Cash flow management 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


This article explains how you can use Cash flow management for Russia for Microsoft Dynamics AX. This functionality is available if you have installed hotfix 3072850 for Russia (RUS).

The Cash flow management process involves the payment processing and includes the following tasks:

  - Configure Cash flow management parameters to support new functionality.

  - Perform a planned payment processing. Automatically creation and update of forecast transactions of forthcoming outpayments and inpayments based on purchase orders, sales orders and free text invoices.

  - Perform a payment request processing (including creation, update, approve) based on indebtedness to vendor, customer, worker and a prepayment requirements from vendors. This task is dependent on the Payment request configuration key being active.

  - Perform a payment schedule journal processing for mid-term liquidity planning (payment plan) and daily payment management (payment register). Cash deficit and surplus analysis through payment schedule sheet balancing (the simulation function).

  - Generate payments based on approved Payment register (a variety of payment schedule journal).

**Example**

In a centralized payments organization, there are many legal entities for operations, and each operating legal entity manages its own invoices payable information. Payment for all the operating legal entities are generated from a single legal entity, which in this example is called the Treasury legal entity. The Treasury department is responsible to monitor the flow of cash/liquidity movement across companies and cash positions, and prevent a corporate cash shortage in good time. The key goals of the Treasury department are:

  - Obtain an accurate liquidity/cash flow forecast and perform an analysis for mid-term/short-term horizon.

  - Manage payments on a daily basis using payment schedule journals.

  - Control the company’s cash position (shortage, surplus).

  - Maintain the company’s cash flows with centralized control.

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Parameters</p></td>
<td><p>Specify Cash flow management parameters (<strong>Cash and bank management</strong> &gt; <strong>Setup</strong> &gt; <strong>Cash and bank management parameters</strong>).</p></td>
</tr>
<tr class="even">
<td><p>Optional Setup</p></td>
<td><p>Create Centralized payments hierarchy. For more information, see <a href="create-or-modify-an-organization-hierarchy.md">Create or modify an organization hierarchy</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Data setup</p></td>
<td><ul>
<li><p>Specify payment priority code for party (vendor, customer, worker).</p></li>
<li><p>Create Payment request type (<strong>Cash and bank management</strong> &gt; <strong>Setup</strong> &gt; <strong>Cash flow management</strong> &gt; <strong>Payment request type</strong>).</p></li>
<li><p>Create and arrange Payment priority. (<strong>Cash and bank management</strong> &gt; <strong>Setup</strong> &gt; <strong>Cash flow management</strong> &gt; <strong>Payment priority</strong>)</p></li>
<li><p>Specify payment request types on Terms of payment form (<strong>Accounts payable</strong> &gt; <strong>Setup</strong> &gt; <strong>Payment</strong> &gt; <strong>Terms of payment</strong>).</p></li>
<li><p>Mark payment line of payment schedule as prepayment on Payment schedules form (<strong>Accounts payable</strong> &gt; <strong>Setup</strong> &gt; <strong>Payment</strong> &gt; <strong>Payment schedules</strong>).</p></li>
<li><p>Mark main account as remittance en route account on Liquidity form (<strong>General ledger</strong> &gt; <strong>Setup</strong> &gt; <strong>Posting</strong> &gt; <strong>Liquidity</strong>).</p></li>
<li><p>Specify Minimum cash balance for bank account (<strong>Cash and bank management</strong> &gt; <strong>Common</strong> &gt; <strong>Bank accounts</strong>).</p></li>
<li><p>Specify Minimum cash balance for cash account (<strong>Cash and bank management</strong> &gt; <strong>Common</strong> &gt; <strong>Cash accounts</strong>).</p></li>
<li><p>Specify Payment order requisites for purchase agreement (<strong>Accounts payable</strong> &gt; <strong>Common</strong> &gt; <strong>Purchase orders</strong> &gt; <strong>Purchase agreements</strong>).</p></li>
<li><p>Specify Payment order requisites for sales agreement (<strong>Accounts receivable</strong> &gt; <strong>Common</strong> &gt; <strong>Sales orders</strong> &gt; <strong>Sales agreements</strong>).</p></li>
<li><p>Create and specify payment schedule journals for two types: payment plan and payment register (<strong>Cash and bank management</strong> &gt; <strong>Setup</strong> &gt; <strong>Cash flow management</strong> &gt; <strong>Payment schedule journal names</strong>).</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Workflow setup</p></td>
<td><p>Create Cash flow management workflows (<strong>Cash and bank management</strong> &gt; <strong>Setup</strong> &gt; <strong>Cash and bank management workflows</strong> &gt; <strong>Payment request approval</strong> and <strong>Payment schedule journal approval</strong>.</p></td>
</tr>
</tbody>
</table>


## Process planned payments

Planned payments are a source for cash flow forecast. In addition, planned payment with an indicator Prepayment is a basis for prepayment generation if the payment request functionality is used.

To process planned payments, follow these steps:

1.  Click the **Invoice** \> **Bill** \> **Planned payments** button on the All purchase orders form, All sales orders form or All free text invoices form to generate or validate planned payments.

2.  Use the periodic operation Calculate planned payments (**Cash and bank management** \> **Periodic** \> **Cash flow management** \> **Calculate planned payments**) to generate or recalculate planned payments for selected sources and legal entities.

## Process payment requests

Payment requests are a main source for cash flow forecast and payments generation. Payment request can be created manually or automatically based on posted vendor invoices, customer return invoices, prepayment planned payments.

To process payment requests, follow these steps:

1.  Use the All payment requests form (**Cash and bank management** \> **Common** \> **Payment requests** \> **All payment requests**) to create, update, copy, cancel, hold, split payment requests.

2.  Click **Purchase** \> **Generate** \> **Payment requests** on the **All purchase orders** form, **All sales orders** form or **All free text invoices** form to generate payment requests. Click **Purchase** \> **Journals** \> **Payment requests** to validate associated with selected source payment requests.

3.  Use the periodic operation Create payment requests (**Cash and bank management** \> **Periodic** \> **Cash flow management** \> **Create payment requests**) to generate payment requests for selected sources and legal entities.

4.  Use the periodic operation Update payment requests (**Cash and bank management** \> **Periodic** \> **Cash flow management** \> **Update payment requests**) to update payment requests for selected sources and legal entities.

## Process payment schedule journals

Payment schedule journals represent aggregated information for cash flow analysis, simulation and payments creation. They collect information from different sources.Payment schedule journals have two types:

  - **Payment plan** – This journal type is intended for cash flow forecast in medium/short horizon.

  - **Payment register** – This journal type is used or daily payment management and intended for payments generation.

To process payment schedule journals, follow these steps:

1.  Create and calculate new payment schedule journal (**Cash and bank management** \> **Journals** \> **Payment schedule journal**). Click **New** on the **Payment schedule journal** form and specify journal parameters. Click **Calculate** on the **Payment schedule journal** form.

2.  Click **Lines** on the **Payment schedule journal** form to validate journal lines. Click **Edit beginning balance** on the **Payment schedule journal lines** form to validate and change a beginning balance of particular journal.

3.  Click **Payment schedule** on the **Payment schedule journal** form to generate payment schedule sheet. Double click on amount for journal data source equal to Payment request (if payment request configuration key is active) or Accounts payable \> Accounts receivable (if payment request configuration key is inactive) opens sources of this amount. Right click a mouse and click operation Change payment sources to make changes in coming payments.

4.  Click **Functions** \> **Apply changes** or **Revert changes** on the **Payment schedule journal** form to confirm or reject changes in this journal.

5.  Click **Confirm** on the **Payment schedule journal** form to confirm payment schedule journal.

6.  Click the **Functions** \> **Generate payments** button on the **Payment schedule journal** form for journal with type **Payment register** to generate vendor or customer payment journals based on confirmed payment schedule journal.

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Configuration keys</strong></p></td>
<td><p><strong>Cash flow management</strong></p>
<p><strong>Payment request</strong> (optional)</p></td>
</tr>
<tr class="even">
<td><p><strong>Security duties</strong></p></td>
<td><p>CFMConfigure</p>
<p>CFMExtendedMaintain</p>
<p>CFMGeneralMaintain</p>
<p>CFMGeneralView</p>
<p>CFMPaymentGeneration</p>
<p>CFMPaymentRequestView</p>
<p>CFMPaymScheduleJourMaintain</p>
<p>CFMPaymScheduleJourView</p>
<p>CFMPeriodicMaintain</p></td>
</tr>
<tr class="odd">
<td><p><strong>Security privileges</strong></p></td>
<td><p>CFMAnalyticEdit</p>
<p>CFMAnalyticView</p>
<p>CFMJournalApproveWorkflow</p>
<p>CFMJournalPost</p>
<p>CFMJournalSetup</p>
<p>CFMJournalUpdate</p>
<p>CFMJournalView</p>
<p>CFMPaymentJournalCreate</p>
<p>CFMPaymentPriorityMaintain</p>
<p>CFMPaymentPriorityView</p>
<p>CFMPaymentRequestCreate</p>
<p>CFMPaymentRequestCreate_FTI</p>
<p>CFMPaymentRequestCreate_PO</p>
<p>CFMPaymentRequestCreate_SO</p>
<p>CFMPaymentRequestMaintain</p>
<p>CFMPaymentRequestOrigin</p>
<p>CFMPaymentRequestTypeMaintain</p>
<p>CFMPaymentRequestTypeView</p>
<p>CFMPaymentRequestUpdateFromSource</p>
<p>CFMPaymentRequestUpdFromSourcePeriodic</p>
<p>CFMPaymentRequestView</p>
<p>CFMPaymentRequestView_CustTrans</p>
<p>CFMPaymentRequestView_FTI</p>
<p>CFMPaymentRequestView_PO</p>
<p>CFMPaymentRequestView_SO</p>
<p>CFMPaymentRequestView_VendTrans</p>
<p>CFMPaymentRequestWFCancel</p>
<p>CFMPaymentRequestWFSubmit</p>
<p>CFMPaymentRequestWorkFlow</p>
<p>CFMPlannedPaymentUpdate</p>
<p>CFMPlannedPaymentView</p>
<p>CFMPRPeriodicCreate</p></td>
</tr>
</tbody>
</table>

  


