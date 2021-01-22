---
title: About quotation prognosis
TOCTitle: About quotation prognosis
ms:assetid: 4e44cd44-f540-41fa-8e6c-4ec492147c09
ms:mtpsurl: https://technet.microsoft.com/library/Aa497122(v=AX.60)
ms:contentKeyID: 36057050
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About quotation prognosis 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use quotation prognosis to indicate the time in which a quotation might become a sales order or a project. Defining a prognosis code for the quotation is optional and can be defined when a quotation is created.

The prognosis that you define for each quotation affects sales statistics for sales management and sales pipeline management by defining which quotations are in the pipeline and helping define the expected value of the quotations in the pipeline.

Depending on how your company defines its sales process, a quotation prognosis interval might be expressed in shorter time periods, such as days or weeks, or longer periods, such as months.

The quotation prognosis is defined by a prognosis code and two fields: **Prognosis from days** and **Prognosis to days**. These fields define the start period and end period of the prognosis code, respectively, and they are measured in the number of days after the quotation has been created.

When you set up each prognosis code, make sure that the prognosis days do not overlap.


> [!NOTE]
> <P>You can change both quotation header prognosis and quotation line prognosis, as required in the quotation; however, if you change the prognosis in the quotation header, the prognosis in the quotation lines will automatically change to reflect the new prognosis in the quotation header.</P>


  


