---
title: Manage vendor requests overview
TOCTitle: Manage vendor requests overview
ms:assetid: ed3af57c-b639-44ae-8779-2d7fe9ebc7b6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh227499(v=AX.60)
ms:contentKeyID: 36059903
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- vendor
- vendors
- vendor request
- vendor requests
---

# Manage vendor requests overview 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Workers in your company may want to purchase products from a vendor who is not approved to do business with your company. In this case, a worker can submit a request to add the vendor to the vendor master. The worker must submit a new vendor request in the Employee portal in Enterprise Portal for Microsoft Dynamics AX. The request includes contact information for the vendor and a justification for the request. New vendor requests appear on the **Vendor requests** list page in Microsoft Dynamics AX.

New vendor requests are routed, via workflow, to an approver. If the request is approved, the vendor becomes a prospective vendor. Your system administrator adds the contact for the prospective vendor to the list of external Microsoft Dynamics AX users and grants the contact access to the **Vendor registration** page in Enterprise Portal. A notification is sent to the vendor, and the vendor must complete the application and submit it for approval. The application includes information such as the vendor address, tax information, and banking information.

You must configure the new vendor request pages in the Employee portal, Vendor portal, and vendor registration page in Enterprise Portal. You can define which fields on the pages are hidden, displayed, and required and specify system checks that you want to perform for the application. For example, the system can determine whether the vendor is a potential duplicate, a disallowed vendor, or located in an embargoed country/region.

You can create multiple application profiles to meet the needs of your business. For more information about how to set up the vendor request pages, see [Configuring Enterprise Portal for vendor requests](configuring-enterprise-portal-for-vendor-requests.md).

The following diagram illustrates the basic process for requesting a new vendor, reviewing the prospective vendor profile, and approving or rejecting the prospective vendor.

![Swimlane diagram of the NVA NVJ process](images/Hh227499.NVJ_NVA_Process_Diagram(AX.60).gif "Swimlane diagram of the NVA NVJ process")

## Request a new vendor

The information in the following table outlines the tasks and statuses for a new vendor request.

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
<td><p>Save the new vendor request.</p></td>
<td><p>None</p></td>
<td><p><strong>Draft</strong></p></td>
</tr>
<tr class="even">
<td><p>Worker</p></td>
<td><p>Review and submit the new vendor request.</p></td>
<td><p><strong>Draft</strong></p></td>
<td><p><strong>Request submitted</strong></p></td>
</tr>
<tr class="odd">
<td><p>System</p></td>
<td><p>Submit the request to workflow for approval.</p></td>
<td><p><strong>Request submitted</strong></p></td>
<td><p><strong>Request pending approval</strong></p></td>
</tr>
<tr class="even">
<td><p>Reviewer</p></td>
<td><p>Approve the new vendor request.</p></td>
<td><p><strong>Request pending approval</strong></p></td>
<td><p><strong>Request approved</strong></p></td>
</tr>
<tr class="odd">
<td><p>Microsoft Dynamics AX administrator</p></td>
<td><p>Complete the tasks that are required to grant a vendor access to Enterprise Portal and mark the vendor request as completed.</p></td>
<td><p><strong>Request pending complete</strong></p></td>
<td><p><strong>Vendor invited</strong></p></td>
</tr>
</tbody>
</table>


A new vendor request can be canceled when the request has a status of **Request pending approval** or **Request submitted**. When a new vendor request is canceled, it moves from its current status to a status of **Request cancelled**.

When a new vendor request is rejected, the status of the request changes to **Request rejected**. The worker can add information to a rejected request and resubmit it. When a request is resubmitted, it moves from a status of **Request rejected** to a status of **Request submitted**.

## Review a prospective vendor request

The information in the following table outlines the tasks and statuses for a prospective vendor request.

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
<td><p>Complete the vendor profile in the Vendor portal.</p></td>
<td><p><strong>Vendor invited</strong></p></td>
<td><p><strong>Application drafted</strong></p></td>
</tr>
<tr class="even">
<td><p>Vendor</p></td>
<td><p>Submit the vendor profile in the Vendor portal.</p></td>
<td><p><strong>Application drafted</strong></p></td>
<td><p><strong>Application submitted</strong></p></td>
</tr>
<tr class="odd">
<td><p>System</p></td>
<td><p>Submit the profile to workflow for processing.</p></td>
<td><p><strong>Application submitted</strong></p></td>
<td><p><strong>Application pending review</strong></p></td>
</tr>
<tr class="even">
<td><p>Reviewer</p></td>
<td><p>View the workflow history for the prospective vendor profile.</p></td>
<td><p><strong>Application pending review</strong></p></td>
<td><p><strong>Application reviewed</strong></p></td>
</tr>
<tr class="odd">
<td><p>Reviewer</p></td>
<td><p>Request additional information from the prospective vendor.</p></td>
<td><p><strong>Application reviewed</strong></p></td>
<td><p><strong>Application pending approval</strong></p></td>
</tr>
<tr class="even">
<td><p>Reviewer</p></td>
<td><p>Delegate review of the vendor profile to another worker.</p></td>
<td><p><strong>Application pending approval</strong></p></td>
<td><p><strong>Application pending approval</strong></p></td>
</tr>
<tr class="odd">
<td><p>Reviewer</p></td>
<td><p>Review and approve the prospective vendor profile.</p></td>
<td><p><strong>Application pending approval</strong></p></td>
<td><p><strong>Application approved</strong></p></td>
</tr>
</tbody>
</table>



> [!NOTE]
> <P>If the reviewer rejects the prospective vendor, the status of the request changes from <STRONG>Application pending approval</STRONG> to <STRONG>Application rejected</STRONG>.</P>



## See also

[Key tasks: Review new vendor requests from employees](key-tasks-review-new-vendor-requests-from-employees.md)

[Key tasks: Manually set up user access to the Vendor portal](key-tasks-manually-set-up-user-access-to-the-vendor-portal.md)

[Key tasks: Manage prospective vendor requests](key-tasks-manage-prospective-vendor-requests.md)

[Key tasks: Manage category requests from employees](key-tasks-manage-category-requests-from-employees.md)

[Key tasks: Manage vendor status change requests](key-tasks-manage-vendor-status-change-requests.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

