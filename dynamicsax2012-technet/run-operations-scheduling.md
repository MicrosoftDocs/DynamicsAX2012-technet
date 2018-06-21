---
title: Run operations scheduling
TOCTitle: Schedule operations
ms:assetid: 3a7850db-88fe-4a10-95ca-0b33b649cd7d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa570151(v=AX.60)
ms:contentKeyID: 43976711
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Run operations scheduling [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you schedule operations for a production order, you can also schedule and synchronize reference production orders and subproductions. The dates of the subproductions are adjusted to fit the main production order. The system schedules each operation and an operations resource or resource group for each operation in the production route. The scheduling also assigns durations to each operation.

You can use the buttons in the **Operations scheduling** form to do the following:

  - **Select** – Enter criteria for a query to select the production orders that you want to schedule.

  - **Default values** – Set up default values for scheduling, such as scheduling direction, managing cancellations, and whether to consider capacity and material limitations for selected production orders.

  - **Sorting** – Sort or prioritize the processing sequence for production orders. You can sort in the following ways:
    
      - On ascending or descending delivery dates at the item level
    
      - On the status of the production based on the scheduled start date
    
      - On the priority of the production based on its delivery date

<!-- end list -->

1.  Click **Production control** \> **Common** \> **Production orders** \> **All production orders**.

2.  Select the production order that you want to schedule, and then on the **Action Pane**, on the **Schedule** tab, click **Schedule operations**.

3.  In the **Operations scheduling** form, on the **General** tab, in the **Production** field, select the production order that you want to schedule.

4.  In the **Name** field, verify the name and description of the production order.

5.  In the **Scheduling direction** field, select the scheduling direction that you want to base the operations schedule on.

6.  In the **Scheduling date** field, select the date on which you want the operation to occur. By default, the system suggests the current date. If the date is not relevant for the scheduling direction, leave the default date in the field.

7.  To schedule all reference production orders that are related to this one, select the **Schedule references** check box.

8.  To base all previous and subsequent reference production orders on the scheduling of the current production, select the **Synchronize references** check box.
    
    The **Synchronize references** check box is available only if the **Schedule references** check box is selected.

9.  If you want to schedule with finite capacity, select the **Finite capacity** check box.
    
    To schedule with finite capacity, the **Finite capacity** check box must also be selected for the resource that is assigned to the operation.

10. If you want to schedule with finite material, select the **Finite material** check box.
    
    To schedule with finite material, the **Finite material** check box must also be selected for the resource that is assigned to the operation.

11. To use only resources that are assigned to the selected production unit, select the **Keep production unit** check box.

12. To use only resources that are assigned to the selected input warehouse, select the **Keep warehouse from resource** check box.

13. To specify what you do not want to include in the scheduling, click the **Cancellation** tab, and select any of the following options:
    
      - To exclude the queue time for the current production order, select the **Cancel queue time** check box.
    
      - To exclude the setup time for the current production order, select the **Cancel setup** check box.
    
      - To exclude the process time for the current production order, select the **Cancel process** check box.
    
      - To exclude the overlap time for the current production order, select the **Cancel overlap** check box.
    
      - To exclude the transport time for the current production order, select the **Cancel transport** check box.

14. Click **OK** to run the operations scheduling.

## See also

[About operations scheduling](about-operations-scheduling.md)

[Set up operations scheduling (form)](https://technet.microsoft.com/en-us/library/aa501256\(v=ax.60\))

[Production - Operations scheduling (class form)](https://technet.microsoft.com/en-us/library/aa571353\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

