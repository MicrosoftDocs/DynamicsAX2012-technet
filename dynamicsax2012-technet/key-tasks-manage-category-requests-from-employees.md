---
title: 'Key tasks: Manage category requests from employees'
TOCTitle: 'Key tasks: Manage category requests from employees'
ms:assetid: e304e9ef-0efa-4e21-b86b-6a5b3a364dd5
ms:mtpsurl: https://technet.microsoft.com/library/JJ735275(v=AX.60)
ms:contentKeyID: 49693276
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Key tasks: Manage category requests from employees 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When a vendor is approved to provide items and services to your legal entity, the vendor is authorized to provide them only in specific procurement categories. Employees can request that a vendor be authorized to do business in additional procurement categories. Requests are submitted in the Employee services site in Enterprise Portal for Microsoft Dynamics AX.

Category requests include the procurement categories and a justification for the request to add those categories. The request is routed via workflow to an approver. When the request is approved, the vendor is sent a request to confirm their ability to supply items and services in the requested categories.

Category requests are displayed on the **Vendor requests** list page in the Microsoft Dynamics AX client. The status of the category request appears on the list page and changes as the request is processed in workflow. For more information, see [About workflow statuses for category extension requests](about-workflow-statuses-for-category-extension-requests.md).

## What do you want to do?

Learn more about...

Maintain category requests from employees

Maintain vendor category confirmations

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[Vendor category requests overview](vendor-category-requests-overview.md)

[About vendor request configuration](about-vendor-request-configuration.md)

## Maintain category requests from employees

Use these procedures to approve and reject category requests from employees. You can also delegate these tasks to another reviewer and view the workflow history of an employee’s category request.

### Approve a category request

1.  Click **Procurement and sourcing** \> **Common** \> **Vendor requests** \> **Vendor requests**. On the **Vendor requests** list page, open a request of the **Category** request type that has a status of **Request pending approval**.

2.  In the **Vendor category request** form, on the **Categories** FastTab, view the requested procurement categories.

3.  Optionally, you can add or remove procurement categories before you approve the request. On the **Action Pane**, click **Edit**. Use the following procedures to modify the request:
    
      - To add a procurement category to the request, on the **Categories** FastTab, click **New**, and then select a category.
    
      - To remove a procurement category, on the **Categories** FastTab, select the check box for the category that you want to remove, and then click **Delete**.

4.  On the **Business justification** FastTab, view the employee’s justification for the request.

5.  If the employee attached a document to the request, on the **Action Pane**, click **Attachments**.

6.  To approve the category request, in the workflow message bar, click **Actions** \> **Approve**.

If workflow is configured to notify the vendor, the vendor is sent an e-mail message to complete a category confirmation. The employee can view the status of the category request in the Employee services site in Enterprise Portal.

### Reject a category request

1.  Click **Procurement and sourcing** \> **Common** \> **Vendor requests** \> **Vendor requests**. On the **Vendor requests** list page, open a request of the **Category** request type that has a status of **Request pending approval**.

2.  In the **Vendor category request** form, on the **Categories** FastTab, view the requested procurement categories.

3.  On the **Business justification** FastTab, view the justification for the request.

4.  To reject the categories in the request, in the workflow message bar, click **Actions** \> **Reject**.

The employee can see the status of the category request in the Employee services site in Enterprise Portal. The employee can add details and resubmit the request.

### Delegate review of a category request

1.  Click **Procurement and sourcing** \> **Common** \> **Vendor requests** \> **Vendor requests**. On the **Vendor requests** list page, open a request of the **Category** request type that has a status of **Request pending approval**.

2.  In the **Vendor category request** form, on the **Categories** FastTab, view the requested procurement categories.

3.  On the **Business justification** FastTab, view the justification for the request.

4.  To delegate review of the request, in the workflow message bar, click **Actions** \> **Delegate**.

The selected reviewer is notified via workflow to review the request.

### View the workflow history for a category request

1.  Click **Procurement and sourcing** \> **Common** \> **Vendor requests** \> **Vendor requests**. On the **Vendor requests** list page, open a request that has a request type of **Category**.

2.  In the **Vendor category request** form, in the workflow message bar, click **Actions** \> **View history**.

The workflow history includes information about who created the workflow work item, the time and date when the work item was created, a list of actions associated with the work item, and any comments that were entered during the workflow process. For more information, see [Workflow history (form)](https://technet.microsoft.com/library/hh597256\(v=ax.60\)).

Back to top

## Maintain vendor category confirmations

When you approve an employee’s request to authorize a vendor to do business in procurement categories, the vendor is sent a request via workflow to confirm their ability to supply items and services in the requested categories. Use these procedures to approve or reject a vendor category confirmation. You can also delegate these tasks to another reviewer and view the workflow history of the vendor category confirmation.

### Approve a vendor category confirmation

1.  Click **Procurement and sourcing** \> **Common** \> **Vendor requests** \> **Vendor requests**. On the **Vendor requests** list page, open a request of the **Category** request type that has a status of **Application pending approval**.

2.  In the **Vendor category approval** form, on the **Categories** FastTab, view the requested procurement categories.

3.  On the **Questionnaires** FastTab, view the vendor’s responses to a questionnaire, if applicable.

4.  If the vendor attached a document to the confirmation, on the **Action Pane**, click **Attachments**.

5.  To approve the confirmation, in the workflow message bar, click **Actions** \> **Approve**.

If workflow is configured to notify the vendor, the vendor is sent an e-mail message that the category confirmation is approved and the vendor is authorized to provide products in the additional procurement category. The vendor can also see the status of the category confirmation in the Vendor services portal in Enterprise Portal.

### Reject a vendor category confirmation

1.  Click **Procurement and sourcing** \> **Common** \> **Vendor requests** \> **Vendor requests**. On the **Vendor requests** list page, open a request of the **Category** request type that has a status of **Application pending approval**.

2.  In the **Vendor category approval** form, on the **Categories** FastTab, view the requested procurement categories.

3.  On the **Questionnaires** FastTab, view the vendor’s responses to a questionnaire, if applicable.

4.  If the vendor attached a document to the confirmation, on the **Action Pane**, click **Attachments**.

5.  To reject the confirmation, in the workflow message bar, click **Actions** \> **Reject**.

If workflow is configured to notify the vendor, the vendor is sent an e-mail message that the category confirmation is rejected. The vendor can also see the status of the category confirmation in the Vendor services portal in Enterprise Portal. The vendor can add details and resubmit the category confirmation.

### Delegate review of a vendor category confirmation

1.  Click **Procurement and sourcing** \> **Common** \> **Vendor requests** \> **Vendor requests**. On the **Vendor requests** list page, open a request of the **Category** request type that has a status of **Application pending approval**.

2.  In the **Vendor category approval** form, on the **Categories** FastTab, view the requested procurement categories.

3.  On the **Questionnaires** FastTab, view the vendor’s responses to a questionnaire, if applicable.

4.  If the vendor attached a document to the confirmation, on the **Action Pane**, click **Attachments**.

5.  To delegate review of the confirmation, in the workflow message bar, click **Actions** \> **Delegate**.

The selected reviewer is notified via workflow to review the vendor category confirmation.

### View the workflow history for a category confirmation

1.  Click **Procurement and sourcing** \> **Common** \> **Vendor requests** \> **Vendor requests**. On the **Vendor requests** list page, open a request of the **Category** request type that has a status of **Application pending approval**.

2.  In the **Vendor category request** form, in the workflow message bar, click **Actions** \> **View history**.

The workflow history includes information about who created the workflow work item, the time and date when the work item was created, a list of actions associated with the work item, and any comments that were entered during the workflow process. For more information, see [Workflow history (form)](https://technet.microsoft.com/library/hh597256\(v=ax.60\)).

Back to top

## Find form help

[Vendor category request (form)](https://technet.microsoft.com/library/hh227509\(v=ax.60\))

[Vendor category approval (form)](https://technet.microsoft.com/library/hh227618\(v=ax.60\))

## Find related tasks

[Key tasks: Set up vendor category requests](key-tasks-set-up-vendor-category-requests.md)

[Key tasks: Manage category requests from vendors](key-tasks-manage-category-requests-from-vendors.md)

  


