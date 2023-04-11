---
title: Submit a general budget reservation to workflow (Public sector)
TOCTitle: Submit a general budget reservation to workflow (Public sector)
ms:assetid: 9bff8da6-86ef-4ac4-82d0-5665f77ac139
ms:mtpsurl: https://technet.microsoft.com/library/Dn906411(v=AX.60)
ms:contentKeyID: 65205502
author: tonyafehr
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- workflows
- workflow
- public sector
- budget reservation
- budget reservations
- general budget reservation
- general budget reservations
- budget reservation workflow
- general budget reservation workflow
- budget reservation workflow submittal
- general budget reservation workflow submittal
audience: Application User
ms.search.region: Denmark, France
---

# Submit a general budget reservation to workflow (Public sector) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

After you have activated and set up workflow for general budget reservations, when you create a budget reservation, a yellow workflow bar appears at the top of the reservation form.


> [!NOTE]
> <P>General budget reservations are available only if the <STRONG>Public Sector</STRONG> configuration key is selected and if Microsoft Dynamics AX 2012 R3 Cumulative Update 8 is installed with the following hotfix: KB3047235</P>



To submit a general budget reservation to workflow, you must be the preparer. All required fields must be filled in, and the budget reservation must contain at least one line item before it can be submitted. The reservation must have a workflow status of **Draft**.

To submit a general budget reservation to workflow, follow these steps.

1.  Click **Budgeting \> Common \> General budget reservations \> All general budget reservations**.

2.  Select the budget reservation that you want to submit to workflow.

3.  Click **Submit** in the yellow message bar. A dialog box appears.

4.  Add a note in the **Comment** field if you want, and then click **Submit**. The budget reservation status will move to the next step of the workflow.

5.  The button in the yellow message bar changes to **Actions**. You can click it at any time to do the following:
    
      - View the history and see where the document stands in the workflow process.
    
      - If the reservation is in workflow, recall the workflow status to **Draft** status, make any changes you want to the reservation, and then resubmit the amended reservation to workflow.

6.  As the reservation moves through workflow, the reservation status and workflow status change and are reflected in the header of the general budget reservation.

7.  When the workflow is completed and the reservation status is set to **Approved**, the **Budget reservation** button, in the **Post** group on the **Action Pane**, becomes available and you can post the general budget reservation.

## See also

[Set up general budget reservation workflows (Public sector)](set-up-general-budget-reservation-workflows-public-sector.md)

[Set up Budgeting workflows](set-up-budgeting-workflows.md)

[Create a general budget reservation (Public sector)](create-a-general-budget-reservation-public-sector.md)

  


