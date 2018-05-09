---
title: 'Key tasks: Set up vendor user provisioning'
TOCTitle: 'Key tasks: Set up vendor user provisioning'
ms:assetid: 7126df3b-0969-4082-a964-59339fc63e21
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242649(v=AX.60)
ms:contentKeyID: 36058065
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- vendor
- vendors
- provision
- user provisioning
- vendor user
- vendor users
---

# Key tasks: Set up vendor user provisioning 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic provides information about how to configure Microsoft Dynamics AX to enable user provisioning. Users are provisioned either as part of the user request process, or automatically through specific tasks in the user request workflow. User provisioning automates the creation of Microsoft Dynamics AX user accounts and user permission assignments. This ensures proper control of users and their access to the Vendor portal and simplifies the process of creating users.

Microsoft Dynamics AX 2012 supports flexible authentication. Flexible authentication allows users to be authenticated in Microsoft Dynamics AX by using Windows Live ID, Active Directory Federation Services (AD FS), or forms-based authentication. When you use flexible authentication, users do not have to be listed in Active Directory Domain Services (AD DS) to access data or forms in Microsoft Dynamics AX. For more information, see [Deploy an Enterprise Portal site that uses forms-based authentication](deploy-an-enterprise-portal-site-that-uses-forms-based-authentication.md).

## What do you want to do?

Learn more about...

Set up Enterprise Portal parameters for vendor user provisioning

Set up the user request workflow

Set up the inactivate user request workflow

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About provisioning vendor users](about-provisioning-vendor-users.md)

## Set up Enterprise Portal parameters for vendor user provisioning

You must set up the user provisioning parameters for Enterprise Portal for Microsoft Dynamics AX to support user authentication in the Vendor portal.

1.  Click **System administration** \> **Setup** \> **Enterprise Portal** \> **Enterprise Portal parameters**. Click **User provisioning**.

2.  Select options in the **Forms based user credentials** section:
    
      - Select the **Use e-mail address as user alias** check box if you are using forms-based authentication or Windows Live ID authentication, and you are using the **Automated user provisioning** task in the user request workflow.
    
      - If you are using the **Notify user alias** task in the user request workflow, in the **User alias notification template** field, select a template. The template defines the email message that is sent to users to notify them that their user alias has been created.
        

        > [!NOTE]
        > <P>This step is required when you are using forms-based authentication and optional for other authentication methods.</P>

    
      - In the **Temporary password notification template** field, select a template. The template defines the email message that is sent to users to notify them of their temporary password for accessing the Vendor portal.
        

        > [!NOTE]
        > <P>This step is required when you are using forms-based authentication and optional for other authentication methods.</P>



3.  Select options in the **Vendor user account authentication** section:
    
      - In the **Vendor self-service portal website** field, enter the URL for the Vendor portal website. The user is directed to this website after they have been authenticated as a Microsoft Dynamics AX user.
    
      - In the **Vendor authentication method** field, select the method to use for authenticating vendor users before they can access the Vendor portal.
    
      - In the **E-mail template for vendor user request** field, select the email template to use to welcome vendor users. The template defines the email message that is sent to users to notify them that the user request process is complete and they can log on to the Vendor portal. This email template is invoked by the **Notify new user** task in the user request workflow.
    
      - In the **Vendor claims provider name** field, enter the name of the claims provider. The claims provider is the authentication provider that you specified in Microsoft SharePoint Foundation 2010 or Microsoft SharePoint Server 2010 when you configured flexible authentication. For more information, see [Deploy an Enterprise Portal site that uses forms-based authentication](deploy-an-enterprise-portal-site-that-uses-forms-based-authentication.md).

Back to top

## Set up the user request workflow

The user request workflow controls the user provisioning process. This includes adding new users and modifying existing users. The user request workflow can be set up to automate the user provisioning process, or it can be set up to allow the system administrator to set up users manually or by using provisioning.

This procedure explains some of the workflow tasks that are specific to the user request process.

1.  Click **System administration** \> **Setup** \> **Workflow** \> **User workflows**.

2.  On the **Action Pane**, click **New** to create a new workflow configuration for user requests.

3.  In the **Create workflow** form, in the **Name** field, select **User request workflow**. Then click **Create workflow**.

4.  In the workflow editor, select and configure the workflow tasks.
    
      - **Approve user request** – This task defines the approval process for user requests. It defines approvers, conditions for initiating the approval step, escalation criteria, and approval actions. Approval actions include approving or rejecting a request, or delegating the request to another reviewer.
    
      - **Automated provision user** – Use this task to start the user provisioning process automatically. To use this task, the **Use e-mail address as user alias** check box in the **Enterprise Portal parameters** form must be selected.
    
      - **Notify new user** – Use this task to send an email message to a new user to notify them of their Microsoft Dynamics AX alias. To use this task for vendor user requests, a template must be selected in the **Enterprise Portal parameters** form, in the **E-mail template for vendor user request** field.
    
      - **Notify user alias** – Use this task to send an email message to users to notify them of their user alias in Microsoft Dynamics AX. To use this task, a template must be selected in the **Enterprise Portal parameters** form, in the **User alias notification template** field.
        

        > [!NOTE]
        > <P>This task applies only when forms-based authentication is used to verify workers.</P>

    
      - **Provision new user** – Use this task to allow the system administrator to start the new user provisioning process manually in the **User request details** form.

Back to top

## Set up the inactivate user request workflow

An inactivate user request is used to remove user access privileges for an existing user. The inactivate user request workflow allows the system administrator to initiate the user inactivation process manually.

This procedure explains some of the workflow tasks that are specific to the inactivate user request process.

1.  Click **System administration** \> **Setup** \> **Workflow** \> **User workflows**.

2.  On the **Action Pane**, click **New** to create a new workflow configuration for user requests.

3.  In the **Create workflow** form, in the **Name** field, select **Inactivate user request workflow**. Then click **Create workflow**.

4.  In the workflow editor, select and configure the workflow tasks.
    
      - **Approve user request** – This task defines the approval process for inactivate user requests. It defines approvers, conditions for initiating the approval step, escalation criteria, and approval actions. Approval actions include delegating, escalating, approving, or denying requests.
    
      - **Inactivate existing user** – This task defines the inactivate process, including step assignment, escalation criteria, and step actions. Step actions include delegating, escalating, and marking the task completed.

Back to top

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

