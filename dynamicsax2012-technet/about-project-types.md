---
title: About project types
TOCTitle: About project types
ms:assetid: 13db418e-07e2-4f00-8f30-fa2a1f4611bd
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa496605(v=AX.60)
ms:contentKeyID: 36811396
ms.date: 06/09/2014
mtps_version: v=AX.60
f1_keywords:
- time
- cost
- internal
- time and material
- fixed-price
- project type
- investment
- invoicing setup
audience: Application User
ms.search.region: Global
---

# About project types 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes the project types that you can create in **Project management and accounting**. The primary difference among these project types, apart from their different purposes, lies in how they are set up for costs and revenue recognition.

The project type that you choose depends on the purpose of the project. The following table describes the typical use of each project type.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Project type</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Time and material</strong></p></td>
<td><p>In Time and material projects, the customer is billed for all costs that are incurred on a project. These include costs for hours, expenses, items, and fees.</p></td>
</tr>
<tr class="even">
<td><p><strong>Fixed-price</strong></p></td>
<td><p>The invoices in fixed-price projects consist of on-account transactions. These projects are invoiced according to a billing schedule that is based on a project contract. Revenue for a fixed-price project can be calculated and posted throughout the project by using the completed percentage method, or when the project is finished, by using the completed contract method. Companies can often benefit from using the value of the work in process (WIP) to calculate the degree of completion of a project or group of projects.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Investment</strong></p></td>
<td><p>Investment projects are projects that do not produce immediate earnings. They are typically used for long-term internal projects in which the costs have to be capitalized. The following are also true of investment projects:</p>
<ul>
<li><p>Only costs for items, hours, and expenses can be recorded for an investment project.</p></li>
<li><p>Costs in an investment project are tracked and controlled by using the <strong>Project management and accounting</strong> Estimate feature.</p></li>
<li><p>Investment projects can be set up with an optional maximum capitalization limit.</p></li>
</ul>
<p>As an investment project progresses, you record its costs in WIP accounts, where the costs are held until the project is completed. When the project is eliminated, you transfer the WIP value to a fixed asset, a ledger account, or a new project.</p>
<div class="alert">

> [!NOTE]
> <P>Transactions on investment projects are not reflected in the <STRONG>Post costs</STRONG> form, <STRONG>Accrue revenue</STRONG> form, or <STRONG>Create invoice proposals</STRONG> form.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Cost project</strong></p></td>
<td><p>Like Investment projects, Cost projects are typically used to track internal projects, and only hours, expenses, and items can be recorded for costs projects. Cost projects are usually of shorter duration than investment projects. Unlike Investment projects, Cost projects cannot be capitalized to balance sheet accounts. Instead, their project transactions are posted only to profit and loss accounts.</p>
<div class="alert">

> [!NOTE]
> <P>Transactions on cost projects are not reflected in the <STRONG>Post costs</STRONG> form, <STRONG>Accrue revenue</STRONG> form, or <STRONG>Create invoice proposals</STRONG> form.</P>


</div>
<p>Because Cost projects are typically used to track internal projects, they do not ordinarily have to be associated with a customer account. However, if your setup requires that item requirements be created for purchase orders, you do have to associate the Cost project with a customer. This is because item requirements are managed as sales order lines, and the system requires that a customer be specified. However, this setup will not result in item requirements being created automatically from a purchase order. For Cost projects, the <strong>Create item requirement</strong> setting is ignored.</p>
<p>If you do need an item requirement in a Cost project, you can create one manually, so long as a customer is associated with the project. You can select the <strong>Create item requirement</strong> option in the <strong>General</strong> area in the <strong>Project management and accounting parameters</strong> form.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Internal</strong></p></td>
<td><p>Internal projects are used to track costs on a project that is internal to your organization. This type of project can provide a planning tool to manage resource consumption.</p>
<div class="alert">

> [!NOTE]
> <P>Transactions on internal projects are not reflected in the <STRONG>Accrue revenue</STRONG> form or <STRONG>Create invoice proposals</STRONG> form.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Time project</strong></p></td>
<td><p>Time projects are used to track time that is associated with non-chargeable and non-productive activities, such as a project to track sick time for workers. Transactions in Time projects are not posted to the ledger. Instead, they are included in worker utilization reports.</p>
<p>Only hour transactions can be recorded in Time projects. You use an hour journal or timesheet to register these hours to the project. After the hours are registered, they appear as project transactions, but without a corresponding voucher transaction.</p>
<div class="alert">

> [!NOTE]
> <P>Transactions on time projects are not reflected in the <STRONG>Post costs</STRONG> form, <STRONG>Accrue revenue</STRONG> form, or <STRONG>Create invoice proposals</STRONG> form.</P>


</div></td>
</tr>
</tbody>
</table>


## See also

[About using the Time and material project type for a fixed-price project](about-using-the-time-and-material-project-type-for-a-fixed-price-project.md)

  


