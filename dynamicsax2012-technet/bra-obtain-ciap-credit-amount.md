---
title: (BRA) Obtain CIAP credit amount
TOCTitle: (BRA) Obtain CIAP credit amount
ms:assetid: 15e1f2ca-f2f3-43e0-8dab-efe8d39a4798
ms:mtpsurl: https://technet.microsoft.com/library/Dn305864(v=AX.60)
ms:contentKeyID: 54912964
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Brazil
---

# (BRA) Obtain CIAP credit amount 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Every month the tax credit amount is calculated for each fiscal establishment for its past fixed asset acquisitions for each fixed asset until the maximum number of tax credit installment payments is reached or the fixed asset no longer belongs to the legal entity. Each fixed asset tax credit installment payment is used to create a tax fiscal document that is part of the ICMS tax assessment for the legal entity.


> [!NOTE]
> <P>This topic applies only if KB 2839295 and KB 2850595 for Microsoft Dynamics AX 2012 R2 are installed, if cumulative update 6 or later for AX 2012 R2 is installed, or if AX 2012 R3 is installed.</P>



## CIAP credit amount

1.  Click **Fiscal books** \> **Common** \> **Booking period**. Create new booking period Select **Create new booking period** on the **Action Pane**.
    
    CIAP transactions, acquisitions, transfers and disposals, are created from the fiscal documents that were created during the booking period.

2.  Click **Fiscal books** \> **Common** \> **Tax assessment** \> **ICMS**. Click **CIAP assessment** to open the **CIAP assessment form**

3.  On the **Action Pane**, click **Calculate parameters** to calculate the total amount of taxable outgoing transactions and the total transaction amount, which is based on the **CFOP codes** form (**General ledger** \> **Setup** \> **Sales tax** \> **CFOP codes**).

4.  For each active fixed asset that has not reached the maximum number of installments, an installment is created for the booking period.

5.  Create and post a tax fiscal document for the fixed asset credit amount.
    
    To view the fixed asset credit amount, click **General ledger** \> **Journal** \> **All tax fiscal documents** \> **New tax fiscal document**. Select **ICMS installment** in the **Tax fiscal document type** field.

6.  In the **Booking period** form, select the current booking period.

7.  Synchronize the new tax fiscal document to the current booking period in the **Synch** form. Click **Fiscal books** \> **Common**, select the booking period, and then click **Sync**.

  


