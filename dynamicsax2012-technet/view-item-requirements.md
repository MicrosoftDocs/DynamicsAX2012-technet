---
title: View item requirements
TOCTitle: View item requirements
ms:assetid: daef5e16-e3c3-4e2f-ab06-ccd8f1835182
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa551216(v=AX.60)
ms:contentKeyID: 37822162
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- requirements
- MRP
- net requirements
- requirements planning
---

# View item requirements [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

After you run master scheduling, you can view the calculated requirements in the **Net requirements** form. You can access this form from the planned orders list or from the item record.

Click **Master planning** \> **Common** \> **Planned orders**. Select a planned order. On the **View** tab, in the **Requirements** group, click **Requirement profile**.

–or–

Click **Product information management** \> **Common** \> **Released products**. On the **Plan** tab, in the **Requirements** group, click **Net requirements**.

## View item requirements by using a period template

In the **Net requirements** form, you can view requirements by using a period template. Use the following procedure to configure and use this functionality.

1.  Create and set up a period template. For more information, see [Period templates (form)](https://technet.microsoft.com/en-us/library/hh209650\(v=ax.60\)). To group item requirements, you can set up, for example, one period of 5 days and another period of 3 weeks.

2.  Assign the period template to a coverage group. Click **Master planning** \> **Setup** \> **Coverage** \> **Coverage groups**. Select the coverage group. On the **General** FastTab, in the **Period template** field, select the period template that you want to use.

3.  In the **Net requirements** form, click the **Period** tab to view the requirements by using the format of the period template that you selected. The item requirements are displayed in the periods that are defined by the period template.
    
    If you do not assign a period template to a coverage group, the grid on the **Period** tab is blank.

## See also

[Net requirements (form)](https://technet.microsoft.com/en-us/library/aa577013\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

