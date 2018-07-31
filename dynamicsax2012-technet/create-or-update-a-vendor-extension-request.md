---
title: Create or update a vendor extension request
TOCTitle: Create or update a vendor extension request
ms:assetid: 393932d5-190e-4ced-a14d-5de204f4e27e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh271500(v=AX.60)
ms:contentKeyID: 36384132
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- VendRequestCompanyAdd
- VendRequestCompanyAddEdit
- VendRequestCompanyInfo
- VendRequestCompanyExtension
audience: Application User
ms.search.region: Global
---

# Create or update a vendor extension request 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When a vendor is approved to do business with your organization, it is authorized to provide goods and services in only specified legal entities. Use a vendor extension request to request that a vendor be authorized to do business with your legal entity when it is already doing business with another legal entity in the organization.

For information about vendor requests, see [About vendor requests](about-vendor-requests.md).

## Create a vendor extension request


> [!NOTE]
> <P>Depending on your role or the privileges that are assigned to you, you might need to go to your Employee services site before you complete the procedures in this topic.</P>



1.  Click **Order products** on the top link bar, and then click **Vendor requests** on the Quick Launch.

2.  On the **Vendor requests** list page, click **Vendor**.

3.  On the **New extension request** page, select a vendor, select a contact at the vendor location, and then click **Save and close**.

4.  On the **Edit vendor request** page, select the procurement categories and operating units that you want the vendor to be allowed to do business in.

5.  Change any other data, as necessary, and then enter the business justification for your request.

6.  If questionnaires are listed on the **Questionnaires** FastTab, complete the questionnaires.

7.  Click **Save and close**.

8.  On the workflow message bar, click **Submit**.

## View or modify a vendor extension request

You can modify requests that have a status of **Draft**, **Request cancelled**, or **Request rejected**


> [!NOTE]
> <P>Depending on your role or the privileges that are assigned to you, you might need to go to your Employee services site before you complete the procedures in this topic.</P>



1.  Click **Order products** on the top link bar, and then click **Vendor requests** on the Quick Launch.

2.  Click a request ID. The request must have a request type of **Extension** and a status of **Draft**, **Request cancelled**, or **Request rejected**.

3.  To modify the request, click **Edit**.

4.  Enter your changes, and then click **Save and close**.

5.  On the workflow message bar click **Submit**.

## Delete a vendor extension request

You can delete requests that have a status of **Draft**.

1.  Click **Order products** on the top link bar, and then click **Vendor requests** on the Quick Launch.

2.  Select a request that has a request type of **Extension** and a status of **Draft**.

3.  Click **Delete**.

## Cancel a vendor extension request

You can cancel requests that have a status of **Request submitted** or **Request pending approval**.


> [!NOTE]
> <P>Depending on your role or the privileges that are assigned to you, you might need to go to your Employee services site before you complete the procedures in this topic.</P>



1.  Click **Order products** on the top link bar, and then click **Vendor requests** on the Quick Launch.

2.  Click a request ID that has a request type of **Extension** and a status of **Request submitted** or **Request pending approval**.

3.  On the workflow message bar select **Actions** \> **Cancel** to cancel the request. The request status changes to **Request cancelled**

## View workflow history for a vendor extension request

You can view the workflow history for any vendor extension request that has been submitted for review.


> [!NOTE]
> <P>Depending on your role or the privileges that are assigned to you, you might need to go to your Employee services site before you complete the procedures in this topic.</P>



1.  Click **Order products** on the top link bar, and then click **Vendor requests** on the Quick Launch.

2.  Click a request ID that has a request type of **Extension** and any status other than **Draft**.

3.  On the workflow message bar, select **Actions** \> **View history**. The **Workflow history details** page lists all of the workflow steps completed for the request to this point.

## See also

[About vendor requests](about-vendor-requests.md)

[About workflow for vendor requests](about-workflow-for-vendor-requests.md)

  


