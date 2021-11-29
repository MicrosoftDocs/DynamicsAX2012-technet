---
title: Prepare currencies for upgrade
TOCTitle: Prepare currencies for upgrade
ms:assetid: 8e1a9fea-938d-4aec-af59-7f116d5a17a5
ms:mtpsurl: https://technet.microsoft.com/library/Gg731867(v=AX.60)
ms:contentKeyID: 35132758
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Prepare currencies for upgrade 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In releases previous to Microsoft Dynamics AX 2012, you could set up currencies for each company. In Microsoft Dynamics AX 2012, the currencies that you set up are shared by the legal entities that are set up in the **Legal entities** form, so the currencies can be used by any of those legal entities.

Use the **Prepare currencies for upgrade** form to select the currencies, a triangulation currency, and the exchange rates that will be shared by the legal entities.

If you are upgrading to Microsoft Dynamics AX 2012 R2 or AX 2012 R3, you must identify a data partition when performing this task. If you have configured multiple partitions, the procedure must be repeated for each partition. For more information about data partitions and upgrade, see [Configure partitions](configure-partitions.md).

1.  Click **Prepare currencies for upgrade** to open the **Prepare currencies for upgrade** form.

2.  In the **Partition key** field, select a partition for preprocessing.

3.  In the **Generate shared currencies** field, select which currencies will be available as shared currencies:
    
      - **For each company** – All the currencies that currently are set up in each company will be available as shared currencies.
    
      - **Specific company account** – Only the currencies for the company that you select in the **Company accounts** field in the **Currencies** field group will be available as shared currencies.

4.  If you selected **Specific company account**, select the company account that contains the currencies that will be shared.

5.  In the **Company accounts** field in the **Triangulation currency** field group, select the company account that contains the triangulation currency to upgrade. This triangulation currency will represent the euro currency.

6.  In the **Generate shared exchange rates** field, select which exchange rates will be available as shared exchange rates:
    
      - **For each company** – All the exchange rates that currently are set up in each company will be available as shared exchange rates.
    
      - **Specific company account** – Only the exchange rates for the company that you select in the **Company accounts** field in the **Generate shared exchange rates** field group will be available as shared exchange rates.

7.  If you selected **Specific company account**, select the company account that contains the exchange rates that will be shared.

8.  Optional: Click **Currency code upgrade validation** to display the shared currency codes and the upgrade error status of each code.

9.  Click **Set to ready for upgrade** to select this checklist item as ready for upgrade.

  


