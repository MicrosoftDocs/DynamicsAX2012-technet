---
title: Integration planning process
TOCTitle: Integration planning process
ms:assetid: 56c4b24d-cc42-4ebf-a407-0ac0a6c14fb4
ms:mtpsurl: https://technet.microsoft.com/library/Dd309680(v=AX.60)
ms:contentKeyID: 35132640
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Integration planning process 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A typical integration scenario uses document-based exchanges. Whether you require integration with internal legacy systems or external trading partners, planning for the integration involves common key steps.

## Integration planning steps

1.  In a typical integration scenario, users who have business expertise first determine the requirements for document exchanges. These requirements are requirements from a business perspective. The business users work with the implementation team to determine the following requirements:
    
      - The data that must be exchanged
    
      - Any business logic that is related to that data
    
      - The external systems with which data must be exchanged
    
      - The conditions under which data is sent from or received by Microsoft Dynamics AX

2.  The system implementer works with the IT staff to determine the hardware and software requirements for Application Integration Framework (AIF). The system implementer analyzes the existing environment, and recommends any new hardware or software that must be installed.

3.  The IT staff installs and configures any hardware and software that are required to support AIF.

4.  A developer programs the document exchange. The developer may either customize the AIF documents or create new documents to meet the requirements of the business users. The configuration of AIF partly depends on the network environment. Therefore, the developer may work with the IT staff to implement an integration scenario.

5.  The IT staff monitors the document exchanges and troubleshoots any errors that are generated.

The following figure provides a high-level view of the process that is used to integrate Microsoft Dynamics AX with other systems.

![AIF Integration Process](images/Dd309680.AIFIntegrationProcess(AX.60).gif "AIF Integration Process")

**Overview of the process of integrating Microsoft Dynamics AX with other systems**

## See also

[Plan for integration](plan-for-integration.md)

  


