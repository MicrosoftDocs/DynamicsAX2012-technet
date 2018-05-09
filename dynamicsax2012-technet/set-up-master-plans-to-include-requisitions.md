---
title: Set up master plans to include requisitions
TOCTitle: Set up master plans to include requisitions
ms:assetid: 749bfc46-86d6-488d-a46d-fc2743933314
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ683228(v=AX.60)
ms:contentKeyID: 49684851
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Set up master plans to include requisitions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can set up Microsoft Dynamics AX to include requisition demand in master scheduling. After this is set up, approved requisitions that have a purpose of replenishment are automatically released to master scheduling, and the fulfillment method for the demand created by these requisitions is automatically determined. It is determined by the supply policies that have been set up for the items in your organization and planned by using master scheduling. After a replenishment requisition has been created and approved, no additional user action is required.

In master plans, you can also enter the number of days in the past when demand from approved requisitions is included in master scheduling. For example, you can indicate if only unfulfilled, past-due demand from approved requisitions that were created in the last 10 days should be considered and planned for. In this case, demand created more than 10 days ago is disregarded.


> [!NOTE]
> <P>This functionality is supported only if the <STRONG>Master planning</STRONG> license code and the <STRONG>Master planning</STRONG> configuration key are enabled.</P>



## Set up master plans to include replenishment requisition demand

1.  Click **Master planning** \> **Setup** \> **Plans** \> **Master plans**.

2.  On the **General** tab, in the **Setup** section, select the **Include requisitions** check box.

## Set up a time fence for replenishment requisition demand

1.  Click **Master planning** \> **Setup** \> **Plans** \> **Master plans**.

2.  On the **Time fences** tab, select the **Approved requisitions** check box to override the time fence settings that are defined for items. Then, enter the number of days in the past when demand from approved requisitions is included in master scheduling. For example, enter 10 if the system should only consider and plan for demand from approved requisitions that were created in the last 10 days.

## See also

[About purchase requisitions](about-purchase-requisitions.md)

[Master plans (form)](https://technet.microsoft.com/en-us/library/aa591284\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

