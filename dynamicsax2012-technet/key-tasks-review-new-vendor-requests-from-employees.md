---
title: 'Key tasks: Review new vendor requests from employees'
TOCTitle: 'Key tasks: Review new vendor requests from employees'
ms:assetid: cda48608-976b-423b-a6fe-d495dfd89707
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242908(v=AX.60)
ms:contentKeyID: 36059463
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- vendor request
- new vendor
- review vendor request
---

# Key tasks: Review new vendor requests from employees [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When an employee wants to work with a vendor that is not already on your organization’s list of approved vendors, the employee can request to have the vendor added to the list. As a purchasing agent, you are responsible for reviewing new vendor requests and approving or rejecting them.

Employees create and submit a vendor request in the Employee services portal in Enterprise Portal for Microsoft Dynamics AX. The vendor request includes preliminary address information for the vendor, vendor contact name and email address, and a reason for the request. Vendor requests appear on the **Vendor requests** list page in the Microsoft Dynamics AX client, where you can review them. If you approve a request, the prospective vendor is invited to submit a full profile about the vendor’s organization, contacts, and other details. The vendor provides this information by using the **Vendor registration** page in Enterprise Portal.

You can view the workflow history to track the status of a new vendor request. As you and others complete the tasks in workflow, the status of the vendor request and the status of the prospective vendor profile are automatically updated. You can view the status of a vendor request on the **Vendor requests** list page. For more information, see [Vendor requests (list page)](https://technet.microsoft.com/en-us/library/hh242710\(v=ax.60\)).

**Prerequisites**

  - Your system administrator must set up the workflow tasks for the vendor request process. For more information about the workflow tasks, see [Setting up and maintaining procurement and sourcing workflows](setting-up-and-maintaining-procurement-and-sourcing-workflows.md).

  - Before an employee can submit a request to add a new vendor, an administrator must set up the **New vendor request** page in Enterprise Portal. For more information about how to configure the **New vendor request** page, see [Key tasks: Set up vendor add requests](key-tasks-set-up-vendor-add-requests.md).

  - Before a prospective vendor can complete the registration process, an administrator must configure the fields that appear on the **Vendor registration** page in Enterprise Portal. For more information about how to configure the information for a prospective vendor, see [Vendor request configurations (form)](https://technet.microsoft.com/en-us/library/hh209430\(v=ax.60\)).

  - Before the vendor contact can complete the prospective vendor profile, an administrator must set up the **Vendor registration** page. For more information, see [Configuring Enterprise Portal for vendor requests](configuring-enterprise-portal-for-vendor-requests.md).

## What do you want to do?

Learn more about...

Approve new vendor requests

Reject new vendor requests

Delegate vendor request tasks to another

View workflow history for a new vendor request

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[Manage vendor requests overview](manage-vendor-requests-overview.md)

## Approve new vendor requests

Use this procedure to review and approve a request from an employee to add a vendor to your organization’s list of approved vendors.

1.  Click **Procurement and sourcing** \> **Common** \> **Vendor requests** \> **Vendor requests**.

2.  On the **Vendor requests** list page, open a request that has a status of **Request pending approval**.

3.  In the **New vendor request** form, review any warnings that are associated with the request.
    
    Warnings are set up on the **Vendor request configurations** form. A warning notifies you of a possible conflict of interest or other issue in a vendor request. For example, a vendor name may have a matching record in the employee database, or the vendor in the request may be located in an embargoed country or region.

4.  To approve the request, in the workflow message bar, click **Actions** \> **Approve**.

5.  In the **Vendor add justification workflow** form, enter an optional comment, and then click **Approve**.
    

    > [!NOTE]
    > <P>The requester, approver, and vendor can see any comments that you add in the workflow history.</P>



The vendor becomes a **Prospective vendor**. The vendor contact receives a notification to complete a prospective vendor profile in Enterprise Portal.

Back to top

## Reject new vendor requests

Use this procedure to review and reject a request from an employee to add a vendor to your organization’s list of approved vendors.

1.  Click **Procurement and sourcing** \> **Common** \> **Vendor requests** \> **Vendor requests**.

2.  On the **Vendor requests** list page, double-click a request that has a status of **Request pending approval**.

3.  In the **New vendor request** form, review any warnings that are associated with the request.
    
    Warnings are set up on the **Vendor request configurations** form. A warning notifies you of a possible conflict of interest or other issue in a vendor request. For example, a vendor name may have a matching record in the employee database, or the vendor in the request may be located in an embargoed country or region.

4.  To reject the request, in the workflow message bar, click **Actions** \> **Reject**.

5.  In the **Workflow** - **Reject** dialog box, enter an optional comment, and then click **Reject**. When you reject a request, workflow ends for the rejected vendor request.
    

    > [!NOTE]
    > <P>The requester, approver, and vendor can see any comments that you add in the workflow history.</P>



The employee who initiated the request is notified that the request was rejected and given the reason for the rejection.

Back to top

## Delegate vendor request tasks to another

Use this procedure to assign the workflow task of reviewing a vendor request to another authorized employee.

1.  Click **Procurement and sourcing** \> **Common** \> **Vendor requests** \> **Vendor requests**.

2.  On the **Vendor requests** list page, open a request that has a status of **Request pending approval**.

3.  In the **New vendor request** form, in the workflow message bar, click **Actions** \> **Delegate**.

4.  In the **Vendor add justification workflow** form, in the **User** field, select the identifier for an employee who is authorized to review vendor requests. Enter an optional comment, and then click **Delegate**.
    

    > [!NOTE]
    > <P>The requester, approver, and vendor can see any comments that you add in the workflow history.</P>



The employee that you select is notified via workflow to review the vendor request.

Back to top

## View workflow history for a new vendor request

Vendor requests that an employee submits in the Employee portal in Enterprise Portal are moved to the Microsoft Dynamics AX client via workflow. You can track the progress of the request in the workflow history. Use this procedure to view the details of completed tasks in workflow for a vendor request.

1.  Click **Procurement and sourcing** \> **Common** \> **Vendor requests** \> **Vendor requests**.

2.  On the **Vendor requests** list page, open a request that has a status of **Request pending approval**.

3.  In the **New vendor request** form, in the workflow message bar, click **Actions** \> **View history**.

4.  In the **Workflow history** form, view the status of the request and view the names of employees who are assigned to each workflow task.

5.  In the **Workflow details:** section, on the **Tracking details** tab, view details about the completed steps in the workflow for this vendor request.

For more information about workflow, see [Workflow history (form)](https://technet.microsoft.com/en-us/library/hh597256\(v=ax.60\)).

Back to top

## Find form help

[New vendor request (form)](https://technet.microsoft.com/en-us/library/hh242728\(v=ax.60\))

[Workflow history (form)](https://technet.microsoft.com/en-us/library/hh597256\(v=ax.60\))

## Find related tasks

[Key tasks: Set up vendor add requests](key-tasks-set-up-vendor-add-requests.md)

[Key tasks: Manage prospective vendor requests](key-tasks-manage-prospective-vendor-requests.md)

[Key tasks: Manually set up user access to the Vendor portal](key-tasks-manually-set-up-user-access-to-the-vendor-portal.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

