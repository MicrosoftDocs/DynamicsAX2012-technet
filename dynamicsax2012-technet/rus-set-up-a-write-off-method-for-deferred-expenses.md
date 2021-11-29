---
title: (RUS) Set up a write-off method for deferred expenses
TOCTitle: (RUS) Set up a write-off method for deferred expenses
ms:assetid: 3ad62b84-cc1f-466b-aef5-adf62a8a5a20
ms:mtpsurl: https://technet.microsoft.com/library/JJ665297(v=AX.60)
ms:contentKeyID: 49387386
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Deferred
- expenses
- (RUS)
- Russia
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up a write-off method for deferred expenses 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Writing off methods** form to specify **Amount** or **Percent** as the calculation type for a deferred expense. For more information, see[(RUS) Writing off methods (form)](https://technet.microsoft.com/library/jj711659\(v=ax.60\))

If you specify **Amount** as the calculation type for a write-off method, you must specify the write-off amount in the **Deferrals models** form. If you write off a defined amount over time, you can specify a write-off amount for each interval. For more information, see [(RUS) Set up a deferrals model](rus-set-up-a-deferrals-model.md).

1.  Click **General ledger** \> **Setup** \> **Deferrals** \> **Writing off methods**.

2.  Create a write-off method. For more information, see [(RUS) Generate a deferrals write-off ratio](rus-generate-a-deferrals-write-off-ratio.md).

3.  In the **Writing off method** and **Name** fields, enter the identification code and description of the write-off method.

4.  In the **Type** field, select **Manual**.

5.  In the **Writing off period** field, select **Month**.

6.  In the **Calculation type** field, select **Amount**.
    

    > [!NOTE]
    > <P>You cannot change the calculation type for a write-off method if any transactions currently use that method to calculate the write-off amount.</P>



## See also

[(RUS) Deferrals models (form)](https://technet.microsoft.com/library/jj678655\(v=ax.60\))

  


