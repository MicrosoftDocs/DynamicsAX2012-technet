---
title: Set up alert email templates in HTML
TOCTitle: Set up alert email templates in HTML
ms:assetid: 86111fcc-f8dc-4a0d-9b74-19aa4a46040b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa834405(v=AX.60)
ms:contentKeyID: 46687553
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Set up alert email templates in HTML 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

## Create an email template in HTML

1.  Create an email identification. Give the identification a name that you can easily recognize later, such as Alert email. For more information, see [Configure email functionality in Microsoft Dynamics AX](configure-email-functionality-in-microsoft-dynamics-ax.md).

2.  Connect the identification to the alerts function. For more information, see [Define an email identification for alerts](define-an-email-identification-for-alerts.md).

3.  Click **Organization administration** \> **Setup** \> **E-mail templates**. Press CTRL+N to create a new email template.

4.  In the **Sender name** field, enter a name for the sender. Make sure that the sender name indicates that the purpose of the email message is to send an alert from Microsoft Dynamics AX.

5.  In the **Sender e-mail** field, enter the email address of the sender.

6.  In the lower pane of the form, create records for each language that you require. After you have created a template for a particular language, users can receive email messages in that language.

7.  For each record, or template, enter the following information:
    
      - In the **Subject** field, enter a subject for the template. The subject can include merge data. For more information, see [About setting up alert email templates](about-setting-up-alert-email-templates.md).
    
      - In the **Layout** field, select the **HTML** layout.
    

    > [!NOTE]
    > <P>In the <STRONG>Options</STRONG> form, make sure that an email address is defined for every user who may want to receive alerts by email. On the <STRONG>File</STRONG> menu, click <STRONG>Tools</STRONG>, and then select <STRONG>Options</STRONG> to open the <STRONG>Options</STRONG> form.</P>



## Insert elements for merge data in the email template

1.  In the **E-mail templates** form, click the **E-mail message** button.

2.  In the email editor, enter the merge data element that you want to appear in the email messages. For more information, see [About setting up alert email templates](about-setting-up-alert-email-templates.md).

3.  On the **File** menu, click **Save** to save the contents of the email message.

## See also

[About setting up alert email templates](about-setting-up-alert-email-templates.md)

[Syntax of HTML template for alert emails](https://technet.microsoft.com/en-us/library/aa834376\(v=ax.60\))

[Set up alert email templates in XSLT](set-up-alert-email-templates-in-xslt.md)

[About drilling down from an alert email message](about-drilling-down-from-an-alert-email-message.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

