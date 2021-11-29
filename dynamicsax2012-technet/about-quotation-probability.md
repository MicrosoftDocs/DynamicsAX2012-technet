---
title: About quotation probability
TOCTitle: About quotation probability
ms:assetid: 42931392-39c5-4a3f-81d3-912dee68fc8b
ms:mtpsurl: https://technet.microsoft.com/library/Aa496961(v=AX.60)
ms:contentKeyID: 36056873
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About quotation probability 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use quotation probability codes to indicate the probability that the quotation will become a sales order or a project. The quotation probability is expressed as a percentage between 0–100 percent, and each quotation must have a probability defined for it when it is created.


> [!NOTE]
> <P>By default, if the quotation probability is not set, the system will use the value 0%.</P>



You can define the expected value of a quotation in the pipeline by adjusting the total value of the quotation by the probability of the quotation actually becoming an order. Because this adjustment determines the expected value, set the probability as correctly as possible for the given quotation. For example, if the total value of a quotation is USD 1,000 and the quotation probability is 80 percent, your expected value might be USD 800.

You can also include quotations with item demands in the master scheduling. By specifying a base probability on the master plan, you can additionally delimit the quoted items that are to be considered in the planning.


> [!NOTE]
> <P>You can define and modify the probability for the quotation header and each quotation line as required; however, if you change the probability for the quotation header, the probability for all the quotation lines will automatically change to reflect the new quotation probability.</P>


  


