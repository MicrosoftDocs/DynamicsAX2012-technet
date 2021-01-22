---
title: Create or update a vendor status change request
TOCTitle: Create or update a vendor status change request
ms:assetid: 51303009-51bb-4b99-9e0f-aedb45897c97
ms:mtpsurl: https://technet.microsoft.com/library/Hh271531(v=AX.60)
ms:contentKeyID: 36384163
author: Khairunj
ms.author: daxcpft
ms.date: 05/01/2014
mtps_version: v=AX.60
f1_keywords:
- VendRequestStatusChangeAdd
- VendRequestStatusChangeEdit
- VendRequestStatusChangeInfo
audience: Application User
ms.search.region: Global
---

# Create or update a vendor status change request 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use a vendor status change request to request a change to a vendor's hold status. A vendor's hold status determines whether purchase orders can be created for the vendor, whether the vendor invoice can be paid, and so on.


> [!NOTE]
> <P>Depending on your role or the privileges that are assigned to you, you might need to go to your Employee services site before you complete the procedures in this topic.</P>



## Create a vendor status change request

1.  Click **Order products** on the top link bar, and then click **Vendor requests** on the Quick Launch.

2.  On the **Vendor requests** page, click **Vendor status**.

3.  On the **Vendor status change request** page, select your name in the **Requester** field, and then select the vendor account number in the **Vendor account** field.

4.  In the **Requested status** field, select the appropriate status. The following values are available:
    
      - **No** – No transaction types are on hold for this vendor. All types of transactions are permitted.
    
      - **Invoice** – No invoices can be created or posted for this vendor.
    
      - **All** – All transactions for this vendor are on hold.
    
      - **Payment** – No payments can be generated for this vendor. Payments that were generated before the hold was applied can be posted.
    
      - **Requisition** – No requisitions that reference this vendor can be created.
    
      - **Never** – No transaction types are on hold for this vendor, and the vendor cannot automatically be put on hold because of inactivity. This status is used for vendors who are used regularly but rarely. For example, you can use the **Never** hold status for a vendor that performs some kind of annual maintenance.

5.  Click **Create**. The **Vendor status change request** page displays more details about the vendor, such as the vendor address and contact information.

6.  Enter the business justification for the request, and then click **Save and close**.

7.  In the workflow message bar, click **Submit**.

## View or update a vendor status change request

The **Vendor requests** page displays all of the vendor requests that you have created. You can view the details of a status change request by clicking the request ID. Only requests that have a status of **Draft**, **Request cancelled**, or **Request rejected** can be updated.

1.  Click **Order products** on the top link bar, and then click **Vendor requests** on the Quick Launch.

2.  Click a request ID. The request must have a request type of **Status change**, and a status of **Draft**, **Request cancelled**, or **Request rejected**.

3.  On the **View vendor status change request** page, on the **Action Pane**, click **Edit**.

4.  Change the fields in the request as necessary, and then click **Save and close**.

5.  In the workflow message bar, click **Submit**.

## Delete a vendor status change request

You can delete requests that have a status of **Draft**.

1.  Click **Order products** on the top link bar, and then click **Vendor requests** on the Quick Launch.

2.  Select a request that has a request type of **Status change** and a status of **Draft**.

3.  Click **Delete**.

## Cancel a vendor status change request

You can cancel vendor status change requests that have a status of **Request submitted** or **Pending approval**.

1.  Click **Order products** on the top link bar, and then click **Vendor requests** on the Quick Launch.

2.  Click a request ID that has a request type of **Status change**, and a status of **Request submitted** or **Pending approval**.

3.  In the workflow message bar, click **Actions** \> **Cancel**.

## View the workflow history for a vendor status change request

You can view the workflow history for any vendor status change request that has been submitted for review.

1.  Click **Order products** on the top link bar, and then click **Vendor requests** on the Quick Launch.

2.  Click a request ID that has a request type of **Status change** and any status other than **Draft**.

3.  In the workflow message bar, click **Actions** \> **View history**.

The **Workflow history details** page lists all of the workflow steps that have been completed for the request.

## See also

[About vendor requests](about-vendor-requests.md)

[About workflow for vendor requests](about-workflow-for-vendor-requests.md)

  


