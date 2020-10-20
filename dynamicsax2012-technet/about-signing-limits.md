---
title: About signing limits
TOCTitle: About signing limits
ms:assetid: 9f3d1376-d969-45a9-a958-0cfe33d36cf9
ms:mtpsurl: https://technet.microsoft.com/library/Hh271613(v=AX.60)
ms:contentKeyID: 36384245
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About signing limits 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A key element of financial risk management for organizations is managing expenditure. Managing expenditure includes strengthening internal controls and making sure that workers comply with these controls. Signing limits are an important part of expenditure controls and compliance.

A signing limit defines the largest financial commitment that a worker is authorized to make on behalf of an employer. As a direct result of the worker’s spending activity, and his manager’s subsequent approval activity, the organization may enter into a contractual relationship with a third party. For example, a purchase order may be issued to a vendor.

There are two types of signing limits: spending limits and approval limits. A **spending limit** is the amount that a worker can spend on business-related purchases. An **approval limit** is the maximum amount that a worker is authorized to approve for a specific business document. Signing limits can differ per transaction type, such as purchase requisitions, expense reports, purchase orders, or invoices.

Organizations assign default signing limits based on a worker’s job or compensation level. Depending on how signing limits are configured, a worker obtains a default signing limit in one of the following ways:

  - The worker is automatically assigned the default signing limit for their job or compensation level.

  - The worker must submit a signing limit request in the employee self-service portal.

Signing limit agreements are time-limited. Before an agreement expires, a worker must renew it to confirm that he agrees to comply with the policy. After a signing limit expires, the worker cannot make purchases until it is renewed.

## Process overview: Spending and approval limits

The process of configuring and activating signing limits involves the following steps:

1.  An administrator selects the signing limit basis.

2.  If required, the administrator restricts signing limits to users who have an employee record in Microsoft Dynamics AX.

3.  If required, the administrator configures signing limits to require workers to request the default signing limit amount for their job or compensation level. Requests are submitted in the employee self-service portal in Enterprise Portal.

4.  The administrator defines the default spending limits and approval limits, by transaction type, for each job or compensation level.
    

    > [!NOTE]
    > <P>Default signing limits for a job or compensation level can be defined differently for different legal entities in an organization. Within a legal entity, they can also be defined differently in different areas, such as department or cost center. Employees who are assigned a position in more than one legal entity in an organization might have different default signing limits in each legal entity.</P>



5.  When a worker is hired, she is assigned a specific job or compensation level in Microsoft Dynamics AX.
    
      - If signing limits are configured to automatically grant limits to workers based on job or compensation level, the worker is automatically granted a signing limit on that basis.
    
      - If signing limits are configured to require workers to request signing limits for their job or compensation level, the worker must submit a request in the employee self-service portal.

6.  The worker’s manager reviews the limit request and approves or rejects it. A manager can also revoke a signing limit at any point.

After a spending limit is set up for a worker, the worker can make purchases within their limit amounts. Spending limits are invoked at the time of purchase. Approval limits are invoked as a part of the document approval cycle, when the worker’s manager approves the purchase.

## Example: Spending limit

Prakash is a project manager. As the person responsible for the on-time delivery of the project, Prakash must be able to make catalog purchases for business software and hardware. The default spending limit defined for his job is 500 USD. However, to make the purchases that are required to meet his project deadline, Prakash needs a higher spending limit. He submits a request to increase his spending limit to 2,500 USD. A limit of this amount enables him to purchase items and services costing up to 2,500 USD.

Prakash’s spending limit request flows to Reina, the resource manager on the project, who approves the request. Prakash can now make catalog purchases of up to 2,500 USD, which is 2,000 USD over the default signing limit defined for his job.

If Prakash needs a higher spending limit for a specific purchase over 2,500 USD, he can submit a request for a one-time spending limit increase.

## Example: Approval limit

Reina is a project resource manager at Fabrikam, Inc. For managers at Reina’s level, a default approval limit of 2,000 USD is set for purchase requisitions.

Fabrikam has configured signing limits to require workers to submit signing limit requests. Limits are not granted automatically. If Reina were to request the default approval limit of 2,000 USD, her request would be granted without having to pass through the approval workflow. However, Reina’s workers require spending limits over 2,000 USD for purchase requisitions. Reina submits an approval limit request for 2,500 USD. June, the product division manager, approves the request. Now Reina can approve purchases made by her workers up to 2,500 USD.

## Example: Renewing signing limit agreements

Signing limit agreements are time-limited. Workers must renew them periodically to confirm that they agree to comply with the policy. For example, Prakash has a spending limit for purchase requisitions. When he requested this signing limit, he read the “Purchasing Terms” agreement and agreed to its terms on June 1, 2011. The duration of the agreement was defined as 12 months. Therefore, his confirmation expires on June 1, 2012. Before this date, he must reconfirm his agreement to comply with the “Purchasing Terms” agreement.

The **Open agreement** period that is defined for Prakash’s spending limit is two months. Starting on April 1, 2012, the **Signing limit confirmation** page will be available for Prakash to renew his signing limit. Between April 1, 2012 and May 31, 2012, Prakash can go this page and renew his signing limit. If he does not renew his signing limit during this period, his signing limit will expire and he will not be able to make purchases until this task is completed.

## See also

[Create and maintain signing limit requests](create-and-maintain-signing-limit-requests.md)

[Maintain signing limit requests for your workers](maintain-signing-limit-requests-for-your-workers.md)

  


