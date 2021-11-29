---
title: Transfer actual costs in a flexible budget
TOCTitle: Transfer actual costs in a flexible budget
ms:assetid: 29743a81-8bf3-41d3-a1b7-037a24172027
ms:mtpsurl: https://technet.microsoft.com/library/Aa496847(v=AX.60)
ms:contentKeyID: 36056220
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Transfer actual costs in a flexible budget 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Click **Cost accounting** \> **Journals** \> **Flexible budgeting**. On the **Transfer balances** form, click the **Transfer balances** button.

Enter the following information on the **General** tab before you run the transfer of balances:

  - **Forecast model** – Select the budget model that the balances are to be transferred into. Select the **Overwrite** check box if all existing budget values in the selected budget model should be removed before the transfer of balances.

  - **Period** – Select **Date interval code** or **From date** and **To date** of balances to be transferred into the flexible budget.

  - **Change** – Specify the time shift of the balances. The **Quantity** field defines the number of time units for time shift. The **Unit** field defines the units for time shift (days, months, years). The **From date** and **To date** fields display the automatically updated date interval for the transfer.

  - **Rules** – Specify the factor and round-off for cost balances. Factor increases the existing transaction amounts by this factor.

  - **Area** – Define which types of values to transfer: **Fixed costs**, **Variable costs**, and **Services**.

  - **Financial dimensions** – Define which dimension balances to transfer by selecting the appropriate dimensions.

  - **Create settings automatically** – Define whether to create flexible budget settings automatically and to transfer balances for cost categories, service categories, and dimensions defined in the flexible budget model setup.

  


