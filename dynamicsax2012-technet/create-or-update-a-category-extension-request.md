---
title: Create or update a category extension request
TOCTitle: Create or update a category extension request
ms:assetid: 6e7fda7a-e095-409e-9270-a14b43a79f4f
ms:mtpsurl: https://technet.microsoft.com/library/Hh271559(v=AX.60)
ms:contentKeyID: 36384190
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- VendRequestCategoryEmployAdd
- VendRequestCategoryEmployEdit
- VendRequestCategoryEmployInfo
audience: Application User
ms.search.region: Global
---

# Create or update a category extension request 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When vendors are approved to provide products in your organization, they are granted permission to provide items and services only in specific legal entities. In those legal entities, the vendors are granted permission to provide items and services only in specific procurement categories. Procurement categories help classify vendor items and services. Procurement categories also help control the vendors and products that are available to employees when they make business-related purchases. Additionally, purchasing managers use these categories to measure and report on the overall health of the purchasing organization, and to evaluate vendor performance.

As an employee, you can submit a request to extend a vendor into additional procurement categories for your legal entity.

**Example**

Fabrikam is a print media specialist and an advertising specialist. You want to use Fabrikam for print media services, but this vendor is only authorized to do business in the "Advertising" procurement category. Therefore, you create a category extension request to ask the purchasing department to add Fabrikam to the "Print media" procurement category. Your request is reviewed by the purchasing department, and approved or rejected as appropriate for the business.


> [!NOTE]
> <P>Depending on your role or the privileges that are assigned to you, you might need to go to your Employee services site before you complete the procedures in this topic.</P>



## Create a category extension request

1.  Click **Order products** on the top link bar, and then click **Vendor requests** on the Quick Launch.

2.  On the **Action Pane**, on the **Request** tab, click **Categories**.

3.  On the **Category request** page, enter the name of the requester, select the vendor and vendor contact, and then click **Create**.

4.  On the **Edit category request** page, select the procurement categories and operating units in which you want the vendor to be authorized to do business.

5.  Enter the business justification for your request.

6.  If questionnaires are listed on the **Questionnaires** FastTab, complete the questionnaires.

7.  Click **Save and close**.

8.  In the workflow message bar, click **Submit**.

Vendor category extension requests are routed through workflow for review. Vendor requests can have the following statuses:

  - **Draft** – The request has been saved, but it has not been submitted for approval.

  - **Request cancelled** – The request has been canceled by the user who created the request.

  - **Request submitted** – The request has been routed for approval.

  - **Request pending approval** – The request has been submitted to workflow and is awaiting review.

  - **Request approved** – The request has been approved.

  - **Request rejected** – The request was rejected. You can review the reason code and comments that are associated with the rejection by workflow.
    

    > [!NOTE]
    > <P>When a request is rejected, the reviewer can provide a reason for the rejection. If applicable, you can provide more information and resubmit the request.</P>



  - **Category request ready** – The request was approved. A notification is sent to the vendor. The notification requests that the vendor respond to the vendor category confirmation.

For more information about the vendor workflow, see [About workflow for vendor requests](about-workflow-for-vendor-requests.md).

## View or change a category extension request

The **Vendor requests** page displays all of the vendor requests that you have created. You can view the details of a category extension request by clicking the request ID. Only requests that have a status of **Draft**, **Request cancelled**, or **Request rejected** can be modified.

1.  Click **Order products** on the top link bar, and then click **Vendor requests** on the Quick Launch.

2.  Click a request ID. The request must have a request type of **Category**, and a status of **Draft**, **Request cancelled**, or **Request rejected**.

3.  On the **View category request** page, on the **Action Pane**, click **Edit**.

4.  Change the fields in the request as necessary. When you have finished, click **Save and close**.

5.  In the workflow message bar, click **Submit**.

## Delete a category extension request

You can delete requests that have a status of **Draft**.

1.  Click **Order products** on the top link bar, and then click **Vendor requests** on the Quick Launch.

2.  Select a request that has a request type of **Category** and a status of **Draft**.

3.  Click **Delete**.

## Cancel a category extension request

You can cancel category extension requests that have a status of **Request submitted** or **Request pending approval**.

1.  Click **Order products** on the top link bar, and then click **Vendor requests** on the Quick Launch.

2.  Click a request ID that has a request type of **Category**, and a status of **Request submitted** or **Request pending approval**.

3.  In the workflow message bar, click **Actions** \> **Cancel** to cancel the request. The request status changes to **Request cancelled**.

## View the workflow history for a category extension request

You can view the workflow history for any category extension request that has been submitted for review.

1.  Click **Order products** on the top link bar, and then click **Vendor requests** on the Quick Launch.

2.  Click a request ID that has a request type of **Category** and any status other than **Draft**.

3.  In the workflow message bar, click **Actions** \> **View history**. The **Workflow history details** page lists all of the workflow steps that have been completed for the request.

## See also

[About vendor requests](about-vendor-requests.md)

[About workflow for vendor requests](about-workflow-for-vendor-requests.md)

  


