---
title: (RUS) Set up an inflation index
TOCTitle: (RUS) Set up an inflation index
ms:assetid: 4af1e875-26a9-47a3-acc5-7b0784a88755
ms:mtpsurl: https://technet.microsoft.com/library/JJ856112(v=AX.60)
ms:contentKeyID: 50406410
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up an inflation index 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



Set up inflation indexes to specify rules for currency conversion for the source company into the target company's currency.

1.  Click **General ledger** \> **Setup** \> **Translation** \> **Inflation indexes**.

2.  In the **Rule group** field, select the translation group for which the inflation indexes are being set up.
    

    > [!NOTE]
    > <P>You can specify several inflation index lists for one group.</P>



3.  In the **Inflation index** field, enter the unique inflation index list code.

4.  In the **Description** field, enter a text description of the inflation index list.

5.  Click the **Graphics** tab to view the graph of the inflation index's change over time.

6.  On the **Rules for dimensions** tab, in the **From date** field, select the starting date for the index.
    

    > [!NOTE]
    > <P>The configured index will function starting from that date to the next configured starting date for another index. You can also set up an index without specifying a start date. The index will function for all transactions before the start date of another index.</P>



7.  In the **Exchange rate** field, enter the value for the index that is used for the currency conversion that falls in the index validity period.

8.  Press CTRL+S or close the form.

## See also

[(RUS) Inflation indexes (form)](https://technet.microsoft.com/library/jj665426\(v=ax.60\))

  


