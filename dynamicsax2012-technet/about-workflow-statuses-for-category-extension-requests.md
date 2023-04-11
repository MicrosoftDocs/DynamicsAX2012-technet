---
title: About workflow statuses for category extension requests
TOCTitle: About workflow statuses for category extension requests
ms:assetid: 07417cf6-b457-4c64-8734-278de30e7836
ms:mtpsurl: https://technet.microsoft.com/library/Hh242115(v=AX.60)
ms:contentKeyID: 36055967
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About workflow statuses for category extension requests 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A category extension request is a request to add a vendor to a procurement category in which the vendor is not yet approved to do business. Category extension requests are submitted by employees or vendors, and are routed through workflow for approval. Employees and vendors can track the progression of a category request by monitoring its workflow status in the Employee services portal or the Vendor portal.

In the Employee services portal, employees can view the workflow status of a request on the **Vendor requests** list page

In the Vendor portal, vendors can view the workflow status of a request on the **Category requests** list page. Vendors can also view the workflow status of applications that they submit in response to category requests that were initiated by employees.

## Employee-submitted category requests

Employee-submitted category requests have a request type of **Category** and any of the following statuses:

  - **Draft** – The employee has created the request but has not submitted it to workflow.

  - **Request submitted** – The employee has submitted the request to workflow but it has not yet been processed by workflow.

  - **Request pending approval** – The request has been processed by workflow and is awaiting review by the reviewer who is designated in the workflow.

  - **Request cancelled** – The employee has canceled the request.

  - **Request rejected** – The reviewer has rejected the request. If the request was rejected because of insufficient information, the employee can provide the additional information and resubmit the request.

  - **Request approved** – The request has been approved.

## Vendor-submitted category requests

Vendor-submitted category requests have a request type of **Category** and any of the following statuses:

  - **Application ready** – A category request application has been created in the Vendor portal. The vendor can complete the draft of the application and submit it for approval.

  - **Application drafted** – The vendor has created the request but has not submitted it to workflow.

  - **Application submitted** – The vendor has submitted the application to workflow but it has not yet been processed by workflow.

  - **Application pending review** – The application is awaiting review.

  - **Application reviewed** – The application review has been completed.

  - **Application pending approval**– The application is awaiting approval.

  - **Application approved** – The application has been approved.

  - **Application rejected** – The application has been rejected.

## See also

[Vendor category request (form)](https://technet.microsoft.com/library/hh227509\(v=ax.60\))

  


