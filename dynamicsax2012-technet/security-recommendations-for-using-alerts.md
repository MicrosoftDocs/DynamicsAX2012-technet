---
title: Security recommendations for using alerts
TOCTitle: Security recommendations for using alerts
ms:assetid: 9b54f4ed-9659-4fb4-a0a4-52e4736ede33
ms:mtpsurl: https://technet.microsoft.com/library/Aa834421(v=AX.60)
ms:contentKeyID: 46687560
author: tonyafehr
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Security recommendations for using alerts 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

## Limit access to email setup forms and tables

Email messages, and the forms and tables that support them, often contain sensitive data. Therefore, in general, access to these forms and tables should be restricted.

Only administrators should have access to the forms and tables at the following locations:

  - Click **System administration** \> **Setup** \> **System** \> **E-mail parameters**.

  - Click **System administration** \> **Periodic** \> **E-mail processing** \> **Retry schedule**.

  - Click **System administration** \> **Periodic** \> **E-mail processing** \> **E-mail sending status**.

## Limit access to the field that is used to specify users' email accounts

You must avoid situations where email messages that are processed by the email batch server are sent to email accounts that are not secure company accounts. Users’ email accounts can be specified in the **E-mail** field in the **Options** form. We recommend that only administrators have access to this field. To open the **Options** form, on the **File** menu, click **Tools**, and then select **Options**.

## Limit access to computers that run Application Object Server

Access to the computer that is running Application Object Server (AOS) must be restricted correctly to prevent users from tampering with the system date. Changes to the system date cause corruption of the retry schedule.

## Limit the size of email attachments

A system-wide size limit must be specified for email attachments. Otherwise, attachments of any size are accepted, and any large file that is passed to the SMTP can slow the system. A slow system can cause denial of service to other users.

## Set the size limit for email attachments

1.  Click **System administration** \> **Setup** \> **System** \> **E-mail parameters**.

2.  Under **E-Mail settings**, in the **Attachment size limit (MB)** field, enter a size limit.

## Set the location for email attachments

You must specify a system location that email attachments and embedded email data can originate from. Attachments from other locations are restricted.


> [!NOTE]
> <P>The location that is specified should not be on the client computer. The location should always be on the server or on a share.</P>



## Specify the location for embedded data and attached files

1.  Click **System administration** \> **Setup** \> **System** \> **E-mail parameters**.

2.  In the **Allow embedded data and attached files from** field, enter a path.

3.  Click **Close** to save the settings.

  


