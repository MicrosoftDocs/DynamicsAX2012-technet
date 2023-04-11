---
title: About synchronizing project information between Microsoft Dynamics AX and Microsoft Dynamics CRM
TOCTitle: About synchronizing project information between Microsoft Dynamics AX and Microsoft Dynamics CRM
ms:assetid: 7e809461-8779-490c-87b9-d783ecff3202
ms:mtpsurl: https://technet.microsoft.com/library/Dn269117(v=AX.60)
ms:contentKeyID: 54920069
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About synchronizing project information between Microsoft Dynamics AX and Microsoft Dynamics CRM 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

To help your project teams and sales teams create and process project quotations more efficiently, you can synchronize data between Microsoft Dynamics AX and Microsoft Dynamics CRM. Data that is entered or updated in one program is automatically changed in the other. You set up this synchronization by installing the Integration Solution for Microsoft Dynamics AX projects and Microsoft Dynamics CRM.

The integration solution enables four key scenarios:

  - When you create and submit a project quotation in Microsoft Dynamics CRM, the project quotation is also created in Microsoft Dynamics AX.

  - When you update and approve the project quotation in Microsoft Dynamics AX, the quotation is updated to **Approved in Microsoft Dynamics AX** in Microsoft Dynamics CRM.

  - When you update the status of a project quotation to **Won** in Microsoft Dynamics CRM, the status of the quotation is updated to **Confirmed** in Microsoft Dynamics AX.

  - When you create a project in Microsoft Dynamics AX, high-level project information is updated in Microsoft Dynamics CRM.

**Prerequisites**

Before you can use the integration solution, you must do the following:

  - Install the Connector for Microsoft Dynamics and the Integration Solution for Microsoft Dynamics AX projects and Microsoft Dynamics CRM.

  - Configure the integration services in Microsoft Dynamics CRM and Microsoft Dynamics AX.

For more information, see [Integration Solution for Microsoft Dynamics AX projects and Microsoft Dynamics CRM](https://mbs.microsoft.com/partnersource/deployment/documentation/installationandsetup/msdcrmaxintegrationsol.htm) on PartnerSource.

## Creating and submitting project quotations

When you create and submit a project quotation in Microsoft Dynamics CRM, a corresponding project quotation is automatically created in Microsoft Dynamics AX. The following figure illustrates this process.

![Project quotation flow between CRM and AX](images/Dn269117.Conncectorscenario_1(AX.60).png "Project quotation flow between CRM and AX")

  
 **The process:**

1.  A member of the sales team creates a new project quotation in Microsoft Dynamics CRM.

2.  The salesperson adds line items to the project quotation.
    

    > [!NOTE]
    > <P>Products and product categories that are defined in Microsoft Dynamics AX are synchronized into Microsoft Dynamics CRM.</P>



3.  The salesperson clicks the **Submit** button to submit the project quotation.
    
    After the project quotation is submitted, the quotation can’t be edited in Microsoft Dynamics CRM until it is approved or rejected in Microsoft Dynamics AX.

4.  A project quotation is automatically created in Microsoft Dynamics AX.


> [!NOTE]
> <P>If you create a project quotation in Microsoft Dynamics CRM, but you do not submit it to be synchronized with Microsoft Dynamics AX, the project quotation is created automatically in Microsoft Dynamics AX when you update the quotation status to <STRONG>Won</STRONG>.</P>



## Updating and approving project quotations

After a project quotation is created and submitted in Microsoft Dynamics CRM and created in Microsoft Dynamics AX, the quotation can be updated as necessary in Microsoft Dynamics AX. When the quotation is set to **Approved** in Microsoft Dynamics AX, the status in Microsoft Dynamics CRM is automatically updated to **Approved in Microsoft Dynamics AX**. The following figure illustrates this process.

![Project quotation flow](images/Dn269117.Connectorscenario_2(AX.60).png "Project quotation flow")

  
 **The process:**

1.  In Microsoft Dynamics AX, the project manager updates the details of the project quotation and then approves the changes.

2.  In Microsoft Dynamics CRM, the project quotation is automatically updated to **Approved in Microsoft Dynamics AX**.

## Updating the status when a project quotation is won

After a project quotation is approved in Microsoft Dynamics AX, the salesperson can activate the quotation in Microsoft Dynamics CRM and then share the project quotation with the customer. After the customer accepts the project quotation, the salesperson can update the status of the project quotation to **Won** in Microsoft Dynamics CRM. The quotation status is automatically updated to **Confirmed** in Microsoft Dynamics AX. The following figure illustrates this process.

![Project quotation flow between AX and CRM](images/Dn269117.Connectorscenario_3(AX.60).png "Project quotation flow between AX and CRM")

  
 **The process:**

1.  The salesperson activates the project quotation in Microsoft Dynamics CRM.

2.  The salesperson marks the project quotation as **Won**.

3.  The project quotation status is updated to **Confirmed** in Microsoft Dynamics AX.

## Creating a new project in Microsoft Dynamics AX from the project quotation

After your organization has won the project quotation, use the **Transfer to project** wizard in Microsoft Dynamics AX to create a new project that is based on the details of the project quotation. After the project is created in Microsoft Dynamics AX, the project is synchronized in Microsoft Dynamics CRM. The following figure illustrates this process.

![Create a project in AX from a CRM won quotation](images/Dn269117.Connectorscenario_4(AX.60).png "Create a project in AX from a CRM won quotation")

  
 **The process:**

1.  In Microsoft Dynamics AX, the project manager transfers the project quotation to a project by using the **Transfer to project** wizard.

2.  The project manager opens the **Projects** form for the new project and selects the **Synchronize to Dynamics CRM Project** check box.

3.  In Microsoft Dynamics CRM, the salesperson can view information about the new project.

  


