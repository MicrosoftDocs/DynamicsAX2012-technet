---
title: Specify the invoice frequency for an existing project contract
TOCTitle: Specify the invoice frequency for an existing project contract
ms:assetid: f28f066c-2128-4be0-b6dd-077e402d3366
ms:mtpsurl: https://technet.microsoft.com/library/Aa551624(v=AX.60)
ms:contentKeyID: 36059966
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- buffer
- invoice frequency
- project contract
audience: Application User
ms.search.region: Global
---

# Specify the invoice frequency for an existing project contract 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The invoice frequency that is specified for a project contract is one of two factors that determine the sales payment date on a forecast. The other factor, for time-and-material projects only, is the number of buffer days that are allowed as a grace period. Buffer days are set up in the **Project management and accounting parameters** form.

The invoice frequency plus the number of buffer days determine when a sales payment is due.


> [!NOTE]
> <P>You can specify the invoice frequency in the <STRONG>Project contracts</STRONG> form.</P>



1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **Project contracts**.

2.  Select the project contract for which you want to define an invoice frequency.

3.  On the **Action Pane**, on the **Project contract** tab, click **Edit**.

4.  On the **General** FastTab, in the **Invoice frequency** field, select an invoice frequency.
    
      - **Daily** – The invoice date of forecasts is set to the project date.
    
      - **Weekly** – The invoice date of forecasts is set to the first Sunday after the project date.
    
      - **Monthly** – The invoice date of forecasts is set to the end of the current month, according to the project date.
    
      - **Quarterly** – The invoice date of forecasts is set to the end of the current quarter, according to the project date.
    
      - **Yearly** – The invoice date of forecasts is set to the end of the current year, according to the project date.
    
      - **End of project** – The invoice date of forecasts is set to the end date of the project.

## See also

[Create a project contract](create-a-project-contract.md)

[Set buffer days for sales payments](set-buffer-days-for-sales-payments.md)

[Project management and accounting parameters (form)](https://technet.microsoft.com/library/aa599440\(v=ax.60\))

[Project contracts (form)](https://technet.microsoft.com/library/aa586038\(v=ax.60\))

  


