---
title: "What's new: Public sector features"
TOCTitle: Public sector features
ms:assetid: 7b00bf89-5448-433c-98f9-14e82c39d027
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527148(v=AX.60)
ms:contentKeyID: 59623277
ms.date: 03/27/2015
mtps_version: v=AX.60
f1_keywords:
- features
- Public sector
- feature
- Public sector feature
- Public sector features
---

# What's new: Public sector features 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The following features have been added to the [Public sector](public-sector.md) feature area. To learn more, see the tables that apply to your version of the product.

## What’s new in Microsoft Dynamics AX 2012 R2

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Improvements to Public sector Role Centers and business intelligence content</p>
<p></p></td>
<td><p>The following Public sector Role Centers were updated: Accounts Receivable Administrator, Finance Director, Accounting Manager, and Accountant. You can now categorize Role Centers by the type of role: Strategic, Tactical, or Operational. The key performance indicators (KPIs) and organization performance indicators on Role Centers can now be easily modified, and can report variances and percentage of goal measurements. Chart rendering was improved, and an organization performance indicator to track the spendable balance by fund was added.</p></td>
</tr>
<tr class="even">
<td><p>Budget analysis inquiry (Public sector)</p>
<p></p></td>
<td><p>In Microsoft Dynamics AX 2012 R2, public sector customers can display revenues and expenditures by financial dimension, by using a combination of data from budget register entries, the general ledger, and budget control. Revised budgets, actual expenditures, encumbrances, pre-encumbrances, and a discrete breakout of carry-forward amounts are available. Detail transactions can be displayed for a selected financial dimension for each budgeted amount, such as the original budget or revisions.</p>
<p>For more information, see <a href="budget-control-cube-budgetcontrolcube-for-microsoft-dynamics-ax-2012-r2-and-r3.md">Budget control cube (BudgetControlCube) for Microsoft Dynamics AX 2012 R2 and R3</a>.</p></td>
</tr>
</tbody>
</table>


## What’s new in cumulative update 7 for Microsoft Dynamics AX 2012 R2

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Regulatory features for France</p></td>
<td><p>The primary address of the organization no longer has to be in France if you want to use the French public sector accounting rules. Instead, you must select the <strong>Use French public sector accounting rules</strong> check box in the <strong>Budget parameters</strong> form. Organizations that don’t use French public sector accounting rules should disable the <strong>French regulatory</strong> license configuration key (under the <strong>Public Sector</strong> license configuration key). By disabling this license configuration key, you remove any unusable menu items when the <strong>Use French public sector accounting rules</strong> check box is cleared.</p>
<p>In versions of Microsoft Dynamics AX 2012 before cumulative update 7, only the <strong>Public Sector</strong> configuration key must be selected. However, the primary address of the legal entity must be in France.</p></td>
</tr>
<tr class="even">
<td><p>Dispose of fixed assets</p></td>
<td><p>You can now dispose of more than one fixed asset at the same time. This feature saves time and reduces the risk of errors.</p>
<p>For more information, see <a href="about-fixed-asset-disposal.md">About fixed asset disposal</a>.</p></td>
</tr>
</tbody>
</table>


## What’s new in Microsoft Dynamics AX 2012 R3

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Publishing a request for quotation (RFQ)</p></td>
<td><p>You can publish an RFQ to the public Vendor portal so that unregistered vendors can view it. All lines of the RFQ are also sent to the vendors that are selected in the RFQ.</p>
<p>For more information, see <a href="create-a-request-for-quotation.md">Create a request for quotation</a>.</p></td>
</tr>
<tr class="even">
<td><p>Viewing details of closed RFQs</p></td>
<td><p>Public sector vendors can view all open and closed purchase orders, RFQs, and their details. These details include scoring information and award notes about bids that are accepted.</p>
<p>For more information, see <a href="bid-on-a-request-for-quotation.md">Bid on a request for quotation</a>.</p></td>
</tr>
</tbody>
</table>


## What’s new in Microsoft Dynamics AX 2012 R3 Cumulative Update 8

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Creating one or more one-time vendor accounts at the same time as creating invoices for those vendors</p></td>
<td><p>When approval or a contract in the form of a purchase order is not required, you can quickly create invoices at the same time as creating records for the vendors. You can generate an account for a vendor directly from the Invoice form. You can also import a CSV-formatted file of information for multiple one-time vendors and corresponding invoices, and create vendor accounts and accompanying invoices.</p>
<p>For more information, see <a href="create-a-one-time-vendor-and-invoice-public-sector.md">Create a one-time vendor and invoice (Public sector)</a> and <a href="import-and-create-one-time-vendors-and-invoices-public-sector.md">Import and create one-time vendors and invoices (Public sector)</a>.</p></td>
</tr>
<tr class="even">
<td><p>Permitting only invited vendors to bid on an RFQ on the Vendor portal</p></td>
<td><p>You can specify that a published request for quotation having a specific solicitation type is visible only to vendors who are included on the RFQ.</p>
<p>For more information, see <a href="create-and-use-a-solicitation-type.md">Create and use a solicitation type</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Controlling which details vendors see about closed RFQs on the Vendor portal</p></td>
<td><p>You can specify which elements to allow vendors to see on the <strong>Closed requests for quotations</strong> page.</p>
<p>For more information, see <a href="create-and-use-a-solicitation-type.md">Create and use a solicitation type</a>.</p></td>
</tr>
<tr class="even">
<td><p>Publishing an RFQ to the Vendor portal and sending it to a vendor at the same time</p></td>
<td><p>The <strong>Send</strong> button on the RFQ <strong>Action Pane</strong> has been replaced by a <strong>Send and publish to Vendor portal</strong> button, allowing one-step distribution to vendors.</p>
<p>For more information, see <a href="create-a-request-for-quotation.md">Create a request for quotation</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Streamlining the Vendor portal signup process</p></td>
<td><p>Vendor users can search to see if their organization is already registered, and add themselves to that record. This can streamline the signup process.</p></td>
</tr>
</tbody>
</table>


## What’s new in Microsoft Dynamics AX 2012 R3 Cumulative Update 8 with hotfix KB3047235

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What’s new</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Regulatory features updated</p></td>
<td><p>The <strong>Budget parameters</strong> form now includes check boxes for the public sector regulatory documents <strong>General budget reservations</strong> and <strong>Commitments (France)</strong>.</p>
<p>For more information, see <a href="about-general-budget-reservations-public-sector.md">About general budget reservations (Public sector)</a>.</p></td>
</tr>
<tr class="even">
<td><p>(Public sector) General budget reservation source document added for planned purchasing</p></td>
<td><p>General budget reservations are documents often used by public sector entities to set aside or reserve budgeted funds so that they are not available for other purposes. Typically these reservations are made before any vendors have been selected for the purchase.</p>
<p>For more information, see the following public sector topics:</p>
<ul>
<li><p><a href="about-general-budget-reservations-public-sector.md">About general budget reservations (Public sector)</a></p></li>
<li><p><a href="set-up-general-budget-reservation-rules-and-reservation-types-public-sector.md">Set up general budget reservation rules and reservation types (Public sector)</a></p></li>
<li><p><a href="add-modify-or-delete-a-general-budget-reservation-type-public-sector.md">Add, modify, or delete a general budget reservation type (Public sector)</a></p></li>
<li><p><a href="create-a-general-budget-reservation-public-sector.md">Create a general budget reservation (Public sector)</a></p></li>
<li><p><a href="view-modify-delete-or-cancel-a-general-budget-reservation-public-sector.md">View, modify, delete, or cancel a general budget reservation (Public sector)</a></p></li>
<li><p><a href="relieve-a-general-budget-reservation-public-sector.md">Relieve a general budget reservation (Public sector)</a></p></li>
<li><p><a href="finalize-a-general-budget-reservation-public-sector.md">Finalize a general budget reservation (Public sector)</a></p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>General budget reservation workflow</p></td>
<td><p>For public sector, you can create a specific workflow for approving general budget reservations, and add a general budget reservation task to a purchase requisition workflow. For more information, see the following topics:</p>
<ul>
<li><p><a href="set-up-general-budget-reservation-workflows-public-sector.md">Set up general budget reservation workflows (Public sector)</a></p></li>
<li><p><a href="submit-a-general-budget-reservation-to-workflow-public-sector.md">Submit a general budget reservation to workflow (Public sector)</a></p></li>
<li><p><a href="create-a-purchase-order.md">Create a purchase order</a></p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Project accounting</p></td>
<td><p>For the public sector, if you use project accounting, you can include references to your project in general budget reservations. This can affect budgeting, committed costs, and funding-source reservations and consumption. For more information, see <a href="use-project-accounting-with-general-budget-reservations-public-sector.md">Use project accounting with general budget reservations (Public sector)</a>.</p></td>
</tr>
</tbody>
</table>

  


