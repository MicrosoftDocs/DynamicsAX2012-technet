---
title: Maintain signing limit requests for your workers
TOCTitle: Maintain signing limit requests for your workers
ms:assetid: 7a9ec1b3-0ce5-4696-932c-50232d0f4a73
ms:mtpsurl: https://technet.microsoft.com/library/Hh271573(v=AX.60)
ms:contentKeyID: 36384204
author: Khairunj
ms.date: 12/02/2020
mtps_version: v=AX.60
f1_keywords:
- HRPEditMyReportsLimits
audience: Application User
ms.search.region: Global
---

# Maintain signing limit requests for your workers 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A signing limit defines the largest financial commitment that a worker is authorized to make on behalf of an employer. As a direct result of the worker's spending activity, and subsequent approval of the activity by the worker's manager, the organization may enter into a contractual relationship with a third party. For example, a purchase order may be issued to a vendor.

Managers can accept, reject, or modify a worker's request for a signing limit. Managers can also reduce the amount of the signing limit for an individual worker, and revoke signing limits when appropriate.

## Approve or reject a signing limit request

When a worker submits a signing limit request, the worker's manager receives an e-mail notification that a request is pending the manager's approval.

1.  Click **Approvals** on the top link bar, and then click **Signing limits** on the Quick Launch.

2.  On the **Manage signing limits** page, select the limit request that is pending approval.

3.  Click **View signing limit request**.

4.  Do one of the following:
    
      - To approve the request, click **Action** \> **Approve** in the workflow message bar.
    
      - To reject the request, click **Action** \> **Reject** in the workflow message bar, and then enter a reason in the comment box.

## Delegate the review of a signing limit request to another user

Typically, the manager is responsible for reviewing signing limit requests, and accepting or rejecting them. However, the manager can delegate the responsibility for reviewing requests to another Microsoft Dynamics AX user.


> [!NOTE]
> <P>The configuration of the template for the signing limit workflow determines which user receives a signing limit request for review. Typically, the worker's manager approves the signing limit request. However, some organizations centralize the responsibility for reviewing signing limit requests. For information about the configuration of the signing limit workflow, contact your system administrator.</P>



1.  Click **Approvals** on the top link bar, and then click **Signing limits** on the Quick Launch.

2.  Click the document link for the signing limit request that you want to delegate.

3.  On the **View signing limit request** page, click **Action** \> **Delegate** in the workflow message bar.

4.  Select a user, and then enter a comment to explain why you are delegating the signing limit request to the user. Then click **OK**.

## Modify a worker's signing limit

You can modify signing limits that you have already approved.

1.  Click **Approvals** on the top link bar, and then click **Signing limits** on the Quick Launch.

2.  On the **Manage Signing Limit Requests** page, in the **My Reports Signing Limit** section, select an approved signing limit request.

3.  On the **Edit My Reports Signing Limits** page, modify the signing limit, and then click **OK**.

## See also

[About signing limits](about-signing-limits.md)

[Create and maintain signing limit requests](create-and-maintain-signing-limit-requests.md)

  


