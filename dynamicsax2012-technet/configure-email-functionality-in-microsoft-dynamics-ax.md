---
title: Configure email functionality in Microsoft Dynamics AX
TOCTitle: Configure email functionality in Microsoft Dynamics AX
ms:assetid: 68c28942-7e06-42c6-b1d4-83472ed7f7b0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa834374(v=AX.60)
ms:contentKeyID: 39520464
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Configure email functionality in Microsoft Dynamics AX 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To configure email functionality in Microsoft Dynamics AX, complete the procedures in this topic. These procedures will help you connect Microsoft Dynamics AX to an SMTP mail server, configure email settings for users, set up a batch to send email messages, and create email templates.

After you complete the procedures in this topic, Microsoft Dynamics AX can send email messages to users based on the features that you are using. For example, Microsoft Dynamics AX can send email messages to users when documents are assigned to them for approval (as defined by a [workflow](workflow-for-microsoft-dynamics-ax.md)), or when sales orders are canceled (as defined by an [alert rule](alerts.md)).

## At a glance

The following diagram shows the steps in the process for configuring the email functionality in Microsoft Dynamics AX.

![How to configure email functionality](images/Gg732160.Workflow_EmailProcess(AX.60).gif "How to configure email functionality")

## 1\. Set up your SMTP mail server

The first step in the process is to set up a Simple Mail Transfer Protocol (SMTP) mail server in your environment. To do so, complete the following procedures.

## Install the SMTP server

Install the SMTP server on a computer that is running Windows Server. The directions vary based on the version of Windows Server that you are using.

If you are using Windows Server 2008 or Windows Server 2008 R2, follow these steps to install the SMTP server.

1.  Click **Start** \> **Administrative Tools** \> **Server Manager**.

2.  In the **Features Summary** area, click **Add Features**.

3.  The **Select Features** page is displayed. Click the **SMTP Server** check box.

4.  A window is displayed that asks whether you want to add role services and features for the SMTP server. Click **Add Required Role Services**.

5.  The **Select Features** page is redisplayed. Click **Next**.

6.  The **Web Server (IIS)** page is displayed. Click **Next**.

7.  The **Select Role Services** page is displayed. Click **Next**.

8.  The **Confirm Installation Services** page is displayed. Click **Install**.

If you are using Windows Server 2012, follow these steps to install the SMTP server.

1.  On the **Start** screen, click **Server Manager**.

2.  Click the **Manage** menu, and then click **Add Roles and Features**.

3.  The **Before you begin** page is displayed. Click **Next**.

4.  The **Select installation type** page is displayed. Select the **Role-based or feature-based installation** option and then click **Next**.

5.  The **Select destination server** page is displayed. Select the server on which you want to install the SMTP server. Click **Next**.

6.  The **Select server roles** page is displayed. Click **Next**.

7.  The **Select Features** window is displayed. Click the **SMTP Server** check box.

8.  A window is displayed that asks whether you want to add role services and features for the SMTP server. Click **Add Features**.

9.  The **Select Features** page is redisplayed. Click **Next**.

10. The **Web Server (IIS)** page is displayed. Click **Next**.

11. The **Select Role Services** page is displayed. Click **Next**.

12. The **Confirm Installation Services** page is displayed. Click **Install**.

## Configure the SMTP server

Use the following procedure to configure the SMTP server to use integrated Windows authentication.

1.  From the **Start** menu or screen click **Administrative Tools**.

2.  Click **Internet Information Services (IIS) 6.0 Manager** to open IIS Manager.

3.  In the left pane, select the name of your server.

4.  In the right pane, right-click **\[SMTP Virtual Server \#1\]** and then click **Properties**.

5.  The **\[SMTP Virtual Server \#1\] Properties** window is displayed. Click the **Access** tab.

6.  Click the **Authentication** button.

7.  The **Authentication** window is displayed. Select the **Integrated Windows Authentication** check box. Click **OK**.

8.  The **Access** tab is redisplayed. Click the **Relay** button.

9.  The **Relay Restrictions** window is displayed. Select the **Allow all computers which successfully authenticate to relay, regardless of the list above** check box. Click **OK**.

10. The **\[SMTP Virtual Server \#1\] Properties** window is redisplayed. Click **OK** to close the window.

## Connect Microsoft Dynamics AX to the SMTP mail server

Use the following procedure to connect Microsoft Dynamics AX to the SMTP mail server.

1.  Open the Microsoft Dynamics AX client.

2.  Click **System administration** \> **Setup** \> **System** \> **E-mail parameters**.

3.  In the **Outgoing mail server** field, enter the name of the computer on which you installed the SMTP server.

4.  In the **Local computer name** field, enter the name of the local computer.

5.  In the **SMTP port number** field, enter the port number to use with SMTP. The default port number is 25.

6.  If the SMTP server requires authentication, enter a valid username and password.

7.  Select the **Use NTLM** check box.

8.  In the **Attachment size limit (MB)** field, enter a size limit for email attachments.
    
    The **maxbuffersize** registry key also limits the acceptable size for email attachments. If the size that you enter in this field exceeds the maximum buffer size, the maximum buffer size limit will apply.

9.  In the **Allow embedded data and attached files from** field, enter or browse to the location where email attachments or other embedded data in an email is stored.

## 2\. Enter the email address of each user

To enter the email address of each Microsoft Dynamics AX user, complete this procedure.


> [!NOTE]
> <P>If you’d rather have users enter their own email addresses, instruct users to do the following:</P>
> <OL>
> <LI>
> <P>Open the Microsoft Dynamics AX client.</P>
> <LI>
> <P>Click <STRONG>File</STRONG> &gt; <STRONG>Tools</STRONG> &gt; <STRONG>Options</STRONG>.</P>
> <LI>
> <P>Enter an email address in the <STRONG>E-mail</STRONG> field.</P></LI></OL>



1.  Open the Microsoft Dynamics AX client.

2.  Click **System administration** \> **Common** \> **Users** \> **Users**.

3.  Select a user.

4.  Click **Options**.

5.  In the **E-mail** field, enter the email address of the selected user.

6.  Click **Close**.

7.  The **Users** page is redisplayed. Select another user and repeat steps 4-6.

## 3\. Use batch processing to send email messages

Batch processing is used to send email messages that are generated from Microsoft Dynamics AX. Use the following procedures to create a batch group and configure the batch job that will send email messages.

## Create a batch group

A batch job, which is named *E-mail Distributor Batch Job*, is used to send email messages that are generated from Microsoft Dynamics AX. The batch job must run within the context of a batch group. Complete the following steps to create a batch group for the E-mail Distributor Batch Job.

1.  Click **System administration** \> **Setup** \> **Batch group**.

2.  Click **New** to create a new batch group.

3.  In the **Group** field, enter a unique name for the batch group. For example, enter *Email*.

4.  In the **Description** field, enter a description to help you identify the batch group.

5.  Click the **Batch servers** tab.
    
    The **Selected servers** list displays the AOS instances that the batch group runs on. The **Remaining servers** list displays the remaining AOS instances that are available as batch servers.

6.  Use the arrow buttons to add servers to the **Selected servers** list or to remove servers from the **Selected servers** list.

## Configure the batch job

Complete the following steps to configure the E-mail Distributor Batch Job.

1.  Click **System administration** \> **Periodic** \> **E-mail processing** \> **Batch**.

2.  Select the **Batch processing** check box.

3.  In the **Task description** field, enter a description for this batch job.

4.  In the **Batch group** list, select the batch group that you created in the previous procedure.

5.  Select the **Private** check box if you want to restrict other users from running this batch job. A private batch job can be run only by the user who specified it and only on the computer where the user is logged on.

6.  Click **Recurrence** to specify how often this batch job will run.

7.  Click **Alerts** to send notifications when this batch job ends, has an error, or is canceled.

## 4\. Configure email settings for specific features or applications

Many of the features and applications in Microsoft Dynamics AX can be configured to send email notifications to users. You must configure email settings that are specific to these features and applications. Refer to the documentation for these features and applications for specialized instructions. For example:

  - If you are using workflows, see [Configure email settings for the workflow system](configure-email-settings-for-the-workflow-system.md) for information about how to configure email functionality for the workflow system.

  - If you are using alert rules, see the [Alert email messages](alert-email-messages.md) for information about how to configure email functionality for alert rules.

  - If you are using Retail, see [Set up email receipts](set-up-email-receipts.md) for information about how to email receipts to customers.

The process of configuring email settings for specific features or applications will vary, but at a minimum, the process will include creating one or more email templates. The steps for creating an email template are included below.

## Create an email template

As part of the process of configuring email settings for a specific feature or application, you will need to create one or more email templates.

For example, suppose you have created a workflow in Microsoft Dynamics AX for purchase requisitions. This workflow defines who must approve purchase requisitions. You can configure the workflow so that email messages—based on an email template—are sent to the users who have purchase requisitions assigned to them for approval.

An email template can contain multiple versions, with each version written in a different language.

Complete the following procedure to create an email template.

1.  Click **Organization administration** \> **Setup** \> **E-mail templates**.

2.  Will the email template that you are creating be used across the whole organization or with a specific company? The answer to that question determines whether you should mark the **Show system e-mails** check box.
    
      - If the email template that you are creating will be used with a feature or application that is used across the whole organization, select the **Show system e-mails** check box.
        
        For example, if you are creating an email template to use with a purchase requisition workflow, select this check box. This is because a purchase requisition workflow is used across an entire organization. (For more information about how each type of workflow is used, see [Workflow types](workflow-types.md).)
    
      - If the email template that you are creating will be used with a feature or application that is used with a specific company, **do not** select the **Show system e-mails** check box.
        
        For example, if you are creating an email template to use with a purchase order workflow, do not select this check box. This is because a purchase order workflow is used with a specific company.

3.  In the upper pane of the form, press CTRL+N to create an email template.

4.  Enter the following information for the email template:
    
    1.  In the **E-mail ID** field, enter an ID for the email template. The ID should correspond to the purpose of the template. This field is limited to 10 characters.
    
    2.  In the **E-mail description** field, enter a description for the email template.
    
    3.  In the **Default language code** field, select a language code. If a user uses a different language and there is no corresponding version of the email template for that language, the email message will be sent using the language that you specify here.
    
    4.  In the **Sender name** field, enter a name for the sender, such as *Microsoft Dynamics AX*. This is the name that a recipient sees in his or her inbox when receiving an email message.
    
    5.  In the **Sender e-mail** field, enter an email address that can be used to send email messages generated by Microsoft Dynamics AX.

5.  Click the **General** tab. Complete the following steps:
    
    1.  In the **Priority** list, select a priority. This determines whether the email message will appear with priority in the recipient’s inbox.
    
    2.  In the **Batch group** list, select the batch group that you created earlier in this topic.

6.  In the lower pane of the form, press CTRL+N to create a language-specific version of the template. For each version you create, follow these steps:
    
    1.  Verify that the **E-mail ID** field displays the ID that you created in step 4.
    
    2.  In the **Language** field, select the language that you will use to write the body of the email message.
    
    3.  In the **Subject** field, enter the subject of the email message.
        
        If you want the subject of the email message to be automatically generated, enter **%subject%**. To better understand how this placeholder works, see the example listed in the following table.
        
        <table>
        <colgroup>
        <col style="width: 50%" />
        <col style="width: 50%" />
        </colgroup>
        <tbody>
        <tr class="odd">
        <td><p><strong>SCENARIO:</strong></p></td>
        <td><p>You are creating an email template for a purchase requisition workflow.</p></td>
        </tr>
        <tr class="even">
        <td><p><strong>IF:</strong></p></td>
        <td><p>Assume the following:</p>
        <ul>
        <li><p>You enter the following placeholder in the <strong>Subject</strong> field of the email template:</p>
        <p><strong>%subject%</strong></p></li>
        <li><p>The <strong>Work item subject</strong> field contains the following text. This field is located in the <strong>Properties</strong> form for the workflow approval step.</p>
        <p><strong>Action required: A purchase requisition is assigned to you for approval</strong></p></li>
        </ul></td>
        </tr>
        <tr class="odd">
        <td><p><strong>THEN:</strong></p></td>
        <td><p>In the email that is generated and sent to users, the placeholder <strong>%subject%</strong> is automatically replaced with the following text:</p>
        <p><strong>Action required: A purchase requisition is assigned to you for approval</strong></p></td>
        </tr>
        </tbody>
        </table>
        
        For more information about placeholders, see the next section in this topic.
    
    4.  In the **Layout** field, select either **XSLT** or **HTML**, depending on how the message should be displayed.
    
    5.  Click **E-mail message**. In the form that is displayed, enter the contents of the message.
        
        If you want the message to be automatically generated, enter **%message%**. To better understand how this placeholder works, see the example listed in the following table.
        
        <table>
        <colgroup>
        <col style="width: 50%" />
        <col style="width: 50%" />
        </colgroup>
        <tbody>
        <tr class="odd">
        <td><p><strong>SCENARIO:</strong></p></td>
        <td><p>You are creating an email template for a purchase requisition workflow.</p></td>
        </tr>
        <tr class="even">
        <td><p><strong>IF:</strong></p></td>
        <td><p>Assume the following:</p>
        <ul>
        <li><p>You enter the following placeholder as the message of the email template:</p>
        <p><strong>%message%</strong></p></li>
        <li><p>The <strong>Work item instructions</strong> field contains the following text. This field is located in the <strong>Properties</strong> form for the workflow approval step.</p>
        <p><strong>Purchase requisition %Purchase requisition.PurchReqId% has been assigned to you for approval.</strong></p>
        <p><strong>This purchase requisition totals %Purchase requisition.Approval amount%, and has been submitted by %Purchase requisition.Worker.createdBy%.</strong></p>
        <div class="alert"> 

        > [!NOTE]
        > <P>The text in between the <STRONG>%</STRONG> symbols are placeholders you can insert when you configure the workflow. In this example, the placeholders will be replaced with specific data related to purchase requisitions.</P>


        </div></li>
        </ul></td>
        </tr>
        <tr class="odd">
        <td><p><strong>THEN:</strong></p></td>
        <td><p>In the email that is generated and sent to users, the placeholder <strong>%message%</strong> is automatically replaced with the following text:</p>
        <p><strong>Purchase requisition PR-0108 has been assigned to you for approval.</strong></p>
        <p><strong>This purchase requisition totals USD 5000, and has been submitted by Jimmy Matney.</strong></p></td>
        </tr>
        </tbody>
        </table>
        
        For more information about placeholders, see the next section in this topic.
    
    6.  Save the message.

## Use placeholders

Placeholders can be used when you create email templates. The placeholders will be replaced with text that is specific to the feature for which you’re creating the email template.

For example, suppose you are creating an email template that will be sent to users who must approve purchase requisitions. If you enter **%message%** in the body of the email template, the placeholder **%message%** will be replaced with the text that was entered in the workflow configuration properties.

The following placeholders can be added to email templates. The placeholders you should use depend on whether you chose to create the email template using HTML or XSLT.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>HTML placeholder</p></th>
<th><p>XSLT placeholder</p></th>
<th><p>Information that is displayed in the email message</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>%subject%</p></td>
<td><p>alert/subject</p></td>
<td><p>The subject that is defined in the configuration properties of the related feature.</p></td>
</tr>
<tr class="even">
<td><p>%message%</p></td>
<td><p>alert/message</p></td>
<td><p>The message that is defined in the configuration properties of the related feature.</p></td>
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


## Specify when each template should be used

After you have created email templates, you must specify when each template should be used. For instructions about how to do this, see the documentation for the features for which you created the email templates.

For example:

  - If you created email templates for workflows, see [Configure email settings for the workflow system](configure-email-settings-for-the-workflow-system.md) for information about how to configure the workflow system to use these templates.

  - If you created email templates for alert rules, see the [Define an email identification for alerts](define-an-email-identification-for-alerts.md) for information about how to configure alert rules to use these templates.

  - If you created email templates for collection purposes in the Accounts Receivable module, see [Set up collections](set-up-collections.md) for information about how to configure Accounts Receivable to use these templates.

## 5\. Monitor email messages that are waiting to be sent

Use the following procedures to monitor outgoing email messages.

## View the status of outgoing email messages

Use the following procedure to monitor the status of email messages that are waiting to be sent.

1.  Click **System administration** \> **Periodic** \> **E-mail processing** \> **E-mail sending status**.

2.  If you want the form to list all email messages—including the ones that have been sent successfully—select the **Also show sent e-mails** check box.

3.  View the status of each email message in the **Status** column.
    
      - When a message has been sent, its status is **Sent**.
    
      - When a message is waiting to be sent, its status is **Waiting**.
        
        The **Waiting** status is followed by a number "n" in parentheses, such as 1. This number indicates the number of attempts made to send the email message. The number cannot be more than the number of retry attempts specified in the retry schedule. (For more information about the retry schedule, see the following section.)
    
      - When a message wasn’t sent successfully—and no retry attempts are scheduled—its status is **Failed**.
        
        If you’d like to try to resend this message, click **Restart send**. The retry schedule will be followed when attempting to send this message.

## Establish a retry schedule

You can set up a retry schedule for messages that were not sent successfully. The retry schedule specifies how many attempts you want made to send email messages, and the time period between each attempt.

The retry schedule must be set up in such a way that the AOS server is not overloaded. The time intervals between attempts must increase gradually. For example, the first retry attempt might occur after one minute, the second attempt might occur after one hour, the third attempt might occur after one day, and so on. To distribute the workload, the retry schedule can be set up on multiple AOS servers, as well.


> [!NOTE]
> <P>Keep in mind that email messages are sent through batch processing. The configuration of the E-mail Distributor Batch Job affects how often retry attempts are made. For example, if you configured the batch job to run hourly, a retry attempt cannot be made five minutes after the first attempt failed.</P>



To set up a retry schedule, complete the following procedure.

1.  Click **System administration** \> **Periodic** \> **E-mail processing** \> **Retry schedule**.

2.  Press CTRL+N to create a new retry attempt.
    
    The retry attempts are automatically numbered for you. (For example, they are numbered 1, 2, 3, and so on.) Each attempt is listed in the **Delay period** column.

3.  In the **Retry delay** field, enter a number.
    
    For example, if you want this attempt to occur 5 minutes after the previous attempt to send the email message, enter **5** here.

4.  In the **Measurement** field, select a time measurement unit, such as **Minutes**, **Hours**, or **Days**.
    
    For example, suppose you want the first retry attempt to occur after one minute, the second attempt to occur after one hour, and the third attempt to occur after one day. In this scenario, the **Retry schedule** form would look like the following table.
    
    <table>
    <colgroup>
    <col style="width: 33%" />
    <col style="width: 33%" />
    <col style="width: 33%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Delay period</p></th>
    <th><p>Retry delay</p></th>
    <th><p>Measurement</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>1</p></td>
    <td><p>1</p></td>
    <td><p>Minutes</p></td>
    </tr>
    <tr class="even">
    <td><p>2</p></td>
    <td><p>1</p></td>
    <td><p>Hours</p></td>
    </tr>
    <tr class="odd">
    <td><p>3</p></td>
    <td><p>1</p></td>
    <td><p>Days</p></td>
    </tr>
    </tbody>
    </table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

