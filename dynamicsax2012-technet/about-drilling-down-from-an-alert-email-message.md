---
title: About drilling down from an alert email message
TOCTitle: About drilling down from an alert email message
ms:assetid: 1a73e735-12e0-4aec-8c65-abae47122f69
ms:mtpsurl: https://technet.microsoft.com/library/Aa834337(v=AX.60)
ms:contentKeyID: 46687534
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About drilling down from an alert email message 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

From an alert email message, you can drill down to see the change in the business data that caused the alert.

You can also drill down to the alert itself. For example, if the alert was triggered when a field value changed, you can drill down to see the original value of the field.

Finally, you can drill down to the alert rule. For example, if you no longer want to receive certain alerts, you can drill down and delete the alert rule that caused the alerts.

## Enabling the drill-down functionality

To enable the drill-down functionality, add the following links to the alert email template. When you receive an alert email message, you can drill down by clicking the relevant drill-down links in the message. The link text that is displayed in the alert email message is defined in the alert email template.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>URL</p></th>
<th><p>What the link drills down to</p></th>
<th><p>Link text in the alert email message</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>In HTML: Dynamics://%LinkToBusinessData%</p>
<p>In XSLT: alert/LinkToBusinessData</p></td>
<td><p>The alert origin, or the business data in Microsoft Dynamics AX that caused the alert</p></td>
<td><p>The link text starts with &quot;Go to&quot; and then indicates the business data.</p></td>
</tr>
<tr class="even">
<td><p>In HTML:</p>
<p>Dynamics://%LinkToAlertRule%</p>
<p>In XSLT: alert/LinkToAlertRule</p></td>
<td><p>The alert rule in the <strong>Manage alert rules</strong> form</p></td>
<td><p>Manage alerts</p></td>
</tr>
<tr class="odd">
<td><p>In HTML: Dynamics://%LinkToAlert%</p>
<p>In XSLT: alert/LinkToAlert</p></td>
<td><p>The alert in the <strong>Notification list</strong> form</p></td>
<td><p>View alerts</p></td>
</tr>
</tbody>
</table>


## Installation requirements

To use the drill-down functionality from an alert email message, you must have a local Microsoft Dynamics AX client that uses a local version of the Microsoft Dynamics AX configuration file. The drill-down functionality does not work if you access Microsoft Dynamics AX by using an application server.

## Accessing the correct database

Alerts can be sent from two different databases. In this case, the drill-down link in alert email messages must drill down to the database where the event occurred.

To identify the correct database, you must define a drill-down target for each database system. The information about the drill-down target prevents users from drilling down to an incorrect database.

If Microsoft Dynamics AX is not running when you click a drill-down link in an alert email message, the default configuration of Microsoft Dynamics AX is started. The attempt to drill down is successful, provided that the default configuration is connected to the database where the alert is stored. If the default configuration is not connected to the correct database, the attempt to drill down is unsuccessful, and you receive an error.

If Microsoft Dynamics AX is already running when you click the drill-down link, the attempt to drill down is successful, provided that the Microsoft Dynamics AX client is connected to the database where the alert is stored.


> [!NOTE]
> <P>If the drill-down target is changed after an alert email message has been generated and sent, the URL in the message is outdated, and the attempt to drill down is unsuccessful.</P>



## Define the drill-down target

1.  Click **System administration** \> **Setup** \> **System parameters**. Click the **Alerts** tab.

2.  In the **Alerts** form, in the **Drill-down target** field, enter the identification number of the drill-down group to which the database belongs.

## See also

[Set up alert email templates in HTML](set-up-alert-email-templates-in-html.md)

  


