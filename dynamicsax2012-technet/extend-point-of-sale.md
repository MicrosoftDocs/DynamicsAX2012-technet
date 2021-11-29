---
title: Extend Point of Sale
TOCTitle: Extend Point of Sale
ms:assetid: 971317d1-61cc-4336-ba94-32cb5d345996
ms:mtpsurl: https://technet.microsoft.com/library/JJ937973(v=AX.60)
ms:contentKeyID: 50950761
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Extend Point of Sale 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Microsoft Dynamics AX for Retail POS is a fully customizable point of sale (POS) component of Microsoft Dynamics AX 2012 for Retail. You use Retail POS to process sales, operate the cash drawer, scan bar codes or print customer receipts, among other business tasks. For more information, see [Overview: Setting up Retail POS](setting-up-retail-pos.md).

To customize business logic in Retail POS, you must install the Retail Software Development Kit (SDK). The Retail SDK ships with Microsoft Dynamics AX 2012. For information about how to install the Retail SDK, see [Install the Retail SDK](install-retail-sdk-retail-pos-plug-ins.md).

The Retail SDK contains the following two folders that relate to Retail POS:

  - POS Clients – contains sample POS clients.

  - POS Plug-ins – contains code that you use to extend and customize Retail POS. For more information about how to install Retail POS Plug-ins, see [Install the Retail SDK](install-retail-sdk-retail-pos-plug-ins.md).


> [!WARNING]
> <P>POS Plug-ins can only be compiled if Retail POS is installed on machine.</P>



For more information about the Retail SDK, see [Retail SDK](retail-sdk.md).

## Retail POS Plug-ins

Retail POS Plug-ins contain sets of services and application triggers. Most of the functionality in Retail POS is implemented by using services. For example, you use the Customer service for tracking, adding or deleting customers from the Retail POS Plug-ins register.

These services are collected in .NET Framework assemblies that implement public interfaces. Retail POS loads the services at runtime and invokes their functionality through these interfaces. Because Retail POS Plug-ins ship with the C\# source code for these assemblies, you can customize or replace services and triggers to extend features in Retail POS, such as calculating taxes.

Retail POS Plug-ins typically are installed in the following directory:

User\\MyDocuments\\Retail SDK\\POS Plug-ins

The folder contains two Visual Studio solutions – one for services and the other for triggers. You use triggers to insert custom code before or after Retail POS Plug-ins operations, such as issuing a gift certificate.

To deploy your customized services or triggers, compile your changes and then copy the updated assemblies into the Retail POS runtime directory, which is typically located at \<root\>\\Program Files (x86)\\Microsoft Dynamics AX\\60\\Retail POS. Beneath that folder is a Triggers folder for customized triggers and a Services folder for customized services.


> [!NOTE]
> <P>When updates are applied to Retail POS, they may overwrite your customized assemblies. If you have customized Retail POS, you must re-merge your code changes to services and triggers, compile, and re-deploy them.</P>



There is also a documented sample solution and the Microsoft.Dynamics.Retail.Pos.Contracts.dll that exposes all the public interfaces you use to implement the following Retail POS core functionality:

  - Operations

  - Services

  - Triggers

  - Commerce Data Exchange: Real-time Service


> [!NOTE]
> <P>Two of the Retail POS Plug-ins services (Price and Discount) rely on a Commerce Runtime project called the PriceEngine, which is located in the SDK under the CommerceRuntime/Services/Pricing/PriceEngine. In previous versions of Retail POS, you would make changes to the code in the Retail POS Plug-ins Price service to modify the GetPrice API. In Microsoft Dynamics AX 2012 R3 or cumulative update 7 or later for AX 2012 R2, you change the code in the PriceEngine service under the PriceEngine project. After you have modified the PriceEngine class, you should deploy those changes to EPOS, Online Storefront (CRT), Retail Server (CRT) and the AOT. Deploy the changes by placing the updated assemblies to all clients.</P>



## Operations

An operation is an activity that occurs in Retail POS. Operations can be single- or multi-step. For example, **Add Item** adds a sales line to the current transaction. The **Customer add** operation presents a form for a cashier to enter customer information. Once data is entered and the form is closed, the customer information is sent to Retail Headquarters.

Microsoft Dynamics AX 2012 ships with a collection of core operations which cannot be modified. However, you can create new functionality by using the BlankOperations. For more information on using BlankOperations, see [Use BlankOperations to implement custom features](use-blankoperations-to-implement-custom-features.md).

## Services

Services include one or more operations and implement a single, unique interface. You can make partial modifications to an existing service and continue to use the remaining functionality. Alternatively, you can replace the entire service assembly with your own custom code. For more information on implementing services, see [Modify a form](modify-a-form.md).

Microsoft Dynamics AX 2012 ships with a collection of core services that can be customized or replaced using Retail POS Plug-ins. You can also create new services, which can be invoked from existing services or triggers.

## Triggers

Triggers are events raised by Retail POS that enable you to insert custom code before or after operations. There are two types of triggers:

  - Pre-triggers

  - Post-triggers

You use pre-triggers to insert custom code before an operation is executed. For example, if a customer uses a coupon for a purchase, you can use a pre-trigger to insert custom code validating that the coupon has not expired or been previously used.

You use post-triggers to insert custom code that responds to a completed operation. For example, you could write code that runs after the **DiscountOperation** completes to verify that the discount is valid. All Retail POS operations raise the PreProcessOperation and the PostProcessOperation events. This enables you to run your code before or after any operation.

Microsoft Dynamics AX 2012 ships with a collection of operation-specific triggers that can be customized or replaced using Retail POS Plug-ins. You can also use the generic OperationTrigger to intercept operations that don’t have operation-specific triggers. For more information on triggers, see [Modify a trigger](modify-a-trigger.md).

## Commerce Data Exchange: Real-time Service Calls

Retail POS can make real-time calls to Microsoft Dynamics AX 2012 using the Commerce Data Exchange: Real-time Service. This service provides real-time, synchronous communication between Microsoft Dynamics AX 2012 and individual Retail POS terminals.

Retail POS uses real-time service calls to invoke Retail POS functionality, such as **Issue Gift Card** or **Create Customer**. You can create custom, real-time service functionality in Retail Headquarters and call it from Retail POS.

  


