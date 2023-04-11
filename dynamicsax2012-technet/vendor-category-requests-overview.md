---
title: Vendor category requests overview
TOCTitle: Vendor category requests overview
ms:assetid: 40d71b3f-8c56-402c-a63e-b200607686eb
ms:mtpsurl: https://technet.microsoft.com/library/JJ735274(v=AX.60)
ms:contentKeyID: 49693275
author: tonyafehr
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- vendor
- vendors
- category request
- category requests
- vendor categories
- vendor category
audience: Application User
ms.search.region: Global
---

# Vendor category requests overview 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When a vendor is approved to provide items and services to your legal entity, the vendor is authorized to provide products only in specific procurement categories. Procurement categories help classify vendor items and services. They also help control which vendors and products are available to employees when they make business-related purchases. Additionally, purchasing managers can use these categories to measure and report on the overall health of the purchasing organization, and to evaluate vendor performance.

To authorize a vendor to provide products in additional procurement categories, a vendor category request must be submitted. There are two ways to submit a vendor category request:

  - An employee can submit a request in the Employee services site to authorize a vendor to do business in additional procurement categories.

  - A vendor can submit a request in the Vendor portal to be authorized to do business in additional procurement categories.

Vendor category requests are submitted to workflow and routed to an approver for review. The approver approves or rejects the request.

## Submit a vendor category request from the Employee services site

When a worker submits a vendor category request, the worker specifies the procurement categories, provides a business justification for the request, and submits the request to workflow. After the request is approved, workers can submit purchase requisitions to order items and services from the vendor in the specified categories.

When a request is rejected, the reviewer can provide a reason for the rejection. If applicable, the worker can provide more information and resubmit the request.

The information in the following table outlines the tasks and workflow statuses for a vendor category request that is submitted by a worker in the Employee services site.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Role</p></th>
<th><p>Task</p></th>
<th><p>Initial status</p></th>
<th><p>Resulting status</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Worker</p></td>
<td><p>Create and save the vendor category request.</p></td>
<td><p>None</p></td>
<td><p><strong>Draft</strong></p></td>
</tr>
<tr class="even">
<td><p>Worker</p></td>
<td><p>Review and submit the category request.</p>
<div class="alert">

> [!NOTE]
> <P>Before a vendor category request can be submitted to workflow, the category justification request and the category application workflows must be set up. For more information, see <A href="set-up-procurement-and-sourcing-workflows.md">Set up Procurement and sourcing workflows</A>.</P>


</div></td>
<td><p><strong>Draft</strong></p></td>
<td><p><strong>Request pending approval</strong></p></td>
</tr>
<tr class="odd">
<td><p>Reviewer</p></td>
<td><p>Approve the vendor category request.</p>
<p>This action forwards the vendor category request to the vendor in the Vendor portal.</p></td>
<td><p><strong>Request pending approval</strong></p></td>
<td><p><strong>Application ready</strong></p></td>
</tr>
<tr class="even">
<td><p>Vendor contact, identified in the vendor category request</p></td>
<td><p>Confirm the vendor’s ability to do business in the specified categories, and complete any required questionnaires. Submit the confirmation.</p></td>
<td><p><strong>Application ready</strong></p></td>
<td><p><strong>Application pending approval</strong></p></td>
</tr>
<tr class="odd">
<td><p>Reviewer</p></td>
<td><p>Approve the vendor category confirmation.</p></td>
<td><p><strong>Application pending approval</strong></p></td>
<td><p><strong>Application approved</strong></p></td>
</tr>
</tbody>
</table>


## Example: A vendor category request is submitted by an employee

Fabrikam is a print media specialist and an advertising specialist. Julia, a marketing executive for Contoso, wants to use Fabrikam for print media services, but this vendor is only authorized to do business in the "Advertising" procurement category. Julia creates a vendor category request to add Fabrikam to the "Print media" procurement category.

The Contoso purchasing department reviews Julia’s request. If the request is approved, it is routed to Fabrikam to confirm that they can provide services in the “Print media” procurement category. Fabrikam submits the confirmation.

The Contoso purchasing department reviews the confirmation. If the purchasing department approves the request, Fabrikam is authorized to do business in the “Print media” procurement category. Julia can now submit a purchasing request for Fabrikam’s print media services.

## Submit a category request from the Vendor portal

When a vendor submits a category request, the vendor specifies the procurement categories that they want to do business in and submits the request to workflow. After the request is approved, workers can submit purchase requisitions to order goods and services from the vendor in the specified categories.

The information in the following table outlines the tasks and workflow statuses for a category request that is submitted by a vendor in the Vendor portal.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Role</p></th>
<th><p>Task</p></th>
<th><p>Initial status</p></th>
<th><p>Resulting status</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Vendor</p></td>
<td><p>Create and save the category request.</p></td>
<td><p>None</p></td>
<td><p><strong>Application drafted</strong></p></td>
</tr>
<tr class="even">
<td><p>Vendor</p></td>
<td><p>Review and submit the category request.</p>
<div class="alert">

> [!NOTE]
> <P>Before a vendor category request can be submitted to workflow, the category justification request and the category application workflows must be set up. For more information, see <A href="set-up-procurement-and-sourcing-workflows.md">Set up Procurement and sourcing workflows</A>.</P>


</div></td>
<td><p><strong>Application drafted</strong></p></td>
<td><p><strong>Application pending approval</strong></p></td>
</tr>
<tr class="odd">
<td><p>Reviewer</p></td>
<td><p>Approve the vendor category request.</p></td>
<td><p><strong>Application pending approval</strong></p></td>
<td><p><strong>Application approved</strong></p></td>
</tr>
</tbody>
</table>


## Example: A vendor category request is submitted by a vendor

Fabrikam is a vendor that provides office supply materials and is authorized to do business in the “Paper goods” procurement category for Contoso. However, Fabrikam has expanded their business to provide graphic reproduction services for items such as brochures and advertising materials. In the Vendor portal, Fabrikam submits a vendor category request to be authorized to do business in the “Print media” procurement category. Fabrikam’s request is reviewed by the Contoso purchasing department, and approved or rejected as appropriate for Contoso’s business.

## See also

[Key tasks: Manage category requests from employees](key-tasks-manage-category-requests-from-employees.md)

[Key tasks: Manage category requests from vendors](key-tasks-manage-category-requests-from-vendors.md)

  


