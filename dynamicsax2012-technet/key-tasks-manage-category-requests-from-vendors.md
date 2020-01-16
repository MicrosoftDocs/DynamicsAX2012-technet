---
title: 'Key tasks: Manage category requests from vendors'
TOCTitle: 'Key tasks: Manage category requests from vendors'
ms:assetid: 2abe85e7-d779-418a-8a98-4d021738a62e
ms:mtpsurl: https://technet.microsoft.com/library/JJ735273(v=AX.60)
ms:contentKeyID: 49693274
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Key tasks: Manage category requests from vendors 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Vendors who are approved to do business in a procurement category in your organization might want to extend their business to supply products in additional procurement categories. The vendor submits the category application request in the Vendor portal in Enterprise Portal for Microsoft Dynamics AX.

When a vendor submits a new category request, the vendor specifies the procurement categories that they want to do business in and submits the request to workflow. A category request is routed via workflow to an approver. Category requests are displayed on the **Vendor requests** list page in the Microsoft Dynamics AX client.

The status of the vendor category request changes as you process the request in workflow. For more information, see [About workflow statuses for category extension requests](about-workflow-statuses-for-category-extension-requests.md).

## What do you want to do?

Learn more about...

Approve a vendor request

Reject a vendor request

Delegate review of a vendor request

View the workflow history for a category request

Find form help

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[Vendor category requests overview](vendor-category-requests-overview.md)

[About vendor request configuration](about-vendor-request-configuration.md)

## Approve a vendor request

Use this procedure to approve a new category request from a vendor.

1.  Click **Procurement and sourcing** \> **Common** \> **Vendor requests** \> **Vendor requests**. On the **Vendor requests** list page, open a request that has a request type of **Category**.

2.  In the **Vendor category approval** form, on the **Categories** FastTab, view the requested procurement category.

3.  Optionally, you can add or remove procurement categories before you approve the request. On the **Action Pane**, click **Edit**. Use the following procedures to modify the request:
    
      - To add a procurement category to the request, on the **Categories** FastTab, click **New**, and then select a category.
    
      - To remove a procurement category, on the **Categories** FastTab, select the check box for the category that you want to remove, and then click **Delete**.

4.  On the **Business justification** FastTab, view the justification for the request.

5.  If the vendor has attached a document to the request, on the **Action Pane**, click **Attachments**.

6.  If your organization requires a vendor to complete a questionnaire to do business in a procurement category, on the **Questionnaire information** FastTab, open the questionnaire to view the responses.

7.  To approve the category request, in the workflow message bar, click **Actions** \> **Approve**.

If workflow is configured to notify the vendor, the vendor is sent an e-mail message that the category request is approved. The vendor can also see the status of the category request in the Vendor portal in Enterprise Portal.

Back to top

## Reject a vendor request

Use this procedure to reject a category request from a vendor.

1.  Click **Procurement and sourcing** \> **Common** \> **Vendor requests** \> **Vendor requests**. On the **Vendor requests** list page, open a request that has a request type of **Category**.

2.  In the **Vendor category approval** form, on the **Categories** FastTab, view the requested procurement categories.

3.  On the **Business justification** FastTab, view the justification for the request.

4.  To reject the categories in the request, in the workflow message bar, click **Actions** \> **Reject**.

If workflow is configured to notify the vendor, the vendor is sent an e-mail message that the category request is rejected. The vendor can also see the status of the category request in the Vendor portal in Enterprise Portal. The vendor can add details and then resubmit the category request.

Back to top

## Delegate review of a vendor request

Use this procedure to delegate the review of a vendor category request to another reviewer.

1.  Click **Procurement and sourcing** \> **Common** \> **Vendor requests** \> **Vendor requests**. On the **Vendor requests** list page, open a request that has a request type of **Category**.

2.  In the **Vendor category approval** form, in the workflow message bar, click **Actions** \> **Delegate**.

The selected reviewer is notified via workflow to review the vendor category request.

Back to top

## View the workflow history for a category request

Use this procedure to view the workflow history for a vendor category request. The workflow history includes information about who created the workflow work item, the time and date when the work item was created, a list of actions associated with the work item, and any comments that were entered during the workflow process.

1.  Click **Procurement and sourcing** \> **Common** \> **Vendor requests** \> **Vendor requests**. On the **Vendor requests** list page, open a request that has a request type of **Category**.

2.  In the **Vendor category approval** form, in the workflow message bar, click **Actions** \> **View history**. For more information, see [Workflow history (form)](https://technet.microsoft.com/library/hh597256\(v=ax.60\)).

Back to top

## Find form help

[Vendor category approval (form)](https://technet.microsoft.com/library/hh227618\(v=ax.60\))

[Vendor requests (list page)](https://technet.microsoft.com/library/hh242710\(v=ax.60\))

  


