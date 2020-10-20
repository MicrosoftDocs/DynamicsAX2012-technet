---
title: About workflow for vendor requests
TOCTitle: About workflow for vendor requests
ms:assetid: de80fda2-4108-4d86-8f2b-2f21c1a463f4
ms:mtpsurl: https://technet.microsoft.com/library/Hh227413(v=AX.60)
ms:contentKeyID: 36059689
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About workflow for vendor requests 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

All vendor requests are routed by workflow to the workers who are assigned to review them. The reviewers evaluate the requests, and then approve or reject them.

The reviewers are defined in the workflow template. The workflow template can be set up to meet the organization’s needs. For example, it might specify a hierarchical approval, in which the employee’s manager reviews the request. Or, the template might be set up to route requests to one or more reviewers in the buying organization.

The following sections describe the approval process for vendor requests.


> [!NOTE]
> <P>Before a request is approved, the reviewer can expand the scope of the request to allow the vendor to do business in additional legal entities and procurement categories as appropriate for the business.</P>



## Workflow for new vendor requests

An employee submits a request for a new vendor. After the request is approved by the reviewer, the request is routed through the remaining steps in the workflow process.

1.  A prospective vendor invitation is sent to the vendor contact who is specified on the request. Using the Web address and credentials that were included in the invitation, the vendor contact logs on to the Vendor portal. In the Vendor portal, the contact completes the vendor profile and submits it for review.

2.  The profile is routed to the reviewer for evaluation.

3.  If the reviewer approves the request, the vendor is added to the vendor master list as a vendor in the approved procurement categories and legal entities.

4.  The vendor is sent a notification informing them whether their application was approved or rejected. If the application was rejected, the vendor can provide additional information and resubmit the application.

## Workflow for vendor extension requests and vendor category extension requests

An employee submits a request to extend a vendor into legal entities or additional product categories. After the request is approved by the reviewer, the request is routed through the remaining steps in the workflow process. The workflow process is the same for extension requests and vendor category extension requests.

1.  The request is routed to the vendor for confirmation.

2.  In the Vendor portal, the vendor reviews the request and confirms that they are willing to do business in the specified legal entity and procurement categories.

3.  The revised vendor profile is routed to the reviewer.

4.  If the reviewer approves the updated vendor profile, the vendor is added to the master vendor list as a vendor in the procurement categories and legal entities approved by the reviewer.

5.  The vendor confirmation is routed back to the vendor with a status of **Request Approved**.

## Workflow for vendor status change requests

An employee submits a request to change the hold status for a vendor. After the request is approved by the reviewer, the request is routed through the remaining steps in the workflow process.

1.  If the reviewer approves the request, the vendor hold is removed and the employee can conduct business with the vendor.

2.  The request is routed back to the requester with a status of **Request Approved**.

## See also

[About vendor requests](about-vendor-requests.md)

  


