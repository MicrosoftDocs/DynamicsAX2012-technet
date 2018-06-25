---
title: 'Key tasks: Manage prospective vendor requests'
TOCTitle: 'Key tasks: Manage prospective vendor requests'
ms:assetid: e67d7faa-338f-42c5-ac29-c0ff5039cc6f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh227458(v=AX.60)
ms:contentKeyID: 36059803
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Key tasks: Manage prospective vendor requests [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

As a vendor request reviewer, you process requests that employees submit to add new vendors to the list of approved vendors for their legal entity. If you approve a request, the vendor becomes a prospective vendor. Your system administrator adds the contact for the prospective vendor to the list of external Microsoft Dynamics AX users and grants the contact access to the **Vendor registration** page in Enterprise Portal for Microsoft Dynamics AX. A notification is sent to the vendor, and the vendor must complete the application and submit it for approval.

**Prerequisites**

  - Your system administrator must set up the workflow tasks for the vendor request process. For more information about the workflow tasks, see [Setting up and maintaining procurement and sourcing workflows](setting-up-and-maintaining-procurement-and-sourcing-workflows.md).

  - If you are using flexible authentication to provide vendor users access to Enterprise Portal and, ultimately, the Vendor portal, your system administrator must set up the user provisioning process. For more information, see [Key tasks: Set up vendor user provisioning](key-tasks-set-up-vendor-user-provisioning.md).

  - Your system administrator must configure the Enterprise Portal pages for prospective vendors, vendors, and employees. For more information, see [About vendor request configuration](about-vendor-request-configuration.md).

## What do you want to do?

Learn more about...

Request additional information from a prospective vendor

Approve a prospective vendor

Reject a prospective vendor

Delegate prospective vendor tasks to another

View workflow history for a prospective vendor request

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[Manage vendor requests overview](manage-vendor-requests-overview.md)

## Request additional information from a prospective vendor

Use this procedure to request additional information from a prospective vendor.

1.  Click **Procurement and sourcing** \> **Common** \> **Vendor requests** \> **Vendor requests**.

2.  On the **Vendor requests** list page, open a request that has the status of **Application pending review**.

3.  On the **Prospective vendor profile** form, review the profile information to determine whether the information is complete.

4.  In the workflow message bar, click **Actions** \> **Additional information required**.

5.  In the **Vendor add application workflow** form, in the **User** field, select the name of the vendor to send the request to. Enter an optional comment, and then click **Additional information required**.

A notification is sent to the vendor contact, via workflow, to indicate that additional information is required. The vendor contact can return to the **Vendor registration** page and provide the additional information and resubmit the application.

Back to top

## Approve a prospective vendor

1.  Click **Procurement and sourcing** \> **Common** \> **Vendor requests** \> **Vendor requests**.

2.  On the **Vendor requests** list page, open a request that has the status of **Application pending review**.

3.  In the **Prospective vendor profile** form, review any warnings that are displayed for the request.
    
    A warning contains information about a possible conflict of interest or other issue in a vendor profile. For example, a vendor name may have a matching record in the employee database or a vendor may be located in an embargoed country or region.

4.  In the **Prospective vendor profile** form, review the information on the **General**, **Payment information**, and **Questionnaire information** FastTabs, according to the purchasing policies of your organization.

5.  To approve the prospective vendor, on the **General** FastTab, in the **Vendor group** field, select a vendor group. This information is required before you can submit the approval to workflow.

6.  In the workflow message bar, click **Actions** \> **Approve**.

7.  In the **Vendor add application workflow** form, enter an optional comment, and then click **Approve** to submit the approval to workflow.

A notification is sent to the employee who requested the vendor to indicate that the vendor has been approved. If your system administrator has configured workflow to send a notification to the vendor, the vendor contact receives an e-mail message that informs them of the approval.

Back to top

## Reject a prospective vendor

1.  Click **Procurement and sourcing** \> **Common** \> **Vendor requests** \> **Vendor requests**.

2.  On the **Vendor requests** list page, open a request that has the status of **Application pending review**.

3.  In the **Prospective vendor profile** form, review any warnings that are associated with the request.
    
    A warning contains information about a possible conflict of interest or other issue in a vendor profile. For example, a vendor name may have a matching record in the employee database or a vendor may be located in an embargoed country or region.

4.  In the **Prospective vendor profile** form, review the information on the **General**, **Payment information**, and **Questionnaire information** FastTabs, according to the purchasing policies of your organization.

5.  To reject the prospective vendor application, on the **General** FastTab, in the **Reason code** field, select a reason for the rejection. This information is required before you can submit the rejection to workflow. In the **Reason comment** field, you can enter an optional detailed explanation that is displayed to the rejected vendor.

6.  In the workflow message bar, click **Actions** \> **Reject**.

7.  In the **Vendor add application workflow** form, enter an optional comment, and then click **Reject** to submit the rejection to workflow.

A notification is sent to the vendor to indicate that their application was rejected.

Back to top

## Delegate prospective vendor tasks to another

Complete the following steps to delegate the review of a prospective vendor profile to another purchasing agent.

1.  Click **Procurement and sourcing** \> **Common** \> **Vendor requests** \> **Vendor requests**.

2.  On the **Vendor requests** list page, open a request that has a status of **Application pending review**.

3.  To delegate the review task to another reviewer, in the **Prospective vendor profile** form, in the workflow message bar, click **Actions** \> **Delegate**.

4.  In the **Vendor add application workflow** form, in the **User** field, select the name of an authorized reviewer. In the **Comment** field, enter an optional comment, and then click **Delegate**.

The reviewer that you select receives a workflow notification to indicate that the prospective vendor review has been delegated to them. The reviewer is responsible approving or rejecting the vendor application.

Back to top

## View workflow history for a prospective vendor request

Use this procedure to view the status and details of completed workflow tasks for a prospective vendor request.

1.  Click **Procurement and sourcing** \> **Common** \> **Vendor requests** \> **Vendor requests**.

2.  On the **Vendor requests** list page, open a request that has a status of **Application pending review**.

3.  In the **Prospective vendor profile** form, in the workflow message bar, click **Actions** \> **View history**.

4.  In the **Workflow history** form, on the **Overview** tab, view the status of the vendor request and view the name of the person to whom the next task is assigned.

5.  In the **Workflow details:** section, click the **Tracking details** tab to view the details about the completed steps in the workflow for this vendor request.

For more information about workflow history, see [Workflow history (form)](https://technet.microsoft.com/en-us/library/hh597256\(v=ax.60\)).

Back to top

## Find form help

[Prospective vendor profile (form)](https://technet.microsoft.com/en-us/library/hh227357\(v=ax.60\))

[Reasons (form)](https://technet.microsoft.com/en-us/library/hh209362\(v=ax.60\))

## Find related tasks

[Key tasks: Review new vendor requests from employees](key-tasks-review-new-vendor-requests-from-employees.md)

[Key tasks: Set up vendor add requests](key-tasks-set-up-vendor-add-requests.md)

[Key tasks: Set up vendor user provisioning](key-tasks-set-up-vendor-user-provisioning.md)

[Key tasks: Manually set up user access to the Vendor portal](key-tasks-manually-set-up-user-access-to-the-vendor-portal.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

