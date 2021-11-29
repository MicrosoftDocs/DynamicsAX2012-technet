---
title: Create or update a new vendor request
TOCTitle: Create or update a new vendor request
ms:assetid: 035cdd9b-f46b-4a8f-abe2-b6a21628a9d5
ms:mtpsurl: https://technet.microsoft.com/library/Hh271441(v=AX.60)
ms:contentKeyID: 36384074
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- VendRequestCompanyAdd
- VendRequestCompanyAddEdit
- VendRequestCompanyInfo
audience: Application User
ms.search.region: Global
---

# Create or update a new vendor request 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Enterprise Portal for Microsoft Dynamics AX, employees can submit new vendor requests to obtain approval to do business with a vendor who is not already on the list of approved vendors.

## Create a new vendor request

The controls that appear in this form may vary, depending on the configuration of your system.


> [!NOTE]
> <P>Depending on your role or the privileges that are assigned to you, you might need to go to your Employee services site before you complete the procedures in this topic.</P>



1.  Click **Order products** on the top link bar, and then click **Vendor requests** on the Quick Launch.

2.  On the **Action Pane**, on the **Requests** tab, click **Vendor request**.

3.  On the **New vendor request** page, enter the name of the requester, the vendor name, and the vendor contact, and then click **Create**.

4.  Optional: On the **Edit vendor request** page, enter information about the vendor address and vendor contact. Then select the procurement categories and operating units that you want the vendor to be allowed to do business in.

5.  Provide a business justification for selecting this vendor.

6.  If questionnaires are listed on the **Questionnaires** FastTab, complete the questionnaires.

7.  Click **Save and close**.

8.  In the workflow message bar, click **Submit**.


> [!NOTE]
> <P>New vendor requests are routed for review through the workflow system. For more information about the vendor workflow, see <A href="about-workflow-for-vendor-requests.md">About workflow for vendor requests</A>.</P>



## View or modify a new vendor request

The **Vendor requests** list page displays all the vendor requests that you have created. To view the details about a new vendor request, click the request ID. Only requests that have a status of **Draft**, **Request cancelled**, or **Request rejected** can be modified.


> [!NOTE]
> <P>Depending on your role or the privileges that are assigned to you, you might need to go to your Employee services site before you complete the procedures in this topic.</P>



1.  Click **Order products** on the top link bar, and then click **Vendor requests** on the Quick Launch.

2.  Click a request ID.

3.  On the **View vendor request** page, on the **Action Pane**, click **Edit**.

4.  Make the required changes to the fields in the request, and then click **Save and close**.

5.  In the workflow message bar, click **Submit**.

## Delete a new vendor request

You can delete requests that have a status of **Draft**.


> [!NOTE]
> <P>Depending on your role or the privileges that are assigned to you, you might need to go to your Employee services site before you complete the procedures in this topic.</P>



1.  Click **Order products** on the top link bar, and then click **Vendor requests** on the Quick Launch.

2.  Select a request that has a request type of **Company** and a status of **Draft**.

3.  Click **Delete**.

## Cancel a new vendor request

You can cancel new vendor requests that have a status of **Request submitted** or **Request pending approval**.


> [!NOTE]
> <P>Depending on your role or the privileges that are assigned to you, you might need to go to your Employee services site before you complete the procedures in this topic.</P>



1.  Click **Order products** on the top link bar, and then click **Vendor requests** on the Quick Launch.

2.  Click a request ID.

3.  In the workflow message bar, click **Actions** \> **Cancel** to cancel the request. The request status changes to **Request cancelled**.

## View the workflow history for a new vendor request

You can view the workflow history for any new vendor request that has been submitted for review.


> [!NOTE]
> <P>Depending on your role or the privileges that are assigned to you, you might need to go to your Employee services site before you complete the procedures in this topic.</P>



1.  Click **Order products** on the top link bar, and then click **Vendor requests** on the Quick Launch.

2.  Click a request ID.

3.  In the workflow message bar, click **Actions** \> **View history**. The **Workflow history details** page lists all the workflow steps that have been completed for the request.

## See also

[About vendor requests](about-vendor-requests.md)

[About workflow for vendor requests](about-workflow-for-vendor-requests.md)

  


