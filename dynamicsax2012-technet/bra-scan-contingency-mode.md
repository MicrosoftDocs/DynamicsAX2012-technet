---
title: (BRA) SCAN contingency mode
TOCTitle: (BRA) SCAN contingency mode
ms:assetid: 0e956008-68bf-448c-bbf0-7c2e3d7a10c1
ms:mtpsurl: https://technet.microsoft.com/library/Dn269132(v=AX.60)
ms:contentKeyID: 54920084
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BR-00046
audience: Application User
ms.search.region: Brazil
---

# (BRA) SCAN contingency mode 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can turn on and use the Sistema de Contingência do Ambiente Nacional (SCAN) contingency environment to generate, export, and import the status of a Nota Fiscal eletrônica (NF-e) when the origin Secretaria da Fazenda (SEFAZ) environment is not available. You can turn off the SCAN contingency mode when the origin SEFAZ is available.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 6 for AX 2012 R2.</P>



## What is the SCAN contingency mode, and when should I turn it on?

Sistema de Contingência do Ambiente Nacional (SCAN) is a contingency environment that is used when the origin Secretaria da Fazenda (SEFAZ) environment is not available. You can turn on the SCAN contingency mode in Microsoft Dynamics AX when the origin SEFAZ is not available and the SCAN environment is activated for the state.

## How do I set up a SCAN authority?

You can set up a SCAN authority in the **NF-e federal parameters** form. You can set up only one authority for the SCAN contingency mode.

## Can I cancel an NF-e if the NF-e was approved using the SCAN contingency mode?

Yes. You can cancel an NF-e if the NF-e was approved in the SCAN contingency mode. Microsoft Dynamics AX sends the cancellation request to the SCAN contingency environment, even if the SCAN contingency mode is turned off. NF-e events for an NF-e that was approved in the SCAN contingency mode are communicated to the SCAN contingency environment.

## Can I check the status of the origin SEFAZ authority?

Yes. You can check the status of the origin SEFAZ authority in the **NF-e web services status** form.

## When and how do I turn off the SCAN contingency mode?

You can turn off the SCAN contingency mode when the origin SEFAZ is available. You can use the **Contingency mode** form to turn off the SCAN contingency mode for a fiscal establishment.

## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

## See also

[(BRA) About the NF-e process](bra-about-the-nf-e-process.md)

[(BRA) About NF-e schemas and processes](bra-about-nf-e-schemas-and-processes.md)

[(BRA) Set up and use SCAN contingency mode](bra-set-up-and-use-scan-contingency-mode.md)

  


