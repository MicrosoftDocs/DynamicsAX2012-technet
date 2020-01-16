---
title: Default Analysis Services roles
TOCTitle: Default Analysis Services roles
ms:assetid: 7a5d0d7d-d3fd-4379-a40f-0f89887aacd1
ms:mtpsurl: https://technet.microsoft.com/library/Hh404117(v=AX.60)
ms:contentKeyID: 36956785
author: Khairunj
ms.date: 07/16/2014
mtps_version: v=AX.60
---

# Default Analysis Services roles 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Security for analysis cubes is set up independently from security for Microsoft Dynamics AX. To grant users access to cubes, you must assign the users to database roles in Microsoft SQL Server Analysis Services.

When you deploy the cubes that are included with Microsoft Dynamics AX, default roles are created in the database where you deploy the cubes. This topic lists the default roles that are created. Notice that these roles correspond to security roles in Microsoft Dynamics AX. For example, if you assign a user to the **Accountant** role in Microsoft Dynamics AX, you should assign that same user to the **Accountant** role in Analysis Services.


> [!IMPORTANT]
> <P>Keep the following information in mind when assigning users to roles in Analysis Services:</P>
> <UL>
> <LI>
> <P>Role members have permission to view all data in the cubes that the role has access to. For example, if you assign a user to the <STRONG>Project supervisor</STRONG> role, that user will have access to all data in the Project accounting cube.</P>
> <LI>
> <P>The default roles that are created in Analysis Services are not synchronized with the security roles in Microsoft Dynamics AX. For example, if you modify the permissions of the <STRONG>Accountant</STRONG> role in Microsoft Dynamics AX, you do not affect the <STRONG>Accountant</STRONG> role in Analysis Services.</P></LI></UL>



<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><img src="images/Hh404117.TopicIcons_Conceptual(AX.60).png" title="Concepts" alt="Concepts" />
<p>Analysis Services roles for Microsoft Dynamics AX 2012 R3 cubes</p>
<p>Analysis Services roles for Microsoft Dynamics AX 2012 R2 cubes</p>
<p>Analysis Services roles for Microsoft Dynamics AX 2012 Feature Pack cubes</p>
<p>Analysis Services roles for Microsoft Dynamics AX 2012 cubes</p></td>
<td><img src="images/Dn507140.TopicIcons_Resources(AX.60).png" title="Resources" alt="Resources" />
<p><a href="security-and-protection-for-analytics.md">Security and protection for analytics</a></p>
<p><a href="grant-users-access-to-cubes.md">Grant users access to cubes</a></p></td>
</tr>
</tbody>
</table>


## Analysis Services roles for Microsoft Dynamics AX 2012 R3 cubes

The following Analysis Services projects are included with Microsoft Dynamics AX 2012 R3.

## Dynamics AX project

When you deploy the Analysis Services project named **Dynamics AX**, the following roles are created in the Analysis Services database where you deploy the cubes.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Analysis Services role</p></th>
<th><p>Cubes that the role has access to</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Accountant</p></td>
<td><p>Accounts payable cube</p>
<p>Accounts receivable cube</p>
<p>General ledger cube</p>
<p>Profit tax totals cube</p>
<p>Purchase cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Accounting manager</p></td>
<td><p>Accounts payable cube</p>
<p>Accounts receivable cube</p>
<p>Budget control cube</p>
<p>Budget plan cube</p>
<p>General ledger cube</p>
<p>Profit tax totals cube</p>
<p>Purchase cube</p>
<p>Retail cube</p>
<p>Sales cube</p>
<p>Trade allowance management cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Accounting payable manager</p></td>
<td><p>Purchase cube</p></td>
</tr>
<tr class="even">
<td><p>Accounting supervisor</p></td>
<td><p>Accounts payable cube</p>
<p>Accounts receivable cube</p>
<p>Budget control cube</p>
<p>Budget plan cube</p>
<p>General ledger cube</p>
<p>Profit tax totals cube</p>
<p>Purchase cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Accounts payable centralized payments clerk</p></td>
<td><p>Accounts payable cube</p>
<p>General ledger cube</p>
<p>Purchase cube</p></td>
</tr>
<tr class="even">
<td><p>Accounts payable clerk</p></td>
<td><p>Accounts payable cube</p>
<p>Expense management cube</p>
<p>General ledger cube</p>
<p>Purchase cube</p></td>
</tr>
<tr class="odd">
<td><p>Accounts payable manager</p></td>
<td><p>Accounts payable cube</p>
<p>Accounts receivable cube</p>
<p>Expense management cube</p>
<p>General ledger cube</p>
<p>Purchase cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Accounts payable payments clerk</p></td>
<td><p>Accounts payable cube</p>
<p>General ledger cube</p></td>
</tr>
<tr class="odd">
<td><p>Accounts receivable centralized payments clerk</p></td>
<td><p>Accounts receivable cube</p>
<p>General ledger cube</p></td>
</tr>
<tr class="even">
<td><p>Accounts receivable clerk</p></td>
<td><p>Accounts receivable cube</p>
<p>General ledger cube</p></td>
</tr>
<tr class="odd">
<td><p>Accounts receivable manager</p></td>
<td><p>Accounts payable cube</p>
<p>Accounts receivable cube</p>
<p>General ledger cube</p>
<p>Retail cube</p>
<p>Sales cube</p>
<p>Trade allowance management cube</p></td>
</tr>
<tr class="even">
<td><p>Accounts receivable payments clerk</p></td>
<td><p>Accounts receivable cube</p>
<p>General ledger cube</p></td>
</tr>
<tr class="odd">
<td><p>Budget clerk</p></td>
<td><p>General ledger cube</p></td>
</tr>
<tr class="even">
<td><p>Budget manager</p></td>
<td><p>Budget control cube</p>
<p>Budget plan cube</p>
<p>General ledger cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Buying agent</p></td>
<td><p>Purchase cube</p></td>
</tr>
<tr class="even">
<td><p>Chief executive officer</p></td>
<td><p>Accounts payable cube</p>
<p>Accounts receivable cube</p>
<p>Budget control cube</p>
<p>Budget plan cube</p>
<p>Environmental sustainability cube</p>
<p>Expense management cube</p>
<p>General ledger cube</p>
<p>Inventory value cube</p>
<p>Production cube</p>
<p>Project accounting cube</p>
<p>Purchase cube</p>
<p>Retail cube</p>
<p>Sales and marketing cube</p>
<p>Sales cube</p>
<p>Trade allowance management cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Chief financial officer</p></td>
<td><p>Accounts payable cube</p>
<p>Accounts receivable cube</p>
<p>Budget control cube</p>
<p>Budget plan cube</p>
<p>Expense management cube</p>
<p>General ledger cube</p>
<p>Human resources cube</p>
<p>Inventory value cube</p>
<p>Project accounting cube</p>
<p>Purchase cube</p>
<p>Retail cube</p>
<p>Sales cube</p>
<p>Trade allowance management cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Collections agent</p></td>
<td><p>Accounts receivable cube</p>
<p>General ledger cube</p></td>
</tr>
<tr class="odd">
<td><p>Collections manager</p></td>
<td><p>Accounts receivable cube</p>
<p>General ledger cube</p></td>
</tr>
<tr class="even">
<td><p>Compensation and benefits manager</p></td>
<td><p>Human resources cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Compliance manager</p></td>
<td><p>Accounts payable cube</p>
<p>Accounts receivable cube</p>
<p>Budget control cube</p>
<p>Budget plan cube</p>
<p>General ledger cube</p>
<p>Purchase cube</p>
<p>Retail cube</p>
<p>Sales cube</p>
<p>Trade allowance management cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Cost accountant</p></td>
<td><p>Inventory value cube</p></td>
</tr>
<tr class="odd">
<td><p>Cost clerk</p></td>
<td><p>Inventory value cube</p></td>
</tr>
<tr class="even">
<td><p>Customer service representative</p></td>
<td><p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Dedicated sales representative</p></td>
<td><p>Trade allowance management cube</p></td>
</tr>
<tr class="even">
<td><p>Environmental manager</p></td>
<td><p>Environmental sustainability cube</p></td>
</tr>
<tr class="odd">
<td><p>Field service technician</p></td>
<td><p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Financial controller</p></td>
<td><p>Accounts payable cube</p>
<p>Accounts receivable cube</p>
<p>Budget control cube</p>
<p>Budget plan cube</p>
<p>Expense management cube</p>
<p>General ledger cube</p>
<p>Purchase cube</p>
<p>Retail cube</p>
<p>Sales cube</p>
<p>Trade allowance management cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Human resource assistant</p></td>
<td><p>Human resources cube</p>
<p>Payroll cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Human resource manager</p></td>
<td><p>Human resources cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Information technology manager</p></td>
<td><p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Manager</p></td>
<td><p>Human resources cube</p></td>
</tr>
<tr class="odd">
<td><p>Marketing coordinator</p></td>
<td><p>Trade allowance management cube</p></td>
</tr>
<tr class="even">
<td><p>Marketing cordinator</p></td>
<td><p>Sales and marketing cube</p></td>
</tr>
<tr class="odd">
<td><p>Marketing manager</p></td>
<td><p>Sales and marketing cube</p>
<p>Trade allowance management cube</p></td>
</tr>
<tr class="even">
<td><p>Marketing staffer</p></td>
<td><p>Trade allowance management cube</p></td>
</tr>
<tr class="odd">
<td><p>Materials manager</p></td>
<td><p>Inventory value cube</p></td>
</tr>
<tr class="even">
<td><p>Payroll administrator</p></td>
<td><p>Payroll cube</p></td>
</tr>
<tr class="odd">
<td><p>Payroll manager</p></td>
<td><p>Payroll cube</p></td>
</tr>
<tr class="even">
<td><p>Product designer</p></td>
<td><p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Production manager</p></td>
<td><p>Production cube</p></td>
</tr>
<tr class="even">
<td><p>Project accountant</p></td>
<td><p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Project manager</p></td>
<td><p>Expense management cube</p>
<p>Project accounting cube</p>
<p>Purchase cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Project supervisor</p></td>
<td><p>Project accounting cube</p></td>
</tr>
<tr class="odd">
<td><p>Purchasing manager</p></td>
<td><p>Accounts payable cube</p>
<p>Purchase cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Receiving clerk</p></td>
<td><p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Recruiter</p></td>
<td><p>Human resources cube</p></td>
</tr>
<tr class="even">
<td><p>Retail merchandising manager</p></td>
<td><p>Retail cube</p>
<p>Sales cube</p>
<p>Trade allowance management cube</p></td>
</tr>
<tr class="odd">
<td><p>Retail operations manager</p></td>
<td><p>Retail cube</p>
<p>Sales cube</p>
<p>Trade allowance management cube</p></td>
</tr>
<tr class="even">
<td><p>Retail store manager</p></td>
<td><p>Retail cube</p>
<p>Sales cube</p>
<p>Trade allowance management cube</p></td>
</tr>
<tr class="odd">
<td><p>Sales and marketing executive</p></td>
<td><p>Trade allowance management cube</p></td>
</tr>
<tr class="even">
<td><p>Sales manager</p></td>
<td><p>Retail cube</p>
<p>Sales and marketing cube</p>
<p>Sales cube</p>
<p>Trade allowance management cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Sales representative</p></td>
<td><p>Sales and marketing cube</p>
<p>Trade allowance management cube</p></td>
</tr>
<tr class="even">
<td><p>Super sales representative</p></td>
<td><p>Trade allowance management cube</p></td>
</tr>
<tr class="odd">
<td><p>Training manager</p></td>
<td><p>Human resources cube</p></td>
</tr>
<tr class="even">
<td><p>Treasurer</p></td>
<td><p>Accounts payable cube</p>
<p>General ledger cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Vendor account manager</p></td>
<td><p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Warehouse manager</p></td>
<td><p>Inventory value cube</p>
<p>Retail cube</p>
<p>Sales cube</p></td>
</tr>
</tbody>
</table>


## Demand Forecast project

When you deploy the Analysis Services project named **Demand Forecast**, the following roles are created in the Analysis Services database where you deploy the cubes.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Analysis Services role</p></th>
<th><p>Cubes that the role has access to</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Production manager</p></td>
<td><p>Demand forecast cube</p></td>
</tr>
<tr class="even">
<td><p>Production planner</p></td>
<td><p>Demand forecast cube</p></td>
</tr>
</tbody>
</table>


## Demand Forecast Accuracy project

When you deploy the Analysis Services project named **Demand Forecast Accuracy**, the following roles are created in the Analysis Services database where you deploy the cubes.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Analysis Services role</p></th>
<th><p>Cubes that the role has access to</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Production manager</p></td>
<td><p>Demand forecast accuracy cube</p></td>
</tr>
<tr class="even">
<td><p>Production planner</p></td>
<td><p>Demand forecast accuracy cube</p></td>
</tr>
</tbody>
</table>


## Analysis Services roles for Microsoft Dynamics AX 2012 R2 cubes

When you deploy the cubes that are included with Microsoft Dynamics AX 2012 R2, the following roles are created in the Analysis Services database where you deploy the cubes.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Analysis Services role</p></th>
<th><p>Cubes that the role has access to</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Accountant</p></td>
<td><p>Accounts payable cube</p>
<p>Accounts receivable cube</p>
<p>General ledger cube</p>
<p>Profit tax totals cube</p>
<p>Purchase cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Accounting manager</p></td>
<td><p>Accounts payable cube</p>
<p>Accounts receivable cube</p>
<p>Budget control cube</p>
<p>Budget plan cube</p>
<p>General ledger cube</p>
<p>Profit tax totals cube</p>
<p>Purchase cube</p>
<p>Retail cube</p>
<p>Sales cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Accounting supervisor</p></td>
<td><p>Accounts payable cube</p>
<p>Accounts receivable cube</p>
<p>Budget control cube</p>
<p>Budget plan cube</p>
<p>General ledger cube</p>
<p>Profit tax totals cube</p>
<p>Purchase cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Accounts payable centralized payments clerk</p></td>
<td><p>Accounts payable cube</p>
<p>General ledger cube</p>
<p>Purchase cube</p></td>
</tr>
<tr class="odd">
<td><p>Accounts payable clerk</p></td>
<td><p>Accounts payable cube</p>
<p>Expense management cube</p>
<p>General ledger cube</p>
<p>Purchase cube</p></td>
</tr>
<tr class="even">
<td><p>Accounts payable manager</p></td>
<td><p>Accounts payable cube</p>
<p>Accounts receivable cube</p>
<p>Expense management cube</p>
<p>General ledger cube</p>
<p>Purchase cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Accounts payable payments clerk</p></td>
<td><p>Accounts payable cube</p>
<p>General ledger cube</p></td>
</tr>
<tr class="even">
<td><p>Accounts receivable centralized payments clerk</p></td>
<td><p>Accounts receivable cube</p>
<p>General ledger cube</p></td>
</tr>
<tr class="odd">
<td><p>Accounts receivable clerk</p></td>
<td><p>Accounts receivable cube</p>
<p>General ledger cube</p></td>
</tr>
<tr class="even">
<td><p>Accounts receivable manager</p></td>
<td><p>Accounts payable cube</p>
<p>Accounts receivable cube</p>
<p>General ledger cube</p>
<p>Retail cube</p>
<p>Sales cube</p></td>
</tr>
<tr class="odd">
<td><p>Accounts receivable payments clerk</p></td>
<td><p>Accounts receivable cube</p>
<p>General ledger cube</p></td>
</tr>
<tr class="even">
<td><p>Budget clerk</p></td>
<td><p>General ledger cube</p></td>
</tr>
<tr class="odd">
<td><p>Budget manager</p></td>
<td><p>Budget control cube</p>
<p>Budget plan cube</p>
<p>General ledger cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Buying agent</p></td>
<td><p>Purchase cube</p></td>
</tr>
<tr class="odd">
<td><p>Chief executive officer</p></td>
<td><p>Accounts payable cube</p>
<p>Accounts receivable cube</p>
<p>Budget control cube</p>
<p>Budget plan cube</p>
<p>Environmental sustainability cube</p>
<p>Expense management cube</p>
<p>General ledger cube</p>
<p>Inventory value cube</p>
<p>Production cube</p>
<p>Project accounting cube</p>
<p>Purchase cube</p>
<p>Retail cube</p>
<p>Sales and marketing cube</p>
<p>Sales cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Chief financial officer</p></td>
<td><p>Accounts payable cube</p>
<p>Accounts receivable cube</p>
<p>Budget control cube</p>
<p>Budget plan cube</p>
<p>Expense management cube</p>
<p>General ledger cube</p>
<p>Inventory value cube</p>
<p>Project accounting cube</p>
<p>Purchase cube</p>
<p>Retail cube</p>
<p>Sales cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Collections agent</p></td>
<td><p>Accounts receivable cube</p>
<p>General ledger cube</p></td>
</tr>
<tr class="even">
<td><p>Collections manager</p></td>
<td><p>Accounts receivable cube</p>
<p>General ledger cube</p></td>
</tr>
<tr class="odd">
<td><p>Compensation and benefits manager</p></td>
<td><p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Compliance manager</p></td>
<td><p>Accounts payable cube</p>
<p>Accounts receivable cube</p>
<p>Budget control cube</p>
<p>Budget plan cube</p>
<p>General ledger cube</p>
<p>Purchase cube</p>
<p>Retail cube</p>
<p>Sales cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Cost accountant</p></td>
<td><p>Inventory value cube</p></td>
</tr>
<tr class="even">
<td><p>Cost clerk</p></td>
<td><p>Inventory value cube</p></td>
</tr>
<tr class="odd">
<td><p>Customer service representative</p></td>
<td><p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Environmental manager</p></td>
<td><p>Environmental sustainability cube</p></td>
</tr>
<tr class="odd">
<td><p>Field service technician</p></td>
<td><p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Financial controller</p></td>
<td><p>Accounts payable cube</p>
<p>Accounts receivable cube</p>
<p>Budget control cube</p>
<p>Budget plan cube</p>
<p>Expense management cube</p>
<p>General ledger cube</p>
<p>Purchase cube</p>
<p>Retail cube</p>
<p>Sales cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Human resource assistant</p></td>
<td><p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Human resource manager</p></td>
<td><p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Information technology manager</p></td>
<td><p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Marketing coordinator</p></td>
<td><p>Sales and marketing cube</p></td>
</tr>
<tr class="odd">
<td><p>Marketing manager</p></td>
<td><p>Sales and marketing cube</p></td>
</tr>
<tr class="even">
<td><p>Materials manager</p></td>
<td><p>Inventory value cube</p></td>
</tr>
<tr class="odd">
<td><p>Product designer</p></td>
<td><p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Production manager</p></td>
<td><p>Production cube</p></td>
</tr>
<tr class="odd">
<td><p>Project accountant</p></td>
<td><p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Project manager</p></td>
<td><p>Expense management cube</p>
<p>Project accounting cube</p>
<p>Purchase cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Project supervisor</p></td>
<td><p>Project accounting cube</p></td>
</tr>
<tr class="even">
<td><p>Purchasing manager</p></td>
<td><p>Accounts payable cube</p>
<p>Purchase cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Receiving clerk</p></td>
<td><p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Retail merchandising manager</p></td>
<td><p>Retail cube</p>
<p>Sales cube</p></td>
</tr>
<tr class="odd">
<td><p>Retail operations manager</p></td>
<td><p>Retail cube</p>
<p>Sales cube</p></td>
</tr>
<tr class="even">
<td><p>Retail store manager</p></td>
<td><p>Retail cube</p>
<p>Sales cube</p></td>
</tr>
<tr class="odd">
<td><p>Sales manager</p></td>
<td><p>Retail cube</p>
<p>Sales and marketing cube</p>
<p>Sales cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Sales representative</p></td>
<td><p>Sales and marketing cube</p></td>
</tr>
<tr class="odd">
<td><p>Treasurer</p></td>
<td><p>Accounts payable cube</p>
<p>General ledger cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Vendor account manager</p></td>
<td><p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Warehouse manager</p></td>
<td><p>Inventory value cube</p>
<p>Retail cube</p>
<p>Sales cube</p></td>
</tr>
</tbody>
</table>


## Analysis Services roles for Microsoft Dynamics AX 2012 Feature Pack cubes

When you deploy the cubes that are included with Microsoft Dynamics AX 2012 Feature Pack, the following roles are created in the Analysis Services database where you deploy the cubes.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Analysis Services role</p></th>
<th><p>Cubes that the role has access to</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Accountant</p></td>
<td><p>Accounts payable cube</p>
<p>Accounts receivable cube</p>
<p>General ledger cube</p>
<p>Purchase cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Accounting manager</p></td>
<td><p>Accounts payable cube</p>
<p>Accounts receivable cube</p>
<p>General ledger cube</p>
<p>Purchase cube</p>
<p>Sales cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Accounting supervisor</p></td>
<td><p>Accounts payable cube</p>
<p>Accounts receivable cube</p>
<p>General ledger cube</p>
<p>Purchase cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Accounts payable centralized payments clerk</p></td>
<td><p>Accounts payable cube</p>
<p>General ledger cube</p>
<p>Purchase cube</p></td>
</tr>
<tr class="odd">
<td><p>Accounts payable clerk</p></td>
<td><p>Accounts payable cube</p>
<p>Expense management cube</p>
<p>General ledger cube</p>
<p>Purchase cube</p></td>
</tr>
<tr class="even">
<td><p>Accounts payable manager</p></td>
<td><p>Accounts payable cube</p>
<p>Accounts receivable cube</p>
<p>Expense management cube</p>
<p>General ledger cube</p>
<p>Purchase cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Accounts payable payments clerk</p></td>
<td><p>Accounts payable cube</p>
<p>General ledger cube</p></td>
</tr>
<tr class="even">
<td><p>Accounts receivable centralized payments clerk</p></td>
<td><p>Accounts receivable cube</p>
<p>General ledger cube</p></td>
</tr>
<tr class="odd">
<td><p>Accounts receivable clerk</p></td>
<td><p>Accounts receivable cube</p>
<p>General ledger cube</p></td>
</tr>
<tr class="even">
<td><p>Accounts receivable manager</p></td>
<td><p>Accounts payable cube</p>
<p>Accounts receivable cube</p>
<p>General ledger cube</p>
<p>Sales cube</p></td>
</tr>
<tr class="odd">
<td><p>Accounts receivable payments clerk</p></td>
<td><p>Accounts receivable cube</p>
<p>General ledger cube</p></td>
</tr>
<tr class="even">
<td><p>Budget clerk</p></td>
<td><p>General ledger cube</p></td>
</tr>
<tr class="odd">
<td><p>Budget manager</p></td>
<td><p>General ledger cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Buying agent</p></td>
<td><p>Purchase cube</p></td>
</tr>
<tr class="odd">
<td><p>Chief executive officer</p></td>
<td><p>Accounts payable cube</p>
<p>Accounts receivable cube</p>
<p>Customer relationship management cube</p>
<p>Environmental sustainability cube</p>
<p>Expense management cube</p>
<p>General ledger cube</p>
<p>Production cube</p>
<p>Project accounting cube</p>
<p>Purchase cube</p>
<p>Sales cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Chief financial officer</p></td>
<td><p>Accounts payable cube</p>
<p>Accounts receivable cube</p>
<p>Expense management cube</p>
<p>General ledger cube</p>
<p>Project accounting cube</p>
<p>Purchase cube</p>
<p>Sales cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Collections agent</p></td>
<td><p>Accounts receivable cube</p>
<p>General ledger cube</p></td>
</tr>
<tr class="even">
<td><p>Collections manager</p></td>
<td><p>Accounts receivable cube</p>
<p>General ledger cube</p></td>
</tr>
<tr class="odd">
<td><p>Compensation and benefits manager</p></td>
<td><p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Compliance manager</p></td>
<td><p>Accounts payable cube</p>
<p>Accounts receivable cube</p>
<p>General ledger cube</p>
<p>Purchase cube</p>
<p>Sales cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Customer service representative</p></td>
<td><p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Environmental manager</p></td>
<td><p>Environmental sustainability cube</p></td>
</tr>
<tr class="odd">
<td><p>Field service technician</p></td>
<td><p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Financial controller</p></td>
<td><p>Accounts payable cube</p>
<p>Accounts receivable cube</p>
<p>Expense management cube</p>
<p>General ledger cube</p>
<p>Purchase cube</p>
<p>Sales cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Human resource assistant</p></td>
<td><p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Human resource manager</p></td>
<td><p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Information technology manager</p></td>
<td><p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Marketing coordinator</p></td>
<td><p>Customer relationship management cube</p></td>
</tr>
<tr class="odd">
<td><p>Marketing manager</p></td>
<td><p>Customer relationship management cube</p></td>
</tr>
<tr class="even">
<td><p>Product designer</p></td>
<td><p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Production manager</p></td>
<td><p>Production cube</p></td>
</tr>
<tr class="even">
<td><p>Project accountant</p></td>
<td><p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Project manager</p></td>
<td><p>Expense management cube</p>
<p>Project accounting cube</p>
<p>Purchase cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Project supervisor</p></td>
<td><p>Project accounting cube</p></td>
</tr>
<tr class="odd">
<td><p>Purchasing manager</p></td>
<td><p>Accounts payable cube</p>
<p>Purchase cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Receiving clerk</p></td>
<td><p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Retail merchandising manager</p></td>
<td><p>Sales cube</p></td>
</tr>
<tr class="even">
<td><p>Retail operations manager</p></td>
<td><p>Sales cube</p></td>
</tr>
<tr class="odd">
<td><p>Retail store manager</p></td>
<td><p>Sales cube</p></td>
</tr>
<tr class="even">
<td><p>Sales manager</p></td>
<td><p>Customer relationship management cube</p>
<p>Sales cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Sales representative</p></td>
<td><p>Customer relationship management cube</p></td>
</tr>
<tr class="even">
<td><p>Treasurer</p></td>
<td><p>Accounts payable cube</p>
<p>General ledger cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Vendor account manager</p></td>
<td><p>Workflow cube</p></td>
</tr>
</tbody>
</table>


## Analysis Services roles for Microsoft Dynamics AX 2012 cubes

When you deploy the cubes that are included with the initial release of Microsoft Dynamics AX 2012, the following roles are created in the Analysis Services database where you deploy the cubes.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Analysis Services role</p></th>
<th><p>Cubes that the role has access to</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Accountant</p></td>
<td><p>Accounts payable cube</p>
<p>Accounts receivable cube</p>
<p>General ledger cube</p>
<p>Purchase cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Accounting manager</p></td>
<td><p>Accounts payable cube</p>
<p>Accounts receivable cube</p>
<p>General ledger cube</p>
<p>Purchase cube</p>
<p>Sales cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Accounting supervisor</p></td>
<td><p>Accounts payable cube</p>
<p>Accounts receivable cube</p>
<p>General ledger cube</p>
<p>Purchase cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Accounts payable centralized payments clerk</p></td>
<td><p>Accounts payable cube</p>
<p>General ledger cube</p>
<p>Purchase cube</p></td>
</tr>
<tr class="odd">
<td><p>Accounts payable clerk</p></td>
<td><p>Accounts payable cube</p>
<p>Expense management cube</p>
<p>General ledger cube</p>
<p>Purchase cube</p></td>
</tr>
<tr class="even">
<td><p>Accounts payable manager</p></td>
<td><p>Accounts payable cube</p>
<p>Accounts receivable cube</p>
<p>Expense management cube</p>
<p>General ledger cube</p>
<p>Purchase cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Accounts payable payments clerk</p></td>
<td><p>Accounts payable cube</p>
<p>General ledger cube</p></td>
</tr>
<tr class="even">
<td><p>Accounts receivable centralized payments clerk</p></td>
<td><p>Accounts receivable cube</p>
<p>General ledger cube</p></td>
</tr>
<tr class="odd">
<td><p>Accounts receivable clerk</p></td>
<td><p>Accounts receivable cube</p>
<p>General ledger cube</p></td>
</tr>
<tr class="even">
<td><p>Accounts receivable manager</p></td>
<td><p>Accounts payable cube</p>
<p>Accounts receivable cube</p>
<p>General ledger cube</p>
<p>Sales cube</p></td>
</tr>
<tr class="odd">
<td><p>Accounts receivable payments clerk</p></td>
<td><p>Accounts receivable cube</p>
<p>General ledger cube</p></td>
</tr>
<tr class="even">
<td><p>Budget clerk</p></td>
<td><p>General ledger cube</p></td>
</tr>
<tr class="odd">
<td><p>Budget manager</p></td>
<td><p>General ledger cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Buying agent</p></td>
<td><p>Purchase cube</p></td>
</tr>
<tr class="odd">
<td><p>Chief executive officer</p></td>
<td><p>Accounts payable cube</p>
<p>Accounts receivable cube</p>
<p>Customer relationship management cube</p>
<p>Environmental sustainability cube</p>
<p>Expense management cube</p>
<p>General ledger cube</p>
<p>Production cube</p>
<p>Project accounting cube</p>
<p>Purchase cube</p>
<p>Sales cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Chief financial officer</p></td>
<td><p>Accounts payable cube</p>
<p>Accounts receivable cube</p>
<p>Expense management cube</p>
<p>General ledger cube</p>
<p>Project accounting cube</p>
<p>Purchase cube</p>
<p>Sales cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Collections agent</p></td>
<td><p>Accounts receivable cube</p>
<p>General ledger cube</p></td>
</tr>
<tr class="even">
<td><p>Collections manager</p></td>
<td><p>Accounts receivable cube</p>
<p>General ledger cube</p></td>
</tr>
<tr class="odd">
<td><p>Compensation and benefits manager</p></td>
<td><p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Compliance manager</p></td>
<td><p>Accounts payable cube</p>
<p>Accounts receivable cube</p>
<p>General ledger cube</p>
<p>Purchase cube</p>
<p>Sales cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Customer service representative</p></td>
<td><p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Environmental manager</p></td>
<td><p>Environmental sustainability cube</p></td>
</tr>
<tr class="odd">
<td><p>Field service technician</p></td>
<td><p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Financial controller</p></td>
<td><p>Accounts payable cube</p>
<p>Accounts receivable cube</p>
<p>Expense management cube</p>
<p>General ledger cube</p>
<p>Purchase cube</p>
<p>Sales cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Human resource assistant</p></td>
<td><p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Human resource manager</p></td>
<td><p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Information technology manager</p></td>
<td><p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Marketing coordinator</p></td>
<td><p>Customer relationship management cube</p></td>
</tr>
<tr class="odd">
<td><p>Marketing manager</p></td>
<td><p>Customer relationship management cube</p></td>
</tr>
<tr class="even">
<td><p>Product designer</p></td>
<td><p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Production manager</p></td>
<td><p>Production cube</p></td>
</tr>
<tr class="even">
<td><p>Project accountant</p></td>
<td><p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Project manager</p></td>
<td><p>Expense management cube</p>
<p>Project accounting cube</p>
<p>Purchase cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Project supervisor</p></td>
<td><p>Project accounting cube</p></td>
</tr>
<tr class="odd">
<td><p>Purchasing manager</p></td>
<td><p>Accounts payable cube</p>
<p>Purchase cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Receiving clerk</p></td>
<td><p>Workflow cube</p></td>
</tr>
<tr class="odd">
<td><p>Sales manager</p></td>
<td><p>Customer relationship management cube</p>
<p>Sales cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Sales representative</p></td>
<td><p>Customer relationship management cube</p></td>
</tr>
<tr class="odd">
<td><p>Treasurer</p></td>
<td><p>Accounts payable cube</p>
<p>General ledger cube</p>
<p>Workflow cube</p></td>
</tr>
<tr class="even">
<td><p>Vendor account manager</p></td>
<td><p>Workflow cube</p></td>
</tr>
</tbody>
</table>

  


