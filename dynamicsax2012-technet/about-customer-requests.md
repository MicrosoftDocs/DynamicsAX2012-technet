---
title: About customer requests
TOCTitle: About customer requests
ms:assetid: fb780691-69e5-486f-a28e-ff239f34e2e6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn237264(v=AX.60)
ms:contentKeyID: 54273731
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- request
- configuration
- customer
- customer request
- customer requests
- sign up
- signup
audience: Application User
ms.search.region: Global
---

# About customer requests 


_**Applies To:** Microsoft Dynamics AX 2012_

A prospective customer might want to submit a request to become a registered customer in Microsoft Dynamics AX. The contact person for the prospective customer company can complete a request on the **Sign up** page in Enterprise Portal for Microsoft Dynamics AX, where they provide company address information, contact information, and their preferred user logon credentials.

## Customer request process

![The process for unsolicited customer requests](images/Dn237264.CSSCustomerRequestProcess(AX.60).gif "The process for unsolicited customer requests")

In this process, one external business role and one business role in the organization are included:

  - The customer contact person – The person from an external business who is responsible for sourcing potential vendors

  - The approver – Typically the person from your organization who is responsible for creating and maintaining customer master data

The customer request process follows these steps:

1.  A prospective customer submits a customer request on the **Sign up** page in Enterprise Portal.

2.  The customer validates the request.

3.  The request is received in the **Registration** form in the Microsoft Dynamics AX client. The approver approves the request.

4.  The approver creates a customer record, creates a contact person record, and submits the request to workflow.

5.  The user request workflow performs the user provisioning process. A new registered Microsoft Dynamics AX user is created for the customer contact person.

6.  The workflow automatically generates and sends an email notification that contains Microsoft Dynamics AX logon information to the customer contact person. The customer can log on to the **Customer self-service** portal in Enterprise Portal by using the specified authentication method for your company.
    

    > [!NOTE]
    > <P>You must configure the user request workflow to enable email communication. For more information, see <A href="configure-email-functionality-in-microsoft-dynamics-ax.md">Configure email functionality in Microsoft Dynamics AX</A>.</P>



## Customer request prerequisites

Before customer requests can be submitted and processed, the following configuration steps must be completed:

1.  Create and configure a public Enterprise Portal website that can be accessed by external users.

2.  Set up number sequences for customer requests in the **Customer self-service parameters** form. For more information, see [Customer self-service parameters (form)](https://technet.microsoft.com/en-us/library/aa590303\(v=ax.60\)).

3.  Configure the user request workflow. For more information, see [Set up System administration workflows](set-up-system-administration-workflows.md).
    

    > [!NOTE]
    > <P>If you do not configure the user request workflow, the customer request will not be processed automatically when you click <STRONG>Create</STRONG> from the <STRONG>Registration</STRONG> form to create a new user. For more information about how to create new users, see <A href="process-a-customer-request.md">Process a customer request</A>.</P>



4.  Enable workflow. For more information, see [Configuring the workflow system](configuring-the-workflow-system.md).

## See also

[Create a customer request](create-a-customer-request.md)

[Process a customer request](process-a-customer-request.md)

[Configuring Enterprise Portal for customer requests](configuring-enterprise-portal-for-customer-requests.md)

Checklist: Deploy a customer self-service portal

[Registration (form)](https://technet.microsoft.com/en-us/library/dn277353\(v=ax.60\))

  


