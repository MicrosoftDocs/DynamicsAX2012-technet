---
title: About alert email messages
TOCTitle: About alert email messages
ms:assetid: 14263ace-e94e-422b-af15-7447b55767d0
ms:mtpsurl: https://technet.microsoft.com/library/Aa834334(v=AX.60)
ms:contentKeyID: 46687532
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About alert email messages 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Alerts can be delivered as email messages. After the email option is enabled, you can select whether alerts are delivered as email messages, as pop-up messages, or as both.

Alert email messages cannot be created or sent manually. To deliver alerts by using email, the email messages must be processed through the email system in Microsoft Dynamics AX.

## Prerequisites to use an email system for alerts

Complete the following steps to enable the email option so that you can set up alerts.

1.  On the **File** menu, click **Tools** \> **Options** to open the **Options** form.

2.  On the **General** tab, under **Options**, in the **Language** field, select a language. In the **E-mail** field, enter the email address of the recipient.

3.  Set up an email template. For more information, see [Configure email functionality in Microsoft Dynamics AX](configure-email-functionality-in-microsoft-dynamics-ax.md).

4.  Specify the email template for alerts. For more information, see [Define an email identification for alerts](define-an-email-identification-for-alerts.md).

5.  Optional: Create versions of the template for more languages.

## User options

The option to send alerts as email messages can be set up at the level of the alert rule or at the level of the user options. The setup at the user options level overrides any setup at the rule level.

For every rule that you create, you can select to receive the alerts that are triggered by the rule as email messages, pop-up messages, or both.

## Template

The alert messages that users receive are based on a template, and the layout of this template can be customized. You can insert merge data and links into the email template.

Merge data is a set of data that provides details about the alert. For example, if you insert the %occurred% merge data element, the date and time that the alert occurred are displayed in the email message.

Three types of links can be inserted into the template. These links provide multiple options for linking from the email message to Microsoft Dynamics AX to view information about the alert. For information about merge data and the link types, see [Set up alert email templates in HTML](set-up-alert-email-templates-in-html.md).

## Deleting email alerts

When you delete an alert from the **Notification list** form, the corresponding email alert persists. The email alert is only soft-deleted from the EventInbox table.

## Drill down option

When you receive an email alert, you can drill down to the rule and to the business data. However, you cannot drill down to the alert.

## See also

[Security recommendations for using alerts](security-recommendations-for-using-alerts.md)

[Define an email identification for alerts](define-an-email-identification-for-alerts.md)

[Set up alert email templates in HTML](set-up-alert-email-templates-in-html.md)

  


