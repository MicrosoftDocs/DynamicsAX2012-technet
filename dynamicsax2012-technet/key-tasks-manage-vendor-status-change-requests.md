---
title: 'Key tasks: Manage vendor status change requests'
TOCTitle: 'Key tasks: Manage vendor status change requests'
ms:assetid: fb018b50-da3d-4254-ac4e-b58f80438fff
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ735276(v=AX.60)
ms:contentKeyID: 49693277
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Key tasks: Manage vendor status change requests 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When an employee wants to work with a vendor that is on hold, the employee can request to have the vendor's hold status changed. As a reviewer, you are responsible for reviewing new vendor status change requests, and for approving or rejecting them. Employees submit vendor status change requests by using the Employee services site in Enterprise Portal for Microsoft Dynamics AX.

**Prerequisites**

  - A system administrator must set up the workflow tasks for the vendor request process. For more information about the workflow tasks, see [Setting up and maintaining procurement and sourcing workflows](setting-up-and-maintaining-procurement-and-sourcing-workflows.md).

  - A system administrator must set up the **Vendor status change request** page for the Employee services site in Enterprise Portal. For more information about how to configure the **Vendor status change request** page, see [Set up vendor status change requests](set-up-vendor-status-change-requests.md).

## What do you want to do?

Approve vendor status change requests

Reject vendor status change requests

Delegate vendor status change approval

View workflow history for a vendor status change request

Find form help

Find related tasks

## Approve vendor status change requests

Use this procedure to review and approve a request from an employee to change a vendor’s hold status.

1.  Click **Procurement and sourcing** \> **Common** \> **Vendor requests** \> **Vendor requests**.

2.  On the **Vendor requests** list page, open a request that has a request type of **Status change**.

3.  In the **New status change request** form, review the request.

4.  To approve the request, in the workflow message bar, click **Actions** \> **Approve**.

5.  In the **Vendor status change request workflow** form, enter an optional comment, and then click **Approve**.
    

    > [!NOTE]
    > <P>The requester, approver, and vendor can see any comments that you add in the workflow history.</P>



The vendor’s hold status changes, and the employee can conduct business with the vendor.

Back to top

## Reject vendor status change requests

Use this procedure to review and reject a request from an employee to change a vendor’s hold status.

1.  Click **Procurement and sourcing** \> **Common** \> **Vendor requests** \> **Vendor requests**.

2.  On the **Vendor requests** list page, open a request that has a request type of **Status change**.

3.  In the **New status change request** form, review the request.

4.  To reject the request, in the workflow message bar, click **Actions** \> **Reject**.

5.  In the **Vendor status change request workflow** form, enter an optional comment, and then click **Reject**. When you reject a request, the workflow ends for the rejected vendor request.
    

    > [!NOTE]
    > <P>The requester, approver, and vendor can see any comments that you add in the workflow history.</P>



The vendor’s hold status does not change.

Back to top

## Delegate vendor status change approval

Use this procedure to assign the workflow task of reviewing a vendor request to another authorized employee.

1.  Click **Procurement and sourcing** \> **Common** \> **Vendor requests** \> **Vendor requests**.

2.  On the **Vendor requests** list page, open a request that has a request type of **Status change**.

3.  In the **New status change request** form, review the request.

4.  In the **New status change request** form, in the workflow message bar, click **Actions** \> **Delegate**.

5.  In the **Vendor status change request workflow** form, in the **User** field, select the identifier for an employee who is authorized to review vendor requests. Enter an optional comment, and then click **Delegate**.
    

    > [!NOTE]
    > <P>The requester, approver, and vendor can see any comments that you add in the workflow history.</P>



The employee that you select is notified via workflow to review the vendor request.

Back to top

## View workflow history for a vendor status change request

Status change requests that an employee submits in the Employee services site in Enterprise Portal are moved to the Microsoft Dynamics AX client via workflow. You can track the progress of the request in the workflow history. Use this procedure to view the details of completed tasks in workflow for a vendor request.

1.  Click **Procurement and sourcing** \> **Common** \> **Vendor requests** \> **Vendor requests**.

2.  On the **Vendor requests** list page, open a request that has a request type of **Status change**.

3.  In the **New status change request** form, in the workflow message bar, click **Actions** \> **View history**.

4.  In the **Workflow history** form, view the status of the request, and view the names of employees who are assigned to each workflow task.

5.  On the **Details** tab, view details about the completed steps in the workflow for this vendor request.

For more information about workflow, see [Workflow history (form)](https://technet.microsoft.com/en-us/library/hh597256\(v=ax.60\)).

Back to top

## Find form help

[New status change request (form)](https://technet.microsoft.com/en-us/library/hh227558\(v=ax.60\))

[Workflow history (form)](https://technet.microsoft.com/en-us/library/hh597256\(v=ax.60\))

## Find related tasks

[Set up vendor status change requests](set-up-vendor-status-change-requests.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

