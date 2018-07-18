---
title: Schedule production by using a Gantt chart
TOCTitle: Schedule production by using a Gantt chart
ms:assetid: e0d08111-a65a-4ba5-9398-b20b2a8bf61b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg243208(v=AX.60)
ms:contentKeyID: 44081054
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Schedule production by using a Gantt chart 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A Gantt chart displays a graphical overview of the production plan that is scheduled for the selected resource or production order. You can manually reschedule the production by using commands in the Gantt chart. This topic describes the scheduling tasks.

## Reschedule a resource

Reasons to reschedule a resource may include the following:

  - If orders are scheduled over time, the sequence of operations for a particular item may no longer be practical or optimal.

  - If a particular resource is becoming a bottleneck, you can move some of the scheduled jobs or operations to a different resource.


> [!NOTE]
> <P>You can use this procedure to reschedule only those jobs that load a resource, such as setup and process jobs.</P>



To reschedule a resource:

1.  Click **Organization administration** \> **Common** \> **Resources** \> **Resource groups**. Select a resource group, and then on the **Resources** FastTab, select a resource. Click **Gantt chart**.

2.  In the **Gantt chart** dialog box, enter a start date and an end date to define the time period that you want to view in the Gantt chart. Click **OK**.

3.  In the Gantt chart, right-click a job, and then select **Open job scheduling form**.

4.  In the **Job scheduling** form, reschedule the job that uses the resource. After you reschedule the job, you can make additional changes in the Gantt chart.

## Reschedule a job or operation

When you view the capacity load chart, you may notice that a particular resource has become a bottleneck. You can adjust the jobs that are scheduled for the resource to optimize the available capacity.

To reschedule a job or operation from the Gantt chart, follow these steps:

1.  In the Gantt chart, select a job.

2.  In the calendar grid, drag the job load to an available time slot.

3.  Click **Validate** to check how the change affects the existing schedule. The program displays an Infolog that either confirms that the changes are possible or describes scheduling issues that the change will cause.
    
    Scheduling issues may be acceptable if you intend to make manual changes to the schedule later, or if, for example, you make arrangements with the shop floor personnel to accommodate the change.

4.  If the scheduling issue is acceptable, click **Save** to save the rescheduling change.

## Realign related jobs

Rescheduling a resource can cause disruptions with related jobs. Depending on what you want to do, you can use the following methods to realign the jobs that are affected by the change:

  - Right-click the job, and then click **Schedule previous jobs** to automatically reschedule the preceding job.

  - Right-click the job, and then click **Schedule next jobs** to automatically reschedule the subsequent job.

## Reschedule an order

You can reschedule an order if, for example, a customer requests a different shipping date. To reschedule an order from the Gantt chart, right-click the job and select **Go to production**. In the **Production orders** form, open the **Job scheduling** form and reschedule the production order.

## Cancel a scheduling change

You can simulate various scheduling scenarios and then cancel changes that do not give optimal or acceptable results. To cancel a manual scheduling change, click **Undo**.

## See also

[Gantt chart (form)](https://technet.microsoft.com/en-us/library/hh803027\(v=ax.60\))

[Gantt chart setup (form)](https://technet.microsoft.com/en-us/library/hh545521\(v=ax.60\))

[Gantt chart views (form)](https://technet.microsoft.com/en-us/library/hh803013\(v=ax.60\))

  


