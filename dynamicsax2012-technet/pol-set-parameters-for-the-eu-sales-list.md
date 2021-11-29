---
title: (POL) Set parameters for the EU sales list
TOCTitle: (POL) Set parameters for the EU sales list
ms:assetid: a532c195-7532-4dc8-83a2-74069758bc60
ms:mtpsurl: https://technet.microsoft.com/library/JJ678323(v=AX.60)
ms:contentKeyID: 49387045
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Poland
---

# (POL) Set parameters for the EU sales list 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Organizations that supply items and services to customers in other European Union (EU) countries/regions must submit periodic reports to the appropriate authorities in their own countries/regions. Quarterly reports are typically required to be submitted no later than 10 days after the end of the quarter. For example, first-quarter reports are due April 10.

For more information about how to create and submit the EU sales list, see [Generate the EU sales list](generate-the-eu-sales-list.md).

1.  Click **Organization administration** \> **Setup** \> **Foreign trade** \> **Foreign trade parameters**.

2.  In the left pane, click **EU sales list**, and then select whether to report cash discounts in the EU sales list and whether to transfer purchases to the EU sales list.

3.  Select the report layout, and then click **Load XSLT files** to import the XML style sheets to use to generate the EU sales list.

4.  Enter the rounding rule amount. For example, if you want to round amounts to the nearest whole number, enter **1.00**. If you want to round amounts to the nearest half, enter **.50**.

5.  Select the method to use for rounding amounts:
    
      - **Normal** – Round the amount to the nearest unit that is specified in the **Rounding rule** field.
    
      - **Downward** – Round the amount down to the nearest unit that is specified in the **Rounding rule** field.
    
      - **Rounding-up** – Round the amount up to the nearest unit that is specified in the **Rounding rule** field.

6.  Select the **Use minimum value** check box to round amounts smaller than the rounding rule up to the rounding rule amount.

  


