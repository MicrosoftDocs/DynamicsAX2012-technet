---
title: Use project accounting with general budget reservations (Public sector)
TOCTitle: Use project accounting with general budget reservations (Public sector)
ms:assetid: 02fc85f6-9015-458e-ac01-98e2fa6ee0bc
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn906409(v=AX.60)
ms:contentKeyID: 64978170
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- projects
- public sector
- budget reservation
- budget reservations
- general budget reservation
- general budget reservations
- project accounting
---

# Use project accounting with general budget reservations (Public sector) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

If your organization uses project accounting, you can include references to your project in general budget reservations. This can affect budgeting, committed costs, and funding-source reservations and consumption.


> [!NOTE]
> <P>General budget reservations are available only if the <STRONG>Public Sector</STRONG> configuration key is selected and if Microsoft Dynamics AX 2012 R3 Cumulative Update 8 is installed with the following hotfix: KB3047235</P>



For more information, see [About general budget reservations (Public sector)](about-general-budget-reservations-public-sector.md).

Certain expenditures are planned to be charged to projects. When you create a general budget reservation, you can specify that the planned purchase is for a specific project and project category. You can also specify other project-related information, such as the expected sales price (for public sector entities, this typically is the cost price). These values are all included on the subsequent purchasing documents for projects.

If the general budget reservation contains a project distribution, then the purchase order, purchase requisition, or vendor invoice that references the reservation must include the project distribution and all project information. This information is copied automatically to the source document from the general budget reservation.

For more information about project accounting, see [Project management and accounting](project-management-and-accounting.md) and [About Project management and accounting parameters](about-project-management-and-accounting-parameters.md).

## Enable committed cost tracking for general budget reservations

Project committed costs are created when purchasing documents are approved, confirmed, or posted. The costs represent amounts that will be spent on a project. Project managers can view pending costs for a project in order to track accurate information about their project's costs.

To enable committed cost tracking for general budget reservations, use the following steps.

1.  Click **Project management \> Setup \> Project and accounting parameters**.

2.  Click **Cost control**.

3.  Under **Cost commitments**, select the **General budget reservation** check box.
    

    > [!NOTE]
    > <P>The <STRONG>Purchase order</STRONG>, <STRONG>Vendor invoice</STRONG>, and <STRONG>Purchase requisition</STRONG> check boxes will be automatically selected.</P>



4.  Click **Close**. When the general budget reservation is posted, it will be counted in the project’s committed costs.

## Specify project information in a general budget reservation

To specify project information in a general budget reservation, use the following steps.

1.  Click **Budgeting \> General budget reservations \> All general budget reservations**.

2.  Create a general budget reservation. For more information, see [Create a general budget reservation (Public sector)](create-a-general-budget-reservation-public-sector.md).

3.  Under **General budget reservation lines**, add a project ID and project category for each applicable reservation line. Information from the project will be copied automatically to the reservation.

4.  Optional: To see the project details, click the **Line details** FastTab, and then click the **Project** tab.

## View project committed costs for a general budget reservation

When you post a general budget reservation for a project, a committed cost (the total amount of the distributions to that project) is created for the reservation amount against that project.

To view project committed costs for a general budget reservation, use the following steps.

1.  Click **Budgeting \> General budget reservations \> All general budget reservations**.

2.  Open the posted general budget reservation that you want, and then select a reservation line.

3.  On the **Line details** FastTab, click the **Committed costs** button. The **Committed costs** form opens, displaying the committed costs related to the selected line.


> [!WARNING]
> <P>Committed costs for general budget reservations are based on amount, regardless of whether the committed cost includes a discrete quantity and unit cost. The committed cost quantity will always be 1.</P>


  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

