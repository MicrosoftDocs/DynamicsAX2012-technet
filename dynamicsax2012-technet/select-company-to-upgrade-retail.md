---
title: Select company to upgrade - Retail
TOCTitle: Select company to upgrade - Retail
ms:assetid: 87bf8c28-bd47-44a7-91fb-6aae5e993e7f
ms:mtpsurl: https://technet.microsoft.com/library/Hh500182(v=AX.60)
ms:contentKeyID: 37820249
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Select company to upgrade - Retail 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Some Retail parameters that were company-specific in Microsoft Dynamics AX 2009 have been converted to shared, or global, parameters in Microsoft Dynamics AX 2012. The upgrade administrator must select the company whose parameters are shared with all other companies during the upgrade to Microsoft Dynamics AX 2012. The **Select company to upgrade - Retail** task in the **Preprocessing upgrade checklist** opens a form where you can select one of the existing companies in a list.

In Microsoft Dynamics AX 2012, you can view the global Retail parameters by clicking **Retail** \> **Setup** \> **Parameters** \> **Retail shared parameters**.

## Before you select global parameters

Before you perform the **Select company to upgrade - Retail** task, we recommend that you prepare the existing Retail parameters on the Microsoft Dynamics AX 2009 source system by using the **Retail Headquarters parameters** form. Click **Retail Headquarters** \> **Parameters**. Select a company, determine the parameters that are appropriate for the Microsoft Dynamics AX 2012 system, and then enter those parameters for the selected company. Then, when you use the upgrade preprocessing form, select the company for which you prepared the parameters as the source for global parameters.

## Select and apply global Retail parameters

To apply global Retail parameters, follow these steps.

1.  Click the **Select company to upgrade - Retail** task in the checklist to open the **Select company to upgrade - Retail** form.

2.  If you are upgrading to Microsoft Dynamics AX 2012 R2, select a data partition in the **Partition key** field.

3.  Select the company whose parameters you prepared.

4.  Click **Ready for upgrade**.

  


