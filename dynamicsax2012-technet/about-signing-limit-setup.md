---
title: About signing limit setup
TOCTitle: About signing limit setup
ms:assetid: 4bb412bd-a922-4ac6-bb08-cdbca8044182
ms:mtpsurl: https://technet.microsoft.com/library/Hh208731(v=AX.60)
ms:contentKeyID: 36057002
author: tonyafehr
ms.author: daxcpft
ms.date: 06/13/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About signing limit setup 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Expenditure management is a key part of financial risk management for organizations. Expenditure management involves strengthening internal controls and making sure that workers comply with these controls. Signing limits are an important part of the controls and compliance for expenditure management.

A signing limit defines the largest financial commitment that a worker is authorized to make on behalf of an employer. As a direct result of a worker's spending activity, and approval of the spending activity by the worker's manager, the organization may form a contractual relationship with a third party. For example, a purchase order may be issued to a vendor.

There are two types of signing limits: spending limits and approval limits. A spending limit is the maximum amount that a worker is authorized to spend on business-related purchases. An approval limit is the maximum amount that a worker is authorized to approve for a specific business document. Signing limits can vary, depending on the transaction type. Therefore, purchase requisitions, expense reports, purchase orders, and invoices can have different signing limits.

Organizations assign default signing limits. Depending on the configuration of signing limits in an organization, a worker can obtain a default signing limit in one of the following ways:

  - The worker is automatically assigned the default signing limit, based on the worker's job or compensation level.

  - The worker must submit a signing limit request in the Employee services portal in Enterprise Portal for Microsoft Dynamics AX.

Signing limit agreements are valid only for a limited time. Before an agreement expires, a worker must renew it. During renewal, workers reconfirm that they agree to comply with the terms of the agreement. If a signing limit agreement expires, the worker cannot make purchases until the agreement is renewed.

## Process overview: Spending and approval limits

The process of configuring and activating signing limits involves the following steps:

1.  An administrator selects the signing limit basis.

2.  If necessary, the administrator restricts signing limits to users who have an employee record in Microsoft Dynamics AX.

3.  If necessary, the administrator configures signing limits so that workers must request the default signing limits for their job or compensation level. Requests are submitted in the Employee services portal in Enterprise Portal.

4.  For each job or compensation level, the administrator defines the default spending limits and approval limits by transaction type.
    

    > [!NOTE]
    > <P>Default signing limits for a job or compensation level can be defined differently for different legal entities in an organization. In a legal entity, default signing limits can also be defined differently for different areas, such as departments or cost centers. Employees who have a position in more than one legal entity in an organization may have different default signing limits in each legal entity.</P>



5.  When workers are hired, they are assigned a specific job or compensation level in Microsoft Dynamics AX.
    
      - If signing limits are configured so that limits are granted to workers automatically, based on job or compensation level, the worker is automatically granted a signing limit on that basis.
    
      - If signing limits are configured so that workers must request signing limits for their job or compensation level, the worker must submit a request in the Employee services portal.

6.  The worker's manager reviews the signing limit request, and approves or rejects it. A manager can also revoke a signing limit at any time.

After a spending limit is set up for a worker, the worker can make purchases up to that amount. Spending limits are invoked at the time of purchase. Approval limits are invoked when the worker's manager approves the purchase as part of the document approval cycle.

## Example: Spending limit

Prakash is a project manager. Because he is responsible for delivering the project on time, Prakash must be able to make catalog purchases for business software and hardware. The default spending limit that is defined for his job is USD 500. However, the purchases that Prakash has to make to meet his project deadline require a higher spending limit. Therefore, Prakash submits a request to increase his spending limit to USD 2,500, so that he can purchase items and services that cost up to USD 2,500.

Prakash's spending limit request is sent to Reina, the resource manager on the project, and Reina approves the request. Prakash can now make catalog purchases of up to USD 2,500, which is USD 2,000 more than the default signing limit that is defined for his job.

If Prakash must make a specific purchase of more than USD 2,500, he can submit a request for a one-time increase in spending limit.

## Example: Approval limit

Reina is a project resource manager at Fabrikam, Inc. For managers at Reina's level, a default approval limit of USD 2,000 is defined for purchase requisitions. Fabrikam has configured signing limits so that workers must submit signing limit requests. Signing limits are not granted to workers automatically.

Reina requests the default approval limit of USD 2,000. Therefore, her request is granted automatically and does not have to pass through the approval workflow. However, Reina's workers require spending limits of more than USD 2,000 for purchase requisitions. Therefore, Reina submits an approval limit request for USD 2,500. June, the product division manager, approves the request. Reina can now approve purchases of up to USD 2,500 that her workers make.

## Example: Renewing signing limit agreements

Signing limit agreements are valid only for a limited time. Workers must renew the agreements periodically to reconfirm that they agree to comply with the terms of the agreement. For example, Prakash has a spending limit for purchase requisitions. When Prakash requested this signing limit, he read the “Purchasing Terms” agreement and agreed to its terms on June 1, 2011. The duration of the agreement was defined as 12 months. Therefore, Prakash's confirmation expires on June 1, 2012. Before this date, Prakash must reconfirm that he agrees to comply with the “Purchasing Terms” agreement.

The **Open agreement (months)** field is used to define the length of the renewal period for a signing limit agreement. For Prakash's spending limit, the renewal period is two months. Therefore, starting on April 1, 2012, the **Signing limit agreement confirmation** page is available to Prakash. Between April 1, 2012, and May 31, 2012, Prakash can open this page and renew his signing limit agreement. If Prakash does not renew the signing limit agreement during this period, his signing limit expires, and he cannot make purchases until the agreement is renewed.

## See also

For information about signing limit tasks for workers and managers, search for **Create and maintain signing limit requests** and **Maintain signing limit request for your workers** in the Enterprise Portal for Microsoft Dynamics AX Help.

For information about setting up signing limit parameters, see [Set up signing limit parameters](set-up-signing-limit-parameters.md)

  


