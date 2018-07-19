---
title: Process a customer request
TOCTitle: Process a customer request
ms:assetid: 7ed75e06-a39e-477f-8f05-bcbe54a8afc5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn237263(v=AX.60)
ms:contentKeyID: 54273730
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- request
- customer request
- customer requests
- sign up
- signup
audience: Application User
ms.search.region: Global
---

# Process a customer request 


_**Applies To:** Microsoft Dynamics AX 2012_

Customer requests that have been submitted in Enterprise Portal for Microsoft Dynamics AX are received and processed in the **Registration** form in the Microsoft Dynamics AX client. When you approve and process a customer request, you grant the customer access to your company’s **Customer self-service** portal.

For more general information about customer requests, see [About customer requests](about-customer-requests.md).

## Approve a customer request

Use this procedure to approve a customer request. The approver is typically the person who is responsible for creating and maintaining customer master data.

1.  Click **Sales and marketing** \> **Setup** \> **Customer self-service** \> **Sign up**.

2.  In the **Sign-up status** field, select **Verified by user**. Select a customer request.
    

    > [!TIP]
    > <P>By selecting <STRONG>Requested</STRONG> in the <STRONG>Sign-up status</STRONG> field, you can see the customer requests that have been submitted but not yet verified by the requestor.</P>



3.  Review and validate the information that was entered by the customer, such as the company address. Automatic validation does not occur when the customer request is submitted.

4.  Click **Approve**.

## Create a customer

Use this procedure to create a customer in Microsoft Dynamics AX.

1.  Click **Sales and marketing** \> **Setup** \> **Customer self-service** \> **Sign up**.

2.  In the **Sign-up status** field, select **Approved**. Select a customer request, and then click **Create**.

3.  In the **Create new customer** form, select the **Create new customer** check box if the request is from a new customer.
    
    –or–
    
    If the request is from a customer who is already in the system, select the customer account in the **Existing customer account** field to create a new contact for the customer.

4.  In the **Customer account template** field, select the template that applies to the new customer, if available.
    

    > [!TIP]
    > <P>Using a template speeds up the process of creating customer records. You can create templates that are based on the values in fields in customer records that you specify as template models. The field values of the template are copied to the fields in the new customer record. You can change the fields and enter more information, as appropriate. For more information, see <A href="create-a-customer-record.md">Create a customer record</A>.</P>



5.  Verify the user role that is displayed in the **User role** field to make sure that the user is assigned the correct security permissions.

6.  Click **OK** to create the customer account. If a workflow exists for user requests, a user request for the customer is automatically submitted to the user request workflow and the user provisioning process is performed. You can see the user request in the **User requests** form.

## Workflow for user requests

After the customer account is created, you use workflow to start the user provisioning process. This process creates a registered Microsoft Dynamics AX user for the customer contact person who made the request. Creating a user is the final step in processing an unsolicited customer request. Logon information is generated that the customer can use to log on to the **Customer self-service** portal in Enterprise Portal using the specified authentication method for your company. Depending on how you configure the workflow, an email notification that contains the logon information can be generated and sent to the customer contact person. The user request workflow can be adapted to the actual business processes for your organization.

For more information about the steps that must be completed before a user request is submitted to workflow, see [About customer requests](about-customer-requests.md).


> [!NOTE]
> <P>There are various types of user requests in Microsoft Dynamics AX. You can configure the user request workflow specifically for customers by using the condition <STRONG>User Request.RequestType is Customer</STRONG>. For more information about how to create a user request workflow, see <A href="set-up-system-administration-workflows.md">Set up System administration workflows</A> or <A href="create-a-workflow.md">Create a workflow</A>.</P>



## See also

[About customer requests](about-customer-requests.md)

[Create a customer request](create-a-customer-request.md)

[Set up System administration workflows](set-up-system-administration-workflows.md)

[Configure email functionality in Microsoft Dynamics AX](configure-email-functionality-in-microsoft-dynamics-ax.md)

  


