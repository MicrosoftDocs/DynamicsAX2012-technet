---
title: Configure email settings for the workflow system
TOCTitle: Configure email settings for the workflow system
ms:assetid: e0de6075-a8ff-4080-9c0e-15fea57f4d5a
ms:mtpsurl: https://technet.microsoft.com/library/Gg732160(v=AX.60)
ms:contentKeyID: 35133102
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Configure email settings for the workflow system 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can configure Microsoft Dynamics AX to send email messages to users when workflow-related events occur. For example, email messages can be sent to users when documents are assigned to them for approval. Complete the procedures in this topic to configure email settings for the workflow system.

## This task is part of a bigger process

This topic explains how to configure email settings for the workflow system. This is **step 4** in the following diagram. Configuring the email functionality in Microsoft Dynamics AX is the bigger process that you must complete. For more information about this process, see [Configure email functionality in Microsoft Dynamics AX](configure-email-functionality-in-microsoft-dynamics-ax.md).

![How to configure email functionality](images/Gg732160.Workflow_EmailProcess(AX.60).gif "How to configure email functionality")

## Enable users to receive workflow-related email messages

The first step in the process is to enable users to receive workflow-related email messages. The following procedure explains how to do this. You must complete this procedure for each Microsoft Dynamics AX user.


> [!NOTE]
> <P>If you’d rather have users configure their own email settings, instruct users to do the following:</P>
> <OL>
> <LI>
> <P>Open the Microsoft Dynamics AX client.</P>
> <LI>
> <P>Click <STRONG>File</STRONG> &gt; <STRONG>Tools</STRONG> &gt; <STRONG>Options</STRONG>.</P>
> <LI>
> <P>Complete steps 5 – 8 in the following procedure.</P></LI></OL>



1.  Open the Microsoft Dynamics AX client.

2.  Click **System administration** \> **Common** \> **Users** \> **Users**.

3.  Select a user.

4.  Click **Options**.

5.  In the **E-mail** field, verify the email address of the selected user.

6.  Click **Notifications**.

7.  In the **Workflow notifications** section, specify how you want the user to be notified about workflow-related events. To do so, follow these steps:
    
    1.  In the **Line-item notification type** list, specify how you want the user to receive workflow notifications for line items.
        
          - **Grouped** – Notifications for line items are grouped into a single email message.
        
          - **Individual** – An email message is sent for each line item.
    
    2.  If you want the user to receive notifications in the Microsoft Dynamics AX client, select the **Show notifications in the Microsoft Dynamics AX client** check box.
        
        If you select the **Show notifications in the Microsoft Dynamics AX client** check box, you can also specify whether you want the user to receive notifications as pop-up messages. If you want the user to receive pop-up messages, select the **Show pop-ups for notifications** check box.
    
    3.  If you want the user to receive notifications as email, select the **Send notifications in email** check box.

8.  Click **Close**.

9.  The **Users** page is redisplayed. Select another user and repeat steps 4-8.

## Determine how many email templates you need to create for the workflow system

Determine how many email templates you need to create for the workflow system. You can create multiple email templates, or just two email templates (as explained below). Your business needs will help you determine how many email templates you need to create. For example, you may want to:

  - Create an email template for every workflow.

  - Create an email template for every workflow type.
    
    In this scenario, all workflows of a certain type would use the same email template. See [Workflow types](workflow-types.md) for a list of all the types of workflows you can create.

  - Create two email templates.
    
    In this scenario, one email template would be used by all workflows that are used across the whole organization. The other email template would be used by all workflows that are company-specific. See [Workflow types](workflow-types.md) for more information about how each type of workflow is used.

## Create email templates

After you have determined how many email templates to create, you can create the templates. For instructions on how to do this, see [Configure email functionality in Microsoft Dynamics AX](configure-email-functionality-in-microsoft-dynamics-ax.md).

## Use placeholders

When you create email templates, we recommend that you use placeholders. When email messages are generated, these placeholders will be replaced with specific text from the workflow.

For example, suppose that you entered the placeholder **%subject%** in the email template. In this example, when email is generated and sent to users, that placeholder will be automatically replaced with the text found in the **Work item subject** field. Similarly, if you enter **%message%** in the email template, that placeholder will be replaced with the text found in the **Work item instructions** field.

![Placeholders will be replaced with this text.](images/Gg732160.Workflow_SubjectAndMessage(AX.60).png "Placeholders will be replaced with this text.")

For more information about how to insert placeholders in email templates, see [Configure email functionality in Microsoft Dynamics AX](configure-email-functionality-in-microsoft-dynamics-ax.md).

## Specify when each email template will be used

When you configure the properties of a workflow, you can select the email template that should be used to generate email messages for the workflow. For step-by-step instructions, see [Configure the properties of a workflow](configure-the-properties-of-a-workflow.md).

![Select an email template for the workflow](images/Gg732160.Workflow_EmailTemplateField(AX.60).png "Select an email template for the workflow")

If you do not select an email template when you configure a workflow, a default template will be used. You can specify which email template is the default template by completing the following procedures.

## Specify the default email template for organization-wide workflows

Some workflows are used to process documents that are associated with your whole organization. Complete the following procedure to specify the default email template that will be used to generate notifications for organization-wide workflows.

To view a list of organization-wide workflows, see [Workflow types](workflow-types.md).

1.  Click **System administration** \> **Setup** \> **Workflow** \> **Workflow parameters**.

2.  Select an email template from the list.
    
    The list will display email templates that were created when the **Show system e-mails** check box was marked in the **E-mail templates** form.

3.  Click **Close** to save your changes.

## Specify the default email template for organization-specific workflows

Some workflows are used to process documents that are associated with a specific organization, such as a legal entity. Complete the following procedure to specify the default email template that will be used to generate notifications for organization-specific workflows.

To view a list of organization-specific workflows, see [Workflow types](workflow-types.md).

1.  Click **Organization administration** \> **Setup** \> **Workflow** \> **Workflow parameters**.

2.  Select an email template from the list.
    
    The list will display email templates that were created when the **Show system e-mails** check box was not marked in the **E-mail templates** form.

3.  Click **Close** to save your changes.

  


