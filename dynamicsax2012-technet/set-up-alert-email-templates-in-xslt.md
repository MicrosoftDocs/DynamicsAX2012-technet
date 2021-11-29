---
title: Set up alert email templates in XSLT
TOCTitle: Set up alert email templates in XSLT
ms:assetid: e1ae2408-f19f-40b8-b998-69380058ba9f
ms:mtpsurl: https://technet.microsoft.com/library/Aa570089(v=AX.60)
ms:contentKeyID: 46687568
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up alert email templates in XSLT 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Email templates can be created by using Extensible Stylesheet Language Transformation (XSLT).

## Create an email template in XSLT

1.  Create an email ID. Be sure to use a name that you can recognize later. For example, name the ID Alert email. For more information, see [Configure email functionality in Microsoft Dynamics AX](configure-email-functionality-in-microsoft-dynamics-ax.md).

2.  Connect the ID to the alerts function. For more information, see [Define an email identification for alerts](define-an-email-identification-for-alerts.md).

3.  In the **E-mail templates** form, press CTRL+N to create a new template.

4.  In the **Sender name** field, enter a name for the sender. Make sure that the sender name indicates that the purpose of the email message is to send an alert from Microsoft Dynamics AX. Then, in the **Sender e-mail** field, enter the email address for the sender.

5.  In the lower pane of the form, create records for each language that you require. After you have created a template in a particular language, users can receive email messages in that language.

6.  For each record, or template, enter the following information:
    
    1.  In the **Subject** field, enter a subject for the template. The subject can include merge data. For more information, see [About setting up alert email templates](about-setting-up-alert-email-templates.md).
    
    2.  In the **Layout** field, select the **XSLT** layout.


> [!NOTE]
> <P>In the <STRONG>Options</STRONG> form, make sure that an email address is defined for every user who may want to receive alerts by email. On the <STRONG>File</STRONG> menu, click <STRONG>Tools</STRONG>, and then select <STRONG>Options</STRONG> to open the <STRONG>Options</STRONG> form.</P>



## See also

[About setting up alert email templates](about-setting-up-alert-email-templates.md)

[Syntax of XSLT template for alert emails](https://technet.microsoft.com/library/aa570097\(v=ax.60\))

[Set up alert email templates in HTML](set-up-alert-email-templates-in-html.md)

[About drilling down from an alert email message](about-drilling-down-from-an-alert-email-message.md)

  


