---
title: About alert batch execution
TOCTitle: About alert batch execution
ms:assetid: fb6df49f-fa76-4e80-a6e7-a8cd284dffb8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa570106(v=AX.60)
ms:contentKeyID: 46687574
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# About alert batch execution 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Alerts are processed by the batch processing functionality in Microsoft Dynamics AX. Batch processing must be set up before alerts can be delivered.

Microsoft Dynamics AX supports two types of events:

  - Events that are triggered by change-based events. These events are also referred to as create/delete and update events.

  - Events that are triggered by due dates.

You can set up batch processes for each type of event.

## Process batches for change-based events

Microsoft Dynamics AX reads all change-based events that have occurred since batch processing was last run. Change-based events include updates to fields, the deletion of records, and the creation of records. These events are compared with the conditions that are set up in alert rules. When an event matches the conditions in a rule, the batch process generates an alert.

## Set up a batch frequency for change-based events

For change-based events, you can set up a batch job that triggers the processing of an event soon after the event is logged by the system. If you set up the batch job to recur more frequently, users receive their alerts sooner after a change occurs. However, a high frequency for batch processing might adversely affect the performance of the system.

On the other hand, a batch job that recurs less frequently, and that is scheduled for times when the system load is low, might help improve system performance. However, a low frequency for batch processing might not fulfill users' demands for timely alerts.

Therefore, when you set up the frequency of batch processing for change-based events, consider the balance between the timeliness of alerts and the performance of the whole system.

These considerations become more relevant as the number of users who create alert rules increases. The frequency does not affect the number of events that must be processed. However, if more users create rules, more checks must be performed. This kind of data exchange might affect system performance.


> [!NOTE]
> <P>The time that passes before users receive their alerts is also controlled by the interval at which Microsoft Dynamics AX polls for new alerts. This interval must be set in minutes. The minimum value is 1 minute, and the maximum value is 1440 minutes, or 1 day.</P>



## Set the interval at which Microsoft Dynamics AX polls for new alerts

1.  On the **File** menu, click **Tools** \> **Options** to open the **Options** form.

2.  On the **Notifications** tab, in the **Receive notifications every (minutes)** field, enter an interval.

## Examine the risks of low batch frequency

If you set the batch processing for change-based events to a low frequency, you might lose alerts, because data that is relevant to the conditions in alert rules changes before the batch is processed.

For example, an alert rule is set up to trigger an alert when the event is "customer contact changes" and the condition is customer = BB. Therefore, when the customer contact changes for customer BB, the event is logged. However, the batch processing system is set up so that batch processing occurs less frequently than data entry. If the customer name changes from BB to AA before the event is processed, the data in the database no longer matches the condition in the rule, customer = BB. Therefore, when the event is finally processed, no alert is generated.

## Process batches for due date events

Microsoft Dynamics AX detects all events that are caused by due dates, and these events are compared with the conditions that are set up in alert rules. The batch process generates an alert when an event matches the conditions in a rule.

## Set up batch frequency for due date events

For due date events, you might want to set up batch jobs that run during the night or at specific times of the day, to balance the system load. We recommend that you set up the batch job to run at least one time per day. If you want alerts to be sent as early as possible, set up the batch processing to occur immediately after the system date changes. If you want to generate alerts for due date events that occur after a batch job has already processed alerts, you can run the batch job again on the same day.

For example, a batch job has run on a particular day. You then create a purchase order that has a due date that should trigger an alert on that same day. To receive the alert on that day, you have to run the batch job again after the purchase order is created. However, if you do not run the batch job again on that day, the next day's batch job detects any due date events that were not processed on previous days.


> [!NOTE]
> <P>Even when the batch process is run more than one time per day, alerts are not duplicated for the same due date event and conditions. Alerts are generated only for dates that have become due because of changes that occurred in the system after the last batch job was run.</P>



## Set flexible due dates

Processing of alert rules in a company can be stopped for several reasons. These reasons include vacations, system errors, or other issues that cause batch jobs not to run for some time.

To prevent due date alerts from becoming obsolete because the batch job has not run for several days, you can set up a batch processing window. A batch processing window enables a batch job not to run for a specified number of days.

When a batch processing window is set up, an alert is sent when the alert rule is processed, even if the alert exceeds the time limit that is defined in the due date criteria. An alert continues to be sent as long as the period that is defined by this time limit plus the batch processing window is not exceeded.

However, when the period that is defined by the time limit plus the batch processing window is exceeded, an alert is no longer sent.

## Example

You create an alert rule so that you are alerted two days after an employee's birthday.

The batch processing window is set to 10 days.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>The batch job runs on day 1.</p></td>
<td><p>You are alerted about every employee whose birthday was 2 days ago.</p></td>
</tr>
<tr class="even">
<td><p>The batch job does not run on day 1, but only on day 2.</p></td>
<td><p>You are alerted about every employee whose birthday was 2 or 3 days ago.</p></td>
</tr>
<tr class="odd">
<td><p>The batch job does not run on day 1 or 2, but only on day 3.</p></td>
<td><p>You are alerted about every employee whose birthday was 2, 3, or 4 days ago.</p></td>
</tr>
<tr class="even">
<td><p>The batch job does not run on days 1 through 9, but only on day 10. In other words, the batch job runs in the 10-day window.</p></td>
<td><p>You are alerted about every employee whose birthday was 2, 3, 4, 5, 6, 7, 8, 9, 10, or 11 days ago.</p>
<div class="alert">

> [!NOTE]
> <P>All alerts are generated.</P>


</div></td>
</tr>
<tr class="odd">
<td><p>The batch job does not run on days 1 through 10, but only on day 11.</p></td>
<td><p>You are alerted about every employee whose birthday was 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, or 12 days ago.</p>
<div class="alert">

> [!NOTE]
> <P>Now you are not alerted about any employee whose birthday was 13 days ago.</P>


</div></td>
</tr>
<tr class="even">
<td><p>The batch job does not run on days 1 through 11, but only on day 12.</p></td>
<td><p>You are alerted about every employee whose birthday was 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, or 13 days ago.</p>
<div class="alert">

> [!NOTE]
> <P>Now you are not alerted about any employee whose birthday was 14 days ago.</P>


</div></td>
</tr>
</tbody>
</table>


As you see from this example, if the batch processing window is set to 10, the longest period during which the batch job does not run is 10 days. To guarantee that the alert is generated, the batch has to run on the tenth day at the latest.

If the batch processing window is set to 0, you are alerted only if the batch runs two days after the birthday. In this case, to guarantee that no alert is lost, the batch has to run every day.

## Delete the event queue

When you activate a batch job that processes change-based events for a company, we recommend that you examine the event queue and decide whether all the events in the queue should be sent as alerts. If old, unprocessed, and obsolete events are not deleted from the queue, the batch job generates alerts and may send users many useless messages, or "spam."

Old, unprocessed, and obsolete events can accumulative in the event queue for several reasons. For example, users set up alert rules long before the batch process is started, so that the events that are generated create many obsolete alerts. Alternatively, users had permission to create rules long before the batch job is activated, so that the events that are triggered by the users' rules are logged by the system, even though the batch has not been activated.

If you decide that the events in the event queue are obsolete and should not be sent as alerts, you can delete the event queue.

1.  Press CTRL+D to open the Application Object Tree (AOT). Select **Data Dictionary** \> **Tables**.

2.  Select the EventCUD table, locate the events to delete, and then delete the events as appropriate.

## See also

[Set up alert batch execution](set-up-alert-batch-execution.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

