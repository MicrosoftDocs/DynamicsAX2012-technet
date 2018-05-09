---
title: Configuring alerts
TOCTitle: Configuring alerts
ms:assetid: 5c19866e-53b4-46b8-a28c-2d45407f8759
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa834468(v=AX.60)
ms:contentKeyID: 46687546
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Configuring alerts 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Alerts are generated as part of a notification system that helps users track critical events in Microsoft Dynamics AX.

Before you can use alerts, number sequences and batch processing for alerts must be set up in the **Organization administration** module. You can also enable email alerts, which are an optional feature.

The following sections explain the prerequisites for setup and provide links to the forms that are used.

## Set up number sequences for alerts

Before you can use alerts, number sequences must be set up in the **Number sequences** form. For setup information, see [Number sequences (list page)](https://technet.microsoft.com/en-us/library/aa600321\(v=ax.60\)).

## Set up batch processing for alerts

Batch processing must be set up before alerts can be delivered. Use the **Due date alerts** form and the **Change based alerts** form to set up the basic alerts functionality.

We recommend that you configure these forms in the following order.

1.  Configure the **Due date alerts** form to batch process all events that are caused by due dates. The batch process generates an alert when an event matches the conditions in alert rules.

2.  Configure the **Change based alerts** form to batch process all change-based event that have occurred since the last time that batch processing was performed. Change-based events include updates to fields, the deletion of records, and the creation of records. The batch process generates an alert when an event matches the conditions in alert rules.

When you set up batch processing, decide if you want to set up a batch processing window. The batch processing window is optional, and you can set up the batch process without applying the batch processing window.

For more information and configuration procedures, see [About alert batch execution](about-alert-batch-execution.md).

## Optional setup forms for alerts

The setup of alerts includes several steps besides the setup of basic functionality. The additional setup forms that are used are organized by functionality.

## Batch processing window

A batch processing window defines the interval by which the time limit that is specified in a criterion for a due date alert rule can be exceeded. The interval that you specify in the **Options** form, on the **Notifications** tab, defines the number of days that alerts are delivered even though batches do not run.

For more information, see [About alert batch execution](about-alert-batch-execution.md).

## Email alerts

The email alerts functionality lets users receive alerts as email messages. The email alerts functionality is optional, and you can use the alerts feature without applying this functionality. If you do not set up the email alerts functionality, users can receive their alerts only as pop-up messages. For more setup information, see [About alert email messages](about-alert-email-messages.md).

1.  In the **E-mail parameters** form, configure the parameters that Microsoft Dynamics AX requires to communicate with an SMTP server.

2.  In the **Options** form, set up a valid email address for the recipient.

3.  In the **E-mail templates** form, set up an email identification for alerts, an email address for the sender, and an email template.

## Drill-down links and the drill-down target for email alerts

If you use the email alerts functionality, decide if you want to enable drill-down links and the retry schedule. These features are optional. You can use the email alerts functionality without adding drill-down links in the email template, and without setting up a retry schedule for the email messages.

In the **System parameters** form, on the **Alerts** tab, you can apply drill-down links to the email template. Users can then drill down to alerts, alert rules, or the alert origin from an alert email message.

Drill-down links in email alerts are optional, and you can set up an email template and use the email alerts functionality without using drill-down links.

When you insert drill-down links into the email template, you should also select a value for the drill-down target for the links. The primary purpose of the drill-down target is to prevent users from drilling down to an incorrect Microsoft Dynamics AX database when they can receive alerts from two databases. The drill-down link in alert email messages must drill down to the database where the event occurred, and the value of the drill-down target identifies this database.

If users receive alerts from only one database, you do not have to change the default value of the drill-down target, 0 (zero).

For more information, see [About drilling down from an alert email message](about-drilling-down-from-an-alert-email-message.md).

## Retry schedule for email alerts

In the **Retry schedule** form, you can define how many times the system tries to send email messages that it has not been able to send. You can also define the interval between attempts.

The setup of the retry schedule is optional, and you can use the email alerts functionality without setting up a retry schedule. For more information, see [Configure email functionality in Microsoft Dynamics AX](configure-email-functionality-in-microsoft-dynamics-ax.md).

## See also

[Set up alert batch execution](set-up-alert-batch-execution.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

