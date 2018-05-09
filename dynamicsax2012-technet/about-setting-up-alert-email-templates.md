---
title: About setting up alert email templates
TOCTitle: About setting up alert email templates
ms:assetid: a8466f12-283c-454b-94a1-0d720c566229
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa834423(v=AX.60)
ms:contentKeyID: 46687561
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# About setting up alert email templates 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To set up an alert email template, first create a template. Then, open the email editor to set up the predefined contents of email messages that are based on the template.

The predefined contents consist of merge data and links that can be inserted into the template.

The merge data is a set of data that provides details about the alert in the email message. The links give you three methods for linking from the email message to Microsoft Dynamics AX to view information about the alert.

Templates can be based on either HTML or XSLT. The procedure for setting up each kind of template is described separately. Additionally, the merge data and the link types that are applied for each kind of template differ slightly.

## Link types

In an email template, you can apply three types of links to Microsoft Dynamics AX. The syntax of the links differs slightly, depending on whether you work with HTML or XSLT.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>HTML link</p></th>
<th><p>XSLT link</p></th>
<th><p>Action</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Dynamics://%LinkToBusinessData%</p></td>
<td><p>alert/LinkToBusinessData</p></td>
<td><p>Drill down to the alert origin, or the business data that caused the alert. The alert origin is also the location at which the alert rule is set up.</p></td>
</tr>
<tr class="even">
<td><p>Dynamics://%LinkToAlertRule%</p></td>
<td><p>alert/LinkToAlertRule</p></td>
<td><p>Open the <strong>Manage alert rules</strong> form, where you can view the alert rule that caused the alert.</p></td>
</tr>
<tr class="odd">
<td><p>Dynamics://%LinkToAlert%</p></td>
<td><p>alert/LinkToAlert</p></td>
<td><p>Open the <strong>Notification list</strong> form, where you can view the alert.</p></td>
</tr>
</tbody>
</table>


## Merge data overview

The following merge data elements can be added to the email template. The merge data elements can be used to inform the user about various aspects of the alert.

The merge data elements that you insert depend on the information that you want to display in email messages that are based on the template.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>HTML merge data element</p></th>
<th><p>XSLT merge data element</p></th>
<th><p>Information that is displayed in the email message</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>%subject%</p></td>
<td><p>alert/subject</p></td>
<td><p>The subject that is defined by the owner of the alert rule.</p></td>
</tr>
<tr class="even">
<td><p>%message%</p></td>
<td><p>alert/message</p></td>
<td><p>The message that is written by the owner of the alert rule.</p></td>
</tr>
<tr class="odd">
<td><p>%event%</p></td>
<td><p>alert/event</p></td>
<td><p>The event that occurred.</p></td>
</tr>
<tr class="even">
<td><p>%occurred%</p></td>
<td><p>alert/occurred</p></td>
<td><p>The date on which the event occurred.</p></td>
</tr>
<tr class="odd">
<td><p>%for%</p></td>
<td><p>alert/for</p></td>
<td><p>The record in which the event was observed.</p></td>
</tr>
<tr class="even">
<td><p>%data%</p></td>
<td><p>alert/data</p></td>
<td><p>Detailed information.</p></td>
</tr>
<tr class="odd">
<td><p>%company%</p></td>
<td><p>alert/company</p></td>
<td><p>The company at which the event occurred.</p></td>
</tr>
</tbody>
</table>


## See also

[Set up alert email templates in HTML](set-up-alert-email-templates-in-html.md)

[Set up alert email templates in XSLT](set-up-alert-email-templates-in-xslt.md)

[About drilling down from an alert email message](about-drilling-down-from-an-alert-email-message.md)

[Syntax of HTML template for alert emails](https://technet.microsoft.com/en-us/library/aa834376\(v=ax.60\))

[Syntax of XSLT template for alert emails](https://technet.microsoft.com/en-us/library/aa570097\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

