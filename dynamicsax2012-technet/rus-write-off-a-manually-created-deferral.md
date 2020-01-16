---
title: (RUS) Write off a manually created deferral
TOCTitle: (RUS) Write off a manually created deferral
ms:assetid: 6181a5e5-49a7-44fe-a6d2-c128a6d4caad
ms:mtpsurl: https://technet.microsoft.com/library/JJ665441(v=AX.60)
ms:contentKeyID: 49387530
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (RUS)
- Russia
- deferral
audience: Application User
ms.search.region: Russia
---

# (RUS) Write off a manually created deferral 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Journal voucher** form to write off a deferral that is created manually. To write off a deferral, you must create a write-off transaction in the **Deferrals journal** form by specifying **Writing off** as the transaction type.

1.  Click **General ledger** \> **Journals** \> **Deferrals journal**.

2.  In the **Name** field, select a journal name, and then click **Lines** to open the **Journal voucher** form.

3.  Press CTRL+N to open the **Create new line** form.

4.  In the **Transaction date** field, enter the write-off date for the deferral.

5.  In the **Transaction type** field, select **Writing off**.

6.  In the **Deferral ID** field, select the deferral to write off. Voucher lines are created for the selected deferral in the **Journal voucher** form, based on the interval number and the write-off amount that are specified in the **Deferrals models** form.

7.  In the **Model number** field, select the model number of the deferral.

8.  Click **Validate** \> **Validate**, and then click **Post** \> **Post** to validate and post the journal.

9.  Click **General ledger** \> **Common** \> **Deferrals**. Click **Deferrals models** \> **Transactions** to view the transaction details in the **Deferrals transactions** form.

## See also

[(RUS) Deferrals models (form)](https://technet.microsoft.com/library/jj678655\(v=ax.60\))

[(RUS) Deferrals sum for writing off calculation (form)](https://technet.microsoft.com/library/jj678537\(v=ax.60\))

  


