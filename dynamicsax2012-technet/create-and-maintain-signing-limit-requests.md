---
title: Create and maintain signing limit requests
TOCTitle: Create and maintain signing limit requests
ms:assetid: d36c6855-1fae-4f41-a1fd-50f867203ae8
ms:mtpsurl: https://technet.microsoft.com/library/Hh271654(v=AX.60)
ms:contentKeyID: 36384286
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- HRPLimitCreate
- HRPLimitNotAllowed
- HRPLimitReAttestation
- HRPManageLimitRequests
- HRPViewLimitRequest
audience: Application User
ms.search.region: Global
---

# Create and maintain signing limit requests 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Signing limits constrain the financial commitments that a worker is authorized to make or approve on behalf of the employer. A worker can have different signing limits for different document types, such as purchase requisitions, expense reports, purchase orders, and invoices. As a direct result of the worker’s spending or approval activity, his employer may enter into a contractual relationship with a third party. For example, a purchase order may be issued to a vendor.

Signing limits can be limited to workers who have an employee record in Microsoft Dynamics AX. This ensures that only employees, and not contract workers, are granted signing limits.

For more information about signing limits, see [About signing limits](about-signing-limits.md).


> [!NOTE]
> <P>Depending on your role or the privileges that are assigned to you, you might need to go to your Employee services site before you complete the procedures in this topic.</P>



## Create a signing limit request

1.  Click **Approvals** on the top link bar, and then click **Signing limits** on the Quick Launch.

2.  On the **Action Pane**, on the **Signing limits** tab, click **New signing limit request**.

3.  In the **Position** field, select the company and position that you are requesting signing limits for.
    

    > [!NOTE]
    > <P>In cases where the employee is employed by more than one legal entity in Microsoft Dynamics AX, multiple choices are available in the <STRONG>Position</STRONG> list.</P>



4.  In the **Limit type** field, select **Approval limit** or **Spending limit**.

5.  If you are requesting a signing limit amount that is larger than the default amount, select the **Request default signing limit override** check box and type the override amount in the **Request default signing limit override** field. You can see the default amount and the currency that is defined for the amount in the **Default signing limit amount, currency** field.

6.  Select an **Effective** date and **Expiration** date and enter a justification that explains why you need this signing limit and, if applicable, why you are requesting a signing limit that exceeds the default amount.

7.  In the **Agreements** section of the page, click the agreements that are associated with the document type that you selected. The agreement opens in a new window.

8.  After you have read and acknowledged the policies that are associated with the selected document type, select the **I accept the terms and conditions** check box, and then click **OK**.

9.  To submit the request for approval, click **Submit** in the Workflow message bar.

10. In the **Signing limits workflow** box, enter any comments about the signing limit request, and then click **Submit**.

## View a signing limit request

You can view a request that you created if it has not completed the approval cycle.

1.  Click **Approvals** on the top link bar, and then click **Signing limits** on the Quick Launch.

2.  In the **Request number** column, click the signing limit request that you want to view.

## Modify a signing limit request

You can modify a signing limit request that you created if it has a status of **Draft**.

1.  Click **Approvals** on the top link bar, and then click **Signing limits** on the Quick Launch.

2.  In the **Created date** column, click the request that you want to change, and then on the **Action Pane**, on the **Signing limits** tab, click **Edit signing limit request**.

## Cancel a signing limit request

You can cancel a signing limit request that you created after it has been submitted and before it has been approved.

1.  Click **Approvals** on the top link bar, and then click **Signing limits** on the Quick Launch.

2.  In the **Created date** column, click the request that you want to cancel, and then on the **Action Pane**, on the **Signing limits** tab, click **Edit signing limit request**.

3.  Click **Action** \> **Cancel** in the Workflow message bar.

4.  Enter a reason for canceling the request, and then click **OK**.

## Delete a signing limit request

You can delete a signing limit request that you created if it has a status of **Draft**.

1.  Click **Approvals** on the top link bar, and then click **Signing limits** on the Quick Launch.

2.  In the **Created date** column, click the request that you want to delete, and then on the **Action Pane**, on the **Signing limits** tab, click **Delete signing limit request**.

## View workflow history for the signing limit request

You can view the workflow history for a request that you created if it has not completed the approval cycle.

1.  Click **Approvals** on the top link bar, and then click **Signing limits** on the Quick Launch.

2.  In the **Created date** column, click the signing limit request that you want to view, and then on the **Action Pane**, on the **Signing limits** tab, click **View signing limit request**.

3.  Click **Action** \> **View history** in the Workflow message bar.

## Renew your signing limit

The signing limit that is granted to a worker is time-limited. You must renew your signing limits periodically to confirm that you agree to comply with the policy.

1.  Click **Approvals** on the top link bar, and then click **Signing limits** on the Quick Launch.

2.  On the **Action Pane**, on the **Signing limits** tab, click **Signing limit agreement confirmation**.

3.  On the **Signing limit agreement confirmation** page, in the **Agreements** section, review the agreement that you want to renew, and then select the **I accept the terms and conditions** check box.

Your signing limit is renewed for the number of months displayed in the **Confirmation period (in months)** field.

## See also

[About signing limits](about-signing-limits.md)

[Maintain signing limit requests for your workers](maintain-signing-limit-requests-for-your-workers.md)

  


